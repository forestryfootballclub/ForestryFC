
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Forestry | Football Club</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }

    header {
      background: #004300;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    section {
      padding: 30px;
      max-width: 1000px;
      margin: auto;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
    }

    a.button {
      display: inline-block;
      margin-top: 20px;
      background: #006400;
      color: #fff;
      padding: 10px 20px;
      border-radius: 8px;
      text-decoration: none;
    }

    a.button:hover {
      background: #004300;
    }

    footer {
      background: #cc9933;
      color: #fff;
      text-align: center;
      padding: 15px;
    }

    a {
      color: #006400;
      text-decoration: none;
    }

    /* โลโก้ตรงกลาง */
    .logo {
      width: 200px;
      height: auto;
      margin: 20px auto 0;
      display: block;
    }

    /* ราคา 299 เด่น กระพริบ */
    .price-tag {
      font-size: 48px;
      font-weight: bold;
      color: #d10000;
      text-align: center;
      margin: 20px 0;
      animation: blink 1s infinite;
    }

    @keyframes blink {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.4; }
    }
  </style>
</head>
<body>

  <!-- โลโก้ -->
  <img src="forestry football club.png" style="width: 200px; height: auto; margin: 20px auto 0; display: block;" />

  <header>
    <h1>Forestry</h1>
    <p>footballclub</p>
  </header>

  <!-- ราคา -->
  <div class="price-tag">Price 299 Bath</div>

  <section>
    <h2>Products</h2>
    <div class="gallery">
      <img src="1st.jpg">
      <img src="2nd.jpg">
      <img src="Size.png">
      <img src="Texture.jpg">
    </div>
    <a href="order.html" class="button">Order</a>
  </section>

  <section>
    <h2>Contact</h2>
    <p>Instagram: <a href="https://www.instagram.com/forestry.footballclub" target="_blank">@forestry.footballclub</a></p>
  </section>

  <footer>
    &copy; 2025 forestry. All rights reserved.
  </footer>
</body>
</html>
