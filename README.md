# Sentiment Analysis (Practice Case)





##### Zumarsiyah Mahsyari
##### Astra Data Scientist Bootcamp

Sentimen Analysis atau opinion mining merupakan metode analisis berbasis komputasi mengenai pendapat, sentimen, dan emosi (Liu, 2010). Analisis sentimen digunakan untuk melihat kecenderungan suatu sentimen atau pendapat terhadap suatu hal yang terjadi, apakah pendapat tersebut cenderung beropini positif atau negatif.
<br> <br>
Pada Practice Case kali ini, kita melakukan Sentiment Analysis menggunakan Data Tweet yang dapat diakses melalui https://bit.ly/316a1iw. Data tersebut berisi kolom text dan target. Kolom text berisi tweet dan kolom target merupakan sentimen dari tweet tersebut, (0 = sentimen negatif dan 1 = sentimen positif). Data terdiri dari 1.600.000 tweet.

Sebelum melakukan sentiment analysis, kita perlu melakukan Praprocessing Data yang meliputi:
1. Lower Casing: menjadikan text berhuruf kecil semua (tidak ada yang huruf kapital)
2. Punctuation Removal: menghapus tanda baca
3. Stopword: mengambil kata-kata yang penting
4. Lemmatization: mengubah kata-kata yang ada menjadi kata yang sesuai dengan kaidahnya

Setelah dilakukan praprocessing data, hal yang perlu kita lakukan selanjutnya adalah melakukan klasifikasi tweet tersebut. Klasifikasi yang dilakukan pada Practice Case kali ini menggunakan algoritma Logistic Regression dan Naive Bayes. Adapun untuk evaluasi model kita menggunakan nilai Akurasi, Recall, Precision, dan F1 Score.
