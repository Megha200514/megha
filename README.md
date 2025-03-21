# megha<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Creative Corner</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <div class="container">
            <h1>Welcome to Creative Corner</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Unleash Your Creativity</h2>
            <p>Explore, Create, and Inspire</p>
            <a href="#gallery" class="cta-button">Discover Our Work</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Creative Corner is a platform designed for artists, designers, and creators to showcase their work, share
                ideas, and find inspiration. Join our creative community!</p>
        </div>
    </section>

    <section id="gallery">
        <div class="container">
            <h2>Our Gallery</h2>
            <div class="gallery-grid">
                <div class="gallery-item"><img src="https://via.placeholder.com/300" alt="Art 1"></div>
                <div class="gallery-item"><img src="https://via.placeholder.com/300" alt="Art 2"></div>
                <div class="gallery-item"><img src="https://via.placeholder.com/300" alt="Art 3"></div>
                <div class="gallery-item"><img src="https://via.placeholder.com/300" alt="Art 4"></div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>We’d love to hear from you! Reach out to us with any inquiries or collaboration ideas.</p>
            <form id="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit" class="cta-button">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Creative Corner. All Rights Reserved.</p>
        </div>
    </footer>

    <script src="scripts.js"></script>
</body>

</html>
