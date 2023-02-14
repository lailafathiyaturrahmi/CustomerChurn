# CustomerChurn
Status tetap berlangganan atau berhenti berlangganan (Churn) customer penting untuk di prediksi dalam sebuah perusahaan. Hal tersebut penting dipertimbangkan mengingat biaya yang dibutuhkan untuk menarik pelanggan baru dibandingkan mempertahankan customer lama. Prediksi churn pelanggan dapat memberikan peringatan dini bagi perusahaan untuk menetapkan kebijakan untuk mempertahankan customer yang berpeluang besar churn. Maka dari itu, dalam sebuah perusahaan penting untuk memodelkan pelanggan yang mungkin berhenti berlangganan (Churn).

Prediksi churn atau tidaknya pelanggan dapat dilakukan dengan memperhatikan beberapa hal seperti:
1. Demographic terdiri dari jenis kelamin, rentang usia (termasuk dalam usia senior atau muda), adanya partner dan ketergantungan customer
2. Layanan yang di ambil customer seperti, phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
3. informasi akun yang terdiri dari lama berlangganan (tenure), contract, metode pembayaran, paperless billing, biaya bulanan, and total biay

# Data
Data yang digunakan dalam proyek ini adalah data IT Chustomer churn. Adapun data dapat diakses melalui tautan berikut.
https://www.kaggle.com/datasets/soheiltehranipour/it-customer-churn

# Metode
metode klasifikasi yang dilakukan dalam proyek ini adalah logistic regression, decision tree dan random forest. Terdapat permaasalahan unbalanced data dalam kategori churn dan tidaknya customer sehingga untuk menghindari prediksi yang lebih condong ke arah kategori mayoritas. Maka dari itu, dilakukan penanganan dengan teknik oversampling yaitu menyesuaikan kategori minoritas sehingga memiliki kuantitas yang sama dengan jumlah yang sama dengan kategori mayoritas.
# Langkah-Langkah
1. Data cleaning
2. eksplorasi data
3. Penanganan unbalanced data
4. Pemodelan
5. evaluasi

# Hasil
- Eksplorasi data menunjukkan bahwa customer churn paling banyak terjadi di awal customer berlangganan. Hal tersebut wajar mengingat customer sedang beradaptasi atau bahkan memilih apakah paket langganan yang diambil sesuai sehingga saat customer merasa tidak sesuai sangat mudah bagi customer berpindah. Sebaliknya, bagi customer yang sduah berlangganan lama lebih sedikit kemungkinan untuk churn hal tersebut dapat terjadi karena loyalitas pelanggan sudah tinggi terhadap layanan yang diberikan.
- berdasarkan 3 metode yang digunakan terbukti bahwa random forest tanpa diperlukan hyperparameter tuning merupakan model terbaik. Hal tersebut terlihat dari skor presisi, akurasi dan recall yang secara bersama-sama menunjukkan nilai terbaik untuk random forest.

