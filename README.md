<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Relaxation Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>GET IN RELAX TODAY</h1>
            <button class="join-button">JOIN NOW</button>
            <p>25% Discount on first month!</p>
        </section>
    </main>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-image: url('spa-background.jpg');
    background-size: cover;
    color: white;
    text-align: center;
}

header {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 10px 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: black;
    font-weight: bold;
}

.hero {
    margin-top: 20%;
}

h1 {
    font-size: 48px;
}

.join-button {
    background-color: black;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

p {
    font-size: 18px;
    margin-top: 10px;
}

