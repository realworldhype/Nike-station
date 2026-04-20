index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nike Shoes</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <h1>Nike Shoes</h1>
            <nav>
                <ul>
                    <li><a href="#history">History</a></li>
                    <li><a href="#mens-shoes">Men's Shoes</a></li>
                    <li><a href="#womens-shoes">Women's Shoes</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="history">
        <div class="container">
            <h2>The History of Nike</h2>
            <p>
                Nike, Inc. was founded in 1964 by Bill Bowerman and Phil Knight. The company was originally named Blue Ribbon Sports and later rebranded as Nike, after the Greek goddess of victory. Nike has since become a global leader in athletic footwear, apparel, and equipment.
            </p>
            <p>
                Nike is known for its innovative designs and powerful marketing strategies. Over the years, it has signed endorsement deals with some of the biggest names in sports, including Michael Jordan, LeBron James, and Serena Williams.
            </p>
        </div>
    </section>

    <section id="mens-shoes">
        <div class="container">
            <h2>Men's Nike Shoes</h2>
            <div class="shoe-category">
                <div class="shoe-item">
                    <h3>Air Jordan 1</h3>
                    <p>The iconic Air Jordan 1, launched in 1985, continues to be a popular model among sneakerheads.</p>
                    <a href="#">Learn More</a>
                </div>
                <div class="shoe-item">
                    <h3>Air Max 90</h3>
                    <p>Known for its comfort and style, the Air Max 90 remains a favorite among athletes and casual wearers.</p>
                    <a href="#">Learn More</a>
                </div>
                <div class="shoe-item">
                    <h3>Flyknit Racer</h3>
                    <p>A lightweight, performance-driven shoe perfect for runners and sneaker enthusiasts alike.</p>
                    <a href="#">Learn More</a>
                </div>
            </div>
        </div>
    </section>

    <section id="womens-shoes">
        <div class="container">
            <h2>Women's Nike Shoes</h2>
            <div class="shoe-category">
                <div class="shoe-item">
                    <h3>Air Force 1</h3>
                    <p>The classic Air Force 1, first released in 1982, remains a staple in women's sneaker fashion.</p>
                    <a href="#">Learn More</a>
                </div>
                <div class="shoe-item">
                    <h3>Nike Free RN</h3>
                    <p>The Nike Free RN offers flexibility and lightweight comfort for women on the go.</p>
                    <a href="#">Learn More</a>
                </div>
                <div class="shoe-item">
                    <h3>Roshe One</h3>
                    <p>A minimalist design that provides the ultimate in comfort and casual style.</p>
                    <a href="#">Learn More</a>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2026 Nike, Inc. All Rights Reserved.</p>
            <p><a href="https://www.nike.com" target="_blank">Visit Nike Official Website</a></p>
        </div>
    </footer>
</body>
</html>
/* Resetting some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* General Body Style */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Header Style */
header {
    background-color: #111;
    color: white;
    padding: 20px 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

.navbar h1 {
    font-size: 2rem;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ff6600;
}

/* Section Container */
.container {
    width: 80%;
    margin: 0 auto;
    padding: 40px 0;
}

/* History Section */
#history {
    background-color: #fff;
    padding: 40px 0;
    text-align: center;
}

#history h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

#history p {
    font-size: 1.1rem;
    line-height: 1.8;
}

/* Shoe Section Styles */
.shoe-category {
    display: flex;
    justify-content: space-between;
    gap: 20px;
}

.shoe-item {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    text-align: center;
    flex: 1;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.shoe-item h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.shoe-item p {
    font-size: 1rem;
    margin-bottom: 20px;
}

.shoe-item a {
    display: inline-block;
    color: #111;
    font-weight: bold;
    text-decoration: none;
    padding: 10px 20px;
    background-color: #ff6600;
    color: white;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.shoe-item a:hover {
    background-color: #e55b00;
}

/* Footer Style */
footer {
    background-color: #111;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer p {
    font-size: 1rem;
}

footer a {
    color: #ff6600;
    text-decoration: none;
    font-weight: bold;
}

footer a:hover {
    color: #e55b00;
}
