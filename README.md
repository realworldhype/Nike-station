idex.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Nike - The Swoosh Story</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/Logo_Nike.svg" alt="Nike Logo">
            </div>
            <ul>
                <li><a href="#history">History</a></li>
                <li><a href="#shoes">Shoes</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <div class="hero-content">
            <h1>Welcome to Nike</h1>
            <p>Innovation and Performance since 1964</p>
        </div>
    </section>

    <section id="history" class="section">
        <h2>The History of Nike</h2>
        <p>Nike was founded by Bill Bowerman and Phil Knight in 1964. Originally known as Blue Ribbon Sports, the company rebranded to Nike in 1971...</p>
        <p>From track shoes to basketball sneakers, Nike revolutionized sportswear with groundbreaking technology like Air Max, Flyknit, and the Swoosh design.</p>
    </section>

    <section id="shoes" class="section">
        <h2>Popular Nike Shoes</h2>
        <div class="shoe-list">
            <div class="shoe">
                <img src="https://static.nike.com/a/images/t_PDP_1280_v1/f_auto,q_auto:eco/c9b1b8d5-07c3-4737-9251-b18f9b8b2786/air-max-90-mens-shoes-qzrZc9.jpg" alt="Nike Air Max 90">
                <h3>Air Max 90</h3>
                <p>The Air Max 90 is a true icon of sneaker culture.</p>
            </div>
            <div class="shoe">
                <img src="https://static.nike.com/a/images/t_PDP_1280_v1/f_auto,q_auto:eco/7edc27a5-67cf-41fe-b1fc-432b3a63f7f2/air-force-1-07-mens-shoes-LKbxHv.jpg" alt="Nike Air Force 1">
                <h3>Air Force 1</h3>
                <p>The classic Air Force 1, a staple of streetwear and performance.</p>
            </div>
            <div class="shoe">
                <img src="https://static.nike.com/a/images/t_PDP_1280_v1/f_auto,q_auto:eco/d36f22a2-263d-4a1c-bf61-8fe11abf9da3/zoomx-invincible-run-flyknit-road-running-shoes-7R5G8W.jpg" alt="Nike ZoomX">
                <h3>ZoomX Invincible</h3>
                <p>Engineered for comfort and support with responsive ZoomX foam.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <form id="contactForm">
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Nike, Inc. All Rights Reserved.</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>
style.css
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: white;
    color: #333;
}

header {
    background-color: #111;
    color: white;
    padding: 10px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

nav .logo img {
    width: 80px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

section {
    padding: 60px 20px;
}

#hero {
    background: url('https://images.unsplash.com/photo-1614574525507-dfcf9a8de5ed?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjA0NHwwfDF8c2VhY2h8Nnx8bm94JTIwYXBwbGUlMjBmb3JtJTIwZXNjYXBlfGVufDB8fHx8fDE2NDc2MDY0NDA&ixlib=rb-1.2.1&q=80&w=1920') no-repeat center center/cover;
    color: white;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero-content h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.hero-content p {
    font-size: 1.2rem;
}

.section {
    text-align: center;
}

.shoe-list {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 40px;
}

.shoe {
    max-width: 300px;
    text-align: center;
}

.shoe img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

.shoe h3 {
    margin-top: 10px;
    font-size: 1.2rem;
}

footer {
    text-align: center;
    background-color: #111;
    color: white;
    padding: 20px 0;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form input, form textarea {
    width: 100%;
    max-width: 400px;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    padding: 10px 20px;
    background-color: #111;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background-color: #333;
}
app.js
document.getElementById('contactForm').addEventListener('submit', function(event) {
    event.preventDefault();
    alert("Your message has been sent!");
});
