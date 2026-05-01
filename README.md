<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>موقف السلام</title>

<style>
  body {
    margin: 0;
    font-family: Arial;
    background: #0f172a;
    color: white;
    text-align: center;
  }

  header {
    background: #1e293b;
    padding: 20px;
  }

  h1 {
    margin: 0;
    color: #38bdf8;
  }

  p {
    color: #cbd5f5;
  }

  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
    padding: 20px;
  }

  .gallery img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 12px;
    transition: 0.3s;
  }

  .gallery img:hover {
    transform: scale(1.05);
  }

  .location {
    padding: 20px;
  }

  iframe {
    width: 100%;
    height: 300px;
    border: 0;
    border-radius: 12px;
  }

  .btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 15px;
    background: #38bdf8;
    color: black;
    text-decoration: none;
    border-radius: 10px;
    font-weight: bold;
  }

  footer {
    padding: 15px;
    background: #1e293b;
  }
</style>
</head>

<body>

<!-- HEADER -->
<header>
  <h1>🚏 موقف السلام</h1>
  <p>عرض صور وخريطة الموقف</p>
</header>

<!-- GALLERY -->
<section class="gallery">

  <!-- غير الصور دي بصورك -->
  <img src="images/1.jpg" alt="صورة 1">
  <img src="images/2.jpg" alt="صورة 2">
  <img src="images/3.jpg" alt="صورة 3">
  <img src="images/4.jpg" alt="صورة 4">

</section>

<!-- LOCATION -->
<section class="location">
  <h2>📍 موقع الموقف</h2>

  <iframe
    src="https://www.google.com/maps?q=موقف+السلام&output=embed"
    loading="lazy">
  </iframe>

  <br>

  <a 
    href="https://www.google.com/maps?q=موقف+السلام"
    target="_blank"
    class="btn">
    فتح في Google Maps
  </a>
</section>

<!-- FOOTER -->
<footer>
  <p>© جميع الحقوق محفوظة - موقف السلام</p>
</footer>

</body>
</html>
