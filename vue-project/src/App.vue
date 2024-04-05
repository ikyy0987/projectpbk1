<template>
  <link rel="stylesheet" href="https:cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.win.css">
<header>
    <h1>Zacky alvianza</h1>
    <h2>Teknik Informatika</h2>
    <h3>Portofolio</h3>
</header>

<nav>
    <a href="#about">Tentang</a>
    <a href="#hobby">Hobi</a>
    <a href="#contact">Kontak</a>
</nav>

<section id="about" class="about-me">
    <h2>Tentang saya</h2>
    <p>Saya adalah seorang mahasiswa aktif di universitas islam riau.

    </p>
    <div class="gallery">
        <img src="./assets/profile_zacky.jpg" alt="gmbr 1">
    </div>
</section>

<section id="hobby" class="hobby">
    <h2>My Hobbies</h2>
    <ul>
        <li>1: <a href="#">desain grafis</a></li>
        <li>2: <a href="#">menggambar</a></li>
        <li>3: <a href="#">membaca buku</a></li>
    </ul>
</section>

<section id="contact" class="contact">
    <h2>Kontak</h2>
    <p>Anda bisa menghubungi saya melalui email di <a href="mailto:email@example.com">zackyalvianza65@gmail.com</a>.</p>
    <div class="social-icons">
       <a href="https://www.instagram.com/zackyu89/?igsh=MTNobGp3eGN1OWd6dQ%3D%3D" target="_blank"><i class="fa-brands fa-instagram"></i></a>
    </div>
</section>

<section class="testimonials">
    <h2>Address</h2>
    <p>Tempat tanggal lahir</p>
    <p>Duri 08 oktober 2004</p>
</section>

<footer>
    <p>Teknik Informatika &copy: 2024 | Zacky alvianza</p>
</footer>
</template>

<style>
body {
            font-family:  Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9ff9;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 2opx;
            text-align: center;
        }
        nav {
            background-color: #333333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px;
            margin: 5px;
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
        }
        .hobby il {
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
            border-radius: 0 0 5px;
            box-shadow: 20px;
        }
        .testimonials {
            font-style: italic;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333333;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            button: 0;
            width: 100px;
        }
        .social icons {
            margin-top: 10px;
        }
        .social-icons a {
            display: inline block;
            width: 30px;
            height: 30px;
            background-color: #000000;
            color: #fff;
            border-radius: 50px;
            line-height: 30px;
            text-align: center;
            margin: 0 5px;
            text-decoration: none;
        }
</style>