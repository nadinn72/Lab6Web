# Lab6Web

# LANGKAH 1: Menambahkan Header
**Tambahkan section header dengan styling.**

## Code
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana dengan Bootstrap</title>
    
    <!-- Bootstrap CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Custom CSS -->
    <style>
        /* Header Styling */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px 0;
        }
        
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
    </style>
</head>
<body>
    
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Layout Sederhana</h1>
        </div>
    </header>
    
    <!-- Bootstrap JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## Hasil
<img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/0ed8eda2-1c70-4acf-996e-d74fede14b93" />

# LANGKAH 2: Menambahkan Navigation Bar
**Tambahkan navbar responsive dengan Bootstrap.**

## Code
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana dengan Bootstrap</title>
    
    <!-- Bootstrap CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Custom CSS -->
    <style>
        /* Header Styling */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px 0;
        }
        
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        
        /* Navigation Styling */
        .navbar {
            background-color: #343a40;
            margin-bottom: 0;
        }
        
        .navbar-nav .nav-link {
            color: #fff !important;
            padding: 15px 20px !important;
        }
        
        .navbar-nav .nav-link:hover,
        .navbar-nav .nav-link.active {
            background-color: #007bff;
        }
    </style>
</head>
<body>
    
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Layout Sederhana</h1>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="home.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="artikel.html">Artikel</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="kontak.html">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    
    <!-- Bootstrap JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## Hasil
<img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/aeea489f-fa7b-4a73-8fee-35a13168da38" />


# LANGKAH 3: Menambahkan Hero Section
**Tambahkan hero section dengan call-to-action button.**

## Code
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana dengan Bootstrap</title>
    
    <!-- Bootstrap CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Custom CSS -->
    <style>
        /* Header Styling */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px 0;
        }
        
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        
        /* Navigation Styling */
        .navbar {
            background-color: #343a40;
            margin-bottom: 0;
        }
        
        .navbar-nav .nav-link {
            color: #fff !important;
            padding: 15px 20px !important;
        }
        
        .navbar-nav .nav-link:hover,
        .navbar-nav .nav-link.active {
            background-color: #007bff;
        }
        
        /* Hero Section */
        #hero {
            background: linear-gradient(135deg, #e0c3fc 0%, #8ec5fc 100%);
            padding: 60px 0;
            text-align: center;
            color: #333;
        }
        
        #hero h1 {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 20px;
        }
        
        #hero p {
            font-size: 1.1rem;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
    </style>
</head>
<body>
    
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Layout Sederhana</h1>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="home.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="artikel.html">Artikel</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="kontak.html">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero">
        <div class="container">
            <h1>Hello World!</h1>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                pretium ac.
            </p>
            <a href="home.html" class="btn btn-primary btn-lg">Learn more &raquo;</a>
        </div>
    </section>
    
    <!-- Bootstrap JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## Hasil

<img width="700" height="250" alt="image" src="https://github.com/user-attachments/assets/cb75b35a-b559-4ef2-9fc2-27db438308ff" />

# LANGKAH 4: Menambahkan 3 Feature Boxes
**Tambahkan 3 kolom dengan gambar, heading, dan button.**

