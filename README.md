<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tres Collective</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #000;
            color: #fff;
            line-height: 1.6;
        }

        header {
            background-color: #1a1a1a;
            padding: 20px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            color: #fff;
            font-size: 1.8rem;
            margin: 0;
        }

        nav {
            display: flex;
            gap: 20px;
        }

        nav a {
            color: #bbb;
            text-decoration: none;
            font-size: 1rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #fff;
        }

        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
            padding: 0 20px;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin: 0 0 20px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .hero .button {
            background-color: #444;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s;
        }

        .hero .button:hover {
            background-color: #666;
        }

        section {
            padding: 50px 30px;
            text-align: center;
        }

        section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #ccc;
        }

        section p {
            font-size: 1rem;
            color: #aaa;
            max-width: 800px;
            margin: 0 auto;
        }

        footer {
            background-color: #1a1a1a;
            color: #bbb;
            text-align: center;
            padding: 20px;
        }

        footer p {
            margin: 5px 0;
            font-size: 0.9rem;
        }

        footer a {
            color: #bbb;
            text-decoration: none;
        }

        footer a:hover {
            color: #fff;
        }

        @media (max-width: 768px) {
            .hero h2 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1rem;
            }

            nav {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Tres Collective</h1>
        <nav>
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h2>Empowering D3 Athletes and Communities</h2>
        <p>A pioneering NIL agency creating connections between Division III athletes, local businesses, and the community.</p>
        <a href="#services" class="button">Discover More</a>
    </div>

    <section id="services">
        <h2>What We Do</h2>
        <p>Our mission is to bridge the gap between Division III athletes and local businesses through innovative NIL opportunities, focusing on community impact and growth potential. We empower underrepresented markets with a model inspired by microfinance principles.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Tres Collective is redefining how Division III athletics engages with local communities. By tapping into the untapped potential of D3 sports, we create mutually beneficial partnerships that celebrate the spirit of collaboration and growth.</p>
    </section>

    <section id="contact">
        <h2>Get In Touch</h2>
        <p>Interested in collaborating or learning more? We’d love to hear from you.</p>
        <p>Email: <a href="mailto:info@trescollective.com">info@trescollective.com</a></p>
        <p>Phone: (555) 123-4567</p>
    </section>

    <footer>
        <p>&copy; 2025 Tres Collective. All Rights Reserved.</p>
        <p><a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
    </footer>
</body>

</html>

