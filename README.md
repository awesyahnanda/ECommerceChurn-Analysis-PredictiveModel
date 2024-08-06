# E-Commerce Customer Churn Analysis To reduce acquisition and retention costs Using Predictive Modeling

# Background Context
Dalam dunia bisnis yang dinamis dan penuh persaingan, cara perusahaan beroperasi dan berinteraksi dengan pasar terus berubah. E-commerce adalah salah satu contoh nyata dari evolusi bisnis ini, membuka peluang baru bagi perusahaan dan individu untuk membeli dan menjual barang secara online. Ketika pandemi COVID-19 melanda, penguncian global mendorong lonjakan besar dalam e-commerce. Pada tahun 2020, penetrasi penjualan e-commerce di Amerika Serikat meningkat lebih dari dua kali lipat menjadi 35% dari tahun sebelumnya, yang setara dengan pertumbuhan selama satu dekade. Secara global, hampir 20% dari total penjualan pada tahun 2021 dilakukan secara online, dan diperkirakan akan mencapai hampir seperempat dari semua penjualan global pada tahun 2025 (Mckinsey).

Meningkatnya pembelian secara online menjadikan fokus pada pelanggan semakin penting bagi e-commerce. Menurut McKinsey & Company (McKinsey & Company), peningkatan pengalaman pelanggan dapat menurunkan churn pelanggan hingga hampir 15%, serta meningkatkan rasio kemenangan hingga hampir 40%. Churn pelanggan adalah fenomena di mana pelanggan memutuskan untuk berhenti membeli atau menggunakan produk atau layanan dari suatu perusahaan. Memahami dan meningkatkan pengalaman pelanggan sangat penting untuk mempertahankan loyalitas mereka (retensi) dan mengurangi churn.

Pengalaman pelanggan ini sangat berkorelasi dengan kebiasaan mereka terhadap e-commerce atau perusahaan tertentu. Menyediakan layanan yang memuaskan, responsif, dan personal adalah kunci untuk menjaga hubungan jangka panjang dengan pelanggan. Dengan strategi yang tepat, perusahaan dapat mengurangi churn, meningkatkan retensi pelanggan, dan pada akhirnya meningkatkan profitabilitas. Penelitian menunjukkan bahwa pelanggan yang puas dan loyal cenderung menghabiskan lebih banyak dan lebih sering, menjadikan investasi dalam pengalaman pelanggan sebagai langkah strategis yang penting bagi kesuksesan jangka panjang perusahaan e-commerce.

Oleh karena itu, bagi perusahaan e-commerce, penting untuk memahami dan memprediksi churn rate guna mengidentifikasi pelanggan yang berisiko dan mengambil langkah proaktif untuk mempertahankan mereka. Dengan analisis yang tepat, perusahaan dapat merancang program loyalitas, menawarkan insentif yang relevan, dan meningkatkan kualitas layanan secara keseluruhan untuk meminimalkan churn dan memaksimalkan keuntungan.

Apa itu churn?

Churn rate dalam e-commerce adalah persentase pelanggan yang berhenti melakukan pembelian atau berinteraksi dengan perusahaan dalam periode waktu tertentu. Menurut shopify.com, churn rate dihitung dengan cara berikut:

(Jumlah pelanggan di awal periode - jumlah pelanggan di akhir periode + jumlah pelanggan baru)/Jumlah pelanggan di awal periode

Menentukan apakah customer churn dapat dilihat dari data historis pembelian pelanggan untuk melihat frekuensi pembelian mereka. Jika pelanggan biasanya membeli setiap bulan tetapi belum melakukan pembelian selama tiga bulan, ini bisa menjadi indikator churn.

# Problem Statement
Berdasarkan invespcro.com, 44% perusahaan lebih fokus terhadap akuisisi pelanggan dibandingkan retensi. Padahal peluang barang terjual kepada pelanggan tetap (60%-70%) lebih besar dibandingkan menjual produk ke pelanggan baru (5%). Selain itu, 70% perusahaan setuju bahwa biaya retensi pelanggan jauh lebih murah dibandingkan dengan akuisisi pelanggan baru ($29/pelanggan) (semrush.com & invespcro.com). Bahkan 44% perusahaan tidak menghitung customer retention rate mereka. Hal ini mengakibatkan peningkatan biaya pemasaran dan akuisisi yang tidak efisien, sementara potensi keuntungan dari pelanggan yang sudah ada belum dimanfaatkan sepenuhnya.

