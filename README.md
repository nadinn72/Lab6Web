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
        
        /* Image Circle */
        .image-circle {
            border-radius: 50%;
            margin-bottom: 15px;
        }
        
        /* Box Styling */
        .feature-box {
            text-align: center;
            padding: 20px;
            margin-bottom: 30px;
        }
        
        .feature-box h3 {
            margin: 15px 0;
            font-size: 1.5rem;
        }
        
        /* Spacing */
        .content-section {
            padding: 40px 0;
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

    <!-- Main Content -->
    <div class="container content-section">
        <!-- Three Feature Boxes -->
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
    
    <!-- Bootstrap JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## Hasil
<img width="704" height="250" alt="image" src="https://github.com/user-attachments/assets/d8a34493-cf27-41c9-afae-bc0e468d7078" />

# LANGKAH 5: Menambahkan Grid Layout (Main + Sidebar)
**Tambahkan layout 2 kolom: konten utama (9 kolom) dan sidebar (3 kolom).**
**Tambahkan kode ini setelah feature boxes dan sebelum tag penutup </div> dari container:**

```
<div class="row">
            <!-- Main Section -->
            <div class="col-lg-9">
                <h2>Main Content Area</h2>
                <p>Ini adalah area konten utama yang mengambil 9 kolom dari 12 kolom grid.</p>
            </div>

            <!-- Sidebar -->
            <div class="col-lg-3">
                <aside>
                    <h3>Sidebar</h3>
                    <p>Ini adalah sidebar yang mengambil 3 kolom dari 12 kolom grid.</p>
                </aside>
            </div>
        </div>
```
## Hasil

<img width="700" height="250" alt="image" src="https://github.com/user-attachments/assets/1b8b73c2-1c9e-4cbe-b323-d5d2706478dd" />

# LANGKAH 6: Menambahkan Article dengan Gambar Float
**Tambahkan 2 artikel dengan gambar float left dan right.**
**Ganti konten di dalam <div class="col-lg-9"> dengan:**

## Code

```
<div class="col-lg-9">
                <hr class="my-4">

                <!-- Article 1 -->
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

                <!-- Article 2 -->
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

## Hasil
<img width="700" height="250" alt="image" src="https://github.com/user-attachments/assets/a986179f-2ba6-45ea-8f82-2a16f4fb21b1" />

