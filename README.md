<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tres Collective</title>
    <style>
        body {
            margin: 0;
            font-family: 'Georgia', serif;
            background-color: #000;
            color: #fff;
        }

        header {
            background-color: #111;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #bbb;
        }

        header h1 {
            color: #bbb;
            margin: 0;
            font-size: 2.5rem;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #bbb;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            color: #fff;
        }

        .hero h2 {
            font-size: 2rem;
            color: #bbb;
        }

        .hero p {
            font-size: 1.2rem;
            margin: 20px 0;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            color: #000;
            background-color: #bbb;
            text-decoration: none;
            font-size: 1.1rem;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #999;
        }

        section {
            padding: 50px 20px;
            text-align: center;
        }

        .services h2,
        .contact h2 {
            font-size: 2rem;
            color: #bbb;
            margin-bottom: 20px;
        }

        .services p,
        .contact p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        footer {
            background-color: #111;
            color: #fff;
            text-align: center;
            padding: 20px;
            border-top: 2px solid #bbb;
        }

        footer p {
            margin: 5px 0;
            font-size: 1rem;
        }

        footer a {
            color: #bbb;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            nav a {
                font-size: 1rem;
            }

            .hero h2 {
                font-size: 1.5rem;
            }

            .services h2,
            .contact h2 {
                font-size: 1.5rem;
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
        <h2>Bridging the Gap Between D3 Athletes and Communities</h2>
        <p>A first-of-its-kind NIL agency focused on connecting Division III athletes, local businesses, and their communities.</p>
        <a href="#services" class="button">Learn More</a>
    </div>

    <section id="services" class="services">
        <h2>Our Services</h2>
        <p>We specialize in empowering Division III athletes by creating meaningful NIL opportunities through sponsorships, brand collaborations, and community-driven initiatives. Tres Collective helps D3 athletes and local businesses grow together, much like the microfinance model, by focusing on underrepresented markets with significant growth potential.</p>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Division III athletics is an untapped growth market, offering unique opportunities for local businesses to connect with passionate, community-driven athletes. Tres Collective is dedicated to elevating D3 athletes by fostering authentic partnerships that benefit both the athletes and the businesses that support them.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Interested in learning more or starting a partnership? Reach out to us today!</p>
        <p>Email: <a href="mailto:info@trescollective.com">info@trescollective.com</a></p>
        <p>Phone: (555) 123-4567</p>
    </section>

    <footer>
        <p>&copy; 2025 Tres Collective. All Rights Reserved.</p>
        <p><a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
    </footer>
</body>

</html>
