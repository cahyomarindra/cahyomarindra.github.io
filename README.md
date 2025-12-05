<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cahyo Utomo Marindra - Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #b0e0e6;
      color: #000000;
    }
    header {
      background: #000080;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav {
      background: #191970;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
      background: #E0FFFF;
      margin-top: 2rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: justify;
    }
    h2 {
      color: #000080;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #191970;
      color: white;
      margin-top: 3rem;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideDown {
      from { transform: translateY(-20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <img src="images/Foto Profil.png" alt="Profile Photo" style="width:150px;height:200px;border-radius:50%;border:4px solid white;animation: fadeIn 2s;" />
    <h1 style="animation: slideDown 1.5s;">Cahyo Utomo Marindra</h1>
    <p style="animation: fadeIn 2s;">Fresh Graduate | Mechanical Engineering</p>
  </header>
  
  <nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#works">Works</a>
    <a href="#organisations">Organisations</a>
    <a href="#certificates">Certificates</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Saya Cahyo Utomo Marindra, lulusan Sarjana Teknik Mesin, Universitas Muhammadiyah Surakarta, dengan nilai IPK 3.28 dan meraih predikat kelulusan sangat memuaskan. Saya pernah melakukan tugas kuliah praktik di PT Pertamina Patra Niaga Integrated Terminal Semarang dan telah membekali saya dengan keahlian dalam pemahaman gambar teknik, software keteknikan seperti AUTOCAD, Ms. Office Word, Excel, dan Powerpoint. Tidak hanya itu, kemampuan seperti berpikir kritis, pemecahan masalah, ketelitian terhadap data, komunikasi, observasi lapangan, dan kerjasama tim juga dimiliki untuk penyelesaian tugas yang diberikan pembimbing lapangan. Tugas utama saat kuliah praktik seperti pembuatan desain perencanaan jalan antar tangki minyak telah dipresentasikan kepada jajaran perusahaan sebagai bahan pertimbangan untuk mempermudah akses pekerja. Saya memiliki ketertarikan besar pada bidang manufaktur, khususnya perancangan dan analisis performa equipment, dan juga pada bidang konversi energi, khususnya perancangan dan pengelolaan sistem.
    </p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <p>
      <strong>S1 Teknik Mesin - Universitas Muhammadiyah Surakarta</strong><br>
      <em>Tahun Lulus: 2025</em><br>
      <em>IPK: 3.28/4.00</em></p>
    <p><strong>Judul Skripsi:</strong> "Performa Alat Pirolisis Pengkonversi Limbah Plastik Menjadi Minyak Dengan Variasi Jenis Plastik."</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <p><strong>Hard Skills:</strong></p>
    <ul>
      <li>Mechanical Drawing (SolidWorks, AutoCAD)</li>
      <li>Basic 3D Modelling & Simulation (SolidWorks)</li>
      <li>Microsoft Office (Word, Excel, Powerpoint)</li>
      <li>Analisis Data Teknis (Excel Advanced / Google Sheets)</li>
    </ul>
    <p><strong>Soft Skills:</strong></p>
    <ul>
      <li>Berorientasi Pada Detail</li>
      <li>Berpikir Kritis</li>
      <li>Kerjasama Tim</li>
      <li>Komunikasi</li>
      <li>Manajemen Waktu</li>
      <li>Pemecahan Masalah</li>
      <li>Observasi Lapangan</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Project Experiences</h2>
    <p>
      <strong>Analisis Performa Alat Pirolisis Untuk Mengkonversi Sampah Plastik Menjadi Bahan Bakar - Tugas Akhir</strong>
      <em>( 2025 )</em><br>
      <strong>Tools:</strong> Reaktor Pirolisis, Digital Thermocouple, Timer, Ms. Word, Ms.Excel (Analisis Data)</p>
    <ul>
      <li>Melakukan pengujian alat pirolisis plastik milik Badan Usaha Milik Desa (BUMDes).</li>
      <li>Melakukan pengujian performa alat menggunakan tiga jenis sampah plastik, seperti plastik LDPE, PP, dan plastik campuran.</li>
      <li>Menganalisis pengaruh jenis plastik terhadap yield dan kualitas minyak yang dihasilkan.</li>
      <li>Menghitung efisiensi sistem dan tekno ekonomi pirolisis plastik selama proses pengujian.</li>
      <li>Menyusun laporan teknis berbasis data eksperimen.</li>
    </ul>
    <p>
      <strong>Proyek Pelatihan SolidWorks - Program Drafter 3D Mekanikal</strong>
      <em>( 2023 )</em><br>
      <strong>Tools:</strong> SolidWorks, Engineering Drawing Standard, Measurement Tools</p>
    <ul>
      <li>Membuat model 3D komponen mekanik menggunakan SolidWorks.</li>
      <li>Melakukan assembly beberapa komponen menjadi satu kesatuan.</li>
      <li>Membuat engineering drawing lengkap dengan dimensi dan etiket.</li>
      <li>Melakukan simple motion analysis untuk mengevaluasi interaksi antar part.</li>
    </ul>
    <p>
      <strong>Desain Rangkaian Jalan Antar Tangki PT. Pertamina Integrated Terminal Semarang - Kuliah Praktik</strong>
      <em>( 2022 )</em><br>
      <strong>Tools:</strong> AutoCAD, Measurement Tools, Safety Equipment, Ms. Word, Ms. Powerpoint</p>
    <ul>
      <li>Melakukan observasi lapangan secara langsung di area distribusi bahan bakar minyak.</li>
      <li>Melakukan pengukuran pada area tangki untuk mengetahui jarak antar tangki.</li>
      <li>Membuat desain CAD 2D dan 3D lay-out rancangan jalan antar tangki.</li>
      <li>Membuat laporan hasil kuliah praktik selama satu bulan.</li>
    </ul>
    <p>
      <strong>Re-Drawing Alat Stand Hand Bor - Tugas Perencanaan Mesin</strong>
      <em>( 2022 )</em><br>
      <strong>Tools:</strong> SolidWorks, Engineering Drawing Standard, Measurement Tools, Ms. Word</p>
    <ul>
      <li>Membuat model 3D masing - masing komponen menggunakan software SolidWorks.</li>
      <li>Melakukan assembly beberapa komponen menjadi satu kesatuan.</li>
      <li>Membuat engineering drawing lengkap dengan dimensi dan etiket.</li>
      <li>Membuat laporan hasil re-drawing alat stand hand bor.</li>
    </ul>
    <p>
      <strong>Re-Drawing Mesin Pemipil Jagung - Proyek Pribadi</strong>
      <em>( 2021 )</em><br>
      <strong>Tools:</strong> SolidWorks</p>
    <ul>
      <li>Melakukan re-drawing mesin pemipil jagung menggunakan SolidWorks berdasarkan gambar.</li>
      <li>Membuat model 3D beberapa komponen, seperti rangka, pully, poros, dan pillow.</li>
      <li>Membuat engineering drawing lengkap dengan dimensi.</li>
    </ul>
  </section>

  <section id="works">
    <h2>Work Experiences</h2>
    <p>
      <strong>Freelance Crew Store - Playtopia (PT. Amazone Dunia Rekreasi)</strong><br>
      <em>April 2024 - Februari 2025</em></p>
    <ul>
      <li>Bertanggungjawab dalam menjaga wahana permainan anak – anak berumur <17 tahun dengan pengunjung sebanyak >100 anak.</li>
      <li>Bertanggungjawab atas kebersihan wahana setiap sebelum maupun sesudah wahana dibuka.</li>
      <li>Berperan dalam pelaksanaan prosedur keselamatan untuk 4 wahana yang memiliki indikator cukup membahayakan.</li>
    </ul>
    <p>
      <strong>Part Time Consultant - Lab Art Aromatique Parfume</strong><br>
      <em>Agustus 2023 - November 2023</em></p>
    <ul>
      <li>Bertanggungjawab atas pelayanan pelanggan dan memberikan rekomendasi terkait parfum yang cocok dengan pelanggan.</li>
      <li>Bertanggungjawab atas kebersihan dan kenyamanan toko selama 6 jam kerja.</li>
      <li>Berperan dalam pengecekan ketersediaan stok, seperti minyak parfum, alkohol, maupun botol parfum, dan melaporkan kepada kepala toko.</li>
    </ul>
  </section>

  <section id="organisations">
    <h2>Organisation Experiences</h2>
    <p>
      <strong>Ketua Departemen Tata Usaha - Lembaga Pers Mahasiswa Fakultas Teknik Uniersitas Muhammadiyah Surakarta</strong><br>
      <em>Januari - Desember 2022</em></p>
    <ul>
      <li>Berperan dalam meliput 50% kejadian atau kegiatan yang ada di dalam kampus maupun diluar kampus untuk dijadikan produk jurnalistik, seperti majalah, buletin, koran, atau blogspot pada tahun 2022.</li>
      <li>Menyelesaikan karya tulis sebanyak 5 karya untuk kemudian dipublikasikan pada blogspot, buletin, atau majalah.</li>
      <li>Bertanggungjawab atas pendataan dan pengelolaan >62 barang inventaris organisasi dengan pengarsipan menggunakan Microsoft Excel dan pengelolaan atribut organisasi untuk pengurus baru.</li>
      <li>Menyelesaikan proposal pengiklanan yang digunakan untuk mencari iklan dan dicantumkan pada produk cetak, serta berhasil mendapatkan 8 UMKM yang bersedia untuk diiklankan produknya.</li>
    </ul>
    <p>
      <strong>Anggota Bidang Sosial Pemberdayaan Masyarakat - Ikatan Mahasiswa Muhammadiyah Fakultas Teknik Universitas Muhammadiyah Surakarta</strong><br>
      <em>September 2021 - September 2022</em></p>
    <ul>
      <li>Bertanggungjawab atas pendataan dan pengelolaan dana yang dikumpulkan untuk korban bencana maupun anggota yang terkena musibah.</li>
      <li>Berperan dalam mengelola dana program berbagi makanan kepada orang - orang yang membutuhkan di wilayah Surakarta.</li>
      <li>Bertanggungjawab membuat laporan pengelolaan dana untuk korban bencana dan program berbagi makanan untuk dilaporkan kepada ketua bidang dan ketua organisasi.</li>
      <li>Berperan dalam membantu lembaga LAZISMU Surakarta sebagai supir ambulance sementara untuk warga yang membutuhkan bantuan.</li>
    </ul>
    <p>
      <strong>Staff Departemen Tata Usaha - Lembaga Pers Mahasiswa Fakultas Teknik Uniersitas Muhammadiyah Surakarta</strong><br>
      <em>Januari - Desember 2021</em></p>
    <ul>
      <li></li>
    </ul>
  </section>
