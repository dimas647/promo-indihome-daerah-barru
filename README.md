<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopee Clone - Promosi Toko Online</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { font-family: Arial, sans-serif; }
        .header { background-color: #ee4d2d; color: white; padding: 10px 0; }
        .promo-banner { background-color: #f8f9fa; padding: 20px; text-align: center; }
        .category { margin: 20px 0; }
        .product-card { border: 1px solid #ddd; padding: 10px; margin: 10px; text-align: center; }
        footer { background-color: #343a40; color: white; padding: 20px; text-align: center; }
    </style>
</head>
<body>

    <!-- Header -->
    <header class="header">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-2">
                    <h2>Shopee Clone</h2> <!-- Ganti dengan logo gambar jika ada -->
                </div>
                <div class="col-md-6">
                    <input type="text" class="form-control" placeholder="Cari produk...">
                </div>
                <div class="col-md-4 text-end">
                    <a href="#" class="text-white me-3">Keranjang</a>
                    <a href="#" class="text-white">Login</a>
                </div>
            </div>
        </div>
    </header>

    <!-- Banner Promosi -->
    <section class="promo-banner">
        <h1>Diskon Hingga 70%!</h1>
        <p>Belanja produk favorit Anda dengan harga terbaik. Promo terbatas!</p>
        <img src="https://via.placeholder.com/800x300?text=Promo+Banner" alt="Banner Promosi" class="img-fluid">
    </section>

    <!-- Kategori Produk -->
    <section class="container category">
        <h2>Kategori Populer</h2>
        <div class="row">
            <div class="col-md-3">
                <div class="product-card">
                    <img src="https://via.placeholder.com/200x200?text=Elektronik" alt="Elektronik" class="img-fluid">
                    <h5>Elektronik</h5>
                    <p>Diskon hingga 50%</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="product-card">
                    <img src="https://via.placeholder.com/200x200?text=Fashion" alt="Fashion" class="img-fluid">
                    <h5>Fashion</h5>
                    <p>Stylish dan murah</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="product-card">
                    <img src="https://via.placeholder.com/200x200?text=Kesehatan" alt="Kesehatan" class="img-fluid">
                    <h5>Kesehatan</h5>
                    <p>Produk terbaik untuk Anda</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="product-card">
                    <img src="https://via.placeholder.com/200x200?text=Rumah+Tangga" alt="Rumah Tangga" class="img-fluid">
                    <h5>Rumah Tangga</h5>
                    <p>Segala kebutuhan rumah</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Shopee Clone. Semua hak dilindungi.</p>
        <p>Ikuti kami di: <a href="#" class="text-white">Facebook</a> | <a href="#" class="text-white">Instagram</a></p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