Kemudian, temuan lain mengungkapkan bahwa pelanggan yang sudah ada cenderung menghabiskan 67% lebih banyak dan lebih sering daripada pelanggan baru (semrush.com). Hal tersebut didukung oleh penelitian yang dilakukan oleh invespcro.com, yang menyatakan bahwa dengan meningkatkan retention rate sebesar 5%, perusahaan berpeluang meningkatkan profitabilitasnya sebesar 25%-95%. Namun, banyak platform e-commerce belum mampu menyediakan pengalaman yang memadai untuk mempertahankan pelanggan ini. Ketidakpuasan terhadap layanan, baik dari segi kualitas produk maupun kecepatan pengiriman, sering kali menjadi alasan utama pelanggan beralih ke platform lain (churn). Dengan demikian, meningkatkan pengalaman pelanggan menjadi krusial untuk mendorong loyalitas mereka.

Program loyalitas yang terstruktur dengan baik dapat sangat efektif dalam meningkatkan retensi pelanggan dan penjualan. Sayangnya, banyak e-commerce yang belum mengimplementasikan program loyalitas secara optimal. Program yang ada sering kali tidak memberikan insentif yang cukup menarik bagi pelanggan untuk tetap setia. Selain itu, variasi tingkat retensi pelanggan di berbagai industri menunjukkan bahwa pendekatan satu ukuran untuk semua tidaklah efektif.

Untuk mengatasi masalah ini, penting bagi e-commerce untuk memprediksi churn rate guna memahami perilaku pelanggan dan faktor-faktor yang mempengaruhinya. Dengan prediksi yang akurat, perusahaan dapat mengambil langkah proaktif untuk meningkatkan pengalaman pelanggan dan menerapkan strategi retensi yang lebih efektif. Memahami pola belanja dan preferensi pelanggan dapat membantu dalam merancang program loyalitas yang lebih menarik. Dengan demikian, e-commerce dapat meningkatkan retensi pelanggan, mengurangi biaya akuisisi, dan pada akhirnya meningkatkan profitabilitas.

# Objective and Goals
Mengidentifikasi pelanggan churn untuk mengetahui dan memahami faktor-faktor apa saja yang mempengaruhi pelanggan sehingga pelanggan tersebut churn.
Memprediksi pelanggan yang berpotensi churn agar e-commerce/perusahaan proaktif dalam mempertahan customer tersebut dengan model yang menghasilkan kerugian sekecil mungkin dan mengurangi anggaran perusahaan terkait dengan akuisisi customer baru.
Memahami pola dan alasan di balik churn yang dapat membantu perusahaan untuk meningkatkan aspek-aspek tertentu dari user experience.
Mengembangkan strategi retensi yang lebih baik seperti program loyalitas, diskon khusus, dan layanan pelanggan yang ditingkatkan untuk meningkatkan loyalitas pelanggan dan mengurangi churn.

# Analytics Approach
Berdasarkan problem statement dan goals, maka akan dilakukannya analysis data terhadap pelanggan churn dengan menemukan pola atau faktor-faktor apa yang mempengaruhi pelanggan churn.
Selanjutnya, membangun model klasifikasi yang mampu memprediksi pelanggan yang churn atau no churn.

# Metrics Evaluation
Type 1 error : False Negative
Consequence : Karena diprediksi No Churn namun Aktual pelanggan mengalami Churn maka perusahaan akan kehilangan potensi keuntungan tambahan dari pelanggan yang berhenti menggunakan atau bertransaksi di e-commerce. Pelanggan ini tidak ditargetkan dengan upaya retensi, yang mengarah ke kemungkinan yang lebih tinggi untuk meninggalkan layanan kami (Aplikasi), yang secara langsung berdampak pada pendapatan. Untuk mendapatkan pelanggan baru, diperlukan biaya yang juga menimbulkan biaya.

