# Local-Business-Sagar
A website for a local business in Sagar
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marketing Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>My Company</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Welcome to Our Marketing Website</h2>
            <p>Your success is our priority. Discover our features and how we can help you grow.</p>
            <a href="#features" class="btn">Learn More</a>
        </div>
    </section>

    <section id="features" class="features">
        <div class="container">
            <h2>Features</h2>
            <div class="feature-item">
                <h3>Feature One</h3>
                <p>Description of feature one.</p>
            </div>
            <div class="feature-item">
                <h3>Feature Two</h3>
                <p>Description of feature two.</p>
            </div>
            <div class="feature-item">
                <h3>Feature Three</h3>
                <p>Description of feature three.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit" class="btn">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Company. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
