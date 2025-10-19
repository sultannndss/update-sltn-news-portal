# 📰 UpdateSltn - Portal Berita Terkini

**UpdateSltn** adalah portal berita modern yang menampilkan berita terbaru dari berbagai kategori menggunakan **NewsAPI**.  
Website ini dibangun menggunakan **HTML, CSS, Bootstrap, dan jQuery**, serta mendukung fitur **dark mode otomatis**, **pencarian berita**, dan **penyimpanan berita favorit**.

---

## 🚀 Fitur Utama
- 🗞️ Menampilkan berita terkini dari berbagai sumber.
- 🔍 Pencarian berita berdasarkan kata kunci.
- 🏷️ Kategori berita: Indonesia, Teknologi, Ekonomi, Olahraga, Hiburan.
- 💾 Simpan berita favorit ke *LocalStorage* (tanpa login).
- 🌙 Mode gelap otomatis berdasarkan waktu.
- 🧭 Tampilan responsif berbasis Bootstrap.
- 🔁 Slider berita populer dengan Swiper.js.

---

## 🧠 Teknologi yang Digunakan
- **HTML5**
- **CSS3**
- **Bootstrap 5**
- **jQuery**
- **Swiper.js**
- **NewsAPI** (https://newsapi.org)

---

## 🔑 API Key
Proyek ini menggunakan API dari [NewsAPI.org](https://newsapi.org/).  
Kamu bisa mendapatkan API key gratis di sana, lalu ganti pada bagian berikut di `index.html`:
```js
const API_KEY = "YOUR_API_KEY_HERE";
