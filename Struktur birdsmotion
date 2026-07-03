<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BirdsMotion Dome — Digital Encyclopedia</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <nav class="navbar">
        <div class="nav-brand">BirdsMotion <span>Dome</span></div>
        <div class="tagline">"One Scan, Discover Indonesia's Birds."</div>
    </nav>

    <header class="hero">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <span class="series-badge">Series 1 — Jawa Timur</span>
            <h1 class="bird-name">Cendet Madura</h1>
            <p class="scientific-name"><i>Lanius schach</i></p>
            
            <div class="audio-widget">
                <button id="play-audio-btn" class="btn-audio">
                    <span class="icon">▶️</span> Dengarkan Suara Burung
                </button>
                <audio id="bird-sound" src="https://www.xeno-canto.org/sounds/uploaded/RVKNFSXNYA/XC754321-Long-tailed%20Shrike%20%28Lanius%20schach%29.mp3"></audio>
            </div>
        </div>
    </header>

    <main class="main-container">
        
        <section class="info-grid">
            <div class="profile-card">
                <h2>Profil Burung</h2>
                <table class="profile-table">
                    <tr><td>Famili</td><td>: Laniidae</td></tr>
                    <tr><td>Daerah Asal</td><td>: 📍 Madura, Jawa Timur</td></tr>
                    <tr><td>Ekosistem</td><td>: Padang Terbuka, Agrikultur</td></tr>
                </table>
            </div>

            <div class="status-card">
                <h2>Status Konservasi</h2>
                <div class="status-indicator lc">
                    <span class="status-dot"></span>
                    <div>
                        <h3>🟢 Tidak Terancam (Least Concern)</h3>
                        <p>Secara global belum masuk kategori kritis, namun populasi lokal di habitat aslinya di Indonesia menghadapi tekanan besar akibat aktivitas manusia.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="showcase-section">
            <div class="showcase-box">
                <h2>Wilayah Persebaran</h2>
                <div class="map-placeholder">
                    <div class="pulse-pointer" style="top: 62%; left: 55%;"></div>
                    <p class="map-text">📍 Terkonsentrasi di Pulau Madura dan sekitarnya</p>
                </div>
            </div>
            <div class="showcase-box">
                <h2>Habitat Alami</h2>
                <div class="habitat-visual">
                    <div class="habitat-info">
                        <h3>Padang Rumput & Belukar</h3>
                        <p>Menyukai area terbuka dengan pohon bertengger tinggi untuk mengintai mangsa.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="details-section">
            <h2 class="section-title">Anatomi & Karakter</h2>
            <div class="anatomy-grid">
                <div class="anatomy-card male">
                    <h3>♂️ Jantan</h3>
                    <ul>
                        <li><strong>Warna Bulu:</strong> Kontras hitam pekat di kepala (topeng), tubuh jingga kecokelatan.</li>
                        <li><strong>Ciri Khas:</strong> Ekor lebih panjang dan postur tegap agresif.</li>
                    </ul>
                </div>
                <div class="anatomy-card female">
                    <h3>♀️ Betina</h3>
                    <ul>
                        <li><strong>Warna Bulu:</strong> Cenderung sedikit lebih kusam dibanding jantan.</li>
                        <li><strong>Perbedaan:</strong> Garis samarsamar di area dada pada beberapa subspesies.</li>
                    </ul>
                </div>
            </div>

            <div class="facts-box">
                <h3>💡 Fakta Unik: "Sang Predator Cerdas"</h3>
                <p>Cendet Madura terkenal dengan kebiasaan menancapkan mangsanya (seperti belalang atau kadal kecil) pada duri pohon atau kawat berduri sebelum dimakan. Mereka juga peniru suara ulung!</p>
            </div>
        </section>

        <section class="conservation-section">
            <div class="threat-box">
                <h2>⚠️ Mengapa Mereka Terancam?</h2>
                <div class="threat-list">
                    <div class="threat-item"><strong>Perburuan Liar:</strong> Tingginya minat pasar burung kicau domestik.</div>
                    <div class="threat-item"><strong>Hilangnya Habitat:</strong> Alih fungsi lahan terbuka menjadi pemukiman.</div>
                </div>
            </div>
            <div class="solution-box">
                <h2>✅ Solusi Pelestarian</h2>
                <ul>
                    <li>Melindungi ekosistem padang terbuka asli.</li>
                    <li>Edukasi generasi muda lewat platform interaktif seperti <b>BirdsMotion Dome</b> agar tumbuh rasa memiliki terhadap alam asli Indonesia.</li>
                </ul>
            </div>
        </section>

        <section class="quiz-section">
            <h2>🧠 Uji Pengetahuanmu</h2>
            <div class="quiz-card" id="quiz-block">
                <p class="quiz-question">Dari manakah asal utama habitat Burung Cendet Madura?</p>
                <div class="quiz-options">
                    <button class="opt-btn" onclick="checkAnswer(false, this)">A. Bali</button>
                    <button class="opt-btn" onclick="checkAnswer(true, this)">B. Madura</button>
                    <button class="opt-btn" onclick="checkAnswer(false, this)">C. Papua</button>
                </div>
                <div id="quiz-feedback" class="quiz-feedback hidden"></div>
            </div>
        </section>

    </main>

    <script src="script.js"></script>
</body>
</html>
