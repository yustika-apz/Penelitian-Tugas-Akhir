# Penelitian-Tugas-Akhir
Komparasi Kinerja Feature Extraction TF-IDF dan TF-IDF-DF untuk Metode SVM Berbasis PSO pada Analisis Sentimen UU TPKS

Tujuan penelitian:
- Menghasilkan nilai pembobotan kata dari metode TF-IDF dan TF-IDF-DF serta mengetahui metode feature extraction terbaik dari perbandingan nilai pembobotan kata TF-IDF dan TF-IDF-DF.
- Menghasilkan dan mengetahui nilai evaluasi terbaik dari penggunaan feature extraction TF-IDF dan TF-IDF-DF pada metode SVM berbasis PSO berdasarkan Accuracy, Recall dan Precision.

Tahapan:
1. Pengumpulan data dengan cara crawling menggunakan API twitter. 
2. Pelabelan data Menggunakan Vader Lexicon.
3. Pre-processing (cleansing data, case folding, tokenize, normalisasi, stopwords removal, dan lemmatization).
4. Feature Extraction menggunakan TF-IDF dan TF-IDF-DF
5. Feature Selection menggunakan PSO
6. Mode Klasifikasi menggunakan SVM
7. Evaluasi Model Klasifikasi menggunakan Confusion Matrix
