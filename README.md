<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Food Delivery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #555;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0 20px;
        }
        section {
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        .food-item {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            margin-bottom: 10px;
            background-color: #fff;
        }
        .food-item img {
            max-width: 100px;
            max-height: 100px;
            margin-right: 10px;
            float: left;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Online Food Delivery</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Menu</a>
        <a href="#">Order</a>
        <a href="#">Contact</a>
    </nav>
    <section>
        <div class="container">
            <h2>Today's Special</h2>
            <div class="food-item">
                <h3>Burger</h3>
                <p>A delicious burger with juicy patty and fresh veggies.</p>
                <p>Price: $5.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="food-item">
                <h3>Pizza</h3>
                <p>A mouth-watering pizza topped with cheese and pepperoni.</p>
                <p>Price: $8.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Food Delivery</p>
    </footer>
</body>
</html>
