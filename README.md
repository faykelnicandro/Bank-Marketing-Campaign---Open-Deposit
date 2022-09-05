# Bank-Marketing-Campaign---Open-Deposit

Latar Belakang

Jenis produk keuangan yang beredar dan digunakan oleh masyarakat semakin bertambah dari tahun ke tahun. Salah satu produk keuangan yang cukup diketahui masyarakat adalah deposito berjangka. Mekanisme deposito berjangka sendiri adalah nasabah menyetorkan sejumlah uang kepada bank atau sebuah lembaga keuangan dan uang tersebut hanya akan bisa diambil setelah melewati jangka waktu tertentu. Sebagai bentuk imbalan, nasabah akan diberi bunga tetap sesuai nominal uang yang disetor.

Bank sebagai sebuah badan usaha yang telah memiliki produk keuangan terlebih dahulu dan juga memiliki nasabah yang lebih banyak, tetap harus bersaing agar tidak kehilangan nasabah. Salah satunya dengan melakukan marketing campaign.

Deposit(Target) :    

0 : Tidak berinvestasi di deposito berjangka

1 : Berinvestasi di deposito berjangka

Pernyataan Masalah

Proses *marketing act* atau menghubungi nasabah akan memakan waktu dan sumber daya yang besar bila dilakukan dengan menyeluruh. Maka dari itu, melakukan klasifikasi nasabah akan sangat membantu tim marketing melakukan campaign kepada nasabah yang tepat sehingga dapat mengurangi sumber daya yang dikeluarkan dengan tingkat keberhasilan yang lebih maksimal.

Tujuan:

Dengan permasalahan tersebut, maka bank ingin mampu memprediksi nasabah mana yang ingin dan mampu untuk mengikuti deposito berjangka seperti yang ditawarkan. Selain itu, bank juga ingin mengetahui faktor apa saja yang mempengaruhi seorang nasabah mau menggunakan produk deposito berjangka.

Analisa:

Untuk memenuhi tujuan diatas, kita akan membuat analisa data untuk menemukan algoritma dari nasabah mana yang mau dan tidak mau untuk menggunakan produk deposito berjangka. Selain menganalisa, model klasifikasi juga akan dibuat guna membantu bank untuk memprediksi atau menghitung kemungkinan nasabah akan menggunakan deposito berjangka atau tidak.

Evaluasi performa pada metric terbagi menjadi 4, yaitu:
|  | Predict not Invest | Predict to Invest |
| --- | --- | --- |
| Actual not Invest | True Negative | False Positive |
| Actual Invest | False Negative | True Positive |

Dari 4 metric diatas, ada 2 yang masuk kategori error atau tidak sama dengan prediksi:
1. False Positive    
Beresiko sumber daya dan waktu menjadi sia-sia dalam melakukan marketing
2. False Negative      
Beresiko kehilangan nasabah yang ingin dan mau untuk menggunakan deposito berjangka

Dengan resiko-resiko tersebut, model klasifikasi yang dibuat harus sesuai dengan permasalahan bisnis yaitu mengutamakan agar tidak kehilangan nasabah yang berpotensi menggunakan produk deposito berjangka dengan tanpa mengabaikan pemborosan sumber daya dan waktu yang digunakan.
