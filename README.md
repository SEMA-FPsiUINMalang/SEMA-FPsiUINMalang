<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sema-F Psikologi | Advokasi Center</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            purple: '#7c3aed',
                            purpleDark: '#5b21b6',
                            purpleLight: '#f5f3ff',
                            silver: '#e2e8f0', // Silver metalik lembut
                            silverDark: '#94a3b8',
                            bgBody: '#f8fafc'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
        
        /* Efek Interaktif Professional */
        .card-interactive {
            transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1);
            border: 1px solid transparent;
        }
        .card-interactive:hover {
            transform: translateY(-8px);
            background: white;
            border-color: #7c3aed;
            box-shadow: 0 20px 30px -10px rgba(124, 58, 237, 0.15);
        }

        .social-icon {
            transition: all 0.3s ease;
            background: #f1f5f9;
        }
        .social-icon:hover {
            background: #7c3aed;
            color: white;
            transform: scale(1.1);
        }

        .nav-item {
            position: relative;
            transition: color 0.3s ease;
        }
        .nav-item::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -5px;
            left: 0;
            background: #7c3aed;
            transition: width 0.3s ease;
        }
        .nav-item:hover::after {
            width: 100%;
        }
    </style>
</head>
<body class="bg-brand-bgBody text-slate-800 font-sans">

    <nav class="bg-white/90 backdrop-blur-md sticky top-0 z-50 border-b border-brand-silver/50 py-4">
        <div class="container mx-auto px-6 flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <img src="LOGO SEMA.png" alt="LOGO SEMA.png" class="h-10 w-auto hover:brightness-110 transition-all">
                <div class="border-l-2 border-brand-silver pl-4">
                    <h1 class="font-bold text-slate-900 leading-none text-sm md:text-base">SEMA-F PSIKOLOGI</h1>
                    <p class="text-[9px] text-brand-purple font-bold uppercase tracking-[0.2em]">Advokasi Center</p>
                </div>
            </div>
            
            <div class="hidden md:flex space-x-8 text-[11px] font-bold text-brand-silverDark uppercase tracking-widest">
                <a href="#home" class="nav-item hover:text-brand-purple">Beranda</a>
                <a href="#aspirasi" class="nav-item hover:text-brand-purple">Aspirasi</a>
                <a href="#kontak" class="nav-item hover:text-brand-purple">Kontak</a>
            </div>
        </div>
    </nav>

    <header id="home" class="bg-white py-24 border-b border-brand-silver/30">
        <div class="container mx-auto px-6 text-center">
            <div class="inline-flex items-center space-x-2 bg-brand-purpleLight px-4 py-1.5 rounded-full mb-8 border border-brand-purple/10">
                <span class="w-2 h-2 bg-brand-purple rounded-full animate-pulse"></span>
                <span class="text-[10px] font-black text-brand-purple uppercase tracking-widest text-sm">Psikologi UIN Malang</span>
            </div>
            <h2 class="text-4xl md:text-6xl font-black text-slate-900 mb-6 leading-tight">
                Suara Mahasiswa, <br><span class="text-brand-purple">Prioritas Kami.</span>
            </h2>
            <p class="text-brand-silverDark max-w-2xl mx-auto mb-10 text-lg">
                Wadah aspirasi dan pelayanan advokasi yang transparan bagi seluruh mahasiswa Fakultas Psikologi UIN Maulana Malik Ibrahim Malang.
            </p>
            <div class="flex justify-center">
                <a href="#aspirasi" class="bg-brand-purple text-white px-10 py-4 rounded-2xl font-bold shadow-xl shadow-brand-purple/20 hover:bg-brand-purpleDark hover:-translate-y-1 transition-all duration-300 tracking-wide">
                    Sampaikan Aspirasi
                </a>
            </div>
        </div>
    </header>

    <section id="aspirasi" class="py-24 container mx-auto px-6">
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <div class="card-interactive bg-white/50 p-10 rounded-[2.5rem] flex flex-col">
                <div class="w-14 h-14 bg-brand-purpleLight rounded-2xl flex items-center justify-center mb-8 border border-brand-purple/10">
                    <i class="fas fa-file-alt text-brand-purple text-xl"></i>
                </div>
                <h3 class="text-xl font-bold text-slate-900 mb-4">E-Aspirasi Form</h3>
                <p class="text-brand-silverDark text-sm leading-relaxed mb-8 italic">"Sampaikan keluhan atau saran terkait fasilitas dan akademik secara resmi."</p>
                <a href="LINK_GOOGLE_FORM_MU" class="mt-auto inline-flex items-center font-bold text-brand-purple group">
                    Buka Formulir <i class="fas fa-arrow-right ml-2 group-hover:ml-4 transition-all"></i>
                </a>
            </div>

            <div class="card-interactive bg-white/50 p-10 rounded-[2.5rem] flex flex-col">
                <div class="w-14 h-14 bg-green-50 rounded-2xl flex items-center justify-center mb-8 border border-green-100">
                    <i class="fab fa-whatsapp text-green-600 text-xl"></i>
                </div>
                <h3 class="text-xl font-bold text-slate-900 mb-4">Adyb (Advokasi)</h3>
                <p class="text-brand-silverDark text-sm leading-relaxed mb-8 italic">"Hubungi kami untuk respon cepat dan bantuan pendampingan mendesak."</p>
                <a href="https://wa.me/6282245224689" class="mt-auto block text-center bg-slate-900 text-white py-4 rounded-2xl font-bold text-sm hover:bg-brand-purple transition-colors">
                    Hubungi Via WhatsApp
                </a>
            </div>

            <div class="card-interactive bg-white/50 p-10 rounded-[2.5rem] flex flex-col">
                <div class="w-14 h-14 bg-green-50 rounded-2xl flex items-center justify-center mb-8 border border-green-100">
                    <i class="fab fa-whatsapp text-green-600 text-xl"></i>
                </div>
                <h3 class="text-xl font-bold text-slate-900 mb-4">Neysa (Advokasi)</h3>
                <p class="text-brand-silverDark text-sm leading-relaxed mb-8 italic">"Layanan bantuan aspirasi dan pendampingan hak-hak mahasiswa."</p>
                <a href="https://wa.me/6285749846139" class="mt-auto block text-center bg-slate-900 text-white py-4 rounded-2xl font-bold text-sm hover:bg-brand-purple transition-colors">
                    Hubungi Via WhatsApp
                </a>
            </div>

        </div>
    </section>

    <footer id="kontak" class="bg-white border-t border-brand-silver/30 py-20">
        <div class="container mx-auto px-6 text-center">
            <img src="LOGO SEMA.png" alt="LOGO SEMA.png" class="h-16 mx-auto mb-8 opacity-90">
            <h4 class="font-bold text-slate-900 mb-2 uppercase tracking-widest text-sm text-sm">Kunjungi Media Sosial Kami</h4>
            
            <div class="flex justify-center space-x-4 mt-6 mb-12">
                <a href="https://www.instagram.com/semafpsikologi_uinmalang/" target="_blank" class="social-icon w-12 h-12 rounded-full flex items-center justify-center text-slate-500 shadow-sm">
                    <i class="fab fa-instagram text-xl"></i>
                </a>
                <a href="https://www.tiktok.com/@semafpsikologiuinma" target="_blank" class="social-icon w-12 h-12 rounded-full flex items-center justify-center text-slate-500 shadow-sm">
                    <i class="fab fa-tiktok text-xl"></i>
                </a>
                <a href="https://www.linkedin.com/company/senat-mahasiswa-fakultas-psikologi-uin-malang/" target="_blank" class="social-icon w-12 h-12 rounded-full flex items-center justify-center text-slate-500 shadow-sm">
                    <i class="fab fa-linkedin-in text-xl"></i>
                </a>
            </div>

            <div class="max-w-md mx-auto border-t border-brand-silver/50 pt-10">
                <p class="text-[10px] text-brand-silverDark font-bold uppercase tracking-[0.4em]">© 2026 SEMA-F Psikologi UIN Malang</p>
                <p class="text-[9px] text-brand-purple mt-2 italic tracking-widest font-semibold uppercase">#SuaraMahasiswa #AdvokasiDekat</p>
            </div>
        </div>
    </footer>

</body>
</html>
