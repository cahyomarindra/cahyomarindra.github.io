<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cahyo Utomo Marindra - Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
  <style>
    body {
      font-family: "Times New Roman", Arial, serif;
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
      margin: 1.5rem auto;
      padding: 1rem;
      background: #E0FFFF;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: justify;
    }
    h2 {
      color: #000080;
      margin-top:0
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
    /* Lightbox gallery styles */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 16px;
      margin-top: 20px;
      align-items: start;
    }
    .gallery img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 12px;
      cursor: pointer;
      transition: transform .2s, opacity .3s;
      opacity: 1;
      display: block;
    }
    .gallery img.hidden { display: none; }
    .gallery img:hover { transform: scale(1.03); 
    }
    #lightbox-modal {
      position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.85);display:none;justify-content:center;align-items:center;z-index:9999;padding:20px;box-sizing:border-box
    }
    #lightbox-modal img{max-width:90%;max-height:90%;border-radius:10px}
    /* controls */
    .gallery-filter{display:flex;justify-content:center;gap:12px;align-items:center}
    .gallery-filter select{padding:6px 10px;border-radius:6px}
    /* slideshow highlight */
    .gallery img.dim{opacity:0.35}
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
      <strong>Tools:</strong> Reaktor Pirolisis, Thermocouple, Timer, Ms. Word, Ms.Excel (Analisis Data)</p>
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
      <li>Berperan dalam meliput 50% kejadian atau kegiatan yang ada di dalam kampus maupun diluar kampus untuk dijadikan produk jurnalistik, seperti majalah, buletin, koran, atau blogspot di tahun 2022.</li>
      <li>Menyelesaikan karya tulis sebanyak 5 karya untuk kemudian dipublikasikan pada blogspot, buletin, atau majalah.</li>
      <li>Berperan dalam kepanitian pada program kerja di tahun 2022.</li>
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
      <li>Berperan dalam peliputan kepada 5 narasumber secara online mengenai isu yang ada di kampus maupun luar kampus sebagai bahan produk jurnalistik di tahun 2021.</li>
      <li>Berperan dalam kepanitian pada program kerja di tahun 2021.</li>
      <li>Bertanggungjawab dalam menyiapkan inventaris untuk kegiatan program kerja dan atribut organisasi untuk pengurus baru.</li>
    </ul>
  </section>

  <section id="certificates">
    <h2>Trainings & Certificates</h2>
    <ul>
      <li><strong>TOEFL Score 500</strong> - Sertifikasi Lembaga KIND English Course <em>(2025).</em></li>
      <li><strong>Drafter CAD 3D Mekanikal</strong> - Pelatihan dan sertifikasi Lembaga Sertifikasi Profesi (LSP) Balai Latihan Kerja Surakarta <em>(2023).</em></li>
      <li><strong>Pelatihan CAD</strong> - Pelatihan komunitas Mechanical Engineering Design Club (MEDC) Teknik Mesin Universitas Muhammadiyah Surakarta <em>(2020).</em></li>
      <li><strong>SolidWorks Basic</strong> - Pelatihan Laboratorium CAD/CAM/CAE Fakultas Teknik Universitas Muhammadiyah Surakarta <em>(2020).</em></li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery-filter" style="margin-bottom:20px; text-align:center;">
      <label for="gallery-category"><strong>Kategori:</strong></label>
      <select id="gallery-category" style="padding:6px 10px; border-radius:6px; margin-left:8px;">
        <option value="all">Show All</option>
        <option value="project">Project Experiences</option>
        <option value="organization">Organisation Experiences</option>
        <option value="certificate">Trainings & Certificates</option>
      </select>
    </div>
    <div class="gallery">
      <!-- Project images -->
      <img src="images/Foto Project TA (1).jpg" alt="Final Project Pyrolysis Device" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TA (2).jpg" alt="Final Project Pyrolysis Device" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TA (3).jpg" alt="Final Project Pyrolysis Device" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TA (4).jpeg" alt="Final Project Pyrolysis Device" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TA (5).jpg" alt="Final Project Pyrolysis Device" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Training (1).PNG" alt="SolidWorks Training Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Training (2).PNG" alt="SolidWorks Training Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Training (3).PNG" alt="SolidWorks Training Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Training (4).PNG" alt="SolidWorks Training Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Training (5).PNG" alt="SolidWorks Training Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Training (6).PNG" alt="SolidWorks Training Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Training (7).PNG" alt="SolidWorks Training Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project KP (1).PNG" alt="Kuliah Praktik Pertamina" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project KP (2).PNG" alt="Kuliah Praktik Pertamina" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project KP (3).png" alt="Kuliah Praktik Pertamina" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project KP (4).png" alt="Kuliah Praktik Pertamina" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (1).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (2).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (3).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (4).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (5).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (6).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (7).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (8).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (9).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project TPM (10).PNG" alt="Re-Drawing Stand Hand Bor" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Pribadi (1).PNG" alt="Personal Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Pribadi (2).PNG" alt="Personal Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Pribadi (3).PNG" alt="Personal Project" data-type="project" onclick="openLightbox(this)">
      <img src="images/Foto Project Pribadi (4).PNG" alt="Personal Project" data-type="project" onclick="openLightbox(this)">
      <!-- Organizational images -->
      <img src="images/Foto Presidium.JPG" alt="Lembaga Pers Mahasiswa 2021" data-type="organization" onclick="openLightbox(this)">
      <img src="images/Foto Rapat.JPG" alt="Lembaga Pers Mahasiswa 2022" data-type="organization" onclick="openLightbox(this)">
      <!-- Certificate images -->
      <img src="images/Foto Sertif TOEFL.PNG" alt="Sertifikat TOEFL" data-type="certificate" onclick="openLightbox(this)">
      <img src="images/Foto Sertif CAD.PNG" alt="Sertifikat BNSP" data-type="certificate" onclick="openLightbox(this)">
      <img src="images/Foto Sertif MEDC.PNG" alt="Sertifikat MEDC" data-type="certificate" onclick="openLightbox(this)">
      <img src="images/Foto Sertif LAB.PNG" alt="Sertifikat MEDC" data-type="certificate" onclick="openLightbox(this)">
      <img src="images/Foto Pelatihan MEDC.PNG" alt="Pelatihan MEDC" data-type="certificate" onclick="openLightbox(this)">
      <img src="images/Foto Pelatihan LAB.PNG" alt="Pelatihan LAB CAD" data-type="certificate" onclick="openLightbox(this)">
      <img src="images/Foto Pelatihan LAB1.PNG" alt="Pelatihan LAB CAD" data-type="certificate" onclick="openLightbox(this)">
    </div>
    <div id="lightbox-modal" onclick="closeLightbox()">
      <img id="lightbox-img" src="" alt="Expanded image">
    </div>
    <script>
      /* All gallery scripts run after DOM is ready to avoid accessing undefined elements */
      document.addEventListener('DOMContentLoaded', function() {
        const gallerySelect = document.getElementById('gallery-category');
        const galleryImages = Array.from(document.querySelectorAll('.gallery img'));
        let slideIndex = -1;
        let slideTimer = null;
        function openLightbox(imgEl) {
          const modal = document.getElementById('lightbox-modal');
          const modalImg = document.getElementById('lightbox-img');
          modalImg.src = imgEl.src;
          modal.style.display = 'flex';
        }
        function closeLightbox() {
          const modal = document.getElementById('lightbox-modal');
          const modalImg = document.getElementById('lightbox-img');
          modal.style.display = 'none';
          modalImg.src = '';
        }
        /* expose to global so onclick inline handlers work */
        window.openLightbox = function(el){ openLightbox(el); };
        window.closeLightbox = function(){ closeLightbox(); };
        function filterGallery() {
          const category = gallerySelect.value;
          galleryImages.forEach(img => {
            const type = img.getAttribute('data-type');
            if (category === 'all' || category === type) {
              img.classList.remove('hidden');
            } else {
              img.classList.add('hidden');
            }
          });
        }
        gallerySelect.addEventListener('change', filterGallery);
        function autoSlideshow() {
          // clear previous timer
          if (slideTimer) clearTimeout(slideTimer);
          const visibleImages = galleryImages.filter(i => !i.classList.contains('hidden'));
          if (visibleImages.length === 0) return; // nothing to show
          // dim all
          visibleImages.forEach(img => img.classList.add('dim'));
          slideIndex = (slideIndex + 1) % visibleImages.length;
          const current = visibleImages[slideIndex];
          // highlight current
          current.classList.remove('dim');
          // schedule next
          slideTimer = setTimeout(autoSlideshow, 2500);
        }
        // start slideshow after images have loaded
        const imagePromises = galleryImages.map(img => {
          return new Promise(resolve => {
            if (img.complete) return resolve();
            img.onload = img.onerror = resolve;
          });
        });
        Promise.all(imagePromises).then(() => {
          // initialize state and start
          galleryImages.forEach(img => img.classList.remove('dim'));
          filterGallery();
          // small timeout to ensure layout applied
          setTimeout(autoSlideshow, 500);
        });
        // close modal when clicking outside image
        document.getElementById('lightbox-modal').addEventListener('click', function(e){
          if (e.target.id === 'lightbox-modal') closeLightbox();
        });
      });
    </script>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p><strong>No. Telepon:</strong> (+62) 812-9946-3158</p>
    <p><strong>Email:</strong> cahyo.um123@gmail.com</p>
    <p><strong>Linkedin:</strong> linkedin.com/in/cahyo-utomo-marindra</p>
  </section>

  <footer>
    <p>Terima kasih telah mengunjungi portofolio saya! Saya terbuka untuk diskusi terkait engineering, manufacturing, dan energi baru terbarukan.</p>
    <p>&copy; 2025 Cahyo Utomo Marindra - Portofolio. All Rights Reserved.</p>
  </footer>
</body>
</html>
