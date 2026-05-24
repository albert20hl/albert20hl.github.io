<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Albert Hugo Liberty | Biodata</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family:'Poppins', sans-serif;
      background:#f4f6f9;
      color:#1f2937;
      padding:40px 20px;
    }

    .container{
      max-width:1100px;
      margin:auto;
    }

    .profile-card{
      background:white;
      border-radius:24px;
      padding:40px;
      box-shadow:0 10px 30px rgba(0,0,0,0.06);
    }

    .top-section{
      display:flex;
      gap:40px;
      align-items:center;
      flex-wrap:wrap;
    }

    .image-box{
      width:230px;
      height:230px;
      border:2px dashed #cbd5e1;
      border-radius:24px;
      display:flex;
      align-items:center;
      justify-content:center;
      color:#94a3b8;
      font-size:15px;
      background:#f8fafc;
      overflow:hidden;
    }

    .image-box img{
      width:100%;
      height:100%;
      object-fit:cover;
    }

    .profile-info{
      flex:1;
    }

    .profile-info h1{
      font-size:42px;
      font-weight:700;
      margin-bottom:10px;
    }

    .subtitle{
      color:#64748b;
      font-size:16px;
      margin-bottom:20px;
    }

    .info-list{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:15px;
      margin-top:20px;
    }

    .info-item{
      background:#f8fafc;
      padding:16px;
      border-radius:16px;
    }

    .info-item span{
      display:block;
      font-size:13px;
      color:#64748b;
      margin-bottom:4px;
    }

    .section-title{
      margin-top:45px;
      margin-bottom:20px;
      font-size:24px;
      font-weight:600;
    }

    .interest-container{
      display:flex;
      flex-wrap:wrap;
      gap:15px;
    }

    .interest{
      background:#111827;
      color:white;
      padding:12px 20px;
      border-radius:14px;
      font-size:14px;
    }

    .box-container{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
      gap:20px;
      margin-top:20px;
    }

    .box{
      background:#f8fafc;
      padding:24px;
      border-radius:20px;
      transition:0.3s;
    }

    .box:hover{
      transform:translateY(-4px);
    }

    .box h3{
      margin-bottom:15px;
      font-size:20px;
    }

    .skills-list{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
    }

    .skill{
      background:white;
      border:1px solid #e2e8f0;
      padding:10px 14px;
      border-radius:12px;
      font-size:14px;
    }

    .quote{
      margin-top:35px;
      background:#111827;
      color:white;
      padding:30px;
      border-radius:24px;
      text-align:center;
      font-size:18px;
      font-style:italic;
      line-height:1.7;
    }

    .footer{
      margin-top:30px;
      text-align:center;
      color:#64748b;
      font-size:14px;
    }

    @media(max-width:768px){
      .profile-info h1{
        font-size:32px;
      }

      .top-section{
        justify-content:center;
        text-align:center;
      }

      .image-box{
        width:200px;
        height:200px;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="profile-card">

      <!-- TOP SECTION -->
      <div class="top-section">

        <!-- IMAGE -->
        <div class="image-box">
          Upload Foto
          <!-- 
          Untuk memasukkan gambar:
          Ganti tulisan "Upload Foto" dengan:
          <img src="Albert foto.jpeg" alt="Albert">
          -->
        </div>

        <!-- PROFILE INFO -->
        <div class="profile-info">
          <h1>Albert Hugo Liberty</h1>
          <p class="subtitle">
            Math & Physics Enthusiast • Future Aerospace Engineer 🚀
          </p>

          <div class="info-list">
            <div class="info-item">
              <span>Tanggal Lahir</span>
              20 Februari 2010
            </div>

            <div class="info-item">
              <span>Asal</span>
              Jakarta
            </div>

            <div class="info-item">
              <span>Sekolah</span>
              SMA Wardaya
            </div>

            <div class="info-item">
              <span>Instagram</span>
              @albert.lbrty
            </div>
          </div>
        </div>
      </div>

      <!-- INTERESTS -->
      <h2 class="section-title">Interests</h2>

      <div class="interest-container">
        <div class="interest">📚 Mathematics</div>
        <div class="interest">⚛️ Physics</div>
        <div class="interest">🎨 Drawing</div>
        <div class="interest">⚽ Futsal</div>
      </div>

      <!-- BOX SECTION -->
      <div class="box-container">

        <!-- ACHIEVEMENT -->
        <div class="box">
          <h3>🏆 Achievements</h3>

          <p>
            Albert has achieved several accomplishments in both academic and non-academic fields. 
            He won a school mathematics competition thanks to his strong analytical thinking 
            and problem-solving abilities. In sports, he also contributed to his futsal team’s 
            success in interschool tournaments through teamwork, discipline, and consistency.
          </p>
        </div>

        <!-- SKILLS -->
        <div class="box">
          <h3>✨ Skills</h3>

          <div class="skills-list">
            <div class="skill">Problem Solving</div>
            <div class="skill">Critical Thinking</div>
            <div class="skill">Fast Learner</div>
            <div class="skill">Leadership</div>
            <div class="skill">Teamwork</div>
            <div class="skill">Public Speaking</div>
          </div>
        </div>

      </div>

      <!-- QUOTE -->
      <div class="quote">
        “The future belongs to those who never stop learning and exploring.”
      </div>

      <!-- FOOTER -->
      <div class="footer">
        © 2026 Albert Hugo Liberty
      </div>

    </div>
  </div>

</body>
</html>
