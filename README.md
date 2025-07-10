<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  KNPI MAUK | Komite Nasional Pemuda Indonesia Mauk
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-white text-yellow-400">
  <!-- Navbar -->
  <header class="bg-blue-800">
    <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <div class="flex items-center space-x-2">
        <img src="Komite_Nasional_Pemuda_Indonesia.png" alt="Logo KNPI" class="w-10 h-10">
        <h1 class="text-xl font-bold">DPK KNPI MAUK</h1>
      </div>
      <nav class="space-x-4">
        <a href="#beranda" class="hover:text-white">Beranda</a>
        <a href="#tentang" class="hover:text-white">Tentang</a>
        <a href="#kegiatan" class="hover:text-white">Kegiatan</a>
        <a href="#galeri" class="hover:text-white">Galeri</a>
        <a href="#kontak" class="hover:text-white">Kontak</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="beranda" class="bg-cover bg-center h-64 flex items-center justify-center" style="background-image: url('https://example.com/banner-knpi.jpg');">
    <div class="bg-black bg-opacity-50 p-6 rounded">
      <h2 class="text-3xl font-bold">Selamat Datang di KNPI Kec. Mauk</h2>
      <p class="mt-2">Bersatu, Bergerak, dan Maju Bersama</p>
    </div>
  </section>

  <!-- Tentang Section -->
  <section id="tentang" class="max-w-4xl mx-auto py-12 px-6">
    <h2 class="text-2xl font-bold text-blue-800 mb-4">Tentang KNPI</h2>
    <p>Komite Nasional Pemuda Indonesia (KNPI) Kecamatan Mauk adalah wadah pemersatu organisasi kepemudaan di wilayah Kecamatan Mauk, Kabupaten Tangerang. KNPI Mauk hadir sebagai motor penggerak semangat kepemudaan yang aktif, inovatif, dan berdaya saing dalam mendukung pembangunan daerah.</p>
  </section>

  <!-- Kegiatan Section -->
  <section id="kegiatan" class="bg-gray-100 py-12 px-6 text-yellow-400">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-2xl font-bold text-blue-800 mb-4">Kegiatan Terbaru</h2>
      <ul class="space-y-4">
        <li class="bg-blue p-4 shadow rounded">
          <h3 class="font-semibold text-lg">Lomba Masak dan Senam Bersama</h3>
          <p>Tanggal: 2 Agustus 2025</p>
          <p>Lokasi: Lapangan Kantor Kecamatan Mauk</p>
        </li>
        <li class="bg-blue p-4 shadow rounded">
          <h3 class="font-semibold text-lg">Futsal KNPI Cup</h3>
          <p>Tanggal: 16 Agustus 2025</p>
          <p>Lokasi: Lapangan Futsal Tanjung Anom</p>
        </li>
        <li class="bg-blue p-4 shadow rounded">
          <h3 class="font-semibold text-lg">Maraton Kemerdekaan</h3>
          <p>Tanggal: 13 Agustus 2025</p>
        </li>
      </ul>
    </div>
  </section>

  <!-- Galeri Section -->
  <section id="galeri" class="max-w-4xl mx-auto py-12 px-6">
    <h2 class="text-2xl font-bold text-blue-800 mb-4">Galeri Kegiatan</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
      <img src="https://via.placeholder.com/300x200" alt="Kegiatan 1" class="rounded shadow">
      <img src="https://via.placeholder.com/300x200" alt="Kegiatan 2" class="rounded shadow">
      <img src="https://via.placeholder.com/300x200" alt="Kegiatan 3" class="rounded shadow">
    </div>
  </section>

  <!-- Kontak Section -->
  <footer id="kontak" class="bg-blue-800 py-6 mt-12">
    <div class="max-w-4xl mx-auto px-4">
      <h3 class="font-bold text-lg">Kontak KNPI</h3>
      <p>Alamat: Jl. Ir Sutami 4. Mauk</p>
      <p>Instagram: @dpkknpimauk_official</p>
    </div>
  </footer>
</body>
</html>
