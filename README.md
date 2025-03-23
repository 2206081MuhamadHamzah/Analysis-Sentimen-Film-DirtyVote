# **Analisis Sentimen Film Dirty Vote 🎬🔍**  

## 📌 **Deskripsi Proyek**  
Film *Dirty Vote* memicu banyak diskusi publik, dengan berbagai opini yang beredar di media sosial. Proyek ini bertujuan untuk menganalisis sentimen dari komentar-komentar terkait film ini menggunakan teknik **Natural Language Processing (NLP)**.  

## 🛠 **Teknologi yang Digunakan**  
- **Python** (pandas, numpy, scikit-learn, TensorFlow, Gensim)  
- **Machine Learning & Deep Learning**  
  - Model **Bi-LSTM**  
  - Model **CNN + LSTM**  
  - Model **GRU dengan TF-IDF**  
- **Web Scraping** untuk mengumpulkan dataset  
- **Preprocessing NLP** (stopwords removal, stemming, tokenization)  
- **Git & GitHub** untuk kolaborasi  

## 📊 **Hasil Model**  
Model terbaik mampu mengklasifikasikan sentimen dengan cukup baik. Contoh inferensi:  
✅ **Input:** *"Film isinya sampah hanya adu domba"*  
🔍 **Prediksi:** **Negatif** 😡  

## 📂 **Struktur Proyek**  
📁 Projek analisis sentimen
│── 📂 Dataset │ ├── Dirty_vote.csv │ ├── Label_sentiment.csv 
│── 📂 Model │ ├── model_cnn_lstm.h5 │ ├── model_gru.h5 │ ├── model_lstm.h5 │ ├── tfidf_vectorizer.pkl │ ├── tokenizer.pkl │
|── Inference.ipynb 
│── Scraping.ipynb 
│── Submission_Analisis_Sentimen_Dirty_vote.ipynb
│── requirements.txt
│── README.md


## 📥 **Download & Gunakan Model**  
Jika tertarik dengan model yang saya buat, bisa mengunduhnya di GitHub ini.  
📌 **GitHub Repository:** [Analysis-Sentimen-Film-DirtyVote](https://github.com/2206081MuhamadHamzah/Analysis-Sentimen-Film-DirtyVote)  

## 📝 **Cara Menjalankan**  
### 1️⃣ Clone repo ini:  
```sh
git clone https://github.com/2206081MuhamadHamzah/Analysis-Sentimen-Film-DirtyVote.git
cd Analysis-Sentimen-Film-DirtyVote
2️⃣ Install dependensi:
sh
pip install -r requirements.txt
3️⃣ Jalankan model inference:
Buka Inference.ipynb dan jalankan untuk menguji model pada teks baru.
```sh
git add README.md
git commit -m "Menambahkan file README.md"
git push origin main

## 📢 Kontak & Feedback
Jika ada pertanyaan atau ingin berkolaborasi, silakan hubungi saya di LinkedIn atau GitHub. 🚀


