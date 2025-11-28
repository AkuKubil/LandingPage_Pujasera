# LandingPage_Pujasera
Anggota :
Brilian Kurniawan Prasisto (5025241213)

Dwinanda Rakhish Baley (5025241198)

HTML File : 

```
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pujasera KTT - Landing Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- 1. Hero Section -->
  <header class="hero">
    <div class="container">
      <img src="logo.png" alt="Logo Pujasera KTT" class="logo">
      <h1>Pujasera KTT</h1>
      <p>Tempat makan dengan pilihan tenant yang beragam dan harga terjangkau</p>
      <a href="#formulir" class="btn">Daftar Sekarang</a>
      <img src="hero.jpg" alt="Suasana Pujasera KTT" class="hero-img">
    </div>
  </header>

  <!-- 2. Benefit Section -->
  <section class="benefit">
    <h2>Mengapa Memilih Kami?</h2>
    <div class="grid">
      <div class="card">- Banyak Pilihan Menu</div>
      <div class="card">- Harga Terjangkau</div>
      <div class="card">- Tempat Nyaman & Asik</div>
      <div class="card">- Parkir Luas</div>
    </div>
  </section>

  <!-- 3. Testimoni -->
  <section class="testimoni">
    <h2>Apa Kata Pengunjung?</h2>
    <blockquote>
      “Tempat nongkrong favorit, makanannya enak dan suasananya asik banget!”  
      <cite>- Brilian, Mahasiswa</cite>
    </blockquote>
  </section>

  <!-- 4. Detail Produk / Layanan -->
  <section class="detail">
    <h2>Apa itu Pujasera KTT?</h2>
    <p>Pusat kuliner dengan lebih dari 20 tenant makanan & minuman, cocok untuk anak kuliahan
      yang sedang mencari makanan murah meriah. Memiliki tempat yang nyaman untuk nugas.</p>
    <img src="food.jpg" alt="Menu Favorit">
  </section>

  <!-- 5. Offer / Promo -->
  <section class="promo">
    <h2>Promo Spesial Bulan Ini!</h2>
    <p>Ayam geprek hanya 13K dengan banyak lauk!</p>
    <a href="#formulir" class="btn">klik disini</a>
  </section>

  <!-- 7. FAQ -->
  <section class="faq">
    <h2>Pertanyaan yang Sering Ditanyakan</h2>
    <details>
      <summary>Jam operasional Pujasera KTT?</summary>
      <p>Setiap hari pukul 24 Jam</p>
    </details>
    <details>
      <summary>Apakah ada area parkir?</summary>
      <p>Ada, area parkir luas untuk motor dan mobil</p>
    </details>
  </section>

  <!-- 8. Footer -->
  <footer>
    <p>Kontak: example@example.com | 0812-3456-7890</p>
    <p>
      Ikuti kami:
      <a href="#">Instagram</a> | <a href="#">Facebook</a> | <a href="#">TikTok</a>
    </p>
  </footer>
</body>
</html>
```
CSS File : 

```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

html {
  scroll-behavior: smooth;
}

body {
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
}

/* Header */
header {
  background: #4233ca;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

header h1 {
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #222;
}

/* Section umum */
section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

section h2 {
  color: #4233ca;
  margin-bottom: 15px;
  border-bottom: 2px solid #4233ca;
  display: inline-block;
  padding-bottom: 5px;
}

section p, section ul {
  margin-top: 10px;
}

/* Gambar */
section img {
  margin-top: 15px;
  border-radius: 10px;
  max-width: 100%;
  height: auto;
  box-shadow: 0 4px 6px rgba(0,0,0,0.2);
}

/* Daftar tenant */
#tenant ul {
  list-style: disc;
  padding-left: 20px;
}

/* Promo */
#promo ul {
  list-style: square;
  padding-left: 20px;
  margin-top: 10px;
}

/* Footer */
footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 15px 0;
  margin-top: 30px;
}

footer a {
  color: #4233ca;
  text-decoration: none;
  font-weight: bold;
}

footer a:hover {
  color: #fff;
}
```

Result : 




