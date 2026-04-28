<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One World Perfume | Hub Pembekal Wangian No.1 Borneo</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-gold: #c5a059;
            --dark-black: #1a1a1a;
            --soft-white: #f9f9f9;
            --text-gray: #4a4a4a;
            --accent-color: #8e7341;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--soft-white);
            color: var(--dark-black);
            line-height: 1.6;
        }

        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Navigation */
        nav {
            padding: 20px 0;
            background: white;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        nav .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-gold);
            letter-spacing: 1px;
        }

        /* Hero Section */
        .hero {
            padding: 100px 0;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1541643600914-78b084683601?auto=format&fit=crop&q=80&w=1920') no-repeat center center/cover;
            color: white;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }

        .btn-primary {
            background-color: var(--primary-gold);
            color: white;
            padding: 15px 40px;
            text-decoration: none;
            font-weight: 600;
            border-radius: 5px;
            transition: 0.3s;
            display: inline-block;
        }

        .btn-primary:hover {
            background-color: var(--accent-color);
            transform: translateY(-3px);
        }

        /* Social Proof / Trust Bar */
        .trust-bar {
            background: white;
            padding: 40px 0;
            text-align: center;
            border-bottom: 1px solid #eee;
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .stat-item h3 {
            font-size: 2.5rem;
            color: var(--primary-gold);
        }

        /* Features Section */
        .features {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title h2 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .feature-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            transition: 0.3s;
            border-bottom: 4px solid transparent;
        }

        .feature-card:hover {
            transform: translateY(-10px);
            border-bottom: 4px solid var(--primary-gold);
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
        }

        .feature-card h3 {
            margin-bottom: 15px;
            color: var(--primary-gold);
        }

        /* Call to Action Section */
        .cta-section {
            background: var(--dark-black);
            color: white;
            padding: 80px 0;
            text-align: center;
        }

        .cta-section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        /* Footer */
        footer {
            padding: 50px 0;
            background: #f1f1f1;
            text-align: center;
            font-size: 0.9rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .hero p { font-size: 1rem; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="container">
            <div class="logo">ONE WORLD PERFUME</div>
            <div>
                <a href="#hubungi" class="btn-primary" style="padding: 10px 20px; font-size: 0.9rem;">WhatsApp Kami</a>
            </div>
        </div>
    </nav>

    <section class="hero">
        <div class="container">
            <h1>Bina Jenama Wangian Anda Dari Borneo!</h1>
            <p>Lupakan kos postage mahal dari Semenanjung. Kami bekalkan pati gred premium dan botol eksklusif terus dari kilang kami di Kota Kinabalu, Kuching, dan Kota Bharu.</p>
            <a href="#hubungi" class="btn-primary">Mula Bisnes Jenama Sendiri</a>
        </div>
    </section>

    <section class="trust-bar">
        <div class="container">
            <div class="stats">
                <div class="stat-item">
                    <h3>250+</h3>
                    <p>Pilihan Pati Wangian</p>
                </div>
                <div class="stat-item">
                    <h3>35+</h3>
                    <p>Reka Bentuk Botol</p>
                </div>
                <div class="stat-item">
                    <h3>3</h3>
                    <p>Pusat Edaran (KK, Kuching, KB)</p>
                </div>
                <div class="stat-item">
                    <h3>No.1</h3>
                    <p>Pembekal Borong Borneo</p>
                </div>
            </div>
        </div>
    </section>

    <section class="features">
        <div class="container">
            <div class="section-title">
                <h2>Mengapa Pilih One World Perfume?</h2>
                <p>Kami menyediakan segala keperluan untuk anda menjadi usahawan minyak wangi yang berjaya.</p>
            </div>
            <div class="feature-grid">
                <div class="feature-card">
                    <h3>Kualiti Gred Premium</h3>
                    <p>Pati wangian kami diimport dan diformulasikan untuk ketahanan lebih 12 jam. Pelanggan anda pasti akan kembali lagi.</p>
                </div>
                <div class="feature-card">
                    <h3>Pakej Rebranding Lengkap</h3>
                    <p>Bukan sekadar minyak wangi, kami sediakan botol eksklusif dan bimbingan pemasaran digital untuk jualan meletop.</p>
                </div>
                <div class="feature-card">
                    <h3>Logistik Pantas & Murah</h3>
                    <p>Dengan fasiliti di Sabah dan Sarawak, penghantaran adalah lebih cepat dan kos postage jauh lebih rendah untuk warga Borneo.</p>
                </div>
            </div>
        </div>
    </section>

    <section style="background-color: #fff; padding: 60px 0; text-align: center;">
        <div class="container">
            <h2 style="font-family: 'Playfair Display', serif; font-size: 2rem; font-style: italic;">"Pakej One World Perfume sangat memudahkan. Saya tak perlu pening cari botol dan pati di tempat berbeza."</h2>
            <p style="margin-top: 15px; font-weight: 600;">— Usahawan Wangian Sabah</p>
        </div>
    </section>

    <section id="hubungi" class="cta-section">
        <div class="container">
            <h2>Sedia Untuk Memulakan Empayar Anda?</h2>
            <p>Hubungi konsultan jualan kami (Syaniesha atau Masir) sekarang untuk dapatkan katalog lengkap dan konsultasi percuma.</p>
            <br>
            <a href="https://wa.me/60123456789" class="btn-primary" style="background-color: #25D366;">WhatsApp Konsultan Kami Sekarang</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2026 One World Perfume. Pakar Wangian Inspirasi & Botol Borong Anda.</p>
            <p>Kota Kinabalu | Kuching | Kota Bharu</p>
        </div>
    </footer>

    <script>
        // Smooth Scroll Logic
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Simple Fade-in Animation on Scroll
        window.addEventListener('scroll', () => {
            const cards = document.querySelectorAll('.feature-card');
            cards.forEach(card => {
                const cardTop = card.getBoundingClientRect().top;
                if (cardTop < window.innerHeight - 100) {
                    card.style.opacity = '1';
                    card.style.transform = 'translateY(0)';
                }
            });
        });

        // Initial state for animation
        document.querySelectorAll('.feature-card').forEach(card => {
            card.style.opacity = '0';
            card.style.transform = 'translateY(20px)';
            card.style.transition = 'all 0.6s ease-out';
        });
    </script>
</body>
</html>
