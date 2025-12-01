<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Promo IndiHome Unlimited - Replika</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');
        body { font-family: 'Poppins', sans-serif; }
    </style>
</head>
<body>

    <header class="promo-header">
        <h1>PROMO INDIHOME UNLIMITED</h1>
        <p>Internet Fiber Optik Tercepat & Stabil untuk Rumah Anda</p>
        <button class="sales-badge">
            <span class="heart-icon">❤</span> 100% Sales Resmi
        </button>
    </header>

    <div class="promo-container">
        
        <div class="promo-card">
            <div class="speed-box">20</div>
            <div class="unit-text">Mbps</div>
            <div class="price-box">
                <span class="currency">Rp</span>340.000
            </div>
            <div class="duration-text">/ bulan</div>
            <div class="divider"></div>
            <h3>Termasuk Aplikasi:</h3>
            <div class="app-badges">
                <span class="app-badge tv">IndiHome TV</span>
            </div>
            <div class="installation-fee">
                Biaya Pasang: Rp 166.500
            </div>
            <button class="form-button red">
                <span class="form-icon">📝</span> Isi Formulir
            </button>
        </div>

        <div class="promo-card best-seller">
            <span class="best-seller-tag">⚡ TERLARIS</span>
            <div class="speed-box">50</div>
            <div class="unit-text">Mbps</div>
            <div class="price-box">
                <span class="currency">Rp</span>240.000
            </div>
            <div class="duration-text">/ bulan</div>
            <div class="divider"></div>
            <h3>Termasuk Aplikasi:</h3>
            <div class="app-badges">
                <span class="app-badge orange">Catchplay+</span>
                <span class="app-badge tv">TV</span>
                <span class="app-badge blue">Prime</span>
            </div>
            <div class="installation-fee">
                Biaya Pasang: Rp 166.500
            </div>
            <button class="form-button red">
                <span class="form-icon">📝</span> Isi Formulir
            </button>
        </div>

        <div class="promo-card">
            <div class="speed-box">75</div>
            <div class="unit-text">Mbps</div>
            <div class="price-box">
                <span class="currency">Rp</span>270.000
            </div>
            <div class="duration-text">/ bulan</div>
            <div class="divider"></div>
            <h3>Termasuk Aplikasi:</h3>
            <div class="app-badges">
                <span class="app-badge orange">Catchplay+</span>
                <span class="app-badge blue">Prime</span>
            </div>
            <div class="installation-fee">
                Biaya Pasang: Rp 166.500
            </div>
            <button class="form-button red">
                <span class="form-icon">📝</span> Isi Formulir
            </button>
        </div>

        <div class="promo-card">
            <div class="speed-box">150</div>
            <div class="unit-text">Mbps</div>
            <div class="price-box">
                <span class="currency">Rp</span>375.000
            </div>
            <div class="duration-text">/ bulan</div>
            <div class="divider"></div>
            <h3>Termasuk Aplikasi:</h3>
            <div class="app-badges">
                <span class="app-badge orange">Catchplay+</span>
                <span class="app-badge blue">Prime</span>
            </div>
            <div class="installation-fee">
                Biaya Pasang: Rp 166.500
            </div>
            <button class="form-button red">
                <span class="form-icon">📝</span> Isi Formulir
            </button>
        </div>

        <div class="promo-card">
            <div class="speed-box">200</div>
            <div class="unit-text">Mbps</div>
            <div class="price-box">
                <span class="currency">Rp</span>515.000
            </div>
            <div class="duration-text">/ bulan</div>
            <div class="divider"></div>
            <h3>Termasuk Aplikasi:</h3>
            <div class="app-badges">
                <span class="app-badge orange">Catchplay+</span>
                <span class="app-badge netflix">Netflix</span>
            </div>
            <div class="installation-fee">
                Biaya Pasang: Rp 166.500
            </div>
            <button class="form-button red">
                <span class="form-icon">📝</span> Isi Formulir
            </button>
        </div>
        
    </div>

    <footer class="promo-footer">
        <p>Harga belum termasuk PPN 11%. Syarat & Ketentuan berlaku.</p>
        <p>DS INDIHOME Barru, Pangkep, Maros</p>
        </footer>

