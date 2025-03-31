<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Milena Shop</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom right, #fce3ec, #fff7f0);
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #ffcad4;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    header h1 {
      font-size: 3em;
      color: #4b2e2e;
    }
    .intro {
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
      text-align: center;
      font-size: 1.3em;
      color: #5a3e36;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
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
      font-size: 1em;
      color: #4b2e2e;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }
      .intro {
        font-size: 1.1em;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Milena Shop</h1>
  </header>  <section class="intro">
    <p>Hello, I sell handmade bracelets and delivery is available throughout Canada.</p>
  </section>  <section class="gallery">
    <img src="https://postimg.cc/fkgPVycv" alt="Bracelet 1">
    <img src="https://postimg.cc/6yvMT059" alt="Bracelet 2">
    <img src="https://postimg.cc/sQLJgBkQ" alt="Bracelet 3">
    <img src="https://postimg.cc/D4bPJvhC" alt="Bracelet 4">
  </section>  <section class="contact">
    <a href="https://www.instagram.com/milenas_shop?igsh=enhyZnljazhvYzRr" target="_blank">Contact on Instagram</a>
  </section>  <footer>
    <p>Follow us on Instagram: @milenas_shop</p>
  </footer>
</body>
</html>
