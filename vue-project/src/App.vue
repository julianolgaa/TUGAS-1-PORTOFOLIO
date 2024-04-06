<template>
  <link rel="stylesheet" href="fontawesome-free-6.5.2-web/css/all.css">
<header>
    <h1>Julian Olga</h1>
    <h2>Teknik Informatika</h2>
    <h3>Portofolio</h3>
</header>

<nav> <br>
    <a href="#about">Tentang</a>
    <a href="#hobby">Hobi</a>
    <a href="#contact">Kontak</a>
</nav>

<section id="about" class="about-me">
    <h2>Tentang saya</h2>
    <p>Saya adalah seorang mahasiswa teknik informatika di universitas islam riau.

    </p>
    <div class="gallery">
        <img src="./assets/julianolga.jpg" alt="gbr 1">
    </div>
</section>

<section id="hobby" class="hobby">
    <h2>Hobiku</h2>
    <ul>
        <li>1: <a href="#">gaming</a></li>
        <li>2: <a href="#">coding</a></li>
        <li>3: <a href="#">olahraga</a></li>
    </ul>
</section>

<section id="contact" class="contact">
    <h2>Kontak</h2>
    <p>Anda bisa menghubungi saya melalui email di <a href="mailto:email@example.com">julianoolgano@gmail.com</a>.</p>
    <div class="social-icons">
       <a href="https://www.instagram.com/julianolgaa?igsh=MTVqdHAzYXM3dGpwZQ==" target="_blank"><i class="fa-brands fa-instagram"></i></a>
       <a href="https://youtube.com/@julianolga6560?si=QRWgVPutogTW3aPU" target="_blank"><i class="fa-brands fa-youtube"></i></a>
    </div>
</section>

<section class="testimonials">
    <h2>Address</h2>
    <p>Tempat tanggal lahir</p>
    <p>Peranap 29 juli 2004</p>
</section>

<footer>
    <p>Teknik Informatika &copy: 2024 | Julian Olga</p>
</footer>
</template>

<style>
body {
            font-family:  Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9ff;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 30px;
            margin: 40px;
            text-align: center;
        }
        nav {
            background-color: #333333;
            height: 100px;
            color: #fff;
            padding: 2px;
            margin: 20px;
            border-radius: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px;
            margin: 20px;
        }
        section {
            padding: 20px;
        }
        .about-me {
            text-align: center;
            justify-content: center;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .hobby {
          text-align: center;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .hobby ul {
           list-style-type: none;
           padding: 0;
        }
        .hobby li {
            margin-bottom: 10px;
        }
        .contact {
          text-align: center;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 20px;
        }
        .gallery {
          text-align: center;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;

        }
        .gallery img {
            width: 200px;
            margin: 10 px;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }
        .testimonials {
            text-align: center;
            background-color: #f9f9ff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .testimonials p {
            font-style: italic;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333333;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .social-icons {
            margin-top: 10px;
        }
        .social-icons a {
            display: inline block;
            width: 80px;
            height: 80px;
            background-color: #000000;
            color: #fff;
            border-radius: 50px;
            line-height: 10px;
            text-align: center;
            margin: 0 5px;
            text-decoration: none;
       }
</style>

