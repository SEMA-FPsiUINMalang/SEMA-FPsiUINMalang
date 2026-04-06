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
                        darkBase: '#0a0a0c', // Hitam Elegan
                        darkPurple: '#1e1b4b', // Deep Purple
                        brandPurple: '#7c3aed', // Ungu Terang untuk Aksen
                        silverMetal: '#cbd5e1', // Silver
                    }
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
        body { background-color: #0a0a0c; color: #cbd5e1; }
        .glass { 
            background: rgba(30, 27, 75, 0.4); 
            backdrop-filter: blur(10px); 
            border: 1px solid rgba(203, 213, 225, 0.1); 
        }
        .hero-gradient {
            background: radial-gradient(circle at top right, #2e1065, #0a0a0c);
        }
        .text-gradient {
            background: linear-gradient(to right, #ffffff, #94a3b8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="font-sans">

    <nav class="glass sticky top-0 z-50 py-3 px-6">
        <div class="container mx-auto flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <img src="LOGO SEMA.png" alt="LOGO SEMA.png" class="h-12 w-auto drop-shadow-[0_0_8px_rgba(124,58,237,0.5)]">
                <div class="hidden sm:block">
                    <p class="font-bold text-white leading-none">SEMA-F PSIKOLOGI</p>
                    <p class="text-[10px] text-brandPurple tracking-widest uppercase">UIN Maulana Malik Ibrahim</p>
                </div>
            </div>
            <div class="space-x-6 text-sm font-semibold uppercase tracking-wider">
                <a href="#home" class="hover:text-brandPurple transition">Home</a>
                <a href="#aspirasi" class="hover:text-brandPurple transition">Aspirasi</a>
                <a href="#kontak" class="hover:text-brandPurple transition">Kontak</a>
            </div>
        </div>
    </nav>

    <header id="home" class="hero-gradient py-28 px-6 text-center">
        <div class="container mx-auto">
            <h1 class="text-5xl md:text-6xl font-black mb-6 text-gradient italic uppercase">Advokasi Bermartabat</h1>
            <p class="text-lg md:text-xl text-silverMetal/70 max-w-2xl mx-auto mb-10 leading-relaxed">
                Menjadi garda terdepan dalam memperjuangkan hak dan menyampaikan aspirasi mahasiswa Psikologi UIN Malang dengan prinsip transparan dan akuntabel.
            </p>
            <div class="flex flex-wrap justify-center gap-5">
                <a href="#aspirasi" class="bg-brandPurple hover:bg-purple-600 text-white px-10 py-4 rounded-full font-bold shadow-[0_0_20px_rgba(124,58,237,0.4)] transition-all transform hover:scale-105">
                    Kirim Aspirasi
                </a>
                <a href="https://www.instagram.com/semafpsikologi_uinmalang/" target="_blank" class="glass px-10 py-4 rounded-full font-bold hover:bg-white/5 transition">
                    Follow IG
                </a>
            </div>
        </div>
    </header>

    <section class="py-20 container mx-auto px-6">
        <div class="grid md:grid-cols-3 gap-6">
            <div class="glass p-8 rounded-3xl border-l-4 border-brandPurple">
                <h3 class="text-brandPurple font-bold text-xl mb-2">Legislasi</h3>
                <p class="text-sm text-silverMetal/60">Merumuskan norma dan aturan organisasi di tingkat fakultas.</p>
            </div>
            <div class="glass p-8 rounded-3xl border-l-4 border-brandPurple">
                <h3 class="text-brandPurple font-bold text-xl mb-2">Penganggaran</h3>
                <p class="text-sm text-silverMetal/60">Memastikan distribusi dana organisasi yang efektif dan tepat sasaran.</p>
            </div>
            <div class="glass p-8 rounded-3xl border-l-4 border-brandPurple">
                <h3 class="text-brandPurple font-bold text-xl mb-2">Pengawasan</h3>
                <p class="text-sm text-silverMetal/60">Mengawasi kinerja DEMA-F demi kepentingan seluruh mahasiswa.</p>
            </div>
        </div>
    </section>

    <section id="aspirasi" class="py-16 bg-white/5 backdrop-blur-sm">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12 text-white">Layanan <span class="text-brandPurple">Advokasi</span></h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="glass p-10 rounded-[2rem] hover:border-brandPurple/50 transition">
                    <i class="fas fa-file-signature text-4xl text-brandPurple mb-6"></i>
                    <h3 class="text-2xl font-bold text-white mb-4">E-Aspirasi</h3>
                    <p class="text-silverMetal/60 mb-8">Formulir digital resmi untuk pengaduan akademik, sarana prasarana, maupun finansial.</p>
                    <a href="LINK_GOOGLE_FORM_MU" class="block text-center py-4 rounded-xl border border-brandPurple text-brandPurple font-bold hover:bg-brandPurple hover:text-white transition">Buka Formulir</a>
                </div>

                <div class="glass p-10 rounded-[2rem] hover:border-green-500/50 transition">
                    <i class="fab fa-whatsapp text-4xl text-green-500 mb-6"></i>
                    <h3 class="text-2xl font-bold text-white mb-4">Hotline Chat</h3>
                    <p class="text-silverMetal/60 mb-6">Butuh respon cepat? Hubungi admin advokasi kami:</p>
                    <div class="space-y-3">
                        <a href="https://wa.me/6282245224689" class="flex items-center justify-between bg-white/5 p-4 rounded-xl hover:bg-white/10">
                            <span class="font-medium text-silverMetal">Adyb</span>
                            <span class="text-xs opacity-50">+62 822-4522-4689</span>
                        </a>
                        <a href="https://wa.me/6285749846139" class="flex items-center justify-between bg-white/5 p-4 rounded-xl hover:bg-white/10">
                            <span class="font-medium text-silverMetal">Neysa</span>
                            <span class="text-xs opacity-50">+62 857-4984-6139</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer id="kontak" class="py-16 text-center border-t border-white/10">
        <div class="container mx-auto px-6">
            <img src="LOGO SEMA.png" alt="LOGO SEMA.png" class="h-16 mx-auto mb-6 opacity-80">
            <div class="flex justify-center space-x-8 mb-8">
                <a href="https://www.instagram.com/semafpsikologi_uinmalang/" target="_blank" class="text-2xl text-silverMetal/40 hover:text-brandPurple"><i class="fab fa-instagram"></i></a>
                <a href="https://www.tiktok.com/@semafpsikologiuinma" target="_blank" class="text-2xl text-silverMetal/40 hover:text-brandPurple"><i class="fab fa-tiktok"></i></a>
                <a href="https://www.linkedin.com/company/senat-mahasiswa-fakultas-psikologi-uin-malang/" target="_blank" class="text-2xl text-silverMetal/40 hover:text-brandPurple"><i class="fab fa-linkedin"></i></a>
            </div>
            <p class="text-xs text-silverMetal/30 uppercase tracking-[0.3em]">© 2026 SEMA-F Psikologi UIN Malang</p>
        </div>
    </footer>

</body>
</html>
