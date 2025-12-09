<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AeroMC - Yükleniyor...</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Trebuchet+MS:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        @font-face {
            font-family: 'Frutiger Aero';
            src: local('Trebuchet MS'), sans-serif;
        }

        body {
            font-family: 'Frutiger Aero', 'Trebuchet MS', sans-serif;
            background: linear-gradient(135deg, #0a3d66 0%, #1a5f4a 50%, #0d4d3d 100%);
            color: #333;
            overflow-x: hidden;
            min-height: 100vh;
        }

        /* Loading Screen */
        .loading-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(10, 61, 102, 0.95) 0%, rgba(26, 95, 74, 0.95) 50%, rgba(13, 77, 61, 0.95) 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 9999;
            opacity: 1;
            transition: opacity 0.8s ease-out;
            pointer-events: auto;
        }

        .loading-screen.fade-out {
            opacity: 0;
            pointer-events: none;
        }

        .loading-content {
            text-align: center;
            animation: pulse 1.5s ease-in-out infinite;
        }

        .loading-logo {
            width: 120px;
            height: 120px;
            margin: 0 auto 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
        }

        .loading-logo img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            display: block;
            border-radius: 8px;
        }

        /* Yarım O spinner (Google benzeri) */
        .loading-logo .spinner {
            position: absolute;
            top: -8px;
            left: -8px;
            width: calc(100% + 16px);
            height: calc(100% + 16px);
            border-radius: 50%;
            box-sizing: border-box;
            border: 6px solid rgba(77,208,225,0.12);
            border-top-color: rgba(77,208,225,0.9);
            border-left-color: rgba(77,208,225,0.9);
            border-right-color: transparent;
            border-bottom-color: transparent;
            animation: spin 1s linear infinite;
            pointer-events: none;
        }

        .loading-text {
            font-size: 24px;
            color: #4dd0e1;
            font-weight: bold;
            text-shadow: 0 0 10px rgba(77, 208, 225, 0.5);
        }

        @keyframes spin {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }

        /* Header */
        header {
            position: relative;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, rgba(10, 61, 102, 0.8) 0%, rgba(26, 95, 74, 0.8) 50%, rgba(13, 77, 61, 0.8) 100%),
                        url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 800"><defs><pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(77,208,225,0.1)" stroke-width="1"/></pattern></defs><rect width="1200" height="800" fill="url(%23grid)"/></svg>');
            background-size: cover;
            background-position: center;
            overflow: hidden;
            position: relative;
        }

        .header-content {
            text-align: center;
            z-index: 10;
            animation: slideInDown 0.8s ease-out;
        }

        .logo-main {
            width: 200px;
            height: 200px;
            border-radius: 20px;
            margin: 0 auto 30px;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, rgba(0,212,255,0.06), rgba(0,153,204,0.04));
            box-shadow: 0 10px 50px rgba(0, 212, 255, 0.08);
            transform: perspective(1000px) rotateX(0deg) rotateY(0deg);
            transition: transform 0.3s ease;
        }

        .logo-main img {
            width: 80%;
            height: 80%;
            object-fit: contain;
            display: block;
        }

        h1 {
            font-size: 48px;
            color: #00d4ff;
            text-shadow: 0 0 20px rgba(0, 212, 255, 0.6);
            margin-bottom: 20px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .header-subtitle {
            font-size: 18px;
            color: #b3e5fc;
            margin-top: 15px;
            text-shadow: 0 0 10px rgba(0, 212, 255, 0.4);
        }

        @keyframes slideInDown {
            from {
                opacity: 0;
                transform: translateY(-50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Content Sections */
        .content-section {
            padding: 80px 20px;
            max-width: 1200px;
            margin: 0 auto;
            animation: fadeInUp 0.8s ease-out;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .section-title {
            font-size: 28px;
            color: #00d4ff;
            margin-bottom: 30px;
            font-weight: bold;
            text-shadow: 0 0 15px rgba(0, 212, 255, 0.4);
            letter-spacing: 1px;
        }

        .service-item {
            background: rgba(255, 255, 255, 0.05);
            border: 2px solid rgba(0, 212, 255, 0.3);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
            box-shadow: 0 8px 32px rgba(0, 212, 255, 0.1);
        }

        .service-item:hover {
            background: rgba(255, 255, 255, 0.1);
            border-color: rgba(0, 212, 255, 0.6);
            box-shadow: 0 8px 32px rgba(0, 212, 255, 0.3);
            transform: translateY(-5px);
        }

        .service-item h3 {
            font-size: 20px;
            color: #4dd0e1;
            margin-bottom: 15px;
            font-weight: bold;
        }

        .service-item p {
            color: #e0f2f1;
            font-size: 16px;
            line-height: 1.6;
        }

        /* Wave Footer */
        .wave-container {
            position: relative;
            width: 100%;
            height: 150px;
            background: linear-gradient(to bottom, transparent 0%, rgba(0, 212, 255, 0.05) 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            margin-top: 60px;
        }

        svg {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
        }

        .wave {
            opacity: 1;
        }

        .wave:nth-child(2) {
            animation-delay: -2s;
            opacity: 0.7;
        }

        .wave:nth-child(3) {
            animation-delay: -4s;
            opacity: 0.5;
        }

        @keyframes wave {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(100%);
            }
        }

        /* Subtle section strip to reduce visual noise (fotoğraftaki şerit) */
        .section-strip {
            position: absolute;
            left: 0;
            right: 0;
            bottom: 0;
            height: 72px;
            background: linear-gradient(90deg, rgba(0,0,0,0.06), rgba(0,0,0,0.03));
            border-top: 1px solid rgba(0,212,255,0.03);
            pointer-events: none;
            z-index: 6;
            backdrop-filter: blur(4px);
        }

        .footer-text {
            position: relative;
            z-index: 10;
            font-family: 'Courier New', monospace;
            font-size: 16px;
            color: #00d4ff;
            text-shadow: 0 0 15px rgba(0, 212, 255, 0.6);
            font-weight: bold;
            letter-spacing: 1px;
            white-space: nowrap;
        }

        footer {
            background: linear-gradient(to bottom, transparent 0%, rgba(10, 61, 102, 0.8) 100%);
            padding: 30px 20px;
            text-align: center;
            color: #80deea;
            font-size: 14px;
            border-top: 2px solid rgba(0, 212, 255, 0.2);
        }

        /* Responsive */
        @media (max-width: 768px) {
            h1 {
                font-size: 32px;
            }

            .logo-main {
                width: 150px;
                height: 150px;
                font-size: 70px;
            }

            .section-title {
                font-size: 22px;
            }

            .service-item h3 {
                font-size: 18px;
            }

            .footer-text {
                font-size: 14px;
            }
        }

        /* Scroll Animations */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
            transition: all 0.8s ease-out;
        }
    </style>
</head>
<body>
    <!-- Loading Screen -->
    <div class="loading-screen" id="loadingScreen">
        <div class="loading-content">
            <div class="loading-logo">
                <img src="aerologo_transparent.png" alt="AeroMC Logo">
                <div class="spinner" aria-hidden="true"></div>
            </div>
            <div class="loading-text">AeroMC</div>
            <p style="color: #80deea; margin-top: 15px; font-size: 12px;">Veriler Yükleniyor...</p>
        </div>
    </div>

    <!-- Header/Banner -->
    <header>
        <div class="header-content">
            <div class="logo-main">
                <img src="aerologo_transparent.png" alt="AeroMC Logo">
            </div>
            <h1>AeroMC</h1>
            <p class="header-subtitle">"Battle Royale" Sunucusu</p>
            <p class="header-subtitle">Oyunun En İyi Deneyimini Yaşa</p>
        </div>
    </header>

    <!-- About Section -->
    <section class="content-section reveal">
        <h2 class="section-title">AeroMC</h2>
        <div class="service-item">
            <p>"Battle Royale" sunucusu olarak oyuncularımız için en iyi hizmeti vermek için çalışmalarını sürdürüyor...</p>
        </div>
    </section>

    <!-- Services Section -->
    <section class="content-section reveal">
        <h2 class="section-title">Geliştirilen Hizmet</h2>
        <div class="service-item">
            <h3>Optimize Oyun Deneyimi</h3>
            <p>Sunucumuza özel sistemler ile daha optimize ve daha güncel bir oyun deneyimi sağlıyoruz. En son teknolojiler kullanarak sunucumuz her zaman en iyi performansı sunar.</p>
        </div>
    </section>

    <!-- User Friendly Section -->
    <section class="content-section reveal">
        <h2 class="section-title">Kullanıcı Dostu</h2>
        <div class="service-item">
            <h3>Güvenli ve Destekleyici</h3>
            <p>Oyuncularımız için en güvenli ve en iyi hizmeti sağlayan yetkili ekibimizle sizlere destek oluyoruz. 24/7 canlı destek ve topluluk yönetimi ile her daim yanınızdayız.</p>
        </div>
    </section>

    <!-- Wave Footer -->
    <div class="wave-container">
        <!-- Daha düzgün, sürekli ve hatasız döngü için animateTransform kullanan SVG katmanları -->
        <svg viewBox="0 0 1200 120" preserveAspectRatio="none" style="position:absolute; width:2400px; height:150px; left:0; top:0;">
            <g class="wave" fill="rgba(0,212,255,0.2)">
                <path d="M0,50 Q300,0 600,50 T1200,50 L1200,120 L0,120 Z" />
                <path d="M1200,50 Q1500,0 1800,50 T2400,50 L2400,120 L1200,120 Z" />
                <animateTransform attributeName="transform" type="translate" from="0 0" to="-1200 0" dur="10s" repeatCount="indefinite" />
            </g>
            <g class="wave" fill="rgba(0,212,255,0.12)" style="opacity:0.9;">
                <path d="M0,60 Q300,10 600,60 T1200,60 L1200,120 L0,120 Z" />
                <path d="M1200,60 Q1500,10 1800,60 T2400,60 L2400,120 L1200,120 Z" />
                <animateTransform attributeName="transform" type="translate" from="0 0" to="-1200 0" dur="14s" repeatCount="indefinite" />
            </g>
            <g class="wave" fill="rgba(0,212,255,0.08)" style="opacity:0.8;">
                <path d="M0,70 Q300,20 600,70 T1200,70 L1200,120 L0,120 Z" />
                <path d="M1200,70 Q1500,20 1800,70 T2400,70 L2400,120 L1200,120 Z" />
                <animateTransform attributeName="transform" type="translate" from="0 0" to="-1200 0" dur="18s" repeatCount="indefinite" />
            </g>
        </svg>
        <div class="section-strip"></div>
        <div class="footer-text">Made by ImJumperr</div>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Tüm hakları saklıdır.</p>
        <p style="margin-top: 10px; font-size: 12px;">AeroMC Minecraft Sunucusu</p>
    </footer>

    <script>
        // Loading Screen Fade Out and removal from DOM after transition
        window.addEventListener('load', function() {
            const loadingScreen = document.getElementById('loadingScreen');
            setTimeout(() => {
                loadingScreen.classList.add('fade-out');
                // remove after transition to avoid blocking interactions
                setTimeout(() => {
                    if (loadingScreen && loadingScreen.parentNode) loadingScreen.parentNode.removeChild(loadingScreen);
                }, 900);
            }, 500);
        });

        // Use IntersectionObserver for robust reveal animations
        const revealElements = document.querySelectorAll('.reveal');
        const revealObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                    // optional: unobserve after reveal to avoid repeated triggers
                    revealObserver.unobserve(entry.target);
                }
            });
        }, { threshold: 0.15 });

        revealElements.forEach(el => revealObserver.observe(el));
    </script>
</body>
</html>
