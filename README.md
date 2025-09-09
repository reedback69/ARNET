
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ARNET</title>
  <style>
    body {
      font-family: 'Comic Sans MS', Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
    }
    header {
      background: #333;
      color: blue;
      padding: 15px;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
    }
    .product {
      background: white;
      border: 1px solid #ddd;
      border-radius: 5px;
      margin: 10px;
      padding: 15px;
      width: 200px;
      text-align: center;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    .product img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .btn {
      display: inline-block;
      padding: 10px;
      background: #28a745;
      color: green;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
    }
    .btn:hover {
      background: #218838;
    }
  </style>
</head>
<body>
  <header>
    <h1>🛒 ARNET</h1>
    <p>Oryginalne koszulki pilkarskie!</p>
  </header>

  <div class="products">
    <div class="product">
      <img src="https://gfx.r-gol.com/media/res/products/198/195198/hj0865-493_1.webp" alt="Koszulka piłkarska">
      <h3>Koszulka piłkarska</h3>
      <p>Koszulka piłkarska PSG</p>
      <p><strong>199,99 zł</strong></p>
      <a href="#" class="btn">Dodaj do koszyka</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="Produkt 2">
      <h3>Produkt 2</h3>
      <p>Opis produktu 2</p>
      <p><strong>79,99 zł</strong></p>
      <a href="#" class="btn">Dodaj do koszyka</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="Produkt 3">
      <h3>Produkt 3</h3>
      <p>Opis produktu 3</p>
      <p><strong>99,99 zł</strong></p>
      <a href="#" class="btn">Dodaj do koszyka</a>
    </div>
  </div>
</body>
</html>
