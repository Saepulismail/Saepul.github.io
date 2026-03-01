<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Saepul Ismail | Demi Chef Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    /* Dasar Desain */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #f8fafc;
      color: #1e293b;
      line-height: 1.6;
    }

    /* Header & Navigasi */
    header {
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 48px;
      font-weight: 700;
      letter-spacing: -1px;
    }

    header p {
      font-size: 20px;
      margin-top: 10px;
      color: #cbd5e1;
    }

    /* Kontainer Utama */
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 60px 20px;
    }

    .section-title {
      font-size: 28px;
      margin-bottom: 30px;
      font-weight: 600;
      color: #0f172a;
      border-left: 5px solid #0ea5e9;
      padding-left: 15px;
    }

    /* Bagian Profil */
    .about-content {
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.05);
      margin-bottom: 40px;
    }

    /* Keahlian & Sertifikasi */
    .grid-layout {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
    }

    .skills ul {
      list-style: none;
    }

    .skills li {
      background: white;
      margin-bottom: 12px;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
      border-left: 3px solid #0ea5e9;
    }

    .certificate-box {
      background: #e0f2fe;
      padding: 25px;
      border-radius: 12px;
      border: 1px dashed #0ea5e9;
    }

    .certificate-box h3 {
      color: #0369a1;
      margin-bottom: 10px;
    }

    /* Kontak */
    .contact {
      text-align: center;
      margin-top: 50px;
      padding: 40px;
      background: #1e293b;
      color: white;
      border-radius: 20px;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 15px 35px;
      background: #0ea5e9;
      color: white;
      text-decoration: none;
      border-radius: 50px;
      font-weight: 600;
      transition: 0.3s;
    }

    .btn:hover {
      background: #0284c7;
      transform: translateY(-3px);
    }

    footer {
      text-align: center;
      padding: 30px;
      font-size: 14px;
      color: #64748b;
    }

    /* Responsif Mobile */
    @media(max-width: 768px){
      .grid-layout { grid-template-columns: 1fr; }
      header h1 { font-size: 32px; }
    }
  </style>
</head>
<body>

<header>
  <h1>Saepul Ismail</h1>
  <p>Demi Chef / Chef de Partie profesional</p>
</header>

<div class="container">
  
  <h2 class="section-title">Tentang Saya</h2>
  <div class="about-content">
    <p>
      Saya adalah seorang profesional kuliner yang berpengalaman sebagai 
      <strong>Demi Chef / Chef de Partie</strong> di RM Padang Payakumbuah. 
      Saya memiliki dedikasi tinggi terhadap kualitas makanan, konsistensi rasa, serta standar keamanan pangan.
    </p>
    <br>
    <p>
      Terbiasa bekerja dalam lingkungan dapur profesional dengan tekanan tinggi 
      serta mampu memimpin dan mengelola section secara efektif.
    </p>
  </div>

  <div class="grid-layout">
    <div class="skills-section">
      <h2 class="section-title">Keahlian Profesional</h2>
      <div class="skills">
        <ul>
          <li>Manajemen Section Dapur</li>
          <li>Food Quality Control & Konsistensi Rasa</li>
          <li>Food Safety & Hygiene Standard</li>
          <li>Inventory & Food Cost Control</li>
          <li>Supervisi dan Training Staff Junior</li>
        </ul>
      </div>
    </div>

    <div class="cert-section">
      <h2 class="section-title">Sertifikasi</h2>
      <div class="certificate-box">
        <h3>HACCP (Hazard Analysis Critical Control Point)</h3>
        <p>
          Memiliki sertifikat HACCP sebagai bukti kompetensi dalam sistem keamanan pangan 
          dan penerapan standar internasional dalam pengolahan makanan.
        </p>
      </div>
    </div>
  </div>

  <div class="contact">
    <h2 style="margin-bottom: 15px;">Hubungi Saya</h2>
    <p>Email: saepulismail1933@gmail.com</p>
    <p>Telepon: 081573554544</p>
    <a href="mailto:saepulismail1933@gmail.com" class="btn">Kirim Pesan Sekarang</a>
  </div>

</div>

<footer>
  &copy; 2024 Saepul Ismail Portfolio. All rights reserved.
</footer>

</body>
</html>
