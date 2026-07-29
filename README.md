<!DOCTYPE html>
<html lang="ms" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hari Mesra Warga @ UiTM Perlis 2.0 - 2026</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            purple: '#4a1b6e',
                            gold: '#f0c05a',
                            orange: '#e65100',
                            light: '#fdf8f5',
                            dark: '#2d0a47'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'], // Font for headings akin to the poster
                    },
                    backgroundImage: {
                        'hero-pattern': "linear-gradient(to bottom right, rgba(74, 27, 110, 0.9), rgba(230, 81, 0, 0.8))",
                    }
                }
            }
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Playfair+Display:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
    <style>
        /* Custom animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fade-in {
            animation: fadeIn 0.8s ease-out forwards;
        }
        .delay-100 { animation-delay: 100ms; }
        .delay-200 { animation-delay: 200ms; }
        .delay-300 { animation-delay: 300ms; }
        
        /* Glassmorphism effect */
        .glass {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-brand-light antialiased selection:bg-brand-gold selection:text-brand-purple">

    <nav class="fixed w-full z-50 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex-shrink-0 flex items-center">
                    <!-- Logo Placeholder based on poster -->
                    <div class="text-white font-serif font-bold text-xl md:text-2xl tracking-wider drop-shadow-md">
                        <span class="text-brand-gold">HMW</span> @ UiTM Perlis
                    </div>
                </div>
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-8">
                    <a href="#utama" class="text-white hover:text-brand-gold transition duration-300 font-semibold text-sm uppercase tracking-wide">Utama</a>
                    <a href="#objektif" class="text-white hover:text-brand-gold transition duration-300 font-semibold text-sm uppercase tracking-wide">Objektif</a>
                    <a href="#program" class="text-white hover:text-brand-gold transition duration-300 font-semibold text-sm uppercase tracking-wide">Program</a>
                    <a href="#sukan" class="text-white hover:text-brand-gold transition duration-300 font-semibold text-sm uppercase tracking-wide">Sukan</a>
                </div>
                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-white hover:text-brand-gold focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-brand-purple bg-opacity-95 backdrop-blur-md absolute w-full shadow-xl">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3 text-center">
                <a href="#utama" class="block px-3 py-3 text-white font-medium hover:bg-brand-dark rounded-md">Utama</a>
                <a href="#objektif" class="block px-3 py-3 text-white font-medium hover:bg-brand-dark rounded-md">Objektif</a>
                <a href="#program" class="block px-3 py-3 text-white font-medium hover:bg-brand-dark rounded-md">Program</a>
                <a href="#sukan" class="block px-3 py-3 text-white font-medium hover:bg-brand-dark rounded-md">Sukan</a>
            </div>
        </div>
    </nav>

    <section id="utama" class="relative bg-hero-pattern bg-cover bg-center min-h-screen flex items-center justify-center overflow-hidden">
        <!-- Abstract background elements to mimic poster -->
        <div class="absolute top-0 left-0 w-full h-full overflow-hidden z-0">
            <div class="absolute -top-[20%] -left-[10%] w-[50%] h-[50%] rounded-full bg-brand-gold opacity-20 blur-3xl mix-blend-screen"></div>
            <div class="absolute bottom-[10%] -right-[10%] w-[60%] h-[60%] rounded-full bg-brand-orange opacity-30 blur-3xl mix-blend-screen"></div>
        </div>

        <div class="relative z-10 text-center px-4 max-w-5xl mx-auto mt-20">
            <div class="mb-6 opacity-0 animate-fade-in">
                <img src="https://perlis.uitm.edu.my/v3/images/Logo-UiTM-Perlis.png" alt="Logo UiTM Perlis" class="h-24 md:h-32 mx-auto drop-shadow-lg bg-white/10 p-2 rounded-xl backdrop-blur-sm" onerror="this.src='https://placehold.co/300x100/4a1b6e/ffffff?text=UiTM+Perlis'">
            </div>
            <h1 class="font-serif text-5xl md:text-7xl lg:text-8xl font-bold text-brand-gold mb-4 leading-tight opacity-0 animate-fade-in delay-100 drop-shadow-xl" style="text-shadow: 2px 2px 4px rgba(0,0,0,0.5);">
                Hari Mesra<br><span class="text-white">Warga</span> 2.0
            </h1>
            <p class="text-xl md:text-3xl text-white mb-2 font-light tracking-wide opacity-0 animate-fade-in delay-200">@ UiTM Cawangan Perlis, Kampus Arau</p>
            
            <div class="mt-8 mb-12 inline-block bg-gradient-to-r from-brand-orange to-red-600 text-white px-8 py-3 rounded-full text-lg md:text-xl font-bold italic shadow-[0_0_15px_rgba(230,81,0,0.6)] opacity-0 animate-fade-in delay-300">
                "Warga Harmoni, Kampus Bestari"
            </div>
            
            <div class="flex flex-col md:flex-row justify-center gap-4 mt-8 opacity-0 animate-fade-in delay-300">
                <a href="#program" class="bg-brand-gold hover:bg-yellow-400 text-brand-dark font-bold py-3 px-8 rounded-full shadow-lg transform transition hover:-translate-y-1 hover:shadow-xl">
                    Jadual Program
                </a>
                <a href="#sukan" class="bg-transparent border-2 border-white hover:bg-white hover:text-brand-purple text-white font-bold py-3 px-8 rounded-full shadow-lg transform transition hover:-translate-y-1 hover:shadow-xl">
                    Senarai Sukan
                </a>
            </div>
        </div>
        
        <!-- Wave transition to next section -->
        <div class="absolute bottom-0 w-full overflow-hidden leading-none">
            <svg class="relative block w-full h-12 md:h-24" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V120H0V95.8C59.71,118,130.98,130.12,201.3,127.5,263.6,125,321.4,111.4,379.4,98.6c43.6-9.6,87-19.4,131.2-27.1,43.2-7.5,87.1-13.6,131-18.7z" fill="#fdf8f5"></path>
            </svg>
        </div>
    </section>

    <section id="objektif" class="py-20 bg-brand-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-brand-purple mb-4 font-serif">Selamat Datang ke HMW 2.0</h2>
                <div class="w-24 h-1 bg-brand-gold mx-auto rounded-full"></div>
                <p class="mt-6 text-gray-600 max-w-2xl mx-auto text-lg">
                    Assalamualaikum dan salam sejahtera. Dengan sukacitanya dimaklumkan bahawa Hari Mesra Warga, UiTM Cawangan Perlis kembali untuk edisi 2.0 bagi tahun 2026.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Objektif 1 -->
                <div class="bg-white rounded-2xl p-8 shadow-xl hover:shadow-2xl transition-shadow duration-300 border-t-4 border-brand-purple flex flex-col items-center text-center group">
                    <div class="w-16 h-16 bg-brand-purple/10 rounded-full flex items-center justify-center text-brand-purple text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">Mengeratkan Silaturahim</h3>
                    <p class="text-gray-600">Mengukuhkan hubungan antara staf akademik dan pentadbiran UiTM Cawangan Perlis.</p>
                </div>
                
                <!-- Objektif 2 -->
                <div class="bg-white rounded-2xl p-8 shadow-xl hover:shadow-2xl transition-shadow duration-300 border-t-4 border-brand-gold flex flex-col items-center text-center group">
                    <div class="w-16 h-16 bg-brand-gold/20 rounded-full flex items-center justify-center text-brand-orange text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fas fa-running"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">Gaya Hidup Sihat</h3>
                    <p class="text-gray-600">Memupuk semangat berpasukan dan menggalakkan gaya hidup aktif serta sihat di kalangan warga.</p>
                </div>

                <!-- Objektif 3 -->
                <div class="bg-white rounded-2xl p-8 shadow-xl hover:shadow-2xl transition-shadow duration-300 border-t-4 border-brand-orange flex flex-col items-center text-center group">
                    <div class="w-16 h-16 bg-brand-orange/10 rounded-full flex items-center justify-center text-brand-orange text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fas fa-heart"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">Suasana Kerja Harmoni</h3>
                    <p class="text-gray-600">Mewujudkan persekitaran dan suasana kerja yang harmoni, positif serta produktif.</p>
                </div>
            </div>
            
            <div class="mt-12 text-center bg-blue-50 rounded-xl p-6 border border-blue-100 shadow-sm max-w-3xl mx-auto">
                <p class="text-brand-dark font-medium">
                    <i class="fas fa-bullhorn text-red-500 mr-2"></i> Semua staf perlu mengambil bahagian. Ayuh, semarakkan semangat rumah masing-masing!
                </p>
                <a href="#" class="inline-block mt-4 text-blue-600 hover:text-blue-800 font-semibold underline decoration-2 underline-offset-4">
                    <i class="fas fa-external-link-alt mr-1 text-sm"></i> Semak Agihan Staf Mengikut Rumah
                </a>
            </div>
        </div>
    </section>

    <section id="program" class="py-20 bg-brand-purple text-white relative overflow-hidden">
        <!-- Decorative background elements -->
        <div class="absolute top-0 right-0 w-64 h-64 bg-brand-gold opacity-10 rounded-full blur-3xl -mr-20 -mt-20"></div>
        <div class="absolute bottom-0 left-0 w-80 h-80 bg-brand-orange opacity-20 rounded-full blur-3xl -ml-20 -mb-20"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <span class="bg-brand-gold text-brand-dark px-4 py-1 rounded-full text-sm font-bold uppercase tracking-wider mb-4 inline-block shadow-md">Acara Kemuncak</span>
                <h2 class="text-3xl md:text-4xl font-bold font-serif mb-4 text-white">Hari Kemuncak HMW 2.0</h2>
                <div class="w-24 h-1 bg-brand-gold mx-auto rounded-full mb-6"></div>
                <div class="flex flex-col md:flex-row justify-center items-center gap-4 text-lg">
                    <div class="flex items-center gap-2"><i class="far fa-calendar-alt text-brand-gold"></i> Khamis, 8 Oktober 2026</div>
                    <div class="hidden md:block text-brand-gold">•</div>
                    <div class="flex items-center gap-2"><i class="far fa-clock text-brand-gold"></i> 6.00 Pagi - Selesai</div>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <!-- Timeline Acara -->
                <div class="space-y-8">
                    <h3 class="text-2xl font-bold text-brand-gold mb-6 border-b border-brand-gold/30 pb-2">Aturcara Majlis</h3>
                    
                    <div class="relative pl-8 border-l-2 border-brand-gold/50 space-y-8">
                        <div class="relative">
                            <div class="absolute -left-[41px] bg-brand-dark border-2 border-brand-gold w-5 h-5 rounded-full mt-1"></div>
                            <div class="bg-white/10 backdrop-blur-sm p-5 rounded-xl border border-white/10 hover:bg-white/20 transition-colors">
                                <span class="text-brand-gold font-bold block mb-1">6.00 Pagi</span>
                                <h4 class="text-xl font-semibold mb-2">Solat Subuh Berjemaah</h4>
                                <p class="text-gray-300 text-sm"><i class="fas fa-map-marker-alt text-brand-orange mr-2"></i> Masjid An-Nur, UiTM Perlis</p>
                                <p class="text-sm mt-2 text-gray-300 italic">"Subuh Macam Jumaat"</p>
                            </div>
                        </div>
                        
                        <div class="relative">
                            <div class="absolute -left-[41px] bg-brand-dark border-2 border-brand-gold w-5 h-5 rounded-full mt-1"></div>
                            <div class="bg-white/10 backdrop-blur-sm p-5 rounded-xl border border-white/10 hover:bg-white/20 transition-colors">
                                <span class="text-brand-gold font-bold block mb-1">7.00 Pagi</span>
                                <h4 class="text-xl font-semibold mb-2">Senamrobik Perdana</h4>
                                <p class="text-gray-300 text-sm"><i class="fas fa-map-marker-alt text-brand-orange mr-2"></i> Padang Kawad</p>
                            </div>
                        </div>

                        <div class="relative">
                            <div class="absolute -left-[41px] bg-brand-dark border-2 border-brand-gold w-5 h-5 rounded-full mt-1"></div>
                            <div class="bg-white/10 backdrop-blur-sm p-5 rounded-xl border border-white/20 ring-1 ring-brand-gold shadow-[0_0_15px_rgba(240,192,90,0.2)]">
                                <span class="text-brand-gold font-bold block mb-1">8.30 Pagi</span>
                                <h4 class="text-xl font-semibold mb-2">Sukaneka Final</h4>
                                <p class="text-gray-300 text-sm"><i class="fas fa-map-marker-alt text-brand-orange mr-2"></i> Stadium Hoki, UiTM Perlis</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Sukaneka List -->
                <div>
                    <h3 class="text-2xl font-bold text-brand-gold mb-6 border-b border-brand-gold/30 pb-2">7 Acara Sukaneka Final</h3>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="bg-white text-brand-dark p-4 rounded-xl shadow-lg border-l-4 border-brand-orange flex items-center gap-4 hover:-translate-y-1 transition-transform">
                            <div class="bg-brand-orange/10 p-3 rounded-lg text-brand-orange"><i class="fas fa-bowling-ball fa-fw text-xl"></i></div>
                            <span class="font-bold">1. Boling Kepala</span>
                        </div>
                        <div class="bg-white text-brand-dark p-4 rounded-xl shadow-lg border-l-4 border-brand-purple flex items-center gap-4 hover:-translate-y-1 transition-transform">
                            <div class="bg-brand-purple/10 p-3 rounded-lg text-brand-purple"><i class="fas fa-hands-holding-circle fa-fw text-xl"></i></div>
                            <div>
                                <span class="font-bold block">2. Sambutlah Kasih</span>
                                <span class="text-xs text-gray-500">(Belon + Kain Batik)</span>
                            </div>
                        </div>
                        <div class="bg-white text-brand-dark p-4 rounded-xl shadow-lg border-l-4 border-brand-gold flex items-center gap-4 hover:-translate-y-1 transition-transform">
                            <div class="bg-brand-gold/20 p-3 rounded-lg text-brand-orange"><i class="fas fa-candy-cane fa-fw text-xl"></i></div>
                            <span class="font-bold">3. Gula Dalam Tepung</span>
                        </div>
                        <div class="bg-white text-brand-dark p-4 rounded-xl shadow-lg border-l-4 border-brand-orange flex items-center gap-4 hover:-translate-y-1 transition-transform">
                            <div class="bg-brand-orange/10 p-3 rounded-lg text-brand-orange"><i class="fas fa-comment-slash fa-fw text-xl"></i></div>
                            <div>
                                <span class="font-bold block">4. Guess It Right</span>
                                <span class="text-xs text-gray-500">(Peneka & Klu Bisu)</span>
                            </div>
                        </div>
                        <div class="bg-white text-brand-dark p-4 rounded-xl shadow-lg border-l-4 border-brand-purple flex items-center gap-4 hover:-translate-y-1 transition-transform">
                            <div class="bg-brand-purple/10 p-3 rounded-lg text-brand-purple"><i class="fas fa-coffee fa-fw text-xl"></i></div>
                            <span class="font-bold">5. Teka Warna Cup</span>
                        </div>
                        <div class="bg-white text-brand-dark p-4 rounded-xl shadow-lg border-l-4 border-brand-gold flex items-center gap-4 hover:-translate-y-1 transition-transform">
                            <div class="bg-brand-gold/20 p-3 rounded-lg text-brand-orange"><i class="fas fa-puzzle-piece fa-fw text-xl"></i></div>
                            <span class="font-bold">6. Puzzle</span>
                        </div>
                        <div class="bg-white text-brand-dark p-4 rounded-xl shadow-lg border-l-4 border-brand-orange flex items-center gap-4 sm:col-span-2 hover:-translate-y-1 transition-transform">
                            <div class="bg-brand-orange/10 p-3 rounded-lg text-brand-orange"><i class="fas fa-campground fa-fw text-xl"></i></div>
                            <span class="font-bold">7. Hiasan Khemah</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Bottom divider -->
        <div class="absolute bottom-0 w-full overflow-hidden leading-none rotate-180">
            <svg class="relative block w-full h-12" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V120H0V95.8C59.71,118,130.98,130.12,201.3,127.5,263.6,125,321.4,111.4,379.4,98.6c43.6-9.6,87-19.4,131.2-27.1,43.2-7.5,87.1-13.6,131-18.7z" fill="#f8fafc"></path>
            </svg>
        </div>
    </section>

    <section id="sukan" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="bg-brand-purple text-white px-4 py-1 rounded-full text-sm font-bold uppercase tracking-wider mb-4 inline-block shadow-md">Acara Bulanan</span>
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4 font-serif">Program Sukan (September 2026)</h2>
                <div class="w-24 h-1 bg-brand-purple mx-auto rounded-full mb-6"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">Acara sukan akan berlangsung sepanjang bulan September menjelang hari kemuncak. Senarai permainan dan jumlah pendaftaran adalah seperti di bawah.</p>
            </div>

            <!-- Jadual Sukan Responsive -->
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden border border-gray-100">
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse">
                        <thead>
                            <tr class="bg-brand-purple text-white text-sm uppercase tracking-wider">
                                <th class="p-4 font-semibold text-center border-b border-brand-dark/20 w-16">Bil</th>
                                <th class="p-4 font-semibold border-b border-brand-dark/20">Permainan</th>
                                <th class="p-4 font-semibold text-center border-b border-brand-dark/20 bg-brand-dark/20" colspan="3">Pendaftaran Pemain</th>
                                <th class="p-4 font-semibold border-b border-brand-dark/20">Catatan</th>
                            </tr>
                            <tr class="bg-brand-purple/90 text-white/90 text-xs text-center border-b-2 border-brand-gold">
                                <th></th>
                                <th></th>
                                <th class="p-2 border-l border-white/20">Lelaki</th>
                                <th class="p-2 border-l border-white/20">L. Veteran</th>
                                <th class="p-2 border-l border-white/20">Wanita</th>
                                <th></th>
                            </tr>
                        </thead>
                        <tbody class="text-gray-700">
                            <tr class="hover:bg-brand-light/50 border-b border-gray-100 transition-colors">
                                <td class="p-4 text-center font-medium">1</td>
                                <td class="p-4 font-bold text-brand-purple">Badminton Berpasukan</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-sm"><span class="bg-gray-100 px-2 py-1 rounded">DL, DLV, DW</span></td>
                            </tr>
                            <tr class="hover:bg-brand-light/50 border-b border-gray-100 transition-colors bg-gray-50/50">
                                <td class="p-4 text-center font-medium">2</td>
                                <td class="p-4 font-bold text-brand-purple">Bola Tampar Campuran</td>
                                <td class="p-4 text-center" colspan="2">8</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-sm text-gray-600">4 L & 2 W dalam permainan</td>
                            </tr>
                            <tr class="hover:bg-brand-light/50 border-b border-gray-100 transition-colors">
                                <td class="p-4 text-center font-medium">3</td>
                                <td class="p-4 font-bold text-brand-purple">Woodball</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-sm"><span class="bg-gray-100 px-2 py-1 rounded">DL, DLV, DW</span></td>
                            </tr>
                            <tr class="hover:bg-brand-light/50 border-b border-gray-100 transition-colors bg-gray-50/50">
                                <td class="p-4 text-center font-medium">4</td>
                                <td class="p-4 font-bold text-brand-purple">Sepak Takraw Regu</td>
                                <td class="p-4 text-center">6</td>
                                <td class="p-4 text-center bg-gray-200"></td>
                                <td class="p-4 text-center bg-gray-800 text-white text-xs">TIADA</td>
                                <td class="p-4 text-sm"></td>
                            </tr>
                            <tr class="hover:bg-brand-light/50 border-b border-gray-100 transition-colors">
                                <td class="p-4 text-center font-medium">5</td>
                                <td class="p-4 font-bold text-brand-purple">Dart Berpasukan</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-sm"><span class="bg-gray-100 px-2 py-1 rounded">DL, DLV, DW</span></td>
                            </tr>
                            <tr class="hover:bg-brand-light/50 border-b border-gray-100 transition-colors bg-gray-50/50">
                                <td class="p-4 text-center font-medium">6</td>
                                <td class="p-4 font-bold text-brand-purple">Karom Berpasukan</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-center">4</td>
                                <td class="p-4 text-sm"><span class="bg-gray-100 px-2 py-1 rounded">DL, DLV, DW</span></td>
                            </tr>
                            <tr class="hover:bg-brand-light/50 transition-colors">
                                <td class="p-4 text-center font-medium">7</td>
                                <td class="p-4 font-bold text-brand-purple">Tenpin Boling Campuran</td>
                                <td class="p-4 text-center">2</td>
                                <td class="p-4 text-center bg-gray-200"></td>
                                <td class="p-4 text-center">2</td>
                                <td class="p-4 text-sm text-gray-600">Berpasukan 4 orang</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="bg-gray-50 p-4 border-t border-gray-100 text-sm text-gray-500">
                    <strong>Petunjuk:</strong> DL - Double Lelaki | DLV - Double Lelaki Veteran (Atas 40 Tahun) | DW - Double Wanita
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-brand-dark text-white pt-16 pb-8 border-t-[6px] border-brand-gold">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-12">
                <div class="col-span-1 md:col-span-1">
                    <div class="text-2xl font-serif font-bold text-brand-gold mb-4">HMW @ UiTM Perlis</div>
                    <p class="text-gray-400 text-sm mb-4">
                        Platform maklumat rasmi untuk program Hari Mesra Warga (HMW) 2.0 bagi staf Universiti Teknologi MARA Cawangan Perlis Kampus Arau.
                    </p>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4 border-b border-gray-700 pb-2 inline-block">Pautan Pantas</h4>
                    <ul class="space-y-2 text-gray-400 text-sm">
                        <li><a href="#utama" class="hover:text-brand-gold transition-colors">Halaman Utama</a></li>
                        <li><a href="#objektif" class="hover:text-brand-gold transition-colors">Objektif Program</a></li>
                        <li><a href="#program" class="hover:text-brand-gold transition-colors">Jadual Hari Kemuncak</a></li>
                        <li><a href="#sukan" class="hover:text-brand-gold transition-colors">Senarai Sukan</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4 border-b border-gray-700 pb-2 inline-block">Hubungi Urusetia</h4>
                    <ul class="space-y-3 text-gray-400 text-sm">
                        <li class="flex items-start gap-3">
                            <i class="fas fa-map-marker-alt mt-1 text-brand-gold"></i>
                            <span>Kompleks Sukan Tuanku Syed Faizuddin Putra,<br>UiTM Cawangan Perlis</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center gap-4">
                <p class="text-gray-500 text-sm text-center md:text-left">
                    &copy; 2026 Hari Mesra Warga UiTM Cawangan Perlis. Direka untuk tujuan demonstrasi.
                </p>
                <div class="flex space-x-4">
                    <a href="#" class="text-gray-500 hover:text-white transition-colors"><i class="fab fa-facebook text-xl"></i></a>
                    <a href="#" class="text-gray-500 hover:text-white transition-colors"><i class="fab fa-instagram text-xl"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Navbar scroll effect
            const navbar = document.getElementById('navbar');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 20) {
                    navbar.classList.add('bg-brand-purple', 'shadow-lg', 'bg-opacity-95', 'backdrop-blur-md');
                    navbar.classList.remove('bg-transparent');
                } else {
                    navbar.classList.add('bg-transparent');
                    navbar.classList.remove('bg-brand-purple', 'shadow-lg', 'bg-opacity-95', 'backdrop-blur-md');
                }
            });

            // Mobile menu toggle
            const btn = document.getElementById('mobile-menu-btn');
            const menu = document.getElementById('mobile-menu');

            btn.addEventListener('click', () => {
                menu.classList.toggle('hidden');
            });

            // Close mobile menu when clicking a link
            const mobileLinks = menu.querySelectorAll('a');
            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                    menu.classList.add('hidden');
                });
            });

            // Trigger initial scroll check for navbar
            window.dispatchEvent(new Event('scroll'));
        });
    </script>
</body>
</html>
