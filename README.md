<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Advokasi SEMA-F Psikologi UIN Malang</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            purple: {
                                50: '#f5f3ff',
                                100: '#ede9fe',
                                600: '#7c3aed', // Warna Utama
                                700: '#6d28d9',
                                800: '#5b21b6',
                                900: '#4c1d95',
                            },
                            silver: {
                                100: '#f3f4f6', // Latar belakang abu muda
                                200: '#e5e7eb', // Silver border/aksen
                                300: '#d1d5db',
                                600: '#4b5563', // Teks sekunder
                            }
                        }
                    }
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
        .hero-gradient { background: linear-gradient(135deg, #7c3aed 0%, #4c1d95 100%); }
    </style>
</head>
<body class="bg-brand-silver-100 text-gray-800">

    <nav class="bg-white/95 backdrop-blur-md sticky top-0 z-50 shadow-sm border-b border-brand-silver-200">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 bg-brand-purple-600 rounded-lg flex items-center justify-center text-white font-bold text-xl shadow-md">Ψ</div>
                <span class="font-bold text-brand-purple-900 tracking-tight text-lg">SEMA-F PSIKOLOGI</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#profil" class="text-brand-silver-600 hover:text-brand-purple-600 transition">Profil</a>
                <a href="#aspirasi" class="text-brand-silver-600 hover:text-brand-purple-600 transition">Aspirasi</a>
                <a href="#kontak" class="text-brand-silver-600 hover:text-brand-purple-600 transition">Kontak</a>
            </div>
            <div class="md:hidden text-brand-purple-600">
                <i class="fas fa-bars text-2xl"></i>
            </div>
        </div>
    </nav>

    <header class="hero-gradient text-white py-24 px-6 relative overflow-hidden">
        <div class="absolute inset-0 opacity-10">
            <svg width="100%" height="100%"><defs><pattern id="dots" width="20" height="20" patternUnits="userSpaceOnUse"><circle cx="2" cy="2" r="1" fill="#e5e7eb"/></pattern></defs><rect width="100%" height="100%" fill="url(#dots)"/></svg>
        </div>
        
        <div class="container mx-auto text-center relative z-10">
            <span class="inline-block bg-white/20 text-brand-silver-100 px-4 py-1 rounded-full text-sm font-medium mb-4 backdrop-blur-sm">Bidang Advokasi & Pelayanan Mahasiswa</span>
            <h1 class="text-4xl md:text-5xl font-extrabold mb-6 leading-tight tracking-tight">Suara Anda, <span class="text-brand-silver-200">Perjuangan Kami.</span></h1>
            <p class="text-lg text-brand-purple-100 max-w-2xl mx-auto mb-10 opacity-90">Wadah resmi SEMA-F Psikologi UIN Malang untuk menampung aspirasi, keluhan, dan memberikan bantuan advokasi bagi seluruh mahasiswa.</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#aspirasi" class="bg-white text-brand-purple-700 px-8 py-3 rounded-xl font-bold shadow-lg hover:bg-brand-silver-100 transition-all hover:-translate-y-0.5">Sampaikan Aspirasi</a>
                <a href="#profil" class="bg-transparent border border-brand-silver-300 text-brand-silver-100 px-8 py-3 rounded-xl font-bold hover:bg-white/10 transition">Pelajari SEMA-F</a>
            </div>
        </div>
    </header>

    <section id="profil" class="py-20 container mx-auto px-6">
        <div class="grid md:grid-cols-3 gap-12 items-center">
            <div class="md:col-span-2 bg-white rounded-3xl p-10 shadow-xl shadow-brand-purple-100/50 border border-brand-purple-100">
                <h2 class="text-3xl font-bold text-brand-purple-900 mb-6 flex items-center">
                    <span class="w-2 h-8 bg-brand-purple-600 rounded-full mr-3"></span>
                    Tentang SEMA-F Psikologi
                </h2>
                <p class="text-brand-silver-600 leading-relaxed text-lg mb-6">
                    Senat Mahasiswa Fakultas (SEMA-F) Psikologi UIN Maulana Malik Ibrahim Malang merupakan organisasi perwakilan mahasiswa di tingkat fakultas yang berperan sebagai mitra kerja Dewan Eksekutif Mahasiswa Fakultas (DEMA-F).
                </p>
                <div class="grid grid-cols-3 gap-4 text-center">
                    <div class="bg-brand-purple-50 p-4 rounded-xl border border-brand-purple-100">
                        <div class="text-3xl font-bold text-brand-purple-600">01</div>
                        <div class="text-sm font-semibold text-brand-purple-900">Legislasi</div>
                    </div>
                    <div class="bg-brand-purple-50 p-4 rounded-xl border border-brand-purple-100">
                        <div class="text-3xl font-bold text-brand-purple-600">02</div>
                        <div class="text-sm font-semibold text-brand-purple-900">Penganggaran</div>
                    </div>
                    <div class="bg-brand-purple-50 p-4 rounded-xl border border-brand-purple-100">
                        <div class="text-3xl font-bold text-brand-purple-600">03</div>
                        <div class="text-sm font-semibold text-brand-purple-900">Pengawasan</div>
                    </div>
                </div>
            </div>
            <div class="bg-brand-purple-900 p-8 rounded-3xl text-brand-silver-100 shadow-xl shadow-brand-purple-900/20 flex flex-col items-center text-center">
                <i class="fas fa-gavel text-5xl text-brand-purple-100 mb-5"></i>
                <h3 class="text-xl font-bold mb-2">Fungsi Advokasi</h3>
                <p class="text-sm text-brand-purple-200 opacity-80">Mendampingi dan memperjuangkan hak-hak mahasiswa dalam bidang akademik maupun sarana prasarana.</p>
            </div>
        </div>
    </section>

    <section id="aspirasi" class="py-16 bg-white border-y border-brand-silver-200">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-extrabold text-brand-purple-900">Pusat Layanan Mahasiswa</h2>
                <p class="text-brand-silver-600 mt-4 max-w-xl mx-auto">Pilih metode yang paling nyaman bagi Anda untuk menyampaikan aspirasi atau membutuhkan bantuan.</p>
            </div>
            <div class="grid md:grid-cols-2 gap-10">
                <div class="bg-brand-silver-100 p-9 rounded-2xl border border-brand-silver-200 hover:border-brand-purple-300 hover:bg-white hover:shadow-2xl transition-all duration-300 group">
                    <div class="w-16 h-16 bg-brand-purple-100 rounded-2xl flex items-center justify-center mb-8 shadow-inner border border-brand-purple-200 transition-colors group-hover:bg-brand-purple-600">
                        <i class="fas fa-file-alt text-brand-purple-600 text-3xl transition-colors group-hover:text-white"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-brand-purple-900">E-Aspirasi Form</h3>
                    <p class="text-brand-silver-600 mb-8 leading-relaxed">Formulir resmi untuk mendata laporan Anda secara terstruktur. Cocok untuk keluhan fasilitas, akademik, atau saran kebijakan. Anda bisa memilih untuk anonim.</p>
                    <a href="LINK_GOOGLE_FORM_DISINI" target="_blank" class="inline-flex items-center justify-center w-full bg-brand-purple-600 text-white py-3 rounded-xl font-bold hover:bg-brand-purple-800 transition">
                        Isi Formulir Melalui Google Form <i class="fas fa-external-link-alt ml-2 text-sm opacity-70"></i>
                    </a>
                </div>

                <div class="bg-brand-silver-100 p-9 rounded-2xl border border-brand-silver-200 hover:border-brand-purple-300 hover:bg-white hover:shadow-2xl transition-all duration-300 group">
                    <div class="w-16 h-16 bg-green-100 rounded-2xl flex items-center justify-center mb-8 shadow-inner border border-green-200 transition-colors group-hover:bg-green-600">
                        <i class="fab fa-whatsapp text-green-600 text-3xl transition-colors group-hover:text-white"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-brand-purple-900">Hotline WhatsApp</h3>
                    <p class="text-brand-silver-600 mb-8 leading-relaxed">Butuh bantuan mendesak, konsultasi privat, atau respon cepat? Hubungi tim advokasi kami secara langsung melalui WhatsApp.</p>
                    <div class="flex flex-col gap-4">
                        <a href="https://wa.me/6282245224689" target="_blank" class="flex items-center justify-between bg-white border border-brand-silver-200 px-5 py-3 rounded-xl font-medium text-brand-purple-900 hover:border-brand-purple-200 hover:bg-brand-purple-50 transition">
                            <span><i class="fas fa-user-circle mr-2 text-brand-purple-500"></i>Adyb (Advokasi)</span>
                            <span class="text-sm text-brand-silver-600">+62 822-4522-4689 <i class="fab fa-whatsapp ml-1 text-green-500"></i></span>
                        </a>
                        <a href="https://wa.me/6285749846139" target="_blank" class="flex items-center justify-between bg-white border border-brand-silver-200 px-5 py-3 rounded-xl font-medium text-brand-purple-900 hover:border-brand-purple-200 hover:bg-brand-purple-50 transition">
                            <span><i class="fas fa-user-circle mr-2 text-brand-purple-500"></i>Neysa (Advokasi)</span>
                            <span class="text-sm text-brand-silver-600">+62 857-4984-6139 <i class="fab fa-whatsapp ml-1 text-green-500"></i></span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer id="kontak" class="bg-brand-purple-900 text-brand-silver-100 pt-20 pb-10 relative overflow-hidden">
        <div class="absolute inset-0 opacity-5">
            <svg width="100%" height="100%"><defs><pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="#e5e7eb" stroke-width="1"/></pattern></defs><rect width="100%" height="100%" fill="url(#grid)"/></svg>
        </div>

        <div class="container mx-auto px-6 text-center relative z-10">
            <h2 class="text-2xl font-bold mb-3 tracking-tight">SEMA-F Psikologi UIN Malang</h2>
            <p class="text-brand-purple-200 mb-8 max-w-md mx-auto opacity-80">Gedung Student Center Lt. 1, Fakultas Psikologi, UIN Maulana Malik Ibrahim Malang.</p>
            
            <div class="flex justify-center space-x-6 mb-12">
                <a href="https://www.instagram.com/semafpsikologi_uinmalang/" target="_blank" class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center text-brand-silver-200 hover:bg-white hover:text-brand-purple-900 text-2xl transition-all"><i class="fab fa-instagram"></i></a>
                <a href="https://www.tiktok.com/@semafpsikologiuinma" target="_blank" class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center text-brand-silver-200 hover:bg-white hover:text-brand-purple-900 text-2xl transition-all"><i class="fab fa-tiktok"></i></a>
                <a href="https://www.linkedin.com/company/senat-mahasiswa-fakultas-psikologi-uin-malang/" target="_blank" class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center text-brand-silver-200 hover:bg-white hover:text-brand-purple-900 text-2xl transition-all"><i class="fab fa-linkedin"></i></a>
            </div>
            <div class="border-t border-brand-purple-800 pt-8 mt-8">
                <p class="text-brand-purple-300 text-sm opacity-70">© 2024 SEMA-F Psikologi UIN Malang. All Rights Reserved.</p>
                <p class="text-brand-purple-400 text-xs mt-2 italic">#AdvokasiHumanis #PsikologiSatu</p>
            </div>
        </div>
    </footer>

</body>
</html>
