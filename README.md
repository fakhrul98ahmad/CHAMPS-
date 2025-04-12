<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PSS CHAMPS</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #d0e9ff, #f0f8ff);
      margin: 0;
      padding: 0;
      color: #2c3e50;
    }
    header {
      background: linear-gradient(135deg, #8e44ad, #6c5ce7);
      color: white;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      position: relative;
      border-bottom-left-radius: 40px;
      border-bottom-right-radius: 40px;
    }
    .logos {
      position: absolute;
      top: 15px;
      right: 20px;
      display: flex;
      gap: 10px;
    }
    .logos img {
      height: 60px;
      border-radius: 12px;
      background: white;
      padding: 5px;
    }
    .robot-image {
      width: 120px;
      position: absolute;
      top: 15px;
      left: 20px;
      animation: float 3s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    nav {
      background: #a29bfe;
      padding: 15px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }
    nav li {
      position: relative;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffeaa7;
    }
    nav li:hover > ul {
      display: block;
    }
    nav ul ul {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      background: #a29bfe;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      z-index: 1000;
    }
    nav ul ul li {
      padding: 10px 20px;
      white-space: nowrap;
    }
    nav ul ul li a {
      color: white;
    }
    main {
      padding: 30px 20px;
    }
    section {
      margin-bottom: 40px;
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    section:hover {
      transform: scale(1.02);
    }
    footer {
      background: #6c5ce7;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 14px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 12px;
      text-align: left;
    }
    th {
      background: #dfe6e9;
    }
    form input, form button {
      padding: 10px;
      margin-top: 10px;
      width: 100%;
      max-width: 400px;
      margin-bottom: 10px;
      border: 1px solid #b2bec3;
      border-radius: 8px;
    }
    form button {
      background: #6c5ce7;
      color: white;
      font-weight: bold;
      border: none;
      cursor: pointer;
    }
    form button:hover {
      background: #a29bfe;
    }
    h1, h2 {
      color: #2d3436;
    }
    h1 {
      font-size: 2.8em;
    }
    h2 {
      font-size: 2em;
    }
  </style>
</head>
<body>
  <header>
    <img class="robot-image" src="https://cdn-icons-png.flaticon.com/512/4712/4712104.png" alt="Robot Digital">
    <div class="logos">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Logo_Kementerian_Pendidikan_Malaysia.svg/1200px-Logo_Kementerian_Pendidikan_Malaysia.svg.png" alt="Logo KPM">
      <img src="/mnt/data/logo-removebg-preview.png" alt="Logo Sekolah">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Logo_NILAM_Malaysia.svg/512px-Logo_NILAM_Malaysia.svg.png" alt="Logo NILAM Johor">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Library_icon.svg/1024px-Library_icon.svg.png" alt="Logo PSS">
    </div>
    <h1>PSS CHAMPS</h1>
    <p>Selamat datang ke Portal Pusat Sumber Sekolah - CHAMPS</p>
  </header>

  <nav>
    <ul>
      <li><a href="#">Utama</a>
        <ul>
          <li><a href="#">Visi dan Misi PSS</a></li>
          <li><a href="#">Piagam Pelanggan</a></li>
          <li><a href="#">Hebahan</a></li>
        </ul>
      </li>
      <li><a href="#">Korporat</a>
        <ul>
          <li><a href="#">Carta Organisasi</a></li>
          <li><a href="#">Maklumat Pengawas PSS</a></li>
        </ul>
      </li>
      <li><a href="#">e-Perkhidmatan</a>
        <ul>
          <li><a href="#">Carian Buku</a></li>
          <li><a href="#">Pinjaman dan Pemulangan Buku</a></li>
          <li><a href="#">Semakan Emel MOE Murid</a></li>
          <li><a href="#">Semakan Jadual Perpustakaan</a></li>
          <li><a href="#">Lain-lain</a></li>
        </ul>
      </li>
      <li><a href="#">Direktori</a>
        <ul>
          <li><a href="#">Maklumat Emel</a></li>
          <li><a href="#">Laman Web PSS</a></li>
          <li><a href="#">Nombor Telefon Sekolah dan Guru</a></li>
        </ul>
      </li>
    </ul>
  </nav>

  <main>
    <section>
      <h2>Selamat Datang ke PSS CHAMPS!</h2>
      <p>Portal ini menyediakan pelbagai maklumat dan perkhidmatan digital untuk murid-murid. Klik pada menu di atas untuk mula meneroka.</p>
    </section>
  </main>

  <footer>
    &copy; 2025 Pusat Sumber Sekolah CHAMPS. Semua Hak Cipta Terpelihara.
  </footer>
</body>
</html>
