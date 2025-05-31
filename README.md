<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="icon" type="image/jpeg" href="https://static.readdy.ai/image/167fd8d95ebda96c451ae356d21a73bb/a7b2360f11995369c28cd6dc350b83d1.jpeg">
<title>TechCare - Solusi Teknologi Mahasiswa</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#0052CC',secondary:'#4C9AFF'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Inter', sans-serif;
}
.hero-section {
background-image: url('https://readdy.ai/api/search-image?query=professional%2520tech%2520repair%2520service%2520with%2520blue%2520gradient%2520background%2C%2520showing%2520laptop%2520and%2520smartphone%2520repair%2520tools%2C%2520modern%2520clean%2520workspace%2C%2520soft%2520lighting%2C%2520minimalist%2520style%2C%2520with%2520empty%2520space%2520on%2520the%2520left%2520side%2520for%2520text%2C%2520high%2520quality%2520professional%2520photo&width=1200&height=600&seq=1&orientation=landscape');
background-size: cover;
background-position: center right;
}
.accessibility-toggle:checked + .toggle-bg {
background-color: #0052CC;
}
.accessibility-toggle:checked + .toggle-bg .toggle-circle {
transform: translateX(100%);
}
</style>
</head>
<body class="bg-gray-50">
<!-- Header & Navigation -->
<header class="bg-white shadow-sm">
<div class="container mx-auto px-4 py-4 flex items-center justify-between">
<div class="flex items-center">
<img src="https://static.readdy.ai/image/167fd8d95ebda96c451ae356d21a73bb/a7b2360f11995369c28cd6dc350b83d1.jpeg" alt="TechCare Logo" class="h-16 w-auto">
</div>
<nav class="hidden md:flex items-center space-x-8">
<a href="#" class="text-gray-800 hover:text-primary font-medium">Beranda</a>
<a href="#layanan" class="text-gray-800 hover:text-primary font-medium">Layanan</a>
<a href="#tentang" class="text-gray-800 hover:text-primary font-medium">Tentang Kami</a>
<a href="#komunitas" class="text-gray-800 hover:text-primary font-medium">Komunitas</a>
<a href="#kontak" class="text-gray-800 hover:text-primary font-medium">Kontak</a>
</nav>
<button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-opacity-90 transition">
Booking Service
</button>
<div class="md:hidden w-8 h-8 flex items-center justify-center">
<i class="ri-menu-line ri-lg"></i>
</div>
</div>
</header>
<!-- Hero Section -->
<section class="hero-section min-h-[600px] flex items-center">
<div class="container mx-auto px-4 w-full">
<div class="max-w-xl bg-white bg-opacity-95 p-8 !rounded-lg shadow-lg">
<h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Solusi Teknologi Mahasiswa</h1>
<p class="text-xl text-gray-700 mb-8">Layanan reparasi gadget yang terjangkau, edukatif, dan inklusif untuk semua mahasiswa.</p>
<div class="flex flex-col sm:flex-row gap-4">
<button class="bg-primary text-white px-6 py-3 !rounded-button whitespace-nowrap font-medium hover:bg-opacity-90 transition">
Konsultasi Gratis
</button>
<button class="bg-white text-primary border border-primary px-6 py-3 !rounded-button whitespace-nowrap font-medium hover:bg-gray-50 transition">
Lihat Layanan
</button>
</div>
</div>
</div>
</section>
<!-- Layanan Utama -->
<section id="layanan" class="py-16 bg-white">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Layanan Utama Kami</h2>
<p class="text-lg text-gray-600 max-w-2xl mx-auto">Kami menyediakan berbagai layanan untuk membantu kebutuhan teknologi Anda dengan harga terjangkau dan kualitas terbaik.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
<!-- Layanan 1 -->
<div class="bg-white p-6 !rounded-lg shadow-md hover:shadow-lg transition">
<div class="w-16 h-16 bg-blue-100 !rounded-full flex items-center justify-center mb-4 mx-auto">
<i class="ri-tools-fill ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold text-gray-900 mb-2 text-center">Reparasi Gadget</h3>
<p class="text-gray-600 mb-4 text-center">Perbaikan layar, baterai, dan komponen lainnya untuk laptop dan smartphone Anda.</p>
<button class="w-full bg-gray-100 text-primary px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-gray-200 transition">
Selengkapnya
</button>
</div>
<!-- Layanan 2 -->
<div class="bg-white p-6 !rounded-lg shadow-md hover:shadow-lg transition">
<div class="w-16 h-16 bg-blue-100 !rounded-full flex items-center justify-center mb-4 mx-auto">
<i class="ri-computer-fill ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold text-gray-900 mb-2 text-center">Instalasi Software</h3>
<p class="text-gray-600 mb-4 text-center">Instalasi ulang sistem operasi dan software pendukung untuk performa optimal.</p>
<button class="w-full bg-gray-100 text-primary px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-gray-200 transition">
Selengkapnya
</button>
</div>
<!-- Layanan 3 -->
<div class="bg-white p-6 !rounded-lg shadow-md hover:shadow-lg transition">
<div class="w-16 h-16 bg-blue-100 !rounded-full flex items-center justify-center mb-4 mx-auto">
<i class="ri-book-open-fill ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold text-gray-900 mb-2 text-center">Edukasi Digital</h3>
<p class="text-gray-600 mb-4 text-center">Pembelajaran dan tips harian untuk mengoptimalkan penggunaan teknologi Anda.</p>
<button class="w-full bg-gray-100 text-primary px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-gray-200 transition">
Selengkapnya
</button>
</div>
<!-- Layanan 4 -->
<div class="bg-white p-6 !rounded-lg shadow-md hover:shadow-lg transition">
<div class="w-16 h-16 bg-blue-100 !rounded-full flex items-center justify-center mb-4 mx-auto">
<i class="ri-user-heart-fill ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold text-gray-900 mb-2 text-center">Pendampingan Teknis</h3>
<p class="text-gray-600 mb-4 text-center">Layanan pendampingan ramah disabilitas dengan panduan audio atau teks besar.</p>
<button class="w-full bg-gray-100 text-primary px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-gray-200 transition">
Selengkapnya
</button>
</div>
</div>
</div>
</section>
<!-- Tentang Kami -->
<section id="tentang" class="py-16 bg-gray-50">
<div class="container mx-auto px-4">
<div class="flex flex-col lg:flex-row items-center gap-12">
<div class="lg:w-1/2">
<h2 class="text-3xl font-bold text-gray-900 mb-6">Tentang TechCare</h2>
<p class="text-gray-700 mb-4">TechCare adalah usaha jasa servis dan edukasi teknologi berbasis komunitas, didirikan oleh mahasiswa Politeknik Negeri Jakarta. Fokus kami adalah menyediakan layanan reparasi gadget (laptop & HP) yang terjangkau, edukatif, dan inklusif.</p>
<p class="text-gray-700 mb-4">Dengan semangat kolaborasi, TechCare bukan hanya penyedia jasa, tapi juga ruang belajar bersama yang terbuka bagi semua, tanpa kecuali. Kami hadir menjawab kebutuhan mahasiswa—termasuk mereka yang disabilitas—yang sering kesulitan memperbaiki gadget karena mahal atau terbatas akses.</p>
<p class="text-gray-700 mb-6">Didukung oleh tim dari jurusan Administrasi Niaga dan Akuntansi, dua di antaranya punya keahlian teknis otodidak. TechCare juga membuka peluang magang dan komunitas berbagi bernama TechFriends.</p>
<div class="grid grid-cols-3 gap-4 mb-6">
<div class="bg-white p-4 !rounded-lg shadow-sm text-center">
<div class="text-primary text-2xl font-bold">200+</div>
<div class="text-gray-600 text-sm">Klien Puas</div>
</div>
<div class="bg-white p-4 !rounded-lg shadow-sm text-center">
<div class="text-primary text-2xl font-bold">4.9</div>
<div class="text-gray-600 text-sm">Rating</div>
</div>
<div class="bg-white p-4 !rounded-lg shadow-sm text-center">
<div class="text-primary text-2xl font-bold">50+</div>
<div class="text-gray-600 text-sm">Anggota Komunitas</div>
</div>
</div>
</div>
<div class="lg:w-1/2">
<img src="https://readdy.ai/api/search-image?query=diverse%2520group%2520of%2520Indonesian%2520university%2520students%2520working%2520together%2520on%2520laptop%2520and%2520smartphone%2520repairs%2C%2520in%2520a%2520bright%2520modern%2520workspace%2C%2520showing%2520collaboration%2520and%2520learning%2C%2520tools%2520and%2520components%2520visible%2520on%2520desk%2C%2520inclusive%2520environment%2C%2520professional%2520photo&width=600&height=500&seq=2&orientation=landscape" alt="Tim TechCare" class="w-full h-auto !rounded-lg shadow-lg object-cover object-top">
</div>
</div>
</div>
</section>
<!-- Komunitas TechFriends -->
<section id="komunitas" class="py-16 bg-blue-50">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Komunitas TechFriends</h2>
<p class="text-lg text-gray-600 max-w-2xl mx-auto">Bergabunglah dengan komunitas kami untuk berbagi pengetahuan, mendapatkan dukungan, dan tumbuh bersama dalam dunia teknologi.</p>
</div>
<div class="flex flex-col lg:flex-row gap-12 items-center">
<div class="lg:w-1/2">
<img src="https://readdy.ai/api/search-image?query=diverse%2520group%2520of%2520Indonesian%2520students%2520in%2520a%2520tech%2520workshop%2520setting%2C%2520sharing%2520knowledge%2C%2520collaborative%2520learning%2520environment%2C%2520people%2520helping%2520each%2520other%2520with%2520devices%2C%2520inclusive%2520community%2C%2520bright%2520modern%2520space%2C%2520professional%2520photo&width=600&height=400&seq=3&orientation=landscape" alt="Komunitas TechFriends" class="w-full h-auto !rounded-lg shadow-lg object-cover object-top">
</div>
<div class="lg:w-1/2">
<div class="bg-white p-8 !rounded-lg shadow-md">
<h3 class="text-2xl font-semibold text-gray-900 mb-4">Gabung TechFriends</h3>
<p class="text-gray-700 mb-6">Dapatkan akses ke forum diskusi, workshop, dan kesempatan magang. Kami membuka pintu bagi siapa saja yang ingin belajar dan berbagi pengetahuan teknologi.</p>
<form>
<div class="mb-4">
<label for="nama" class="block text-gray-700 mb-2">Nama Lengkap</label>
<input type="text" id="nama" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Masukkan nama lengkap">
</div>
<div class="mb-4">
<label for="email" class="block text-gray-700 mb-2">Email</label>
<input type="email" id="email" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Masukkan email">
</div>
<div class="mb-4">
<label for="minat" class="block text-gray-700 mb-2">Minat</label>
<select id="minat" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent pr-8">
<option value="">Pilih minat Anda</option>
<option value="reparasi">Reparasi Gadget</option>
<option value="software">Software & Pemrograman</option>
<option value="desain">Desain Digital</option>
<option value="lainnya">Lainnya</option>
</select>
</div>
<button type="submit" class="w-full bg-primary text-white px-4 py-3 !rounded-button whitespace-nowrap font-medium hover:bg-opacity-90 transition">
Daftar Sekarang
</button>
</form>
</div>
</div>
</div>
<!-- Testimonial -->
<div class="mt-16">
<h3 class="text-2xl font-semibold text-gray-900 mb-8 text-center">Apa Kata Anggota Kami</h3>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="bg-white p-6 !rounded-lg shadow-md">
<div class="flex items-center mb-4">
<div class="w-12 h-12 bg-blue-100 !rounded-full flex items-center justify-center mr-4">
<i class="ri-user-fill ri-lg text-primary"></i>
</div>
<div>
<h4 class="font-semibold text-gray-900">Budi Santoso</h4>
<p class="text-gray-600 text-sm">Mahasiswa Teknik Informatika</p>
</div>
</div>
<p class="text-gray-700">"TechCare membantu saya memperbaiki laptop yang rusak dengan biaya terjangkau. Selain itu, saya juga belajar banyak tentang perawatan gadget yang benar."</p>
</div>
<div class="bg-white p-6 !rounded-lg shadow-md">
<div class="flex items-center mb-4">
<div class="w-12 h-12 bg-blue-100 !rounded-full flex items-center justify-center mr-4">
<i class="ri-user-fill ri-lg text-primary"></i>
</div>
<div>
<h4 class="font-semibold text-gray-900">Anita Wijaya</h4>
<p class="text-gray-600 text-sm">Mahasiswa Manajemen</p>
</div>
</div>
<p class="text-gray-700">"Komunitas TechFriends sangat inklusif dan membantu. Saya yang awalnya gaptek sekarang jadi lebih paham teknologi berkat workshop-workshop yang diadakan."</p>
</div>
<div class="bg-white p-6 !rounded-lg shadow-md">
<div class="flex items-center mb-4">
<div class="w-12 h-12 bg-blue-100 !rounded-full flex items-center justify-center mr-4">
<i class="ri-user-fill ri-lg text-primary"></i>
</div>
<div>
<h4 class="font-semibold text-gray-900">Rudi Hartono</h4>
<p class="text-gray-600 text-sm">Mahasiswa Akuntansi</p>
</div>
</div>
<p class="text-gray-700">"Sebagai mahasiswa tunanetra, saya sangat terbantu dengan layanan pendampingan teknis yang ramah disabilitas. TechCare benar-benar inklusif!"</p>
</div>
</div>
</div>
</div>
</section>
<!-- Booking Section -->
<section id="booking" class="py-16 bg-white">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Booking Service</h2>
<p class="text-lg text-gray-600 max-w-2xl mx-auto">Butuh bantuan dengan gadget Anda? Isi form di bawah untuk menjadwalkan layanan atau konsultasi gratis.</p>
</div>
<div class="max-w-4xl mx-auto bg-white !rounded-lg shadow-lg p-8 border border-gray-100">
<form>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
<div>
<label for="nama-lengkap" class="block text-gray-700 mb-2">Nama Lengkap</label>
<input type="text" id="nama-lengkap" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Masukkan nama lengkap">
</div>
<div>
<label for="no-hp" class="block text-gray-700 mb-2">Nomor HP/WhatsApp</label>
<input type="tel" id="no-hp" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Masukkan nomor HP/WhatsApp">
</div>
<div>
<label for="email-booking" class="block text-gray-700 mb-2">Email</label>
<input type="email" id="email-booking" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Masukkan email">
</div>
<div>
<label for="jenis-layanan" class="block text-gray-700 mb-2">Jenis Layanan</label>
<select id="jenis-layanan" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent pr-8">
<option value="">Pilih jenis layanan</option>
<option value="ganti-layar">Ganti Layar (Rp 350.000 - Rp 750.000)</option>
<option value="ganti-baterai">Ganti Baterai (Rp 250.000 - Rp 500.000)</option>
<option value="bersihkan">Bersihkan Perangkat (Rp 100.000 - Rp 200.000)</option>
<option value="instal-os">Instal Ulang OS (Rp 150.000 - Rp 300.000)</option>
<option value="edukasi">Edukasi Digital (Rp 100.000/jam)</option>
<option value="pendampingan">Pendampingan Teknis (Rp 150.000/jam)</option>
<option value="konsultasi">Konsultasi (Gratis)</option>
</select>
</div>
<div>
<label for="jenis-perangkat" class="block text-gray-700 mb-2">Jenis Perangkat</label>
<select id="jenis-perangkat" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent pr-8">
<option value="">Pilih jenis perangkat</option>
<option value="laptop">Laptop</option>
<option value="smartphone">Smartphone</option>
<option value="tablet">Tablet</option>
<option value="lainnya">Lainnya</option>
</select>
</div>
<div>
<label for="tanggal" class="block text-gray-700 mb-2">Tanggal</label>
<input type="date" id="tanggal" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent">
</div>
</div>
<div class="mb-6">
<label for="deskripsi" class="block text-gray-700 mb-2">Deskripsi Masalah</label>
<textarea id="deskripsi" rows="4" class="w-full px-4 py-2 !rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Jelaskan masalah yang Anda alami dengan perangkat"></textarea>
</div>
<div class="mb-6">
<label class="flex items-center">
<input type="checkbox" class="w-5 h-5 text-primary border-gray-300 !rounded focus:ring-primary">
<span class="ml-2 text-gray-700">Saya membutuhkan layanan yang ramah disabilitas</span>
</label>
</div>
<div class="text-center">
<button type="submit" class="bg-primary text-white px-8 py-3 !rounded-button whitespace-nowrap font-medium hover:bg-opacity-90 transition">
Kirim Permintaan
</button>
</div>
</form>
</div>
</div>
</section>
<!-- Fitur Aksesibilitas -->
<div class="fixed bottom-6 right-6 z-50">
<button class="bg-white !rounded-full shadow-lg p-3 flex items-center justify-center" id="accessibility-button">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-wheelchair-fill ri-lg text-primary"></i>
</div>
</button>
<div id="accessibility-panel" class="hidden absolute bottom-16 right-0 bg-white !rounded-lg shadow-lg p-4 w-64">
<h3 class="text-lg font-semibold text-gray-900 mb-3">Aksesibilitas</h3>
<div class="space-y-4">
<div>
<label class="flex items-center justify-between">
<span class="text-gray-700">Kontras Tinggi</span>
<div class="relative">
<input type="checkbox" id="high-contrast" class="sr-only accessibility-toggle">
<div class="toggle-bg w-12 h-6 !rounded-full bg-gray-200 transition"></div>
<div class="toggle-circle absolute left-1 top-1 bg-white w-4 h-4 !rounded-full transition"></div>
</div>
</label>
</div>
<div>
<label for="font-size" class="block text-gray-700 mb-1">Ukuran Teks</label>
<input type="range" id="font-size" min="1" max="3" step="1" value="1" class="w-full">
</div>
<div>
<label class="flex items-center justify-between">
<span class="text-gray-700">Mode Layar Pembaca</span>
<div class="relative">
<input type="checkbox" id="screen-reader" class="sr-only accessibility-toggle">
<div class="toggle-bg w-12 h-6 !rounded-full bg-gray-200 transition"></div>
<div class="toggle-circle absolute left-1 top-1 bg-white w-4 h-4 !rounded-full transition"></div>
</div>
</label>
</div>
</div>
</div>
</div>
<!-- Footer -->
<footer class="bg-gray-900 text-white py-12">
<div class="container mx-auto px-4">
<div class="grid grid-cols-1 md:grid-cols-4 gap-8">
<div>
<div class="mb-4">
<img src="https://static.readdy.ai/image/167fd8d95ebda96c451ae356d21a73bb/a7b2360f11995369c28cd6dc350b83d1.jpeg" alt="TechCare Logo" class="h-12 w-auto">
</div>
<p class="text-gray-400 mb-4">Solusi Teknologi Mahasiswa yang terjangkau, edukatif, dan inklusif.</p>
<div class="flex space-x-4">
<a href="#" class="text-gray-400 hover:text-white">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-instagram-fill ri-lg"></i>
</div>
</a>
<a href="#" class="text-gray-400 hover:text-white">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-whatsapp-fill ri-lg"></i>
</div>
</a>
<a href="#" class="text-gray-400 hover:text-white">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-mail-fill ri-lg"></i>
</div>
</a>
</div>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Layanan</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white">Reparasi Gadget</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Instalasi Software</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Edukasi Digital</a></li>
<li><a href="#" class="text-gray-400 hover:text-white">Pendampingan Teknis</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Tautan</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white">Beranda</a></li>
<li><a href="#tentang" class="text-gray-400 hover:text-white">Tentang Kami</a></li>
<li><a href="#komunitas" class="text-gray-400 hover:text-white">Komunitas</a></li>
<li><a href="#booking" class="text-gray-400 hover:text-white">Booking Service</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Kontak</h3>
<ul class="space-y-2">
<li class="flex items-start">
<div class="w-5 h-5 flex items-center justify-center mr-2 mt-0.5">
<i class="ri-map-pin-fill text-gray-400"></i>
</div>
<span class="text-gray-400">Kampus Politeknik Negeri Jakarta, Depok, Jawa Barat</span>
</li>
<li class="flex items-center">
<div class="w-5 h-5 flex items-center justify-center mr-2">
<i class="ri-phone-fill text-gray-400"></i>
</div>
<span class="text-gray-400">+62 812-3456-7890</span>
</li>
<li class="flex items-center">
<div class="w-5 h-5 flex items-center justify-center mr-2">
<i class="ri-mail-fill text-gray-400"></i>
</div>
<span class="text-gray-400">info@techcare.id</span>
</li>
</ul>
<div class="mt-6">
<h4 class="text-sm font-semibold mb-2">Berlangganan Newsletter</h4>
<div class="flex">
<input type="email" placeholder="Email Anda" class="px-4 py-2 !rounded-l-lg border-none focus:outline-none focus:ring-2 focus:ring-primary text-gray-900 w-full">
<button class="bg-primary text-white px-4 py-2 !rounded-r-lg whitespace-nowrap hover:bg-opacity-90 transition">
Daftar
</button>
</div>
</div>
</div>
</div>
<div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
<p>&copy; 2025 TechCare. Hak Cipta Dilindungi.</p>
</div>
</div>
</footer>
<script id="accessibility-script">
document.addEventListener('DOMContentLoaded', function() {
const accessibilityButton = document.getElementById('accessibility-button');
const accessibilityPanel = document.getElementById('accessibility-panel');
accessibilityButton.addEventListener('click', function() {
accessibilityPanel.classList.toggle('hidden');
});
// Close panel when clicking outside
document.addEventListener('click', function(event) {
if (!accessibilityPanel.contains(event.target) && !accessibilityButton.contains(event.target)) {
accessibilityPanel.classList.add('hidden');
}
});
// High contrast toggle
const highContrastToggle = document.getElementById('high-contrast');
highContrastToggle.addEventListener('change', function() {
if (this.checked) {
document.body.classList.add('high-contrast');
} else {
document.body.classList.remove('high-contrast');
}
});
// Font size slider
const fontSizeSlider = document.getElementById('font-size');
fontSizeSlider.addEventListener('input', function() {
const fontSize = this.value;
if (fontSize == 1) {
document.body.style.fontSize = '1rem';
} else if (fontSize == 2) {
document.body.style.fontSize = '1.2rem';
} else {
document.body.style.fontSize = '1.4rem';
}
});
// Screen reader toggle
const screenReaderToggle = document.getElementById('screen-reader');
screenReaderToggle.addEventListener('change', function() {
if (this.checked) {
document.body.classList.add('screen-reader-mode');
} else {
document.body.classList.remove('screen-reader-mode');
}
});
});
</script>
</body>
</html>
