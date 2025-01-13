Let's try using a different image source. Here are some free header images you can use:

1. [Pixabay Header Images](https://pixabay.com/images/search/header/)
2. [Freepik Website Header Images](https://www.freepik.com/free-photos-vectors/website-header)

You can download an image from one of these sources and replace the placeholder URL in the code. Here's the updated HTML with a new image URL from Pixabay:

```html
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
            background: linear-gradient(135deg, #0a0a0a, #111111);
            color: #fff;
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        header {
            background: url('https://cdn.pixabay.com/photo/2016/11/29/09/32/architecture-1868667_1280.jpg') no-repeat center center/cover;
            padding: 20px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }

        header h1 {
            color: #fff;
            font-size: 2.4rem;
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }

        nav {
            display: flex;
            gap: 20px;
        }

        nav a {
            color: #bbb;
            text-decoration: none;
            font-size: 1rem;
            transition: color 0.3s, transform 0.3s;
        }

        nav a:hover {
            color: #fff;
            transform: scale(1.1);
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
            animation: fadeInUp 2s ease-in-out;
        }

        .hero h2 {
            font-size: 3rem;
            margin: 0 0 20px;
        }

        .hero p {
            font-size: 1.4rem;
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
            transition: background-color 0.3s, transform 0.3s;
        }

        .hero .button:hover {
            background-color: #666;
            transform: scale(1.1);
        }

        section {
            padding: 50px 30px;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #ccc;
        }

        section p {
            font-size: 1.2rem;
            color: #aaa;
            max-width: 800px;
            margin: 0 auto;
        }

        footer {
            background-color: #1a1a1a;
            color: #bbb;
            text-align: center;
            padding: 20px;
            animation: fadeIn 2s ease-in-out;
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
                font-size: 2.2rem;
            }

            .hero p {
                font-size: 1.1rem;
            }

            nav {
                flex-direction: column;
                gap: 10px;
            }
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Tres Collective</h1>
        <nav>
            <a href="#services">Services</a>
            <a href="#spotlight">Student-Athlete Spotlight</a>
            <a href="#partners">Partners</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h2>Bringing NIL to Division III Athletics</h2>
        <p>A boutique NIL agency focused on bridging Division III athletes, local businesses, and the community.</p>
        <a href="#services" class="button">Discover More</a>
    </div>

    <section id="services">
        <h2>What We Do</h2>
        <p>Our mission is to bridge the gap between Division III athletes and local businesses through innovative NIL opportunities, focusing on community impact and growth potential. We empower underrepresented markets with a model inspired by microfinance principles.</p>
    </section>

    <section id="spotlight">
        <h2>Student-Athlete Spotlight</h2>
        <p>Highlighting the achievements and stories of Division III student-athletes who are making a difference on and off the field.</p>
    </section>

    <section id="partners">
        <h2>Our Partners</h2>
        <p>We collaborate with local businesses and organizations to create meaningful NIL opportunities for Division III athletes.</p>
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
```

Try using this new image URL. If it still doesn't work, please let me know, and we can troubleshoot further!
