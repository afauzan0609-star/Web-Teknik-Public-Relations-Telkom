<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Telkom Connect — Weblog Resmi</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600;700&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
  <style>
    :root{--red:#E60000;--dark:#111;--muted:#666}
    *{box-sizing:border-box}
    body{font-family:Roboto,system-ui,Segoe UI,Arial;line-height:1.6;margin:0;color:var(--dark);background:#f7f7f9}
    header{background:white;border-bottom:1px solid #eee}
    .container{max-width:1000px;margin:0 auto;padding:20px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:8px;background:var(--red);display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
    nav{margin-left:auto}
    nav a{margin-left:16px;text-decoration:none;color:var(--dark);font-weight:500}
    .hero{background:white;padding:28px;margin-top:18px;border-radius:8px;display:flex;gap:20px;align-items:center}
    .hero h1{margin:0;font-family:Poppins,Roboto;font-size:24px}
    .grid{display:grid;grid-template-columns:2fr 1fr;gap:20px;margin-top:18px}
    article.card{background:white;padding:18px;border-radius:8px}
    .sidebar{display:flex;flex-direction:column;gap:12px}
    .profile dt{font-weight:700}
    .profile dd{margin:0 0 8px 0;color:var(--muted)}
    .news-item{border-bottom:1px dashed #eee;padding:12px 0}
    .news-item:last-child{border-bottom:none}
    .gallery img{max-width:100%;border-radius:6px}
    footer{padding:18px 0;margin-top:22px;text-align:center;color:var(--muted)}
    .btn{display:inline-block;padding:8px 14px;border-radius:6px;background:var(--red);color:white;text-decoration:none;font-weight:600}
    @media(max-width:800px){.grid{grid-template-columns:1fr}.brand{flex-direction:row}nav{margin-left:8px}}
  </style>
</head>
<body>
  <header>
    <div class="container" style="display:flex;align-items:center">
      <div class="brand">
        <div class="logo">T</div>
        <div>
          <div style="font-weight:700">Telkom Connect</div>
          <div style="font-size:12px;color:var(--muted)">Wawasan & berita resmi Telkom Indonesia</div>
        </div>
      </div>
      <nav>
        <a href="#home">Home</a>
        <a href="#profil">Profil</a>
        <a href="#layanan">Layanan</a>
        <a href="#berita">Berita</a>
        <a href="#galeri">Galeri</a>
        <a href="#kontak">Kontak</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="home" class="hero">
      <div style="flex:1">
        <h1>Selamat datang di Telkom Connect</h1>
        <p style="margin-top:8px;color:var(--muted)">Sumber resmi berita, insight, dan pengumuman produk layanan Telkom Indonesia. Mempercepat transformasi digital untuk Indonesia.</p>
        <p style="margin-top:12px"><a class="btn" href="#berita">Baca Berita Terbaru</a></p>
      </div>
      <div style="width:220px;text-align:center">
        <!-- Contoh ilustrasi/placeholder -->
        <img src="/mnt/data/314b05d6-50d8-46bd-9272-1bb56d7af6ea.png" alt="Brosur Telkom" style="width:100%;border-radius:8px;box-shadow:0 6px 18px rgba(0,0,0,0.06)">
        <div style="font-size:12px;color:var(--muted);margin-top:8px">Brosur / materi promosi (contoh)</div>
      </div>
    </section>

    <div class="grid">
      <div>
        <article id="profil" class="card">
          <h2>Profil Perusahaan</h2>
          <dl class="profile">
            <dt>Visi</dt>
            <dd>Menjadi digital telco pilihan utama untuk memajukan masyarakat Indonesia.</dd>
            <dt>Misi</dt>
            <dd>1) Menyediakan layanan digital yang inovatif dan berkualitas.<br>2) Mempercepat transformasi digital nasional.<br>3) Mendukung pengembangan SDM digital.</dd>
            <dt>Struktur Organisasi (singkat)</dt>
            <dd>Dewan Komisaris → Direksi → Divisi: Network, Enterprise Service, Consumer Service, Digital Service, Finance, HR.</dd>
            <dt>Bidang Usaha</dt>
            <dd>Telekomunikasi, layanan internet, data center & cloud, TV digital, solusi ICT, layanan digital untuk korporasi dan konsumen.</dd>
          </dl>
        </article>

        <article id="layanan" class="card" style="margin-top:14px">
          <h2>Layanan Unggulan</h2>
          <ul>
            <li><strong>IndiHome</strong> – Layanan internet fiber untuk rumah dan bisnis.</li>
            <li><strong>Telkom Cloud</strong> – Data center & layanan cloud untuk korporasi.</li>
            <li><strong>Solusi ICT</strong> – Managed services, IoT, cybersecurity.</li>
            <li><strong>Pelatihan Digital</strong> – Program pelatihan untuk UMKM dan masyarakat.</li>
          </ul>
        </article>

        <article id="berita" class="card" style="margin-top:14px">
          <h2>Berita Terbaru</h2>

          <div class="news-item">
            <h3 style="margin:0 0 6px 0">Perluasan Jaringan Fiber Optic IndiHome di Daerah X</h3>
            <p style="margin:0;color:var(--muted)">Telkom melakukan perluasan jaringan fiber optic untuk meningkatkan konektivitas di wilayah X, mendukung akses pendidikan dan UMKM digital.</p>
            <p style="margin-top:8px;font-size:13px;color:var(--muted)">Tanggal: 12 November 2025</p>
          </div>

          <div class="news-item">
            <h3 style="margin:0 0 6px 0">Telkom Gelar Pelatihan Digital untuk 500 UMKM</h3>
            <p style="margin:0;color:var(--muted)">Program pelatihan meliputi pemasaran digital, keamanan siber, dan pemanfaatan layanan cloud untuk UMKM di wilayah Y.</p>
            <p style="margin-top:8px;font-size:13px;color:var(--muted)">Tanggal: 3 Oktober 2025</p>
          </div>

        </article>

      </div>

      <aside class="sidebar">
        <section class="card">
          <h3>Kontak & Sosial Media</h3>
          <p style="margin:6px 0;color:var(--muted)">Telkom Indonesia<br>Jl. Japati No.1, Bandung<br>Tel: (022) 123-4567</p>
          <p style="margin:6px 0"><strong>Follow:</strong> @telkomindonesia (Twitter/IG)</p>
        </section>

        <section class="card">
          <h3>Galeri</h3>
          <div class="gallery">
            <!-- Menggunakan path file yang Anda unggah -->
            <img src="/mnt/data/314b05d6-50d8-46bd-9272-1bb56d7af6ea.png" alt="Brosur Telkom contoh">
            <p style="font-size:13px;color:var(--muted);margin-top:8px">Brosur promosi (contoh). Unggah foto kegiatan untuk melengkapi galeri.</p>
          </div>
        </section>

        <section class="card">
          <h3>Langganan Newsletter</h3>
          <p style="margin:6px 0;color:var(--muted)">Dapatkan update berita dan pengumuman produk Telkom.</p>
          <form onsubmit="event.preventDefault();alert('Terima kasih sudah berlangganan!');">
            <input type="email" placeholder="email@domain.com" required style="width:100%;padding:8px;margin-top:8px;border:1px solid #ddd;border-radius:6px">
            <button class="btn" style="width:100%;margin-top:8px">Berlangganan</button>
          </form>
        </section>
      </aside>
    </div>

    <section id="kontak" class="card" style="margin-top:18px">
      <h2>Hubungi Kami</h2>
      <p style="color:var(--muted)">Untuk pertanyaan media, kerjasama, atau informasi layanan, silakan hubungi tim komunikasi Telkom.</p>
      <p style="margin-top:8px"><strong>Email:</strong> comms@telkom.co.id &nbsp; <strong>Tel:</strong> (022) 123-4567</p>
    </section>

  </main>

  <footer>
    <div class="container">
      <small>&copy; 2025 Telkom Indonesia — Telkom Connect. Semua hak dilindungi.</small>
    </div>
  </footer>

</body>
</html>

