# Sentiment Analysis of Vidio App Reviews 💬🧠🔍



Proyek ini melakukan analisis sentimen terhadap ulasan aplikasi Vidio di PlayStore untuk memahami persepsi dan kepuasan pengguna terhadap platform streaming video Indonesia ini.

## 📋 Deskripsi Proyek

Analisis sentimen ini bertujuan untuk mengklasifikasikan review aplikasi Vidio menjadi kategori sentimen positif, negatif, atau netral. Proyek ini menggunakan teknik Natural Language Processing (NLP) dan machine learning untuk memberikan wawasan tentang pengalaman pengguna dengan aplikasi Vidio.

## 🎯 Tujuan

- Menganalisis sentimen review pengguna aplikasi Vidio
- Mengidentifikasi aspek-aspek yang paling disukai dan tidak disukai pengguna
- Memberikan visualisasi data yang informatif tentang persepsi pengguna
- Menyediakan insights untuk pengembangan aplikasi yang lebih baik


## 📊 Dataset

Dataset berisi review aplikasi Vidio yang dikumpulkan dari:
- Google Play Store

### Struktur Data
- **reviewId**: ID unik untuk setiap review
- **userName**: Nama pengguna yang memberikan review
- **userImage**: URL gambar profil pengguna
- **content**: Teks review dari pengguna (data utama untuk analisis sentimen)
- **score**: Rating numerik yang diberikan pengguna (1-5 bintang)
- **thumbsUpCount**: Jumlah "thumbs up" atau "helpful" yang diterima review
- **reviewCreatedVersion**: Versi aplikasi saat review dibuat
- **at**: Timestamp kapan review dibuat
- **replyContent**: Balasan dari developer
- **repliedAt**: Waktu balasan developer 
- **appVersion**: -

## 📊 Hasil dan Visualisasi

Proyek ini menghasilkan berbagai visualisasi seperti:

- **Distribusi Sentimen**: Pie chart distribusi sentimen
- **Word Cloud**: Visualisasi kata-kata yang paling sering muncul
- **Models**: Menghasilkan 3 skema model, yaitu TF-IDF + SVM (Split 80/20), TF-IDF + Random Forest (70/30), dan TF-IDF + DNN (70/30)

## 🔍 Insights Utama

Berdasarkan analisis yang dilakukan, beberapa temuan utama meliputi:

- Distribusi sentimen review aplikasi Vidio
- Aspek-aspek yang paling sering dikomentari pengguna
- Kata kunci yang mengindikasikan sentimen positif, negatif, dan netral


## 📞 Kontak

Jika Anda memiliki pertanyaan atau saran, silakan hubungi:
- GitHub: [@idhak](https://github.com/idhak)
- Email: [Idha Kurniawati](mailto:idhakurniawati03@gmail.com)

## 🙏 Acknowledgments

- Tim Vidio yang telah menghadirkan platform streaming menarik, sehingga layak untuk dianalisis lebih lanjut.
- Komunitas open source yang telah berkontribusi dalam menyediakan berbagai tools dan library yang digunakan dalam proyek ini.
- Google Play Store sebagai sumber data ulasan publik yang digunakan dalam analisis sentimen.

---

**Catatan**: Pastikan untuk menggunakan data review secara etis dan sesuai dengan terms of service platform yang bersangkutan.
