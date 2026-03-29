index.html <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahsan Builders</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header / Navigation -->
    <header>
        <div class="container">
            <h1>Ahsan Builders</h1>
            <nav>
                <a href="#about">About</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h2>Building Dreams Into Reality</h2>
            <p>We deliver quality construction projects with trust and excellence.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Ahsan Builders is a leading construction company specializing in residential and commercial projects. We prioritize quality, safety, and client satisfaction in every project we undertake.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>Our Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Residential Complex</h3>
                    <p>Modern apartments with premium amenities.</p>
                </div>
                <div class="project-card">
                    <h3>Commercial Plaza</h3>
                    <p>High-end office spaces for businesses.</p>
                </div>
                <div class="project-card">
                    <h3>Luxury Villas</h3>
                    <p>Elegant villas designed for comfort and style.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: info@ahsanbuilders.com</p>
            <p>Phone: +92 300 1234567</p>
            <p>Address: Shahodi Garhi, Pakistan</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2026 Ahsan Builders. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
style.css /* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

/* Container */
.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

/* Header */
header {
    background: #004080;
    color: white;
    padding: 1rem 0;
}
header h1 {
    display: inline-block;
}
header nav {
    float: right;
}
header nav a {
    color: white;
    margin-left: 1rem;
    text-decoration: none;
}

/* Hero */
.hero {
    background: #e6f0ff;
    padding: 4rem 0;
    text-align: center;
}
.hero h2 {
    font-size: 2.5rem;
}
.hero p {
    font-size: 1.2rem;
}

/* Sections */
section {
    padding: 3rem 0;
}

/* Projects Grid */
.projects-grid {
    display: flex;
    gap: 2rem;
    flex-wrap: wrap;
}
.project-card {
    flex: 1 1 250px;
    background: #f0f0f0;
    padding: 1.5rem;
    border-radius: 10px;
}

/* Footer */
footer {
    background: #004080;
    color: white;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}
script.js // Basic JS - for future use or interactive features
console.log("Ahsan Builders Website Loaded");
