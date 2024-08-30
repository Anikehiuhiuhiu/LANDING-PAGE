# LANDING-PAGE
A landing page is an ideal web development project for beginners.
//Start with a simple HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Content will go here -->
</body>
</html>
<header>
    <div class="container">
        <h1>My Landing Page</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </div>
</header>
//Create sections for different content areas

<section id="home">
    <div class="container">
        <h2>Welcome to My Landing Page</h2>
        <p>This is a brief introduction to what you offer.</p>
        <a href="#contact" class="cta-button">Contact Us</a>
    </div>
</section>

<section id="about">
    <div class="container">
        <h2>About Us</h2>
        <p>Details about your product or service.</p>
    </div>
</section>

<section id="contact">
    <div class="container">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <button type="submit">Send</button>
        </form>
    </div>
</section>
<footer>
    <div class="container">
        <p>&copy; 2024 My Landing Page. All rights reserved.</p>
    </div>
</footer>
//Use CSS to style your header, sections, and footer.
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

header h1 {
    margin: 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px 0;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007BFF;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
@media (max-width: 768px) {
    nav ul li {
        display: block;
        margin: 10px 0;
    }
}
