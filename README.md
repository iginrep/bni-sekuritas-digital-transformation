# BIONS Mobile Review Analytics  
**BNI Sekuritas Internship Program 2025**

Proyek ini dibuat untuk mendemonstrasikan kemampuan dalam *data analytics* dan *AI-driven text processing* guna mendukung peningkatan layanan digital BNI Sekuritas. Analisis dilakukan terhadap ulasan pengguna aplikasi **BIONS Mobile** dari App Store menggunakan pipeline otomatis berbasis Python. Hasilnya memberikan gambaran menyeluruh terkait isu teknis yang paling banyak dialami pengguna dan prioritas perbaikan yang memiliki dampak terbesar bagi pengalaman investor ritel.

---

## 🔄 Alur Kerja
1. **Web Scraping** ulasan App Store menggunakan `requests`.  
2. **Data Cleaning & Structuring** ke dalam format Excel (`pandas`, `openpyxl`).  
3. **Sentiment Analysis (VADER)** untuk memetakan persepsi pengguna.  
4. **Technical Keyword Extraction** untuk menemukan *pain points* dominan.  
5. **Data Visualization** (rating distribution & technical word cloud).  
6. **Business Interpretation** berdasarkan pola keluhan pengguna.

---

## 📊 Temuan Utama
- Rating bintang **1** mendominasi ulasan pengguna.  
- Keluhan terbanyak terkait adalah **error**, **login**, **blank/crash**, **server**, **loading**, dan **transaksi lambat**.  
- Visualisasi menunjukkan masalah teknis yang konsisten dan dapat diprioritaskan untuk perbaikan.

---

## 🧩 Value Bisnis
- Menyediakan *data-driven insight* untuk prioritas peningkatan aplikasi BIONS.  
- Mengungkap pola keluhan penting yang berdampak langsung pada pengalaman investor ritel.  
- Mendukung proses transformasi digital melalui analisis keluhan yang lebih terstruktur.  
- Menjadi dasar penyusunan sistem pemantauan kualitas aplikasi yang lebih proaktif.

---

## 🛠️ Skill yang Ditampilkan
- Python (requests, pandas, nltk, matplotlib, wordcloud)  
- Web scraping & automation  
- NLP & Sentiment Analysis  
- Data visualization  
- Analytical thinking & problem framing  

---

## 📁 File Penting
- `scrap_to_excel.py` — script scraping & analitik  
- `bions_reviews_full.xlsx` — hasil data lengkap  
- `bions_rating_dist.png` — grafik distribusi rating  
- `bions_wordcloud_technical.png` — word cloud teknis  

---

## 🚀 Tujuan Proyek
Memberikan contoh nyata bagaimana pendekatan berbasis data dapat mendukung keputusan strategis dalam pengembangan produk digital, khususnya dalam meningkatkan pengalaman pengguna aplikasi BIONS Mobile.

