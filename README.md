# UTS NLP - Analisis Sentimen Ulasan Mobile Legends

Repository ini berisi kode dan dataset untuk proyek Ujian Tengah Semester (UTS) mata kuliah Natural Language Processing (NLP). Proyek ini berfokus pada analisis sentimen ulasan game Mobile Legends di Google Play Store, dengan membandingkan performa representasi teks TF-IDF dan Word2Vec menggunakan model Logistic Regression.

## 📌 Deskripsi Proyek
Tujuan utama proyek ini adalah menerapkan tahapan *text preprocessing* yang lengkap dan mengimplementasikan metode representasi teks tanpa menggunakan model *pretrained* besar (seperti BERT/GPT). 

Sentimen dibagi menjadi dua kelas:
- **Positif (1):** Skor ulasan 4 dan 5 bintang.
- **Negatif (0):** Skor ulasan 1, 2, dan 3 bintang.

## 📂 Struktur Direktori
- `UTS_NLP_Sentimen.ipynb` : File Jupyter Notebook yang berisi keseluruhan kode (mulai dari *preprocessing* hingga visualisasi).
- `mobile_legends_reviews.csv` : Dataset mentah berisi ulasan pengguna.

## ⚙️ Persyaratan (Requirements)
Proyek ini dibuat menggunakan Python 3.8+ dan beberapa library standar. Untuk menjalankan proyek ini, pastikan telah menginstal library berikut:

```bash
pip install pandas numpy scikit-learn nltk gensim matplotlib wordcloud

link github
https://colab.research.google.com/drive/1vd3eFV-SW4EfK4oTGXhOf0lBQBHjoj6s?usp=sharing

link dataset dikarenakan dataset ukurannya besar
https://www.kaggle.com/datasets/abiyyurasyiq/mobile-legends-google-play-reviews
