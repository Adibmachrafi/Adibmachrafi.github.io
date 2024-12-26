<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adib's Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Adib's Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Adib's Store</h2>
        <p>Your one-stop shop for quality clothing!</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="product1.jpg" alt="Product 1">
                <h3>Product 1</h3>
                <p>$20.00</p>
                <button onclick="addToCart('Product 1', 20)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Product 2">
                <h3>Product 2</h3>
                <p>$30.00</p>
                <button onclick="addToCart('Product 2', 30)">Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="cart">
        <h2>Shopping Cart</h2>
        <ul id="cart-items"></ul>
        <p>Total: $<span id="total">0</span></p>
    </section>

    <footer>
        <p>&copy; 2024 Adib's Store</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>