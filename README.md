# UAS_AI_Angga
# Natural Language Processing (NLP) _ Indonesian News Title Classification


## Latar Belakang
Pesatnya pertumbuhan media digital menyebabkan meningkatnya jumlah data teks tidak terstruktur, khususnya berita online. Judul berita merupakan ringkasan informasi utama yang mencerminkan topik suatu berita. 


##  Dataset
- **Nama dataset**: `indonesian-news-title.csv`
- **Jenis data**: Data teks (judul berita) dan label kategori
- **Bahasa**: Bahasa Indonesia
- **Struktur data**:
  - Kolom teks: Judul berita
  - Kolom label: Kategori/topik berita

### Exploratory Data Analysis (EDA)
Tahapan EDA dilakukan untuk memahami karakteristik dataset, meliputi:
- Pemeriksaan struktur dan ukuran dataset
- Identifikasi tipe data pada setiap kolom
- Analisis distribusi label
- Pengecekan nilai kosong (missing values)


###  Pre-processing Data
Tahapan preprocessing bertujuan membersihkan teks dari noise dan ketidakteraturan. Proses yang dilakukan antara lain:
- Case folding (mengubah teks menjadi huruf kecil)
- Penghapusan angka, simbol, dan karakter non-alfabet
- Normalisasi teks sederhana
- Pembersihan noise untuk meningkatkan kualitas data

## Kesimpulan
Berdasarkan hasil eksperimen, pendekatan NLP menggunakan TF-IDF dan Machine Learning klasik mampu mengklasifikasikan judul berita Bahasa Indonesia dengan baik. Model Support Vector Machine (SVM) menunjukkan performa yang lebih stabil dibandingkan Naive Bayes pada data berdimensi tinggi.

