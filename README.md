<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rizz Store - Sewa PS3, PS4 & PS5 Terlengkap</title>
    <!-- Tailwind CSS via CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter & Rajdhani untuk nuansa gaming -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Rajdhani:wght@600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        gaming: ['Rajdhani', 'sans-serif'],
                    },
                    colors: {
                        psBlue: '#0070D1',
                        psDarkBlue: '#00439C',
                        psCyan: '#00E5FF',
                        darkBg: '#090D16',
                        cardBg: '#111827',
                        cardBorder: '#1F2937'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-darkBg text-slate-100 font-sans antialiased selection:bg-psBlue selection:text-white">

    <!-- Notifikasi Toast Pengganti Alert -->
    <div id="toast-box" class="fixed top-5 right-5 z-50 hidden transform transition-all duration-300 max-w-sm w-full">
        <div class="bg-slate-800 border-l-4 border-rose-500 text-white px-4 py-3 rounded-xl shadow-2xl flex items-start gap-3">
            <i class="fa-solid fa-circle-exclamation text-rose-400 mt-1"></i>
            <div class="flex-1">
                <p class="font-semibold text-sm" id="toast-title">Perhatian</p>
                <p class="text-xs text-slate-300 mt-0.5" id="toast-message">Pesan notifikasi</p>
            </div>
            <button onclick="hideToast()" class="text-slate-400 hover:text-white p-1">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
    </div>

    <!-- Navbar -->
    <header class="sticky top-0 z-40 bg-darkBg/90 backdrop-blur-md border-b border-slate-800/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16 sm:h-20">
                <!-- Logo -->
                <a href="#" class="flex items-center gap-3 group">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-psBlue to-psCyan flex items-center justify-center text-white shadow-lg shadow-psBlue/30 group-hover:scale-105 transition">
                        <i class="fa-brands fa-playstation text-2xl"></i>
                    </div>
                    <div>
                        <span class="font-gaming text-2xl font-bold tracking-wider text-white">RIZZ<span class="text-psCyan">STORE</span></span>
                        <span class="block text-[10px] uppercase tracking-widest text-slate-400 -mt-1">Rental PlayStation</span>
                    </div>
                </a>

                <!-- Desktop Menu -->
                <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
                    <a href="#daftar-harga" class="hover:text-psCyan transition">Daftar Harga</a>
                    <a href="#katalog-game" class="hover:text-psCyan transition">Game Populer</a>
                    <a href="#form-pesan" class="hover:text-psCyan transition">Pesan Sekarang</a>
                    <a href="#syarat-pembayaran" class="hover:text-psCyan transition">Pembayaran & S&K</a>
                </nav>

                <!-- CTA Button Header -->
                <div class="flex items-center gap-3">
                    <a href="#form-pesan" class="bg-psBlue hover:bg-blue-600 text-white text-xs sm:text-sm font-semibold px-4 py-2.5 rounded-xl shadow-lg shadow-psBlue/30 transition flex items-center gap-2">
                        <i class="fa-brands fa-whatsapp text-base"></i>
                        <span>Booking WA</span>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative overflow-hidden pt-12 pb-20 lg:pt-20 lg:pb-28 border-b border-slate-800/60">
        <!-- Decorative Background Glows -->
        <div class="absolute top-0 left-1/4 w-96 h-96 bg-psBlue/20 rounded-full blur-3xl -z-10 pointer-events-none"></div>
        <div class="absolute bottom-0 right-1/4 w-80 h-80 bg-psCyan/10 rounded-full blur-3xl -z-10 pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                <!-- Left Content -->
                <div class="lg:col-span-7 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-slate-800/90 border border-slate-700 text-psCyan text-xs font-semibold mb-6">
                        <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                        Ready PS3, PS4 Pro & PS5 Digital/Disc — Unit Terawat!
                    </div>

                    <h1 class="font-gaming text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight text-white mb-6">
                        Mabar Seru Tanpa Batas di <span class="text-transparent bg-clip-text bg-gradient-to-r from-psBlue via-blue-400 to-psCyan">Rizz Store</span>
                    </h1>

                    <p class="text-slate-300 text-base sm:text-lg leading-relaxed mb-8 max-w-2xl mx-auto lg:mx-0">
                        Nikmati sensasi bermain game terbaru dengan stik original responsif dan layar jernih. Tersedia layanan <strong>Main di Tempat</strong>, <strong>COD Ambil Sendiri</strong>, hingga <strong>Antar Jemput Sampai Rumah</strong>. Pembayaran praktis via E-Wallet & Transfer Bank!
                    </p>

                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="#form-pesan" class="w-full sm:w-auto px-7 py-4 rounded-xl bg-gradient-to-r from-psBlue to-blue-600 hover:from-blue-600 hover:to-psBlue text-white font-bold text-sm sm:text-base shadow-xl shadow-psBlue/30 transition flex items-center justify-center gap-2.5">
                            <i class="fa-solid fa-gamepad"></i>
                            <span>Sewa Sekarang via WA</span>
                        </a>
                        <a href="#daftar-harga" class="w-full sm:w-auto px-7 py-4 rounded-xl bg-slate-800/80 hover:bg-slate-800 border border-slate-700 text-slate-200 font-semibold text-sm sm:text-base transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-tags text-psCyan"></i>
                            <span>Lihat Daftar Harga</span>
                        </a>
                    </div>

                    <!-- Mini Highlights -->
                    <div class="grid grid-cols-3 gap-4 mt-10 pt-8 border-t border-slate-800/80 max-w-lg mx-auto lg:mx-0">
                        <div>
                            <p class="font-gaming text-2xl sm:text-3xl font-bold text-white">50+</p>
                            <p class="text-xs text-slate-400">Game Update Terbaru</p>
                        </div>
                        <div>
                            <p class="font-gaming text-2xl sm:text-3xl font-bold text-psCyan">24 Jam</p>
                            <p class="text-xs text-slate-400">Layanan Booking WA</p>
                        </div>
                        <div>
                            <p class="font-gaming text-2xl sm:text-3xl font-bold text-emerald-400">Gratis</p>
                            <p class="text-xs text-slate-400">Ongkir Radius 3 KM</p>
                        </div>
                    </div>
                </div>

                <!-- Right Visual Card -->
                <div class="lg:col-span-5">
                    <div class="relative bg-gradient-to-b from-slate-800/90 to-slate-900 border border-slate-700/80 rounded-3xl p-6 sm:p-8 shadow-2xl">
                        <div class="flex items-center justify-between mb-6">
                            <span class="text-xs font-bold uppercase tracking-wider text-psCyan bg-psCyan/10 px-3 py-1 rounded-lg">Paket Favorit Mabar</span>
                            <div class="flex gap-1.5 text-slate-400 text-sm">
                                <i class="fa-solid fa-play text-psCyan"></i>
                                <i class="fa-regular fa-circle text-rose-400"></i>
                                <i class="fa-solid fa-xmark text-blue-400"></i>
                                <i class="fa-regular fa-square text-pink-400"></i>
                            </div>
                        </div>

                        <div class="space-y-4">
                            <!-- Item 1 -->
                            <div class="p-4 rounded-2xl bg-slate-950/70 border border-slate-800 flex items-center justify-between">
                                <div class="flex items-center gap-3.5">
                                    <div class="w-11 h-11 rounded-xl bg-blue-500/15 text-blue-400 flex items-center justify-center text-xl">
                                        <i class="fa-brands fa-playstation"></i>
                                    </div>
                                    <div>
                                        <h3 class="font-bold text-white text-sm sm:text-base">PlayStation 5 (2 Stik)</h3>
                                        <p class="text-xs text-slate-400">FC 26, eFootball, GTA V, Tekken 8</p>
                                    </div>
                                </div>
                                <div class="text-right">
                                    <span class="block text-xs text-slate-400">Mulai</span>
                                    <span class="font-gaming font-bold text-lg text-psCyan">Rp 15rb<span class="text-xs font-sans text-slate-400">/jam</span></span>
                                </div>
                            </div>

                            <!-- Item 2 -->
                            <div class="p-4 rounded-2xl bg-slate-950/70 border border-slate-800 flex items-center justify-between">
                                <div class="flex items-center gap-3.5">
                                    <div class="w-11 h-11 rounded-xl bg-cyan-500/15 text-psCyan flex items-center justify-center text-xl">
                                        <i class="fa-solid fa-gamepad"></i>
                                    </div>
                                    <div>
                                        <h3 class="font-bold text-white text-sm sm:text-base">PS4 Slim / Pro (2 Stik)</h3>
                                        <p class="text-xs text-slate-400">Paket 24 Jam Bawa Pulang</p>
                                    </div>
                                </div>
                                <div class="text-right">
                                    <span class="block text-xs text-slate-400">Harian</span>
                                    <span class="font-gaming font-bold text-lg text-emerald-400">Rp 85rb</span>
                                </div>
                            </div>

                            <!-- Item 3 -->
                            <div class="p-4 rounded-2xl bg-slate-950/70 border border-slate-800 flex items-center justify-between">
                                <div class="flex items-center gap-3.5">
                                    <div class="w-11 h-11 rounded-xl bg-indigo-500/15 text-indigo-400 flex items-center justify-center text-xl">
                                        <i class="fa-solid fa-truck-fast"></i>
                                    </div>
                                    <div>
                                        <h3 class="font-bold text-white text-sm sm:text-base">Antar Jemput Rumah</h3>
                                        <p class="text-xs text-slate-400">Unit + Kabel HDMI + 2 Stik Siap Main</p>
                                    </div>
                                </div>
                                <div class="text-right">
                                    <span class="inline-block text-xs font-semibold bg-emerald-500/20 text-emerald-300 px-2.5 py-1 rounded-lg">Gratis &lt;3km</span>
                                </div>
                            </div>
                        </div>

                        <div class="mt-6 pt-5 border-t border-slate-800 flex items-center justify-between text-xs text-slate-400">
                            <span><i class="fa-solid fa-wallet text-psCyan mr-1.5"></i>DANA, OVO, GoPay, BCA, BRI</span>
                            <a href="#form-pesan" class="text-psCyan font-semibold hover:underline">Pilih Paket &rarr;</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Daftar Harga Interaktif -->
    <section id="daftar-harga" class="py-16 sm:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center max-w-3xl mx-auto mb-12">
            <span class="text-psCyan font-semibold text-xs uppercase tracking-widest">Transparan & Terjangkau</span>
            <h2 class="font-gaming text-3xl sm:text-4xl font-bold text-white mt-2 mb-4">Daftar Harga Rental PlayStation</h2>
            <p class="text-slate-400 text-sm sm:text-base">
                Pilih kategori bentuk pemesanan di bawah ini untuk melihat rincian tarif sewa PS3, PS4 (Slim/Pro), dan PS5 sesuai durasi yang Anda inginkan.
            </p>
        </div>

        <!-- Filter Tab Bentuk Pemesanan -->
        <div class="flex flex-wrap justify-center gap-3 mb-10" role="tablist">
            <button onclick="switchPriceTab('onsite')" id="tab-onsite" class="price-tab active-tab px-5 py-3.5 rounded-2xl font-semibold text-sm transition flex items-center gap-2.5 bg-psBlue text-white shadow-lg shadow-psBlue/30">
                <i class="fa-solid fa-store"></i>
                <span>1. Main di Tempat (On-Site)</span>
            </button>
            <button onclick="switchPriceTab('cod')" id="tab-cod" class="price-tab px-5 py-3.5 rounded-2xl font-semibold text-sm transition flex items-center gap-2.5 bg-slate-800/80 text-slate-300 hover:bg-slate-800 border border-slate-700">
                <i class="fa-solid fa-bag-shopping"></i>
                <span>2. COD / Ambil Sendiri</span>
            </button>
            <button onclick="switchPriceTab('delivery')" id="tab-delivery" class="price-tab px-5 py-3.5 rounded-2xl font-semibold text-sm transition flex items-center gap-2.5 bg-slate-800/80 text-slate-300 hover:bg-slate-800 border border-slate-700">
                <i class="fa-solid fa-motorcycle"></i>
                <span>3. Antar Jemput Rumah (Delivery)</span>
            </button>
        </div>

        <!-- Banner Info Kategori Aktif -->
        <div id="category-info-banner" class="mb-8 p-4 rounded-2xl bg-slate-900/90 border border-slate-800 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4">
            <div class="flex items-center gap-3">
                <div id="banner-icon" class="w-10 h-10 rounded-xl bg-psBlue/20 text-psCyan flex items-center justify-center text-lg shrink-0">
                    <i class="fa-solid fa-tv"></i>
                </div>
                <div>
                    <h3 id="banner-title" class="font-bold text-white text-sm sm:text-base">Main di Tempat (Studio ZonePlay)</h3>
                    <p id="banner-desc" class="text-xs sm:text-sm text-slate-400">Sudah termasuk TV LED 43"-50" 4K, ruangan ber-AC nyaman, Wi-Fi kencang, dan 2 Stik Wireless.</p>
                </div>
            </div>
            <span id="banner-badge" class="text-xs font-semibold px-3 py-1.5 rounded-xl bg-emerald-500/15 text-emerald-400 border border-emerald-500/30 shrink-0">
                Bisa Sewa Per Jam!
            </span>
        </div>

        <!-- Grid Kartu Harga (PS3, PS4, PS5) -->
        <div id="pricing-cards-container" class="grid md:grid-cols-3 gap-6 lg:gap-8">
            <!-- Konten dirender dinamis oleh JavaScript agar selalu sinkron dengan kalkulator -->
        </div>
    </section>

    <!-- Katalog Game Populer per Konsol -->
    <section id="katalog-game" class="py-16 bg-slate-900/50 border-y border-slate-800/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 gap-4">
                <div>
                    <span class="text-psCyan font-semibold text-xs uppercase tracking-widest">Full Game Siap Mabar</span>
                    <h2 class="font-gaming text-3xl sm:text-4xl font-bold text-white mt-1">Daftar Game Populer Tersedia</h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-400 max-w-md">
                    Bisa request install game tertentu sebelum unit diantar atau diambil (konfirmasi via WhatsApp).
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-6">
                <!-- Game PS3 -->
                <div class="bg-cardBg border border-cardBorder rounded-2xl p-6">
                    <div class="flex items-center justify-between mb-4 pb-3 border-b border-slate-800">
                        <h3 class="font-gaming text-xl font-bold text-white flex items-center gap-2">
                            <span class="w-2.5 h-2.5 rounded-full bg-indigo-400"></span> PlayStation 3
                        </h3>
                        <span class="text-xs text-slate-400">CFW / HEN Full Game</span>
                    </div>
                    <ul class="space-y-2.5 text-sm text-slate-300">
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-futbol text-psCyan text-xs"></i> eFootball PES 2026 Patch Terbaru</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-car text-psCyan text-xs"></i> GTA V & Need For Speed Most Wanted</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-fist-raised text-psCyan text-xs"></i> Naruto Shippuden Ultimate Ninja Storm 3</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-motorcycle text-psCyan text-xs"></i> MotoGP & Downhill Domination</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-skull text-psCyan text-xs"></i> Resident Evil 6 & God of War III</li>
                    </ul>
                </div>

                <!-- Game PS4 -->
                <div class="bg-cardBg border border-psBlue/50 rounded-2xl p-6 relative shadow-lg shadow-psBlue/10">
                    <div class="flex items-center justify-between mb-4 pb-3 border-b border-slate-800">
                        <h3 class="font-gaming text-xl font-bold text-white flex items-center gap-2">
                            <span class="w-2.5 h-2.5 rounded-full bg-psBlue"></span> PlayStation 4 Slim / Pro
                        </h3>
                        <span class="text-xs bg-psBlue/20 text-psCyan px-2 py-0.5 rounded">Terlaris</span>
                    </div>
                    <ul class="space-y-2.5 text-sm text-slate-300">
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-futbol text-psCyan text-xs"></i> EA Sports FC 26 & eFootball 2026</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-gun text-psCyan text-xs"></i> Red Dead Redemption 2 & GTA V</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-hand-fist text-psCyan text-xs"></i> Tekken 7 & Mortal Kombat 11 Ultimate</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-spider text-psCyan text-xs"></i> Marvel's Spider-Man & Miles Morales</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-flag-checkered text-psCyan text-xs"></i> Gran Turismo 7 & CTR Nitro-Fueled</li>
                    </ul>
                </div>

                <!-- Game PS5 -->
                <div class="bg-cardBg border border-cardBorder rounded-2xl p-6">
                    <div class="flex items-center justify-between mb-4 pb-3 border-b border-slate-800">
                        <h3 class="font-gaming text-xl font-bold text-white flex items-center gap-2">
                            <span class="w-2.5 h-2.5 rounded-full bg-psCyan"></span> PlayStation 5
                        </h3>
                        <span class="text-xs text-psCyan">4K 60-120 FPS</span>
                    </div>
                    <ul class="space-y-2.5 text-sm text-slate-300">
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-futbol text-psCyan text-xs"></i> EA Sports FC 26 (Next-Gen HyperMotion)</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-hand-fist text-psCyan text-xs"></i> Tekken 8 & Street Fighter 6</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-spider text-psCyan text-xs"></i> Marvel's Spider-Man 2 & God of War Ragnarök</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-dragon text-psCyan text-xs"></i> Black Myth: Wukong & Elden Ring</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-users text-psCyan text-xs"></i> It Takes Two & Overcooked! All You Can Eat</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Form Pemesanan Langsung ke WhatsApp -->
    <section id="form-pesan" class="py-16 sm:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid lg:grid-cols-12 gap-10 items-start">
            <!-- Form Input (7 Kolom) -->
            <div class="lg:col-span-7 bg-cardBg border border-slate-800 rounded-3xl p-6 sm:p-8 shadow-2xl">
                <div class="mb-6 pb-5 border-b border-slate-800">
                    <span class="text-psCyan text-xs font-bold uppercase tracking-wider">Booking Cepat & Praktis</span>
                    <h2 class="font-gaming text-2xl sm:text-3xl font-bold text-white mt-1">Form Pemesanan Rental PS</h2>
                    <p class="text-slate-400 text-xs sm:text-sm mt-1">Isi detail sewa di bawah ini, total biaya otomatis terhitung dan langsung terkirim ke WhatsApp admin.</p>
                </div>

                <form id="rental-form" onsubmit="submitToWhatsApp(event)" class="space-y-5">
                    <!-- Nama Pemesan -->
                    <div>
                        <label for="customer-name" class="block text-sm font-medium text-slate-300 mb-2">Nama Lengkap Pemesan <span class="text-rose-400">*</span></label>
                        <div class="relative">
                            <span class="absolute inset-y-0 left-0 pl-3.5 flex items-center text-slate-400">
                                <i class="fa-solid fa-user"></i>
                            </span>
                            <input type="text" id="customer-name" required placeholder="Contoh: Budi Santoso"
                                class="w-full pl-10 pr-4 py-3 rounded-xl bg-slate-900 border border-slate-700 text-white placeholder-slate-500 focus:outline-none focus:border-psCyan focus:ring-1 focus:ring-psCyan text-sm">
                        </div>
                    </div>

                    <!-- Pilihan Tipe PS & Bentuk Pemesanan -->
                    <div class="grid sm:grid-cols-2 gap-4">
                        <div>
                            <label for="ps-type" class="block text-sm font-medium text-slate-300 mb-2">Pilih Tipe PlayStation <span class="text-rose-400">*</span></label>
                            <select id="ps-type" onchange="updateFormLogic()"
                                class="w-full px-4 py-3 rounded-xl bg-slate-900 border border-slate-700 text-white focus:outline-none focus:border-psCyan text-sm">
                                <option value="ps3">PlayStation 3 (2 Stik)</option>
                                <option value="ps4" selected>PlayStation 4 Slim / Pro (2 Stik)</option>
                                <option value="ps5">PlayStation 5 (2 Stik DualSense)</option>
                            </select>
                        </div>

                        <div>
                            <label for="order-mode" class="block text-sm font-medium text-slate-300 mb-2">Bentuk Pemesanan <span class="text-rose-400">*</span></label>
                            <select id="order-mode" onchange="updateFormLogic()"
                                class="w-full px-4 py-3 rounded-xl bg-slate-900 border border-slate-700 text-white focus:outline-none focus:border-psCyan text-sm">
                                <option value="onsite">Main di Tempat (Rental On-Site)</option>
                                <option value="cod">COD / Ambil Sendiri ke Lokasi</option>
                                <option value="delivery">Antar Jemput Sampai Rumah (Delivery)</option>
                            </select>
                        </div>
                    </div>

                    <!-- Input Alamat Lengkap (Otomatis muncul jika Delivery) -->
                    <div id="address-wrapper" class="hidden transition-all duration-300">
                        <label for="customer-address" class="block text-sm font-medium text-slate-300 mb-2">
                            Alamat Lengkap Pengantaran & Patokan <span class="text-rose-400">*</span>
                        </label>
                        <textarea id="customer-address" rows="2" placeholder="Masukkan nama jalan, nomor rumah, RT/RW, kelurahan, atau patokan lokasi..."
                            class="w-full px-4 py-3 rounded-xl bg-slate-900 border border-slate-700 text-white placeholder-slate-500 focus:outline-none focus:border-psCyan text-sm"></textarea>
                        <p class="text-xs text-psCyan mt-1.5">
                            <i class="fa-solid fa-circle-info mr-1"></i> Gratis ongkir jarak &lt; 3 km. Di atas 3 km dikenakan ongkir Rp 10.000 - Rp 20.000 (konfirmasi via WA).
                        </p>
                    </div>

                    <!-- Durasi Sewa & Tanggal/Jam Mulai -->
                    <div class="grid sm:grid-cols-2 gap-4">
                        <div>
                            <label for="duration" class="block text-sm font-medium text-slate-300 mb-2">Durasi / Paket Sewa <span class="text-rose-400">*</span></label>
                            <select id="duration" onchange="calculateTotal()"
                                class="w-full px-4 py-3 rounded-xl bg-slate-900 border border-slate-700 text-white focus:outline-none focus:border-psCyan text-sm">
                                <!-- Opsi diisi otomatis oleh JS sesuai Bentuk Pemesanan -->
                            </select>
                        </div>

                        <div>
                            <label for="start-datetime" class="block text-sm font-medium text-slate-300 mb-2">Tanggal & Jam Mulai <span class="text-rose-400">*</span></label>
                            <input type="datetime-local" id="start-datetime" required
                                class="w-full px-4 py-3 rounded-xl bg-slate-900 border border-slate-700 text-white focus:outline-none focus:border-psCyan text-sm">
                        </div>
                    </div>

                    <!-- Opsi Tambahan TV (Jika COD / Delivery) -->
                    <div id="tv-addon-wrapper" class="hidden p-3.5 rounded-xl bg-slate-900/90 border border-slate-800 flex items-center justify-between">
                        <div class="flex items-center gap-3">
                            <input type="checkbox" id="addon-tv" onchange="calculateTotal()" class="w-4 h-4 rounded accent-psBlue cursor-pointer">
                            <label for="addon-tv" class="text-sm text-slate-200 cursor-pointer">
                                Tambah Sewa TV LED 32" <span class="text-xs text-slate-400 block sm:inline">(+Rp 25.000 / paket)</span>
                            </label>
                        </div>
                        <span class="text-xs font-semibold text-psCyan">+Rp 25rb</span>
                    </div>

                    <!-- Metode Pembayaran -->
                    <div>
                        <label class="block text-sm font-medium text-slate-300 mb-2">Metode Pembayaran <span class="text-rose-400">*</span></label>
                        <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                            <!-- E-Wallet -->
                            <label class="cursor-pointer">
                                <input type="radio" name="payment-method" value="E-Wallet (DANA / OVO / GoPay / ShopeePay)" checked onchange="togglePaymentSub()" class="peer sr-only">
                                <div class="p-3.5 rounded-xl bg-slate-900 border border-slate-700 peer-checked:border-psCyan peer-checked:bg-psBlue/15 transition text-center">
                                    <i class="fa-solid fa-wallet text-psCyan text-lg mb-1"></i>
                                    <p class="text-xs font-bold text-white">E-Wallet</p>
                                    <p class="text-[11px] text-slate-400">DANA, OVO, GoPay</p>
                                </div>
                            </label>

                            <!-- Transfer Rekening -->
                            <label class="cursor-pointer">
                                <input type="radio" name="payment-method" value="Transfer Rekening Bank (BCA / BRI / Mandiri)" onchange="togglePaymentSub()" class="peer sr-only">
                                <div class="p-3.5 rounded-xl bg-slate-900 border border-slate-700 peer-checked:border-psCyan peer-checked:bg-psBlue/15 transition text-center">
                                    <i class="fa-solid fa-building-columns text-blue-400 text-lg mb-1"></i>
                                    <p class="text-xs font-bold text-white">Transfer Bank</p>
                                    <p class="text-[11px] text-slate-400">BCA, BRI, Mandiri</p>
                                </div>
                            </label>

                            <!-- Tunai / Cash -->
                            <label id="cash-option-label" class="cursor-pointer">
                                <input type="radio" name="payment-method" id="payment-cash" value="Tunai / Cash di Tempat" onchange="togglePaymentSub()" class="peer sr-only">
                                <div class="p-3.5 rounded-xl bg-slate-900 border border-slate-700 peer-checked:border-psCyan peer-checked:bg-psBlue/15 transition text-center">
                                    <i class="fa-solid fa-money-bill-wave text-emerald-400 text-lg mb-1"></i>
                                    <p class="text-xs font-bold text-white">Tunai / Cash</p>
                                    <p class="text-[11px] text-slate-400">On-Site / COD</p>
                                </div>
                            </label>
                        </div>

                        <!-- Pilihan Provider E-Wallet / Bank Spesifik -->
                        <div id="payment-detail-box" class="mt-3">
                            <select id="payment-provider" onchange="calculateTotal()" class="w-full px-4 py-2.5 rounded-xl bg-slate-900 border border-slate-700 text-slate-200 text-xs sm:text-sm focus:outline-none focus:border-psCyan">
                                <option value="DANA">Pilih Akun E-Wallet: DANA</option>
                                <option value="OVO">Pilih Akun E-Wallet: OVO</option>
                                <option value="GoPay">Pilih Akun E-Wallet: GoPay</option>
                                <option value="ShopeePay">Pilih Akun E-Wallet: ShopeePay</option>
                            </select>
                        </div>
                    </div>

                    <!-- Catatan / Request Game -->
                    <div>
                        <label for="notes" class="block text-sm font-medium text-slate-300 mb-2">Catatan / Request Game (Opsional)</label>
                        <input type="text" id="notes" placeholder="Contoh: Tolong siapkan game FC 26 & Tekken 8 ya min"
                            class="w-full px-4 py-3 rounded-xl bg-slate-900 border border-slate-700 text-white placeholder-slate-500 focus:outline-none focus:border-psCyan text-sm">
                    </div>

                    <!-- Submit Button -->
                    <button type="submit" class="w-full py-4 px-6 rounded-2xl bg-gradient-to-r from-emerald-500 to-green-600 hover:from-emerald-600 hover:to-green-700 text-white font-bold text-base shadow-xl shadow-emerald-600/25 transition flex items-center justify-center gap-3">
                        <i class="fa-brands fa-whatsapp text-2xl"></i>
                        <span>Pesan Sekarang via WhatsApp</span>
                    </button>
                </form>
            </div>

            <!-- Ringkasan Estimasi Harga Real-Time (5 Kolom) -->
            <div class="lg:col-span-5 lg:sticky lg:top-24 space-y-6">
                <div class="bg-gradient-to-b from-slate-800/90 to-slate-900 border border-slate-700 rounded-3xl p-6 sm:p-8 shadow-xl">
                    <div class="flex items-center justify-between pb-4 border-b border-slate-700/80">
                        <h3 class="font-gaming text-xl font-bold text-white">Ringkasan Estimasi Biaya</h3>
                        <span class="text-xs bg-psBlue/20 text-psCyan px-2.5 py-1 rounded-lg font-semibold">Otomatis</span>
                    </div>

                    <div class="space-y-3.5 py-5 text-sm border-b border-slate-700/80">
                        <div class="flex justify-between">
                            <span class="text-slate-400">Konsol:</span>
                            <span id="summary-ps" class="font-semibold text-white">PlayStation 4 Slim / Pro</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-slate-400">Layanan:</span>
                            <span id="summary-mode" class="font-semibold text-psCyan">Main di Tempat</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-slate-400">Paket Durasi:</span>
                            <span id="summary-duration" class="font-semibold text-white">1 Jam</span>
                        </div>
                        <div id="summary-tv-row" class="hidden justify-between">
                            <span class="text-slate-400">Tambahan TV 32":</span>
                            <span class="font-semibold text-white">Rp 25.000</span>
                        </div>
                        <div id="summary-ongkir-row" class="hidden justify-between">
                            <span class="text-slate-400">Estimasi Ongkir:</span>
                            <span class="font-semibold text-emerald-400">Rp 0 - Rp 15.000*</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-slate-400">Pembayaran:</span>
                            <span id="summary-payment" class="font-semibold text-slate-200">E-Wallet (DANA)</span>
                        </div>
                    </div>

                    <div class="pt-5">
                        <div class="flex items-baseline justify-between">
                            <span class="text-slate-300 font-medium">Estimasi Total:</span>
                            <span id="summary-total" class="font-gaming text-3xl sm:text-4xl font-bold text-psCyan">Rp 10.000</span>
                        </div>
                        <p id="summary-note" class="text-xs text-slate-400 mt-2">
                            *Harga sudah termasuk 2 stik wireless & game full terinstall.
                        </p>
                    </div>
                </div>

                <!-- Card Kontak Cepat Admin -->
                <div class="bg-cardBg border border-slate-800 rounded-2xl p-5 flex items-center justify-between">
                    <div class="flex items-center gap-3.5">
                        <div class="w-11 h-11 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-xl">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <div>
                            <p class="text-xs text-slate-400">Butuh bantuan atau tanya stok?</p>
                            <p class="font-bold text-white text-sm">Admin Rizz Store (0812-3456-7890)</p>
                        </div>
                    </div>
                    <a href="https://wa.me/6281234567890?text=Halo%20Admin%20Rizz%20Store,%20saya%20mau%20tanya%20ketersediaan%20unit%20PS." target="_blank" rel="noopener noreferrer"
                        class="px-3.5 py-2 rounded-xl bg-slate-800 hover:bg-slate-700 text-xs font-semibold text-emerald-400 border border-slate-700 transition">
                        Chat WA
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Informasi Pembayaran & Syarat Ketentuan -->
    <section id="syarat-pembayaran" class="py-16 bg-slate-900/60 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-2 gap-8 lg:gap-12">
                <!-- Metode Pembayaran -->
                <div class="bg-cardBg border border-slate-800 rounded-3xl p-6 sm:p-8">
                    <div class="flex items-center gap-3 mb-5">
                        <div class="w-10 h-10 rounded-xl bg-psBlue/20 text-psCyan flex items-center justify-center text-lg">
                            <i class="fa-solid fa-credit-card"></i>
                        </div>
                        <h3 class="font-gaming text-2xl font-bold text-white">Metode Pembayaran Resmi</h3>
                    </div>
                    <p class="text-sm text-slate-400 mb-6">
                        Kami menerima pembayaran non-tunai (cashless) untuk kemudahan transaksi booking maupun pelunasan di tempat:
                    </p>

                    <div class="space-y-4">
                        <div>
                            <p class="text-xs font-semibold uppercase tracking-wider text-slate-400 mb-2.5">E-Wallet & QRIS</p>
                            <div class="flex flex-wrap gap-2.5">
                                <span class="px-4 py-2 rounded-xl bg-sky-500/15 border border-sky-500/30 text-sky-300 font-bold text-xs tracking-wide">DANA</span>
                                <span class="px-4 py-2 rounded-xl bg-purple-500/15 border border-purple-500/30 text-purple-300 font-bold text-xs tracking-wide">OVO</span>
                                <span class="px-4 py-2 rounded-xl bg-emerald-500/15 border border-emerald-500/30 text-emerald-300 font-bold text-xs tracking-wide">GoPay</span>
                                <span class="px-4 py-2 rounded-xl bg-orange-500/15 border border-orange-500/30 text-orange-300 font-bold text-xs tracking-wide">ShopeePay</span>
                                <span class="px-4 py-2 rounded-xl bg-slate-800 border border-slate-700 text-slate-200 font-bold text-xs tracking-wide">QRIS All Payment</span>
                            </div>
                        </div>

                        <div class="pt-2">
                            <p class="text-xs font-semibold uppercase tracking-wider text-slate-400 mb-2.5">Transfer Rekening Bank</p>
                            <div class="flex flex-wrap gap-2.5">
                                <span class="px-4 py-2 rounded-xl bg-blue-600/20 border border-blue-500/30 text-blue-300 font-bold text-xs tracking-wide">Bank BCA</span>
                                <span class="px-4 py-2 rounded-xl bg-indigo-600/20 border border-indigo-500/30 text-indigo-300 font-bold text-xs tracking-wide">Bank BRI</span>
                                <span class="px-4 py-2 rounded-xl bg-amber-500/15 border border-amber-500/30 text-amber-300 font-bold text-xs tracking-wide">Bank Mandiri</span>
                            </div>
                        </div>
                    </div>

                    <div class="mt-6 p-3.5 rounded-xl bg-slate-900 border border-slate-800 text-xs text-slate-400">
                        <i class="fa-solid fa-shield-halved text-psCyan mr-1.5"></i> Nomor rekening / nomor E-Wallet resmi akan dikirimkan langsung oleh Admin saat konfirmasi pesanan di WhatsApp.
                    </div>
                </div>

                <!-- Syarat & Ketentuan Sewa Bawa Pulang -->
                <div class="bg-cardBg border border-slate-800 rounded-3xl p-6 sm:p-8">
                    <div class="flex items-center gap-3 mb-5">
                        <div class="w-10 h-10 rounded-xl bg-amber-500/15 text-amber-400 flex items-center justify-center text-lg">
                            <i class="fa-solid fa-file-contract"></i>
                        </div>
                        <h3 class="font-gaming text-2xl font-bold text-white">Syarat & Ketentuan Sewa</h3>
                    </div>

                    <ul class="space-y-3 text-sm text-slate-300">
                        <li class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-emerald-400 mt-1"></i>
                            <span><strong>Area Antar Jemput:</strong> Melayani pengantaran dalam kota. Gratis ongkir untuk jarak maksimal 3 km dari markas Rizz Store.</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-emerald-400 mt-1"></i>
                            <span><strong>Area Antar Jemput:</strong> Melayani pengantaran dalam kota. Gratis ongkir untuk jarak maksimal 3 km dari markas ZonePlay.</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-emerald-400 mt-1"></i>
                            <span><strong>Perpanjangan Waktu (Extend):</strong> Harap konfirmasi maksimal 1 jam sebelum masa sewa berakhir agar tidak bentrok dengan jadwal penyewa berikutnya.</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-emerald-400 mt-1"></i>
                            <span><strong>Keamanan Unit:</strong> Penyewa bertanggung jawab menjaga kelengkapan unit (Konsol, 2 Stik, Kabel Power, Kabel HDMI, Kabel Charger Stik).</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-darkBg border-t border-slate-800/80 py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center justify-between gap-6">
            <div class="flex items-center gap-3">
                <div class="w-9 h-9 rounded-xl bg-psBlue flex items-center justify-center text-white">
                    <i class="fa-brands fa-playstation text-lg"></i>
                </div>
                <div>
                    <span class="font-gaming text-xl font-bold text-white">RIZZ<span class="text-psCyan">STORE</span> RENTAL PS</span>
                    <p class="text-xs text-slate-400">Jl. Raya Gaming No. 88 • Buka Setiap Hari 09.00 - 02.00 WIB</p>
                </div>
            </div>

            <div class="text-xs text-slate-500 text-center md:text-right">
                <p>&copy; 2026 Rizz Store Rental PlayStation. Semua Hak Dilindungi.</p>
                <p class="mt-1">Order cepat via WhatsApp: <span class="text-slate-300 font-medium">0812-3456-7890</span></p>
            </div>
        </div>
    </footer>

    <!-- JavaScript Logika Harga Interaktif & Integrasi WhatsApp -->
    <script>
        // Nomor WhatsApp Admin (Format Internasional tanpa tanda +)
        const ADMIN_WA_NUMBER = "6281234567890";

        // Data Master Harga berdasarkan Tipe PS, Bentuk Pemesanan, dan Durasi
        const PRICING_DATA = {
            onsite: {
                title: "Main di Tempat (Studio Rizz Store)",
                desc: "Sudah termasuk TV LED 43\"-50\" 4K, ruangan ber-AC nyaman, Wi-Fi kencang, dan 2 Stik Wireless.",
                badge: "Bisa Sewa Per Jam!",
                consoles: {
                    ps3: {
                        name: "PlayStation 3",
                        subtitle: "2 Stik Wireless • TV LED 43\"",
                        highlight: false,
                        packages: [
                            { id: "1h", label: "Per 1 Jam", price: 6000 },
                            { id: "3h", label: "Paket Mabar 3 Jam", price: 15000 },
                            { id: "6h", label: "Paket 6 Jam", price: 28000 },
                            { id: "12h", label: "Paket Begadang 12 Jam", price: 50000 }
                        ]
                    },
                    ps4: {
                        name: "PlayStation 4 Slim / Pro",
                        subtitle: "2 Stik DualShock 4 • TV 4K HDR",
                        highlight: true,
                        packages: [
                            { id: "1h", label: "Per 1 Jam", price: 10000 },
                            { id: "3h", label: "Paket Mabar 3 Jam", price: 27000 },
                            { id: "6h", label: "Paket 6 Jam", price: 50000 },
                            { id: "12h", label: "Paket Begadang 12 Jam", price: 90000 }
                        ]
                    },
                    ps5: {
                        name: "PlayStation 5",
                        subtitle: "2 Stik DualSense • TV 50\" 4K 120Hz",
                        highlight: false,
                        packages: [
                            { id: "1h", label: "Per 1 Jam", price: 15000 },
                            { id: "3h", label: "Paket Mabar 3 Jam", price: 42000 },
                            { id: "6h", label: "Paket 6 Jam", price: 80000 },
                            { id: "12h", label: "Paket Begadang 12 Jam", price: 145000 }
                        ]
                    }
                }
            },
            cod: {
                title: "COD / Ambil Sendiri ke Lokasi",
                desc: "Unit diambil & dikembalikan sendiri ke markas Rizz Store. Kelengkapan: Konsol, 2 Stik, Kabel Power, HDMI & Charger.",
                badge: "Lebih Hemat Tanpa Ongkir!",
                consoles: {
                    ps3: {
                        name: "PlayStation 3",
                        subtitle: "Full Game • 2 Stik + Kabel Lengkap",
                        highlight: false,
                        packages: [
                            { id: "6h", label: "Paket 6 Jam", price: 30000 },
                            { id: "12h", label: "Paket 12 Jam", price: 45000 },
                            { id: "24h", label: "Paket 24 Jam (Harian)", price: 65000 },
                            { id: "7d", label: "Paket Mingguan (7 Hari)", price: 350000 }
                        ]
                    },
                    ps4: {
                        name: "PlayStation 4 Slim / Pro",
                        subtitle: "FC 26 & Game Populer • 2 Stik Ori",
                        highlight: true,
                        packages: [
                            { id: "6h", label: "Paket 6 Jam", price: 45000 },
                            { id: "12h", label: "Paket 12 Jam", price: 65000 },
                            { id: "24h", label: "Paket 24 Jam (Harian)", price: 85000 },
                            { id: "7d", label: "Paket Mingguan (7 Hari)", price: 480000 }
                        ]
                    },
                    ps5: {
                        name: "PlayStation 5",
                        subtitle: "Next-Gen Gaming • 2 Stik DualSense",
                        highlight: false,
                        packages: [
                            { id: "6h", label: "Paket 6 Jam", price: 80000 },
                            { id: "12h", label: "Paket 12 Jam", price: 120000 },
                            { id: "24h", label: "Paket 24 Jam (Harian)", price: 165000 },
                            { id: "7d", label: "Paket Mingguan (7 Hari)", price: 950000 }
                        ]
                    }
                }
            },
            delivery: {
                title: "Antar Jemput Sampai Rumah (Delivery)",
                desc: "Kurir kami mengantar & memasangkan unit langsung ke rumah Anda. Gratis ongkir radius < 3 km (di atas 3 km +Rp 10rb-20rb).",
                badge: "Gratis Ongkir < 3 KM",
                consoles: {
                    ps3: {
                        name: "PlayStation 3",
                        subtitle: "Antar Jemput • 2 Stik + Kabel Lengkap",
                        highlight: false,
                        packages: [
                            { id: "6h", label: "Paket 6 Jam", price: 40000 },
                            { id: "12h", label: "Paket 12 Jam", price: 55000 },
                            { id: "24h", label: "Paket 24 Jam (Harian)", price: 75000 },
                            { id: "7d", label: "Paket Mingguan (7 Hari)", price: 370000 }
                        ]
                    },
                    ps4: {
                        name: "PlayStation 4 Slim / Pro",
                        subtitle: "Antar Jemput • 2 Stik DualShock 4",
                        highlight: true,
                        packages: [
                            { id: "6h", label: "Paket 6 Jam", price: 55000 },
                            { id: "12h", label: "Paket 12 Jam", price: 75000 },
                            { id: "24h", label: "Paket 24 Jam (Harian)", price: 95000 },
                            { id: "7d", label: "Paket Mingguan (7 Hari)", price: 500000 }
                        ]
                    },
                    ps5: {
                        name: "PlayStation 5",
                        subtitle: "Antar Jemput • 2 Stik DualSense",
                        highlight: false,
                        packages: [
                            { id: "6h", label: "Paket 6 Jam", price: 95000 },
                            { id: "12h", label: "Paket 12 Jam", price: 135000 },
                            { id: "24h", label: "Paket 24 Jam (Harian)", price: 180000 },
                            { id: "7d", label: "Paket Mingguan (7 Hari)", price: 980000 }
                        ]
                    }
                }
            }
        };

        // Format Angka ke Rupiah
        function formatRupiah(angka) {
            return "Rp " + angka.toLocaleString("id-ID");
        }

        // Render Kartu Harga pada Tab yang Dipilih
        function switchPriceTab(modeKey) {
            // Update tampilan tombol tab
            document.querySelectorAll('.price-tab').forEach(btn => {
                btn.classList.remove('bg-psBlue', 'text-white', 'shadow-lg', 'shadow-psBlue/30');
                btn.classList.add('bg-slate-800/80', 'text-slate-300', 'border', 'border-slate-700');
            });

            const activeBtn = document.getElementById(`tab-${modeKey}`);
            activeBtn.classList.remove('bg-slate-800/80', 'text-slate-300', 'border', 'border-slate-700');
            activeBtn.classList.add('bg-psBlue', 'text-white', 'shadow-lg', 'shadow-psBlue/30');

            const data = PRICING_DATA[modeKey];
            document.getElementById('banner-title').textContent = data.title;
            document.getElementById('banner-desc').textContent = data.desc;
            document.getElementById('banner-badge').textContent = data.badge;

            const container = document.getElementById('pricing-cards-container');
            container.innerHTML = "";

            Object.entries(data.consoles).forEach(([psKey, psData]) => {
                const isHighlight = psData.highlight;
                const cardBorderClass = isHighlight
                    ? "border-2 border-psBlue bg-gradient-to-b from-slate-800/95 to-cardBg shadow-2xl shadow-psBlue/15 relative"
                    : "border border-cardBorder bg-cardBg";

                const badgeHtml = isHighlight
                    ? `<span class="absolute -top-3.5 right-6 bg-gradient-to-r from-psBlue to-psCyan text-slate-950 font-extrabold text-[11px] uppercase tracking-wider px-3 py-1 rounded-full shadow">Paling Laris</span>`
                    : "";

                let packagesHtml = "";
                psData.packages.forEach(pkg => {
                    packagesHtml += `
                        <div class="flex items-center justify-between py-2.5 border-b border-slate-800/80 last:border-none">
                            <span class="text-sm text-slate-300">${pkg.label}</span>
                            <span class="font-gaming font-bold text-lg text-white">${formatRupiah(pkg.price)}</span>
                        </div>
                    `;
                });

                const cardHtml = `
                    <div class="${cardBorderClass} rounded-3xl p-6 sm:p-7 flex flex-col justify-between transition hover:-translate-y-1 duration-300">
                        ${badgeHtml}
                        <div>
                            <div class="flex items-center gap-3 mb-2">
                                <div class="w-10 h-10 rounded-xl ${isHighlight ? 'bg-psBlue text-white' : 'bg-slate-800 text-psCyan'} flex items-center justify-center text-lg">
                                    <i class="fa-brands fa-playstation"></i>
                                </div>
                                <div>
                                    <h3 class="font-gaming text-2xl font-bold text-white">${psData.name}</h3>
                                    <p class="text-xs text-slate-400">${psData.subtitle}</p>
                                </div>
                            </div>

                            <div class="mt-5 mb-6 bg-slate-950/60 rounded-2xl p-4 border border-slate-800/70">
                                ${packagesHtml}
                            </div>
                        </div>

                        <button type="button" onclick="selectPackageToForm('${psKey}', '${modeKey}')"
                            class="w-full py-3.5 px-4 rounded-xl font-semibold text-sm transition flex items-center justify-center gap-2 ${isHighlight ? 'bg-psBlue hover:bg-blue-600 text-white shadow-lg shadow-psBlue/30' : 'bg-slate-800 hover:bg-slate-700 text-psCyan border border-slate-700'}">
                            <span>Pilih ${psData.name.split(' ')[0]} ${psData.name.split(' ')[1]}</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </button>
                    </div>
                `;
                container.innerHTML += cardHtml;
            });
        }

        // Fungsi saat tombol "Pilih Paket" di kartu harga diklik -> scroll ke form & isi otomatis
        function selectPackageToForm(psKey, modeKey) {
            document.getElementById('ps-type').value = psKey;
            document.getElementById('order-mode').value = modeKey;
            updateFormLogic();
            document.getElementById('form-pesan').scrollIntoView({ behavior: 'smooth' });
        }

        // Perbarui dropdown durasi & field kondisional pada form
        function updateFormLogic() {
            const psKey = document.getElementById('ps-type').value;
            const modeKey = document.getElementById('order-mode').value;
            const durationSelect = document.getElementById('duration');
            const addressWrapper = document.getElementById('address-wrapper');
            const addressInput = document.getElementById('customer-address');
            const tvAddonWrapper = document.getElementById('tv-addon-wrapper');
            const addonTvCheckbox = document.getElementById('addon-tv');
            const cashLabel = document.getElementById('cash-option-label');
            const cashRadio = document.getElementById('payment-cash');

            // 1. Tampilkan / sembunyikan input alamat lengkap
            if (modeKey === 'delivery') {
                addressWrapper.classList.remove('hidden');
                addressInput.setAttribute('required', 'required');
            } else {
                addressWrapper.classList.add('hidden');
                addressInput.removeAttribute('required');
            }

            // 2. Tampilkan / sembunyikan opsi sewa TV (hanya untuk COD / Delivery)
            if (modeKey === 'cod' || modeKey === 'delivery') {
                tvAddonWrapper.classList.remove('hidden');
            } else {
                tvAddonWrapper.classList.add('hidden');
                addonTvCheckbox.checked = false;
            }

            // 3. Atur opsi Tunai/Cash (khusus Main di Tempat & COD)
            if (modeKey === 'delivery') {
                cashLabel.classList.add('opacity-50', 'pointer-events-none');
                if (cashRadio.checked) {
                    document.querySelector('input[name="payment-method"][value^="E-Wallet"]').checked = true;
                    togglePaymentSub();
                }
            } else {
                cashLabel.classList.remove('opacity-50', 'pointer-events-none');
            }

            // 4. Isi ulang pilihan durasi sesuai konsol & mode
            const packages = PRICING_DATA[modeKey].consoles[psKey].packages;
            const previousValue = durationSelect.value;
            durationSelect.innerHTML = "";

            packages.forEach(pkg => {
                const opt = document.createElement('option');
                opt.value = pkg.id;
                opt.textContent = `${pkg.label} — ${formatRupiah(pkg.price)}`;
                durationSelect.appendChild(opt);
            });

            // Pertahankan pilihan durasi jika ID-nya masih ada di mode baru
            if (packages.some(p => p.id === previousValue)) {
                durationSelect.value = previousValue;
            }

            calculateTotal();
        }

        // Atur dropdown sub-pembayaran (E-Wallet vs Bank vs Tunai)
        function togglePaymentSub() {
            const selectedMethod = document.querySelector('input[name="payment-method"]:checked').value;
            const detailBox = document.getElementById('payment-detail-box');
            const providerSelect = document.getElementById('payment-provider');

            if (selectedMethod.startsWith('E-Wallet')) {
                detailBox.classList.remove('hidden');
                providerSelect.innerHTML = `
                    <option value="DANA">Akun E-Wallet: DANA</option>
                    <option value="OVO">Akun E-Wallet: OVO</option>
                    <option value="GoPay">Akun E-Wallet: GoPay</option>
                    <option value="ShopeePay">Akun E-Wallet: ShopeePay</option>
                `;
            } else if (selectedMethod.startsWith('Transfer')) {
                detailBox.classList.remove('hidden');
                providerSelect.innerHTML = `
                    <option value="Bank BCA">Rekening Tujuan: Bank BCA</option>
                    <option value="Bank BRI">Rekening Tujuan: Bank BRI</option>
                    <option value="Bank Mandiri">Rekening Tujuan: Bank Mandiri</option>
                `;
            } else {
                detailBox.classList.add('hidden');
            }

            calculateTotal();
        }

        // Hitung Total Harga & Perbarui Panel Ringkasan
        function calculateTotal() {
            const psKey = document.getElementById('ps-type').value;
            const modeKey = document.getElementById('order-mode').value;
            const durationId = document.getElementById('duration').value;
            const isAddonTv = document.getElementById('addon-tv').checked;
            const selectedMethod = document.querySelector('input[name="payment-method"]:checked').value;
            const provider = document.getElementById('payment-provider').value;

            const consoleData = PRICING_DATA[modeKey].consoles[psKey];
            const selectedPkg = consoleData.packages.find(p => p.id === durationId) || consoleData.packages[0];

            let total = selectedPkg.price;
            if (isAddonTv && (modeKey === 'cod' || modeKey === 'delivery')) {
                total += 25000;
            }

            // Label mode rapi
            const modeLabels = {
                onsite: "Main di Tempat (On-Site)",
                cod: "COD / Ambil Sendiri",
                delivery: "Antar Jemput ke Rumah"
            };

            // Update teks ringkasan
            document.getElementById('summary-ps').textContent = consoleData.name;
            document.getElementById('summary-mode').textContent = modeLabels[modeKey];
            document.getElementById('summary-duration').textContent = selectedPkg.label;

            const tvRow = document.getElementById('summary-tv-row');
            if (isAddonTv) {
                tvRow.classList.remove('hidden');
                tvRow.classList.add('flex');
            } else {
                tvRow.classList.add('hidden');
                tvRow.classList.remove('flex');
            }

            const ongkirRow = document.getElementById('summary-ongkir-row');
            if (modeKey === 'delivery') {
                ongkirRow.classList.remove('hidden');
                ongkirRow.classList.add('flex');
            } else {
                ongkirRow.classList.add('hidden');
                ongkirRow.classList.remove('flex');
            }

            let paymentText = selectedMethod;
            if (!selectedMethod.startsWith('Tunai')) {
                paymentText = `${selectedMethod.split(' ')[0]} (${provider})`;
            }
            document.getElementById('summary-payment').textContent = paymentText;
            document.getElementById('summary-total').textContent = formatRupiah(total);

            return {
                consoleName: consoleData.name,
                modeName: modeLabels[modeKey],
                packageName: selectedPkg.label,
                isAddonTv,
                paymentText,
                total
            };
        }

        // Notifikasi Toast Kustom (Pengganti alert)
        function showToast(title, message) {
            const toast = document.getElementById('toast-box');
            document.getElementById('toast-title').textContent = title;
            document.getElementById('toast-message').textContent = message;
            toast.classList.remove('hidden');
            setTimeout(() => {
                hideToast();
            }, 4500);
        }

        function hideToast() {
            document.getElementById('toast-box').classList.add('hidden');
        }

        // Format Tanggal & Jam Indonesia
        function formatDateTimeID(isoString) {
            if (!isoString) return "-";
            const date = new Date(isoString);
            return date.toLocaleString('id-ID', {
                weekday: 'long',
                day: 'numeric',
                month: 'long',
                year: 'numeric',
                hour: '2-digit',
                minute: '2-digit'
            }) + " WIB";
        }

        // Kirim Pesanan Terformat ke WhatsApp
        function submitToWhatsApp(event) {
            event.preventDefault();

            const name = document.getElementById('customer-name').value.trim();
            const modeKey = document.getElementById('order-mode').value;
            const address = document.getElementById('customer-address').value.trim();
            const startDateTime = document.getElementById('start-datetime').value;
            const notes = document.getElementById('notes').value.trim();

            if (!name) {
                showToast("Nama Belum Diisi", "Silakan masukkan nama pemesan terlebih dahulu.");
                return;
            }

            if (modeKey === 'delivery' && !address) {
                showToast("Alamat Wajib Diisi", "Untuk layanan Antar Jemput Rumah, mohon lengkapi alamat pengiriman.");
                return;
            }

            if (!startDateTime) {
                showToast("Waktu Belum Dipilih", "Silakan tentukan tanggal dan jam mulai sewa.");
                return;
            }

            const summary = calculateTotal();
            const formattedDate = formatDateTimeID(startDateTime);

            // Susun template pesan WhatsApp yang rapi
            let message = `Halo Admin *Rizz Store*! Saya ingin booking sewa PlayStation dengan detail berikut:\n\n`;
            message += `👤 *Nama Pemesan:* ${name}\n`;
            message += `🎮 *Tipe Konsol:* ${summary.consoleName}\n`;
            message += `📦 *Bentuk Layanan:* ${summary.modeName}\n`;
            if (modeKey === 'delivery') {
                message += `📍 *Alamat Antar:* ${address}\n`;
            }
            message += `⏱️ *Durasi Paket:* ${summary.packageName}\n`;
            message += `📺 *Tambahan TV 32":* ${summary.isAddonTv ? 'Ya (+Rp 25.000)' : 'Tidak'}\n`;
            message += `📅 *Jadwal Mulai:* ${formattedDate}\n`;
            message += `💳 *Pembayaran:* ${summary.paymentText}\n`;
            if (notes) {
                message += `📝 *Catatan/Game:* ${notes}\n`;
            }
            message += `\n💰 *Estimasi Total Biaya:* *${formatRupiah(summary.total)}*`;
            if (modeKey === 'delivery') {
                message += ` _(belum termasuk ongkir jika jarak > 3 km)_`;
            }
            message += `\n\nMohon info ketersediaan unit & nomor rekening/E-Wallet pembayarannya. Terima kasih!`;

            const encodedMessage = encodeURIComponent(message);
            const waUrl = `https://wa.me/${ADMIN_WA_NUMBER}?text=${encodedMessage}`;

            window.open(waUrl, '_blank', 'noopener,noreferrer');
        }

        // Inisialisasi Halaman saat Dimuat
        window.addEventListener('DOMContentLoaded', () => {
            // Set default datetime ke 1 jam dari sekarang
            const now = new Date();
            now.setHours(now.getHours() + 1);
            now.setMinutes(0);
            const localISOTime = new Date(now.getTime() - (now.getTimezoneOffset() * 60000)).toISOString().slice(0, 16);
            document.getElementById('start-datetime').value = localISOTime;

            // Render kartu harga awal & sinkronkan form
            switchPriceTab('onsite');
            updateFormLogic();
        });
    </script>
</body>
</html>
