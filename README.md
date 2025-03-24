<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин одягу</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 24px;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background: white;
            padding: 15px;
            margin: 10px;
            border-radius: 5px;
            text-align: center;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 30%;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        Магазин одягу
    </header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Футболка">
            <h3>Футболка</h3>
            <p>Ціна: 500 грн</p>
            <a href="#" class="button">Купити</a>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Джинси">
            <h3>Джинси</h3>
            <p>Ціна: 1200 грн</p>
            <a href="#" class="button">Купити</a>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Куртка">
            <h3>Куртка</h3>
            <p>Ціна: 2500 грн</p>
            <a href="#" class="button">Купити</a>
        </div>
    </div>
</body>
</html>
