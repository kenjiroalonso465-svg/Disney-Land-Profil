<!DOCTYPE html>
<html lang="id">
<head>
  <!-- ========== META & JUDUL ========== -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Website biodata diri - Budi Santoso, siswa Sekolah Kalam Kudus Malang">
  <title>Biodata Diri | Budi Santoso</title>
  <link rel="icon" type="image/svg+xml" href="assets/icons/favicon.svg">

  <!-- ========== LIBRARY: Google Fonts, Bootstrap 5, Bootstrap Icons ========== -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css" rel="stylesheet">

  <!-- ========== CSS KUSTOM ========== -->
  <link href="css/style.css" rel="stylesheet">
</head>

<body>

  <!-- ==================== NAVBAR (sticky) ==================== -->
  <nav class="navbar navbar-expand-lg fixed-top site-nav" id="navbar">
    <div class="container">
      <a class="navbar-brand fw-semibold" href="#home"><i class="bi bi-person-badge-fill me-2"></i>Budi Santoso</a>
      <button class="navbar-toggler border-0" type="button" data-bs-toggle="collapse" data-bs-target="#menu" aria-controls="menu" aria-expanded="false" aria-label="Buka menu">
        <i class="bi bi-list fs-2"></i>
      </button>
      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto gap-lg-1">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#tentang">Tentang Saya</a></li>
          <li class="nav-item"><a class="nav-link" href="#pendidikan">Pendidikan</a></li>
          <li class="nav-item"><a class="nav-link" href="#prestasi">Prestasi &amp; Pengalaman</a></li>
          <li class="nav-item"><a class="nav-link" href="#galeri">Galeri</a></li>
          <li class="nav-item"><a class="nav-link" href="#kontak">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <main>

    <!-- ==================== HOME (hero fullscreen) ==================== -->
    <section id="home" class="hero d-flex align-items-center">
      <div class="container">
        <div class="row align-items-center g-5 flex-column-reverse flex-lg-row">
          <!-- Teks hero -->
          <div class="col-lg-7 text-center text-lg-start hero-text">
            <p class="hero-hello"><i class="bi bi-stars me-1"></i>Halo, perkenalkan saya</p>
            <!-- DATA: nama, kelas, sekolah, motto -->
            <h1 class="hero-name">Budi Santoso</h1>
            <p class="hero-meta"><i class="bi bi-mortarboard-fill me-2"></i>Kelas XI IPA 1</p>
            <p class="hero-meta"><i class="bi bi-building me-2"></i>Sekolah Kalam Kudus Malang</p>
            <blockquote class="hero-motto">“Belajar hari ini, berkarya untuk esok hari.”</blockquote>
            <div class="d-flex flex-wrap gap-3 justify-content-center justify-content-lg-start mt-4">
              <a href="#tentang" class="btn btn-main btn-lg"><i class="bi bi-person-lines-fill me-2"></i>Lihat Biodata</a>
              <a href="#kontak" class="btn btn-outline-main btn-lg"><i class="bi bi-chat-dots-fill me-2"></i>Hubungi Saya</a>
            </div>
          </div>
          <!-- Foto profil lingkaran -->
          <div class="col-lg-5 text-center">
            <div class="avatar-wrap">
              <img src="assets/images/profil.svg" alt="Foto profil Budi Santoso" class="avatar">
            </div>
          </div>
        </div>
      </div>
      <a href="#tentang" class="scroll-down" aria-label="Gulir ke bawah"><i class="bi bi-chevron-double-down"></i></a>
    </section>

    <!-- ==================== TENTANG SAYA ==================== -->
    <section id="tentang" class="section">
      <div class="container">
        <div class="section-head reveal">
          <h2>Tentang Saya</h2>
          <p>Sedikit cerita tentang siapa saya.</p>
        </div>

        <div class="row g-4">
          <!-- Biodata lengkap -->
          <div class="col-lg-7 reveal">
            <div class="card-soft h-100">
              <h3 class="card-title-sm"><i class="bi bi-card-list me-2"></i>Biodata Lengkap</h3>
              <!-- DATA: biodata (mudah diganti) -->
              <dl class="bio-list">
                <div><dt><i class="bi bi-person"></i>Nama</dt><dd>Budi Santoso</dd></div>
                <div><dt><i class="bi bi-calendar-heart"></i>Tempat, Tgl Lahir</dt><dd>Malang, 12 Maret 2009</dd></div>
                <div><dt><i class="bi bi-gender-ambiguous"></i>Jenis Kelamin</dt><dd>Laki-laki</dd></div>
                <div><dt><i class="bi bi-geo-alt"></i>Alamat</dt><dd>Jl. Contoh No. 10, Malang, Jawa Timur</dd></div>
                <div><dt><i class="bi bi-heart"></i>Agama</dt><dd>Kristen</dd></div>
                <div><dt><i class="bi bi-controller"></i>Hobi</dt><dd>Membaca, bermain basket, coding</dd></div>
                <div><dt><i class="bi bi-rocket-takeoff"></i>Cita-cita</dt><dd>Software Engineer</dd></div>
              </dl>
            </div>
          </div>

          <!-- Deskripsi + counter -->
          <div class="col-lg-5 reveal" style="--d:.15s">
            <div class="card-soft card-blue h-100">
              <h3 class="card-title-sm"><i class="bi bi-chat-quote me-2"></i>Deskripsi Diri</h3>
              <!-- DATA: deskripsi singkat -->
              <p>Saya seorang pelajar yang rajin, ramah, dan suka mencoba hal baru. Saya tertarik pada teknologi dan senang bekerja dalam tim untuk menyelesaikan proyek yang bermanfaat.</p>
              <div class="row text-center g-2 mt-3">
                <div class="col-4"><div class="counter-num"><span class="counter" data-target="12">0</span>+</div><small>Prestasi</small></div>
                <div class="col-4"><div class="counter-num"><span class="counter" data-target="5">0</span></div><small>Organisasi</small></div>
                <div class="col-4"><div class="counter-num"><span class="counter" data-target="8">0</span>+</div><small>Sertifikat</small></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== PENDIDIKAN (timeline) ==================== -->
    <section id="pendidikan" class="section section-alt">
      <div class="container">
        <div class="section-head reveal">
          <h2>Pendidikan</h2>
          <p>Perjalanan belajar saya dari waktu ke waktu.</p>
        </div>

        <div class="timeline">
          <!-- DATA: SD -->
          <div class="tl-item reveal">
            <span class="tl-dot"><i class="bi bi-backpack2"></i></span>
            <div class="card-soft">
              <span class="badge-soft">2015 – 2021</span>
              <h3>SD Negeri Contoh 1 Malang</h3>
              <p>Sekolah Dasar. Belajar dasar membaca, menulis, dan berhitung, serta aktif di kegiatan pramuka.</p>
            </div>
          </div>
          <!-- DATA: SMP -->
          <div class="tl-item reveal">
            <span class="tl-dot"><i class="bi bi-book"></i></span>
            <div class="card-soft">
              <span class="badge-soft">2021 – 2024</span>
              <h3>SMP Contoh Malang</h3>
              <p>Sekolah Menengah Pertama. Mulai mengikuti lomba sains dan bergabung dengan OSIS.</p>
            </div>
          </div>
          <!-- DATA: SMA (sekolah sekarang) -->
          <div class="tl-item reveal">
            <span class="tl-dot tl-now"><i class="bi bi-mortarboard"></i></span>
            <div class="card-soft card-blue">
              <span class="badge-soft badge-light">2024 – Sekarang</span>
              <h3>Sekolah Kalam Kudus Malang</h3>
              <p>Sekolah Menengah Atas (sekolah saat ini). Fokus mengembangkan prestasi akademik, kepemimpinan, dan karakter.</p>
              <a href="https://skkkmalang.sch.id/" target="_blank" rel="noopener" class="btn btn-light btn-sm rounded-pill"><i class="bi bi-box-arrow-up-right me-1"></i>Kunjungi Website Sekolah</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== PRESTASI & PENGALAMAN ==================== -->
    <section id="prestasi" class="section">
      <div class="container">
        <div class="section-head reveal">
          <h2>Prestasi &amp; Pengalaman</h2>
          <p>Hal-hal yang sudah saya capai dan jalani.</p>
        </div>

        <!-- DATA: card prestasi (6 kartu) -->
        <div class="row g-4">
          <div class="col-md-6 col-lg-4 reveal">
            <div class="card-soft feature h-100">
              <div class="icon-box"><i class="bi bi-trophy"></i></div>
              <h3>Prestasi Akademik</h3>
              <p>Peringkat 3 besar paralel kelas XI dan Juara 2 Olimpiade Matematika tingkat kota.</p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 reveal" style="--d:.1s">
            <div class="card-soft feature h-100">
              <div class="icon-box"><i class="bi bi-dribbble"></i></div>
              <h3>Prestasi Non Akademik</h3>
              <p>Juara 1 turnamen basket antar sekolah dan finalis lomba desain poster.</p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 reveal" style="--d:.2s">
            <div class="card-soft feature h-100">
              <div class="icon-box"><i class="bi bi-people"></i></div>
              <h3>Organisasi</h3>
              <p>Anggota OSIS (Seksi Teknologi) dan Ketua Klub Coding sekolah.</p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 reveal">
            <div class="card-soft feature h-100">
              <div class="icon-box"><i class="bi bi-calendar-event"></i></div>
              <h3>Kepanitiaan</h3>
              <p>Koordinator Dokumentasi Perayaan Natal Sekolah dan panitia Pentas Seni.</p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 reveal" style="--d:.1s">
            <div class="card-soft feature h-100">
              <div class="icon-box"><i class="bi bi-flag"></i></div>
              <h3>Pengalaman Lomba</h3>
              <p>Peserta lomba karya ilmiah remaja, debat bahasa Inggris, dan hackathon pelajar.</p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 reveal" style="--d:.2s">
            <div class="card-soft feature h-100">
              <div class="icon-box"><i class="bi bi-patch-check"></i></div>
              <h3>Sertifikat</h3>
              <p>Sertifikat dasar pemrograman web, TOEFL Junior, dan pelatihan kepemimpinan.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== GALERI / PORTOFOLIO ==================== -->
    <section id="galeri" class="section section-alt">
      <div class="container">
        <div class="section-head reveal">
          <h2>Galeri &amp; Portofolio</h2>
          <p>Dokumentasi kegiatan dan karya saya. Klik gambar untuk memperbesar.</p>
        </div>

        <!-- DATA: item galeri (ganti src, judul, dan deskripsi) -->
        <div class="row g-4">
          <div class="col-sm-6 col-lg-4 reveal">
            <figure class="gallery-item" data-bs-toggle="modal" data-bs-target="#imgModal" tabindex="0" role="button">
              <div class="gallery-img"><img src="assets/gallery/galeri-1.svg" alt="Karya Seni"></div>
              <figcaption><h4>Karya Seni</h4><p>Ilustrasi digital untuk pameran sekolah.</p></figcaption>
            </figure>
          </div>
          <div class="col-sm-6 col-lg-4 reveal" style="--d:.1s">
            <figure class="gallery-item" data-bs-toggle="modal" data-bs-target="#imgModal" tabindex="0" role="button">
              <div class="gallery-img"><img src="assets/gallery/galeri-2.svg" alt="Kegiatan Sekolah"></div>
              <figcaption><h4>Kegiatan Sekolah</h4><p>Hari Pendidikan bersama teman sekelas.</p></figcaption>
            </figure>
          </div>
          <div class="col-sm-6 col-lg-4 reveal" style="--d:.2s">
            <figure class="gallery-item" data-bs-toggle="modal" data-bs-target="#imgModal" tabindex="0" role="button">
              <div class="gallery-img"><img src="assets/gallery/galeri-3.svg" alt="Lomba Sains"></div>
              <figcaption><h4>Lomba Sains</h4><p>Presentasi karya ilmiah tingkat kota.</p></figcaption>
            </figure>
          </div>
          <div class="col-sm-6 col-lg-4 reveal">
            <figure class="gallery-item" data-bs-toggle="modal" data-bs-target="#imgModal" tabindex="0" role="button">
              <div class="gallery-img"><img src="assets/gallery/galeri-4.svg" alt="Kegiatan Organisasi"></div>
              <figcaption><h4>Kegiatan Organisasi</h4><p>Rapat dan program kerja OSIS.</p></figcaption>
            </figure>
          </div>
          <div class="col-sm-6 col-lg-4 reveal" style="--d:.1s">
            <figure class="gallery-item" data-bs-toggle="modal" data-bs-target="#imgModal" tabindex="0" role="button">
              <div class="gallery-img"><img src="assets/gallery/galeri-5.svg" alt="Kegiatan Sosial"></div>
              <figcaption><h4>Kegiatan Sosial</h4><p>Bakti sosial bersama komunitas sekolah.</p></figcaption>
            </figure>
          </div>
          <div class="col-sm-6 col-lg-4 reveal" style="--d:.2s">
            <figure class="gallery-item" data-bs-toggle="modal" data-bs-target="#imgModal" tabindex="0" role="button">
              <div class="gallery-img"><img src="assets/gallery/galeri-6.svg" alt="Proyek Pribadi"></div>
              <figcaption><h4>Proyek Pribadi</h4><p>Website portofolio sederhana buatan sendiri.</p></figcaption>
            </figure>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== KONTAK ==================== -->
    <section id="kontak" class="section">
      <div class="container">
        <div class="section-head reveal">
          <h2>Kontak</h2>
          <p>Mari terhubung dan berkenalan lebih jauh.</p>
        </div>

        <div class="row g-4">
          <!-- Info kontak (DATA: ganti dengan data asli) -->
          <div class="col-lg-5 reveal">
            <div class="card-soft h-100">
              <ul class="contact-list">
                <li><span class="icon-box sm"><i class="bi bi-envelope"></i></span><div><small>Email</small><a href="mailto:budi.santoso@gmail.com">budi.santoso@gmail.com</a></div></li>
                <li><span class="icon-box sm"><i class="bi bi-telephone"></i></span><div><small>Nomor HP</small><a href="tel:+6281234567890">+62 812-3456-7890</a></div></li>
                <li><span class="icon-box sm"><i class="bi bi-geo-alt"></i></span><div><small>Alamat</small><span>Jl. Contoh No. 10, Malang, Jawa Timur</span></div></li>
                <li><span class="icon-box sm"><i class="bi bi-linkedin"></i></span><div><small>LinkedIn</small><a href="https://www.linkedin.com/" target="_blank" rel="noopener">linkedin.com/in/budisantoso</a></div></li>
                <li><span class="icon-box sm"><i class="bi bi-github"></i></span><div><small>GitHub</small><a href="https://github.com/" target="_blank" rel="noopener">github.com/budisantoso</a></div></li>
                <li><span class="icon-box sm"><i class="bi bi-instagram"></i></span><div><small>Instagram</small><a href="https://www.instagram.com/" target="_blank" rel="noopener">@budisantoso</a></div></li>
              </ul>
              <div class="d-flex flex-wrap gap-2 mt-4">
                <a href="https://www.linkedin.com/" target="_blank" rel="noopener" class="btn btn-main"><i class="bi bi-linkedin me-2"></i>LinkedIn</a>
                <a href="https://github.com/" target="_blank" rel="noopener" class="btn btn-main"><i class="bi bi-github me-2"></i>GitHub</a>
                <a href="https://skkkmalang.sch.id/" target="_blank" rel="noopener" class="btn btn-outline-main"><i class="bi bi-building me-2"></i>Website Sekolah</a>
              </div>
            </div>
          </div>

          <!-- Google Maps placeholder (ganti src dengan embed lokasimu) -->
          <div class="col-lg-7 reveal" style="--d:.15s">
            <div class="map-wrap h-100">
              <iframe title="Lokasi Sekolah Kalam Kudus Malang" src="https://www.google.com/maps?q=Sekolah+Kalam+Kudus+Malang&output=embed" loading="lazy" referrerpolicy="no-referrer-when-downgrade" allowfullscreen></iframe>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- ==================== FOOTER ==================== -->
  <footer class="site-footer">
    <div class="container text-center">
      <div class="social mb-3">
        <a href="https://www.linkedin.com/" target="_blank" rel="noopener" aria-label="LinkedIn"><i class="bi bi-linkedin"></i></a>
        <a href="https://github.com/" target="_blank" rel="noopener" aria-label="GitHub"><i class="bi bi-github"></i></a>
        <a href="https://www.instagram.com/" target="_blank" rel="noopener" aria-label="Instagram"><i class="bi bi-instagram"></i></a>
        <a href="mailto:budi.santoso@gmail.com" aria-label="Email"><i class="bi bi-envelope-fill"></i></a>
      </div>
      <p class="mb-1">&copy; 2026 <strong>Budi Santoso</strong>. Semua hak dilindungi.</p>
      <p class="mb-0"><a href="https://skkkmalang.sch.id/" target="_blank" rel="noopener">Sekolah Kalam Kudus Malang</a></p>
    </div>
  </footer>

  <!-- ==================== TOMBOL KEMBALI KE ATAS ==================== -->
  <button id="toTop" class="to-top" aria-label="Kembali ke atas"><i class="bi bi-arrow-up"></i></button>

  <!-- ==================== MODAL PREVIEW GAMBAR GALERI ==================== -->
  <div class="modal fade" id="imgModal" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg">
      <div class="modal-content modal-soft">
        <div class="modal-header border-0 pb-0">
          <h5 class="modal-title" id="imgModalTitle"></h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Tutup"></button>
        </div>
        <div class="modal-body">
          <img id="imgModalImg" src="" alt="" class="img-fluid rounded-4 w-100">
          <p id="imgModalDesc" class="mt-3 mb-0"></p>
        </div>
      </div>
    </div>
  </div>

  <!-- ========== JAVASCRIPT ========== -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="js/script.js"></script>
</body>
</html>
