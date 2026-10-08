\# Kriteria 1: Memuat Dataset dan Melakukan Exploratory Data Analysis (EDA)



Menampilkan dataset menggunakan function head().

Menampilkan informasi dataset dengan info().

Menampilkan statistik deskriptif dataset dengan menjalankan describe() untuk mendapatkan ringkasan data.



\# Kriteria 2: Pembersihan dan Pra Pemrosesan Data



Mengecek dataset menggunakan isnull().sum() dan duplicated().sum().

Menangani data yang hilang menggunakan dropna().

Menghapus data duplikat menggunakan drop\_duplicates().

Melakukan drop pada kolom yang memiliki keterangan ID, Address, dan Date seperti TransactionID, AccountID, DeviceID,  IPAddress, MerchantID, dan TransactionDate.

Melakukan feature encoding menggunakan LabelEncoder() untuk fitur kategorikal.



\# Kriteria 3: Membangun Model Clustering



Menggunakan dataset yang sudah dilakukan preprocessing.

Melakukan visualisasi Elbow Method untuk menentukan jumlah cluster terbaik menggunakan KElbowVisualizer().

Menggunakan algoritma K-Means Clustering dengan sklearn.cluster.KMeans().

Menjalankan cell code joblib.dump() dengan nama model\_clustering agar reviewer dapat secara otomatis menilai evaluasi model anda.



\# Kriteria 4: Interpretasi Hasil Clustering



Menampilkan analisis deskriptif minimal mean, min, dan max untuk fitur numerik.

Menjelaskan karakteristik tiap cluster berdasarkan hasil proses agregasi.

Mengekspor data training dari proses preprocessing beserta data hasil clustering dan berikan nama untuk kolom tersebut yaitu Target.



\# Kriteria 5: Membangun Model Klasifikasi



Menggunakan train\_test\_split() untuk melakukan pembagian dataset.

Membangun model dengan algoritma Decision Tree.

Menjalankan cell code joblib.dump() dengan nama decision\_tree\_model.h5 agar reviewer dapat secara otomatis menilai evaluasi model anda.