## Code
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana dengan Bootstrap</title>

    <!--  Menghubungkan Bootstrap 5 lewat CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    <!--  CSS Kustom untuk mempercantik tampilan -->
    <style>
        /*  Warna latar belakang seluruh halaman */
        body {
            background-color: #e9ecef;
        }

        /*  Wrapper utama untuk membatasi lebar konten */
        #wrapper {
            max-width: 1200px;
            margin: 20px auto;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 0 20px;
        }

        /*  Responsif: padding lebih kecil di layar kecil */
        @media (max-width: 768px) {
            #wrapper {
                margin: 10px;
                padding: 0 15px;
            }
        }

        /*  Header dengan gradien ungu-biru */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px 0;
            margin-bottom: 0;
        }

        header h1 {
            margin: 0;
            font-size: 2rem;
        }

        /*  Navbar (menu) berwarna gelap */
        .navbar {
            background-color: #343a40;
            margin-bottom: 0;
        }

        /*  Tautan menu berwarna putih */
        .navbar-nav .nav-link {
            color: #fff !important;
            padding: 15px 20px !important;
        }

        /*  Efek hover dan aktif untuk menu */
        .navbar-nav .nav-link:hover,
        .navbar-nav .nav-link.active {
            background-color: #007bff;
        }

        /*  Hero section (bagian pembuka utama) */
        #hero {
            background: linear-gradient(135deg, #e0c3fc 0%, #8ec5fc 100%);
            padding: 60px 0;
            text-align: center;
            color: #333;
        }

        #hero h1 {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 20px;
        }

        #hero p {
            font-size: 1.1rem;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        /*  Gambar bulat pada fitur */
        .image-circle {
            border-radius: 50%;
            margin-bottom: 15px;
        }

        /*  Kotak fitur (tiga kotak di bawah hero) */
        .feature-box {
            text-align: center;
            padding: 20px;
            margin-bottom: 30px;
        }

        .feature-box h3 {
            margin: 15px 0;
            font-size: 1.5rem;
        }

        
    </style>
