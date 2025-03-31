<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Milena Shop</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #e9d5ca;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    .intro {
      padding: 40px 20px;
      text-align: center;
      font-size: 1.2em;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .gallery div {
      background-color: #fff;
      border: 1px solid #ccc;
      height: 200px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #aaa;
    }
    .contact {
      text-align: center;
      margin: 40px 0;
    }
    .contact a {
      background-color: #c084fc;
      color: white;
      padding: 12px 24px;
      text-decoration: none;
      border-radius: 8px;
      font-size: 1.1em;
    }
    footer {
      background-color: #e9d5ca;
      text-align: center;
      padding: 10px;
      font-size: 0.9em;
    }
    @media (max-width: 600px) {
      .intro {
        font-size: 1em;
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
    <div>Image 1</div>
    <div>Image 2</div>
    <div>Image 3</div>
    <div>Image 4</div>
  </section>  <section class="contact">
    <a href="https://www.instagram.com/milenas_shop?igsh=enhyZnljazhvYzRr" target="_blank">Contact on Instagram</a>
  </section>  <footer>
    <p>Follow us on Instagram: @milenas_shop</p>
  </footer>
</body>
</html>
