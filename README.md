# Journ
<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Website Saya</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, Helvetica, sans-serif; }
    body { line-height: 1.6; color: #222; }
    header { background: linear-gradient(135deg, #4f46e5, #6366f1); color: white; padding: 60px 20px; text-align: center; }
    header h1 { font-size: 2.5rem; margin-bottom: 10px; }
    header p { font-size: 1.1rem; opacity: 0.9; }
    nav { background: #111827; padding: 10px 20px; position: sticky; top: 0; }
    nav a { color: #e5e7eb; margin-right: 15px; text-decoration: none; font-size: 0.95rem; }
    nav a:hover { color: #fff; }
    section { padding: 60px 20px; max-width: 1000px; margin: auto; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { border: 1px solid #e5e7eb; border-radius: 12px; padding: 20px; box-shadow: 0 10px 20px rgba(0,0,0,0.05); }
    .card h3 { margin-bottom: 10px; }
    .btn { display: inline-block; margin-top: 15px; padding: 10px 18px; background: #4f46e5; color: white; border-radius: 8px; text-decoration: none; font-size: 0.9rem; }
    .btn:hover { background: #4338ca; }
    footer { background: #111827; color: #9ca3af; text-align: center; padding: 30px 20px; font-size: 0.85rem; }
  </style>
</head>
<body>  <header>
    <h1>Selamat Datang</h1>
    <p>Ini adalah website sederhana yang siap kamu kembangkan 🚀</p>
  </header>  <nav>
    <a href="#tentang">Tentang</a>
    <a href="#layanan">Layanan</a>
    <a href="#kontak">Kontak</a>
  </nav>  <section id="tentang">
    <h2>Tentang Saya</h2>
    <p style="margin-top:10px; max-width:700px;">Website ini cocok untuk profil pribadi, UMKM, portofolio, atau landing page. Desain dibuat sederhana, ringan, dan responsif di HP maupun laptop.</p>
  </section>  <section id="layanan">
    <h2>Layanan / Fitur</h2>
    <div class="grid" style="margin-top:20px;">
      <div class="card">
        <h3>Desain Simpel</h3>
        <p>Mudah dipahami dan nyaman dilihat oleh pengunjung.</p>
      </div>
      <div class="card">
        <h3>Responsif</h3>
        <p>Tampilan rapi di HP, tablet, dan desktop.</p>
      </div>
      <div class="card">
        <h3>Mudah Diedit</h3>
        <p>Kamu bisa mengganti teks, warna, dan konten dengan cepat.</p>
      </div>
    </div>
    <a href="#kontak" class="btn">Hubungi Saya</a>
  </section>  <section id="kontak">
    <h2>Kontak</h2>
    <p style="margin-top:10px;">Email: nama@email.com<br>WhatsApp: 08xxxxxxxxxx</p>
  </section>  <footer>
    © 2025 Website Saya. Dibuat sederhana & rapi.
  </footer></body>
</html>
