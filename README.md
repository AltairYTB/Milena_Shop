<!DOCTYPE

html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Milena Shop</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #fce3ec, #fff7f0);
      color: #333;
    }
    header {
      background: #ffcad4;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    header h1 {
      font-size: 3em;
      color: #4b2e2e;
    }
    .intro {
      max-width: 800px;
      margin: 30px auto;
      padding: 0 20px;
      font-size: 1.3em;
      text-align: center;
      color: #5a3e36;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      max-width: 1200px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    .contact {
      text-align: center;
      margin: 60px 0;
    }
    .contact a {
      background: #ec4899;
      color: white;
      padding: 16px 32px;
      text-decoration: none;
      border-radius: 30px;
      font-size: 1.2em;
      transition: background 0.3s;
    }
    .contact a:hover {
      background: #db2777;
    }
    footer {
      background: #ffcad4;
      text-align: center;
      padding: 20px;
      color: #4b2e2e;
    }
  </style>
</head>
<body>

  <header>
    <h1>Milena Shop</h1>
  </header>

  <section class="intro">
    <p>Hello, I sell handmade bracelets and delivery is available throughout Canada.</p>
  </section>

  <section class="gallery">
    <img src="https://i.postimg.cc/fkgPVycv/image.png" alt="Bracelet 1">
    <img src="https://i.postimg.cc/6yvMT059/image.png" alt="Bracelet 2">
    <img src="https://i.postimg.cc/sQLJgBkQ/image.png" alt="Bracelet 3">
    <img src="https://i.postimg.cc/D4bPJvhC/image.png" alt="Bracelet 4">
  </section>

  <section class="contact">
    <a href="https://www.instagram.com/milenas_shop?igsh=enhyZnljazhvYzRr" target="_blank">Contact on Instagram</a>
  </section>

  <footer>
    <p>Follow us on Instagram: @milenas_shop</p>
  </footer>

</body>
</html>
