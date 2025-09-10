
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Usman is a Professional Amazon FBA Specialist">
    <title>Usman - Amazon FBA Specialist</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>Usman FBA Specialist</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Welcome to Professional Amazon FBA Services</h2>
        <p>Your trusted partner for Amazon product research, PPC, and business optimization.</p>
        <a href="#services" class="cta-button">Explore Services</a>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>With years of experience in Amazon FBA, Usman has helped multiple businesses succeed on Amazon. From product research to listing optimization, I handle it all to make your Amazon store thrive.</p>
        <p>Learn more about my experience and connect on LinkedIn:</p>
        <a href="https://www.linkedin.com/in/usman-amazon-fba-specialist/" target="_blank" class="linkedin-link">Visit LinkedIn Profile</a>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-list">
            <div class="service">
                <h3>Product Research & Sourcing</h3>
                <p>We help you find the best products to sell on Amazon with in-depth research and analysis.</p>
            </div>
            <div class="service">
                <h3>Listing Creation & Optimization</h3>
                <p>We optimize your product listings for better visibility and conversions on Amazon.</p>
            </div>
            <div class="service">
                <h3>Amazon PPC Campaigns</h3>
                <p>We create and manage effective PPC campaigns to increase your sales and ROI on Amazon.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form action="mailto:your-email@example.com" method="POST" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Usman - Amazon FBA Specialist</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>[styles.css](https://github.com/user-attachments/files/22263034/styles.css)

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

header {
    background-color: #2c3e50;
    color: white;
    padding: 1rem;
}

header .logo h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    background-color: #2980b9;
    color: white;
    padding: 5rem 0;
    text-align: center;
}

.cta-button {
    background-color: #27ae60;
    color: white;
    padding: 0.5rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
}

.cta-button:hover {
    background-color: #2ecc71;
}

.about, .services, .contact {
    padding: 3rem;
    text-align: center;
}

.services {
    background-color: #ecf0f1;
}

.service-list {
    display: flex;
    justify-content: space-around;
}

.service {
    background-color: white;
    padding: 2rem;
    margin: 1rem;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    flex: 1;
    max-width: 30%;
}

.contact form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

.contact form input,
.contact form textarea {
    padding: 1rem;
    margin-bottom: 1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact form button {
    padding: 1rem;
    background-color: #2980b9;
    color: white;
    border: none;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #2c3e50;
    color: white;
}

[script.js](https://github.com/user-attachments/files/22263036/script.js)