Type 2 error : False Positive
Consequence : Karena diprediksi Churn namun Aktual pelanggan mengalami No Churn perusahaan akan mengalami pemborosan biaya karena memberikan treatment ekstra (treatment Churn) pada pelanggan yang No Churn. Perusahaan mungkin mengalokasikan sumber daya retensi (diskon, kupon) untuk pelanggan ini yang sebenarnya tidak diperlukan. Hal ini dapat menyebabkan peningkatan biaya tanpa manfaat yang sebenarnya.

Matriks Evaluasi Model: Referensi

Presisi (Precision) merupakan metrics yang digunakan untuk mengukur ada berapa banyak hasil prediksi suatu kelas yang memang sesuai dengan kenyataan. Kata kunci yang sangat tepat untuk menggambarkan presisi adalah exactness.
Recall merupakan metrics pada metode klasifikasi yang menyatakan seberapa besar persentase kejadian pada kelas positif yang berhasil dideteksi. Kata kunci yang paling tepat menggambarkan recall adalah completeness.
F1 score adalah rataan harmonik dari presisi dan recall. Ketika kita gunakan F1-score dalam pemilihan model machine learning, F1-score dapat menjaga agar model yang kita pilih memiliki nilai recall dan presisi yang seimbang. Accuracy adalah salah satu metrik evaluasi yang umum digunakan dalam machine learning untuk mengukur sejauh mana model klasifikasi mampu memprediksi dengan benar kelas atau label dari data uji. Secara sederhana, akurasi mengukur persentase prediksi yang benar dari total jumlah prediksi.

Berdasarkan confusion matrix diatas dan melihat konsekuensinya, maka model yang dibangun akan berfokus pada type error 1 (False Negative) atau nilai recall. Karena type error 1 (False Negative) akan berdampak besar pada revenue perusahaan dibandingkan type error 2 (False Positif).


Walaupun model yang dibangun akan berfokus pada nilai recall namun untuk kasus churn customer, model akan tetap memperhatikan nilai precision, karena 2 nilai tersebut memiliki dampak terhadap perusahaan. Maka model akan dibangun dengan performa yang seimbang antara false negatives (recall) dan false positives (precision).

Analisis cost mengenai False Positive (FP) & False Negative (FN)
Berdasarkan pemilihan metrics evaluation yang menjadi fokus dalam pengembangan ML serta keselarasan pengembangan ML dengan masalah dan tujuan yang ingin dicapai, berikut adalah perhitungan biaya kerugian berdasarkan False Positive (FP) dan False Negative (FN) yang akan menjadi bahan evaluasi. Kita perlu menentukan Customer Spending per Month (CSPM), Customer Acquisition Cost (CAC), dan Customer Retention Cost (CRC).

Menurut yaguara.co, pembeli online di Amerika Serikat menghabiskan rata-rata $5381/tahun atau $448.4167/bulan pada tahun 2023. Nilai ini akan menjadi CSPM.
Menurut semrush.com, untuk menarik 1 customer baru, perusahaan perlu dana sebesar $29/customer. Nilai ini akan bertindak sebagai CAC.
Kemudian, misalkan kita memberikan diskon 5% untuk customer yang diprediksi akan churn. Artinya $448.667*0.05 = $22.433/customer
Define Variables

CSPM = $448.4167

CAC = $29 per Customer

CRC = $22.433 per Customer

FN = 10

FP = 10

Loss Cost FN = 10 * CSPM = 10 * $448.4167 = $4.484.167 Hilangnya pendapatan langsung setara dengan CSPM

Loss Cost FP = 10 * CRC = 10 * $22.433 = $224.33 Hanya menambahkan biaya retensi jauh lebih rendah dibandingkan loss cost FN


Kerugian dari False Negative (FN) jauh lebih besar dibandingkan dengan False Positive (FP). Oleh karena itu, model prediksi yang fokus pada meminimalkan Type Error 1 (False Negative) atau yang memiliki nilai recall tinggi lebih menguntungkan untuk revenue perusahaan. Hal ini karena kehilangan pelanggan yang bisa dihindari dengan insentif retensi akan berdampak signifikan pada pendapatan perusahaan dibandingkan dengan memberikan insentif yang tidak diperlukan.
