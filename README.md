<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TaomGo</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      text-align: center;
    }
    header {
      background-color: #00cc66;
      color: white;
      padding: 20px 0;
    }
    .logo {
      font-size: 32px;
      font-weight: bold;
    }
    .container {
      padding: 30px;
    }
    .btn {
      padding: 15px 30px;
      font-size: 18px;
      background-color: #00cc66;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .btn:hover {
      background-color: #00994d;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">TaomGo</div>
    <div>Tez, qulay va ishonchli yetkazib berish!</div>
  </header>

  <div class="container">
    <p>Taom buyurtma berish uchun quyidagi tugmani bosing:</p>
    <button class="btn" onclick="alert('Bu yerda buyurtma funksiyasi bo‘ladi!')">Buyurtma berish</button>
  </div>
</body>
</html>
