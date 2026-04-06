<!DOCTYPE html>
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
                        psikologi: {
                            light: '#f5f3ff',
                            primary: '#7c3aed', // Ungu Utama
                            dark: '#5b21b6',
                            silver: '#f8fafc',
                            accent: '#94a3b8'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
        
        /* Efek Hover Professional */
        .hover-card {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .hover-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(124, 58, 237, 0.1), 0 10px 10px -5px rgba(124, 58, 237, 0.04);
            border-color: #7c3aed;
        }

        .btn-interact {
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        .btn-interact:after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            background: rgba(255,255,255,0.2);
            border-radius: 50%;
            transform: translate(-50%, -50%);
            transition: width 0.6s, height 0.6s;
        }
        .btn-interact:hover:after {
            width: 300%;
            height: 300%;
        }

        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: #7c3aed;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
    </style>
</head>
<body class="bg-psikologi-silver text-slate-800 font-sans">

    <nav class="bg-white/80 backdrop-blur-md sticky top-0 z-50 border-b border-slate-100 py-4">
        <div class="container mx-auto px-6 flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <img src="LOGO SEMA.png" alt="LOGO SEMA.png" class="h-10 w-auto hover:rotate-3 transition-transform">
                <div class="border-l-2 border-slate-200 pl-4 hidden md:block">
                    <h1 class="font-bold text-slate-900 leading-tight tracking-tight">SEMA-F PSIKOLOGI</h1>
                    <p class="text-[10px] text-psikologi-primary font-semibold uppercase tracking-widest">UIN Maulana Malik Ibrahim</p>
                </div>
            </div>
            
            <div class="hidden md:flex space-x-8 text-sm font-bold text-slate-500 uppercase tracking-widest">
                <a href="#home" class="nav-link hover:text-psikologi-primary transition-colors">Beranda</a>
                <a href="#layanan" class="nav-link hover:text-psikologi-primary transition-colors">Layanan</a>
                <a href="#kontak" class="nav-link hover:text-psikologi-primary transition-colors">Kontak</a>
            </div>
        </div>
    </nav>

    <header id="home" class="relative overflow-hidden bg-white py-24 border-b border-slate-100">
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 bg-psikologi-light rounded-full blur-3xl opacity-50"></div>
        <div class="container mx-auto px-6 text-center relative z-10">
            <span class="inline-block px-4 py-1.5 mb-6 text-xs font-bold tracking-widest text-psikologi-primary uppercase bg-psikologi-light rounded-full">
                Advokasi & Aspirasi Mahasiswa
            </span>
            <h2 class="text-4xl md:text-6xl font-black text-slate-900 mb-6 leading-[1.1]">
                Menjadi Jembatan <br><span class="text-psikologi-primary">Perubahan Positif.</span>
            </h2>
            <p class="text-slate-500 max-w-2xl mx-auto mb-10 text-lg">
                Sampaikan aspirasi Anda untuk mewujudkan tata kelola organisasi mahasiswa yang transparan, akuntabel, dan berorientasi pada kepentingan bersama.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#layanan" class="btn-interact bg-psikologi-primary text-white px-10 py-4 rounded-xl font-bold shadow-lg shadow-psikologi-primary/20 hover:bg-psikologi-dark">
                    Lapor Aspirasi
                </a>
                <a href="https://www.instagram.com/semafpsikologi_uinmalang/" target="_blank" class="bg-white border border-slate-200 text-slate-600 px-10 py-4 rounded-xl font-bold hover:bg-slate-50 transition-colors">
                    Media Sosial
                </a>
            </div>
        </div>
    </header>

    <section id="layanan" class="py-24 bg-psikologi-silver">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h3 class="text-3xl font-black text-slate-900 mb-4">Pusat Bantuan Advokasi</h3>
                <div class="h-1.5 w-20 bg-psikologi-primary mx-auto rounded-full"></div>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="hover-card bg-white p-8 rounded-3xl border border-slate-100 flex flex-col items-start">
                    <div class="w-14 h-14 bg-psikologi-light rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-edit text-psikologi-primary text-xl"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900 mb-3">E-Aspirasi</h4>
                    <p class="text-slate-500 text-sm mb-6 leading-relaxed">Formulir digital resmi untuk pengaduan akademik, sarana prasarana, dan birokrasi kampus.</p>
                    <a href="LINK_GOOGLE_FORM_MU" class="mt-auto text-psikologi-primary font-bold text-sm flex items-center group">
                        Isi Formulir <i class="fas fa-chevron-right ml-2 group-hover:ml-3 transition-all"></i>
                    </a>
                </div>

                <div class="hover-card bg-white p-8 rounded-3xl border border-slate-100 flex flex-col items-start">
                    <div class="w-14 h-14 bg-green-50 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fab fa-whatsapp text-green-600 text-xl"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900 mb-3">Hotline Adyb</h4>
                    <p class="text-slate-500 text-sm mb-6 leading-relaxed">Konsultasi langsung melalui WhatsApp untuk respon yang lebih cepat dan privat.</p>
                    <a href="https://wa.me/6282245224689" class="mt-auto bg-slate-50 hover:bg-psikologi-primary hover:text-white transition-colors w-full text-center py-3 rounded-xl font-bold text-sm text-slate-600">
                        Chat Sekarang
                    </a>
                </div>

                <div class="hover-card bg-white p-8 rounded-3xl border border-slate-100 flex flex-col items-start">
                    <div class="w-14 h-14 bg-green-50 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fab fa-whatsapp text-green-600 text-xl"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900 mb-3">Hotline Neysa</h4>
                    <p class="text-slate-500 text-sm mb-6 leading-relaxed">Layanan pendampingan advokasi mahasiswa untuk kendala perkuliahan.</p>
                    <a href="https://wa.me/6285749846139" class="mt-auto bg-slate-50 hover:bg-psikologi-primary hover:text-white transition-colors w-full text-center py-3 rounded-xl font-bold text-sm text-slate-600">
                        Chat Sekarang
                    </a>
                </div>
            </div>
        </div>
    </section>

    <footer id="kontak" class="bg-white border-t border-slate-100 pt-20 pb-10">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center mb-12">
                <div class="text-center md:text-left mb-8 md:mb-0">
                    <img src="LOGO SEMA.png" alt="LOGO SEMA.png" class="h-14 mx-auto md:mx-0 mb-4 opacity-90">
                    <p class="text-slate-400 text-sm max-w-xs">Gedung Student Center Lt. 1, Fakultas Psikologi UIN Malang.</p>
                </div>
                <div class="flex space-x-6">
                    <a href="https://www.instagram.com/semafpsikologi_uinmalang/" target="_blank" class="w-12 h-12 bg-psikologi-silver rounded-full flex items-center justify-center text-slate-400 hover:text-psikologi-primary hover:bg-psikologi-light transition-all shadow-sm italic font-bold">Ig</a>
                    <a href="https://www.tiktok.com/@semafpsikologiuinma" target="_blank" class="w-12 h-12 bg-psikologi-silver rounded-full flex items-center justify-center text-slate-400 hover:text-psikologi-primary hover:bg-psikologi-light transition-all shadow-sm italic font-bold">Tk</a>
                    <a href="https://www.linkedin.com/company/senat-mahasiswa-fakultas-psikologi-uin-malang/" target="_blank" class="w-12 h-12 bg-psikologi-silver rounded-full flex items-center justify-center text-slate-400 hover:text-psikologi-primary hover:bg-psikologi-light transition-all shadow-sm italic font-bold">Li</a>
                </div>
            </div>
            <div class="pt-8 border-t border-slate-50 text-center">
                <p class="text-[10px] text-slate-400 uppercase tracking-widest font-bold mb-2">© 2024 SEMA-F PSIKOLOGI UIN MALANG</p>
                <p class="text-[9px] text-psikologi-accent italic">#AdvokasiHumanis #SuaraMahasiswaPsikologi</p>
            </div>
        </div>
    </footer>

</body>
</html>
