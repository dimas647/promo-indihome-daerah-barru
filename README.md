# promo-indihome-daerah-barru
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Promo IndiHome Unlimited - Daftar Resmi & Cepat</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
</head>
<body>

    <header class="hero-section">
        <div class="container">
            <h1>Promo IndiHome Unlimited</h1>
            <p class="subtitle">Internet Fiber Optik Tercepat & Stabil untuk Rumah Anda</p>
            <div class="badge-resmi">100% Sales Resmi</div>
        </div>
    </header>

    <main class="container package-grid">

        <div class="package-card" data-package="20Mbps">
            <div class="speed">20Mbps</div>
            <div class="price">
                <span>Rp</span>190<small>.000</small>
                <div class="per-bulan">/ bulan</div>
            </div>
            <ul class="features">
                <li><i class="fas fa-tv"></i> IndiHome TV</li>
            </ul>
            <div class="biaya-pasang">Biaya Pasang: Rp 166.500</div>
            <button class="cta-button" onclick="openModal('20Mbps')">Isi Formulir</button>
        </div>

        <div class="package-card best-seller" data-package="50Mbps">
            <div class="best-seller-tag">TERLARIS</div>
            <div class="speed">50Mbps</div>
            <div class="price">
                <span>Rp</span>240<small>.000</small>
                <div class="per-bulan">/ bulan</div>
            </div>
            <ul class="features">
                <li><i class="fas fa-play"></i> Catchplay+</li>
                <li><i class="fas fa-tv"></i> TV</li>
                <li><i class="fas fa-star"></i> Prime Video</li>
            </ul>
            <div class="biaya-pasang">Biaya Pasang: Rp 166.500</div>
            <button class="cta-button" onclick="openModal('50Mbps')">Isi Formulir</button>
        </div>

        <div class="package-card" data-package="75Mbps">
            <div class="speed">75Mbps</div>
            <div class="price">
                <span>Rp</span>270<small>.000</small>
                <div class="per-bulan">/ bulan</div>
            </div>
            <ul class="features">
                <li><i class="fas fa-play"></i> Catchplay+</li>
                <li><i class="fas fa-star"></i> Prime Video</li>
            </ul>
            <div class="biaya-pasang">Biaya Pasang: Rp 166.500</div>
            <button class="cta-button" onclick="openModal('75Mbps')">Isi Formulir</button>
        </div>

        <div class="package-card" data-package="150Mbps">
            <div class="speed">150Mbps</div>
            <div class="price">
                <span>Rp</span>375<small>.000</small>
                <div class="per-bulan">/ bulan</div>
            </div>
            <ul class="features">
                <li><i class="fas fa-play"></i> Catchplay+</li>
                <li><i class="fas fa-star"></i> Prime Video</li>
            </ul>
            <div class="biaya-pasang">Biaya Pasang: Rp 166.500</div>
            <button class="cta-button" onclick="openModal('150Mbps')">Isi Formulir</button>
        </div>
        
        <div class="package-card" data-package="200Mbps">
            <div class="speed">200Mbps</div>
            <div class="price">
                <span>Rp</span>515<small>.000</small>
                <div class="per-bulan">/ bulan</div>
            </div>
            <ul class="features">
                <li><i class="fas fa-play"></i> Catchplay+</li>
                <li><i class="fas fa-film"></i> Netflix</li>
            </ul>
            <div class="biaya-pasang">Biaya Pasang: Rp 166.500</div>
            <button class="cta-button" onclick="openModal('200Mbps')">Isi Formulir</button>
        </div>

    </main>

    <footer>
        <div class="container">
            <p>Harga belum termasuk PPN 11%. Syarat & Ketentuan berlaku.</p>
            <p class="area-text">DS INDIHOME Barru, Pangkep, Maros</p>
        </div>
    </footer>


    <div id="registrationModal" class="modal">
        <div class="modal-content">
            <span class="close-button" onclick="closeModal()">&times;</span>
            <h2>Formulir Pendaftaran</h2>
            <p>Lengkapi data untuk pengecekan jaringan (ODP)</p>
            
            <form id="regForm">
                <label for="package">Paket Pilihan:</label>
                <input type="text" id="package" name="package" required readonly>

                <label for="name">Nama Lengkap:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Alamat Email:</label>
                <input type="email" id="email" name="email">

                <label for="whatsapp">No. HP / WhatsApp (Aktif):</label>
                <input type="tel" id="whatsapp" name="whatsapp" required>

                <label for="alt_phone">No. Alternatif (Opsional):</label>
                <input type="tel" id="alt_phone" name="alt_phone">

                <label for="address">Alamat Pemasangan Lengkap:</label>
                <textarea id="address" name="address" required></textarea>

                <label for="location">Share Location (Google Maps):</label>
                <input type="url" id="location" name="location">
                <small>*Klik tombol biru untuk otomatis isi lokasi (fitur ini memerlukan JavaScript yang lebih kompleks).</small>

                <button type="submit" class="submit-button">KIRIM DATA SEKARANG</button>
            </form>
        </div>
    </div>


    <script>
        // ================== JAVASCRIPT UNTUK MODAL ==================
        function openModal(packageName) {
            const modal = document.getElementById('registrationModal');
            const packageInput = document.getElementById('package');
            
            // Mengisi input paket dengan nama paket yang dipilih
            packageInput.value = packageName;
            
            modal.style.display = "block";
        }

        function closeModal() {
            const modal = document.getElementById('registrationModal');
            modal.style.display = "none";
        }

        // Menutup modal jika pengguna mengklik di luar area modal
        window.onclick = function(event) {
            const modal = document.getElementById('registrationModal');
            if (event.target == modal) {
                modal.style.display = "none";
            }
        }
    </script>
</body>
</html>