</head>
<body>
    <!--  Wrapper utama -->
    <div id="wrapper">

        <!--  Header -->
        <header>
            <div class="container">
                <h1>Layout Sederhana</h1>
            </div>
        </header>

        <!--  Navigasi -->
        <nav class="navbar navbar-expand-lg navbar-dark">
            <div class="container">
                <!-- Tombol toggle untuk layar kecil -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <!-- Daftar menu -->
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" href="home.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="artikel.html">Artikel</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="kontak.html">Kontak</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <!--  Hero Section -->
        <section id="hero">
            <div class="container">
                <h1>Hello World!</h1>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                    elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                    vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                    pretium ac.
                </p>
                <a href="home.html" class="btn btn-primary btn-lg">Learn more &raquo;</a>
            </div>
        </section>

        <!--  Bagian Konten Utama -->
        <div class="container content-section">
            <div class="row">
                <!--  Kolom kiri (konten utama) -->
                <div class="col-lg-9">
                    <!--  Tiga Kotak Fitur -->
                    <div class="row">
                        <div class="col-md-4">
                            <div class="feature-box">
                                <img src="https://dummyimage.com/120/db7d25/fff.png" alt="Feature 1" class="image-circle">
                                <h3>Heading</h3>
                                <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="feature-box">
                                <img src="https://dummyimage.com/120/3e73e6/fff.png" alt="Feature 2" class="image-circle">
                                <h3>Heading</h3>
                                <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="feature-box">
                                <img src="https://dummyimage.com/120/71e6d4/fff.png" alt="Feature 3" class="image-circle">
                                <h3>Heading</h3>
                                <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
    <!-- Bootstrap JS Bundle (termasuk Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## Hasil
<img width="700" height="250" alt="image" src="https://github.com/user-attachments/assets/dfda21e1-25e8-4fcb-aaf0-e0762ca44b46" />


# LANGKAH 5: Menambahkan Article dengan Gambar Float
**Tambahkan 2 artikel dengan gambar float left dan right.**
**Ganti konten di dalam <div class="col-lg-9"> dengan:**

## Code

```
                    <hr class="my-4">

                    <!--  Artikel Pertama -->
                    <article class="article-section">
                        <h2>First featurette heading.</h2>
                        <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="Article 1" class="left-img rounded">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                            elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                            vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                            pretium ac.
                        </p>
                        <div class="clearfix"></div>
                    </article>

                    <hr class="my-4">

                    <!-- Artikel Kedua -->
                    <article class="article-section">
                        <h2>Second featurette heading.</h2>
                        <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="Article 2" class="right-img rounded">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                            elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                            vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                            pretium ac.
                        </p>
                        <div class="clearfix"></div>
                    </article>
                </div>
```
## Tambahkan Css
```
/*  Artikel utama */
        .article-section {
            margin: 40px 0;
        }

        /*  Gambar di kiri */
        .left-img {
            float: left;
            margin: 0 20px 20px 0;
        }

        /*  Gambar di kanan */
        .right-img {
            float: right;
            margin: 0 0 20px 20px;
        }
```

## Hasil
<img width="700" height="255" alt="image" src="https://github.com/user-attachments/assets/90c2e3e5-ff7c-4e66-98d9-e763a746748b" />

# LANGKAH 6: Menambahkan Sidebar Widgets
**Tambahkan widget di sidebar dengan link list dan text widget.**

## Code
```
<!--  Sidebar Kanan -->
                <div class="col-lg-3">
                    <aside>
                        <!-- Widget daftar tautan -->
                        <div class="widget-box">
                            <h3 class="title">Widget Header</h3>
                            <ul>
                                <li><a href="#">Widget Link</a></li>
                                <li><a href="#">Widget Link</a></li>
                                <li><a href="#">Widget Link</a></li>
                                <li><a href="#">Widget Link</a></li>
                                <li><a href="#">Widget Link</a></li>
                            </ul>
                        </div>

                        <!-- Widget teks -->
                        <div class="widget-box">
                            <h3 class="title">Widget Text</h3>
                            <div class="widget-content">
                                <p>
                                    Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt
                                    arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
                                    pharetra est nunc, nec pretium nunc pretium ac.
                                </p>
                            </div>
                        </div>
                    </aside>
```

## Css
```
 /*  Sidebar (kotak tambahan di sisi kanan) */
        .widget-box {
            background-color: #f8f9fa;
            padding: 0;
            margin-bottom: 20px;
            border-radius: 5px;
            border: 1px solid #dee2e6;
            overflow: hidden;
        }

        .widget-box h3 {
            font-size: 1.3rem;
            margin: 0;
            padding: 15px 20px;
            color: white;
            background-color: #4534db9b;
            font-weight: 500;
        }

        .widget-box .widget-content {
            padding: 20px;
        }

        .widget-box ul {
            list-style: none;
            padding: 0;
        }
        .widget-box ul li {
            padding: 8px 0;
            border-bottom: 1px solid #dee2e6;
        }

        .widget-box ul li:last-child {
            border-bottom: none;
        }

        .widget-box ul li a {
            text-decoration: none;
            color: #4000ffa3;
        }

        .widget-box ul li a:hover {
            color: #4000ffa3;
        }
```

## Hasil
<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/792b8e9f-df63-4aeb-a77c-bfd7a0b0028e" />

# LANGKAH 7: Menambahkan Footer
**Tambahkan footer di bagian bawah halaman.**
**Tambahkan sebelum tag <script> (setelah penutup container):**

## Code
```
<!-- Footer -->
        <footer>
            <div class="container">
                <p>&copy; 2025 - Universitas Pelita Bangsa</p>
            </div>
        </footer>
    </div>
```
## Css
```
/*  Footer (bagian bawah halaman) */
        footer {
            background-color: #a389da;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 0;
        }

        footer p {
            margin: 0;
        }
```

## Hasil
<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/4933ed87-9238-4a46-9988-0a25eb45aab9" />

# LANGKAH 8: Menambahkan Padding Kiri/Kanan
**Tambahkan spacing di sisi kanan dan kiri agar konten tidak mepet.**


## Code
 ```
        /*  Spasi bagian konten */
        .content-section {
            padding: 40px 20px;
        }

        /*  Padding tambahan hero */
        #hero {
            padding: 60px 20px;
        }        /*  Spasi bagian konten */
        .content-section {
            padding: 40px 20px;
        }

        /*  Padding tambahan hero */
        #hero {
            padding: 60px 20px;
        }
```

## Hasil
<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/522537a7-1c97-48d1-9a09-516a42c3793e" />
