index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nike Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <div class="logo">NIKE</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Men</a></li>
                <li><a href="#">Women</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Just Do It.</h1>
        <p>Discover the latest Nike collections</p>
        <button>Shop Now</button>
    </section>

    <section class="products">
        <h2>Featured Products</h2>

        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Shoe">
                <h3>Nike Air Max</h3>
                <p>$120</p>
            </div>

            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Shoe">
                <h3>Nike Revolution</h3>
                <p>$90</p>
            </div>

            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Shoe">
                <h3>Nike ZoomX</h3>
                <p>$150</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2026 Nike Inspired Website</p>
    </footer>

</body>
</html>
style.ccs
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f5f5f5;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: black;
    color: white;
    padding: 15px 40px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    letter-spacing: 2px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: 500;
}

nav a:hover {
    color: #ccc;
}

/* Hero */
.hero {
    height: 80vh;
    background: url('https://images.unsplash.com/photo-1542291026-7eec264c27ff') no-repeat center/cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero h1 {
    font-size: 60px;
    margin-bottom: 10px;
}

.hero button {
    padding: 12px 25px;
    border: none;
    background: white;
    color: black;
    font-weight: bold;
    cursor: pointer;
    margin-top: 15px;
}

.hero button:hover {
    background: #ddd;
}

/* Products */
.products {
    padding: 40px;
    text-align: center;
}

.product-grid {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-top: 20px;
    flex-wrap: wrap;
}

.product {
    background: white;
    padding: 20px;
    border-radius: 10px;
    width: 200px;
}

.product img {
    width: 100%;
}

footer {
    text-align: center;
    padding: 20px;
    background: black;
    color: white;
    margin-top: 40px;
}
