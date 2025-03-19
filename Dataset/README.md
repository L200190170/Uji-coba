Dataset Credit Card Customers ini merupakan dataset yang tergolong dalam domain bisnis perbankan yang akan digunakan untuk memprediksi terjadinya churn pelanggan. Dataset "Credit Card Customers" yang tersedia di Kaggle berisi informasi mengenai pelanggan kartu kredit, mencakup berbagai variabel demografis dan perilaku penggunaan kartu. Berikut adalah struktur data (skema dan format) dari dataset tersebut:​

CLIENTNUM: Nomor unik identifikasi pelanggan (tipe data: numerik).​
Attrition_Flag: Status pelanggan, apakah masih aktif (Existing Customer) atau sudah berhenti (Attrited Customer) (tipe data: kategorikal).​
Customer_Age: Usia pelanggan dalam tahun (tipe data: numerik).​
Gender: Jenis kelamin pelanggan, dengan nilai 'M' untuk laki-laki dan 'F' untuk perempuan (tipe data: kategorikal).​
Dependent_count: Jumlah tanggungan yang dimiliki oleh pelanggan (tipe data: numerik).​
Education_Level: Tingkat pendidikan pelanggan, seperti sekolah menengah, sarjana, pascasarjana, dll. (tipe data: kategorikal).​
Marital_Status: Status pernikahan pelanggan, seperti menikah, lajang, bercerai, atau tidak diketahui (tipe data: kategorikal).​
Income_Category: Kategori pendapatan tahunan pelanggan, misalnya: kurang dari $40K, $40K-$60K, $60K-$80K, dll. (tipe data: kategorikal).​
Gist
Card_Category: Jenis kartu kredit yang dimiliki pelanggan, seperti Blue, Silver, Gold, atau Platinum (tipe data: kategorikal).​
Medium
+1
Gist
+1
Months_on_book: Lama hubungan pelanggan dengan bank dalam bulan (tipe data: numerik).​
Medium
Total_Relationship_Count: Jumlah total produk atau layanan bank yang dimiliki oleh pelanggan (tipe data: numerik).​
Months_Inactive_12_mon: Jumlah bulan di mana pelanggan tidak aktif dalam 12 bulan terakhir (tipe data: numerik).​
Medium
Contacts_Count_12_mon: Jumlah kontak atau interaksi dengan pelanggan dalam 12 bulan terakhir (tipe data: numerik).​
Credit_Limit: Batas kredit yang diberikan pada kartu kredit pelanggan (tipe data: numerik).​
Total_Revolving_Bal: Total saldo bergulir pada kartu kredit, yaitu saldo yang belum dibayar penuh dan dikenakan bunga (tipe data: numerik).​
Medium
Avg_Open_To_Buy: Rata-rata jumlah kredit yang tersedia untuk digunakan oleh pelanggan (tipe data: numerik).​
Total_Amt_Chng_Q4_Q1: Perubahan jumlah transaksi antara kuartal keempat dan kuartal pertama (tipe data: numerik).​
Total_Trans_Amt: Total jumlah transaksi yang dilakukan oleh pelanggan dalam 12 bulan terakhir (tipe data: numerik).​
Total_Trans_Ct: Total jumlah transaksi yang dilakukan oleh pelanggan dalam 12 bulan terakhir (tipe data: numerik).​
Total_Ct_Chng_Q4_Q1: Perubahan jumlah transaksi antara kuartal keempat dan kuartal pertama (tipe data: numerik).​
Avg_Utilization_Ratio: Rasio rata-rata pemanfaatan kredit oleh pelanggan (tipe data: numerik).​
Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_1: Nilai prediksi dari model Naive Bayes terkait kemungkinan pelanggan berhenti menggunakan layanan, berdasarkan beberapa variabel (tipe data: numerik).​
Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_2: Nilai prediksi kedua dari model Naive Bayes dengan variabel yang sama (tipe data: numerik).​
Dataset ini terdiri dari 10.127 baris data dengan 23 kolom seperti yang dijelaskan di atas. Informasi ini dapat digunakan untuk menganalisis perilaku pelanggan, memprediksi kemungkinan churn, dan merancang strategi retensi yang efektif.
