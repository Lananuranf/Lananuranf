<h1 align="center">Hi, I'm Maulana Nur Anfajm 👋</h1>

<p align="center">
  <b>Backend Engineer</b> · alias Lananuranf<br/>
  Mahasiswa Sistem Informasi semester 7 di <b>Universitas Gunadarma</b>, Jakarta
</p>

<p align="center">
  Saya membangun REST API dan merancang database untuk aplikasi web.<br/>
  Sehari-hari menulis <b>Go</b> dan <b>Rust</b> dengan <b>PostgreSQL</b>, lalu mengemasnya dengan <b>Docker</b>.
</p>

<p align="center">
  <a href="https://lananuranf.my.id/"><img src="https://img.shields.io/badge/Portfolio-FA699E?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://lananuranf.my.id/blog/"><img src="https://img.shields.io/badge/Blog-000000?style=for-the-badge&logo=hashnode&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/maulana-nur-anfajm-759a633b4/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:lananuranf@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">🟢 <i>Terbuka untuk magang & freelance di bidang backend</i></p>

---

## 🛠️ Tech Stack

**⚙️ Bahasa & Framework Backend**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Fiber](https://img.shields.io/badge/Fiber-00ADD8?style=flat-square&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Axum](https://img.shields.io/badge/Axum-B7410E?style=flat-square&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-463F37?style=flat-square&logo=rust&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

**🗄️ Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)
![SQLx](https://img.shields.io/badge/SQLx-B7410E?style=flat-square&logo=rust&logoColor=white)
![GORM](https://img.shields.io/badge/GORM-00ADD8?style=flat-square&logo=go&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**☁️ Infrastruktur & Deploy**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**🔧 Tools & Integrasi**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![FCM](https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO_(S3)-C72E49?style=flat-square&logo=minio&logoColor=white)

---

## 📌 Proyek Backend

### 🍽️ [Ruang Rasa API](https://lananuranf.my.id/projects/ruang-rasa/)
`Rust` `Axum` `PostgreSQL` `PostGIS` `WebSocket` `Docker Compose` `Caddy`

Backend untuk aplikasi Android reservasi & discovery restoran: login OTP, pencarian restoran terdekat, reservasi meja, dan chat real-time. Dibangun sebagai workspace Rust empat crate di atas PostgreSQL 16 + PostGIS, dengan chat via WebSocket dan Postgres LISTEN/NOTIFY.

> ✅ Reservasi dikunci dengan `SELECT … FOR UPDATE` dan `Idempotency-Key`. Dari 50 request paralel untuk kursi terakhir, tepat 1 yang lolos.

### 🛍️ [Hii Stranger API](https://lananuranf.my.id/projects/capstone-hi/)
`Go` `PostgreSQL` `pgx` `Redis` `JWT` `Next.js` `Prometheus` `Cloudinary`

Backend toko online streetwear untuk proyek capstone tim. Bagian saya terutama backend Go dan panel admin, dengan struktur satu package per fitur: produk, keranjang, order, pembayaran, pengiriman, dan ongkir RajaOngkir.

> ✅ Order dan varian dikunci saat checkout dan verifikasi bayar, jadi stok tetap benar walau dibeli bersamaan. Stok kembali otomatis saat order dibatalkan.

### 🧺 [Laundry Lastri API](https://lananuranf.my.id/projects/londry-lastri/)
`Laravel 12` `PHP` `Laravel Sanctum` `SQLite` `MySQL`

REST API untuk usaha laundry (pelanggan, layanan, order, pembayaran, riwayat status cucian), dibuat sebagai bahan Penulisan Ilmiah. Pelanggan bisa membuat order dan jadwal jemput tanpa login.

> ✅ Total dan sisa tagihan dihitung di server, pembayaran dan perubahan status dibungkus `DB::transaction`, dan setiap perubahan status tercatat di riwayat.

---

## ✍️ Tulisan Terbaru

- [Checkout Tanpa Stok Minus: Mengunci Keranjang dengan FOR UPDATE di Go dan PostgreSQL](https://lananuranf.my.id/blog/checkout-stok-aman-go-postgresql/)
- [Mencegah Double Booking di Backend Reservasi Rust dengan SELECT FOR UPDATE dan Idempotency-Key](https://lananuranf.my.id/blog/mencegah-double-booking-reservasi-rust/)
- [Membangun Alur Order Laundry di Laravel 12](https://lananuranf.my.id/blog/alur-order-laundry-laravel-12/)

➡️ [Lihat semua artikel](https://lananuranf.my.id/blog/)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Lananuranf&show_icons=true&theme=tokyonight&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lananuranf&layout=compact&theme=tokyonight&hide_border=true" height="160" />
</p>

---

## 📫 Kontak

✉️ [lananuranf@gmail.com](mailto:lananuranf@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/maulana-nur-anfajm-759a633b4/) · 🌐 [lananuranf.my.id](https://lananuranf.my.id/) · 📄 [Unduh CV](https://lananuranf.my.id/cv.pdf)

<p align="center"><i>Thanks for visiting! ⭐</i></p>
