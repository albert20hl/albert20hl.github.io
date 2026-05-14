<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Albert Hugo Liberty | Profile</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #74ebd5, #9face6);
      min-height: 100vh;
      color: #1f2937;
      overflow-x: hidden;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
      padding: 40px 0;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 50px;
      flex-wrap: wrap;
      background: rgba(255,255,255,0.2);
      backdrop-filter: blur(12px);
      border-radius: 30px;
      padding: 50px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    }

    .hero-text {
      flex: 1;
      min-width: 300px;
    }

    .hero-text h1 {
      font-size: 3.5rem;
      line-height: 1.1;
      color: white;
      margin-bottom: 20px;
    }

    .hero-text p {
      color: #f8fafc;
      font-size: 1.1rem;
      margin-bottom: 30px;
      line-height: 1.8;
    }

    .btn {
      display: inline-block;
      padding: 14px 28px;
      background: white;
      color: #4f46e5;
      text-decoration: none;
      font-weight: 600;
      border-radius: 50px;
      transition: 0.3s ease;
      box-shadow: 0 5px 15px rgba(0,0,0,0.15);
    }

    .btn:hover {
      transform: translateY(-3px);
      background: #f1f5f9;
    }

    .hero-image {
      flex: 1;
      display: flex;
      justify-content: center;
      min-width: 280px;
    }

    .profile-card {
      width: 320px;
      background: white;
      border-radius: 30px;
      overflow: hidden;
      box-shadow: 0 15px 40px rgba(0,0,0,0.2);
      transition: 0.4s ease;
    }

    .profile-card:hover {
      transform: translateY(-8px);
    }

    .profile-img {
      width: 100%;
      height: 360px;
      object-fit: cover;
      background: #e2e8f0;
    }

    .profile-content {
      padding: 25px;
      text-align: center;
    }

    .profile-content h2 {
      font-size: 1.8rem;
      margin-bottom: 10px;
      color: #111827;
    }

    .profile-content span {
      color: #6366f1;
      font-weight: 500;
    }

    .section-title {
      text-align: center;
      margin: 70px 0 40px;
      color: white;
      font-size: 2.5rem;
      font-weight: 700;
    }

    .info-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .info-card {
      background: rgba(255,255,255,0.25);
      backdrop-filter: blur(10px);
      padding: 30px;
      border-radius: 25px;
      color: white;
      transition: 0.3s ease;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    }

    .info-card:hover {
      transform: translateY(-6px);
      background: rgba(255,255,255,0.35);
    }

    .info-card h3 {
      margin-bottom: 15px;
      font-size: 1.3rem;
    }

    .info-card p {
      line-height: 1.7;
      font-size: 1rem;
    }

    .achievement {
      margin-top: 60px;
      background: white;
      border-radius: 30px;
      padding: 45px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.15);
    }

    .achievement h2 {
      color: #4f46e5;
      margin-bottom: 20px;
      font-size: 2rem;
    }

    .achievement ul {
      padding-left: 20px;
    }

    .achievement li {
      margin-bottom: 15px;
      font-size: 1.05rem;
      line-height: 1.7;
    }

    footer {
      text-align: center;
      margin-top: 60px;
      color: white;
      padding-bottom: 20px;
      font-size: 0.95rem;
    }

    @media (max-width: 768px) {
      .hero {
        padding: 35px 25px;
        text-align: center;
      }

      .hero-text h1 {
        font-size: 2.5rem;
      }

      .profile-card {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <div class="container">

    <section class="hero">
      <div class="hero-text">
        <h1>Albert Hugo Liberty</h1>
        <p>
          Halo! Saya Albert Hugo Liberty, seorang siswa dari SMA Wardaya yang berasal dari Jakarta.
          Saya memiliki minat besar di bidang matematika, fisika, dan teknologi. Selain belajar,
          saya juga senang bermain futsal dan mengikuti berbagai kompetisi akademik maupun olahraga.
        </p>

        <a href="https://instagram.com/albert.lbrty" target="_blank" class="btn">
          Follow Instagram
        </a>
      </div>

      <div class="hero-image">
        <div class="profile-card">
          <img src="Albert foto.jpeg" alt="Foto Albert" class="profile-img">

          <div class="profile-content">
            <h2>Albert Hugo Liberty</h2>
            <span>Siswa SMA Wardaya</span>
          </div>
        </div>
      </div>
    </section>

    <h2 class="section-title">Tentang Saya</h2>

    <section class="info-grid">
      <div class="info-card">
        <h3>📅 Tanggal Lahir</h3>
        <p>20 Februari 2010</p>
      </div>

      <div class="info-card">
        <h3>🏫 Sekolah</h3>
        <p>SMA Wardaya</p>
      </div>

      <div class="info-card">
        <h3>📍 Kota Asal</h3>
        <p>Jakarta</p>
      </div>

      <div class="info-card">
        <h3>⚽ Hobi</h3>
        <p>Belajar matematika dan bermain futsal</p>
      </div>

      <div class="info-card">
        <h3>🎯 Cita-cita</h3>
        <p>Bisa bekerja di NVIDIA</p>
      </div>

      <div class="info-card">
        <h3>📚 Pelajaran Favorit</h3>
        <p>Matematika dan Fisika</p>
      </div>
    </section>

    <section class="achievement">
      <h2>🏆 Prestasi</h2>

      <ul>
        <li>Memenangkan beberapa lomba matematika di tingkat sekolah maupun kompetisi lainnya.</li>
        <li>Berpartisipasi dan meraih prestasi dalam kompetisi futsal.</li>
        <li>Aktif mengembangkan kemampuan akademik terutama dalam matematika dan fisika.</li>
      </ul>
    </section>

    <footer>
      © 2026 Albert Hugo Liberty | Personal Profile Website
    </footer>

  </div>

</body>
</html>
