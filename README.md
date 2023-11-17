# Trithon
this is my 1st repositoty
Author Patha 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shareride</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 2rem;
}

section {
    margin-bottom: 2rem;
}

footer {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h1>Welcome to Shareride</h1>
            <p>Shareride is a website for booking shared rides to work or anywhere else.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Instant Booking</li>
                <li>Track your driver's location</li>
                <li>One-tap Payment Integration</li>
                <li>Safe & Reliable</li>
            </ul>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>We are a team of dedicated professionals working together to provide the best possible service for our customers. We believe in building long-lasting relationships with our clients.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <br>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <br>
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2022 Shareride. All rights reserved.</p>
    </footer>
</body>
</html>