</body>
</html>
body {
    background-color: #f7f7f7;
    margin: 0;
    padding: 0;
    text-align: center;
    color: #333;
    font-size: 16px;
}

.promo-header {
    background-color: #e50000;
    color: white;
    padding: 30px 20px;
    margin-bottom: 20px;
}

.promo-header h1 {
    font-size: 1.8em;
    margin: 0 0 5px 0;
    font-weight: 700;
}

.promo-header p {
    font-size: 0.9em;
    margin: 0 0 15px 0;
}

.sales-badge {
    background-color: white;
    color: #e50000;
    border: none;
    padding: 8px 15px;
    border-radius: 20px;
    font-weight: 600;
    font-size: 0.85em;
    cursor: pointer;
}

.heart-icon {
    margin-right: 5px;
}

.promo-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 0 15px 30px 15px;
}

.promo-card {
    background-color: white;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
    padding: 25px;
    text-align: center;
    position: relative;
    border: 1px solid #eee;
}

/* Kotak Kecepatan */
.speed-box {
    font-size: 4em;
    font-weight: 700;
    color: #e50000;
    line-height: 1;
    margin-bottom: -5px;
}

.unit-text {
    font-size: 1.2em;
    font-weight: 600;
    color: #333;
    margin-bottom: 20px;
}

/* Kotak Harga */
.price-box {
    font-size: 2.2em;
    font-weight: 700;
    color: #333;
    line-height: 1;
}

.currency {
    font-size: 0.5em;
    font-weight: 400;
    vertical-align: top;
    margin-right: 2px;
}

.duration-text {
    font-size: 0.9em;
    color: #666;
    margin-bottom: 20px;
}

.divider {
    height: 1px;
    background-color: #eee;
    margin: 15px 0;
}

.promo-card h3 {
    font-size: 1em;
    font-weight: 400;
    color: #666;
    margin: 0 0 10px 0;
}

/* Badge Aplikasi */
.app-badges {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 20px;
}

.app-badge {
    padding: 5px 10px;
    border-radius: 5px;
    font-size: 0.8em;
    font-weight: 600;
    color: white;
}

.app-badge.tv { background-color: #315099; } /* IndiHome TV */
.app-badge.orange { background-color: #ff9100; } /* Catchplay+ */
.app-badge.blue { background-color: #007bff; } /* Prime */
.app-badge.netflix { background-color: #e50914; } /* Netflix */

.installation-fee {
    background-color: #fce7e7;
    color: #e50000;
    padding: 8px 15px;
    border-radius: 15px;
    font-size: 0.8em;
    font-weight: 600;
    margin-bottom: 20px;
}

/* Tombol Formulir */
.form-button {
    width: 100%;
    padding: 15px;
    border: none;
    border-radius: 10px;
    font-size: 1.1em;
    font-weight: 700;
    cursor: pointer;
    transition: background-color 0.2s;
}

.form-button.red {
    background-color: #e50000;
    color: white;
    box-shadow: 0 4px 8px rgba(229, 0, 0, 0.4);
}

.form-button.red:hover {
    background-color: #c00000;
}

.form-icon {
    margin-right: 5px;
}

/* Tag Terlaris */
.best-seller {
    border: 2px solid #ff9100; /* Border menonjol untuk Terlaris */
}

.best-seller-tag {
    position: absolute;
    top: 0;
    right: 0;
    background-color: #ff9100;
    color: white;
    padding: 5px 15px;
    font-size: 0.75em;
    font-weight: 700;
    border-top-right-radius: 15px;
    border-bottom-left-radius: 15px;
}

/* Footer */
.promo-footer {
    padding: 20px 15px;
    font-size: 0.8em;
    color: #666;
    background-color: white;
    border-top: 1px solid #eee;
    margin-top: 20px;
}

.promo-footer p {
    margin: 5px 0;
}
