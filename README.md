# Social Media Analysis – Kpop Sentiment

Menganalisis sentimen publik di Twitter terkait topik **Kpop**.
Dataset diperoleh melalui **Tweet Harvest**, kemudian diproses dan dianalisis menggunakan Python di **Google Colab**.

## 📌 Fitur Analisis

* ✅ Scraping tweet dengan **Tweet Harvest** (≥1000 tweet)
* ✅ Cleaning text (hapus URL, mention, perluas singkatan, tanda baca tetap dipertahankan)
* ✅ Analisis kata & hashtag populer (Counter + Wordcloud)
* ✅ Analisis sentimen menggunakan **TextBlob** → label **positif, netral, negatif**
* ✅ Visualisasi:
  * Wordcloud umum & per sentimen
  * Distribusi sentimen (pie chart)
  * Sentiment timeline (tren harian)
  * Engagement vs Sentiment (like & retweet)
  * Top influencer (akun paling banyak like & retweet)
  * Emoji analysis
  * Co-hashtag analysis
* ✅ Output akhir berupa **CSV dengan kolom sentimen** + **laporan analisis**

---

## 🛠 Tools & Library

* **Google Colab**
* **Python Libraries**:

  * `pandas` – olah data
  * `re (regex)` & `BeautifulSoup` – cleaning text
  * `Counter` – frekuensi kata & hashtag
  * `wordcloud` & `matplotlib` – visualisasi
  * `textblob` – analisis sentimen

---

## 📂 Struktur Proyek

```bash
├── kpop_tweets.csv                 # dataset hasil Tweet Harvest
├── kpop_tweets_sentiment.csv       # dataset dengan kolom sentimen
├── Kpop_report.docx                # laporan analisis (Word)
├── Kpop_Analysis_Sentiment.ipynb   # kode Python di Google Colab
└── README.md                       # deskripsi proyek (file ini)
```

---

## 🚀 Cara Menjalankan

1. Upload file hasil scraping Tweet Harvest ke Google Colab.
2. Jalankan notebook (`Kpop_Analysis_Sentiment.ipynb`).
3. Ikuti langkah analisis: cleaning, wordcloud, sentimen, visualisasi.
4. Hasil akhir akan tersimpan dalam file `kpop_tweets_sentiment.csv`.

---

## 📊 Hasil Analisis (Ringkasan)

* **Distribusi Sentimen:**
  * Positif → ±52%
  * Netral → ±33%
  * Negatif → ±15%
* **Hashtag populer:** #kpop, #bts, #blackpink, #comeback
* **Akun berpengaruh:** fanbase besar (ARMY, BLINK, dsb.)
* **Insight:** opini publik di Twitter tentang Kpop **didominasi sentimen positif** dengan dukungan kuat dari fandom.

---
