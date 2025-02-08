<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scripts.DH</title>
    <style>
        /* Global Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #e0e0e0;
        }

        /* Header */
        header {
            background-color: #111;
            color: #ffd700;
            padding: 20px 0;
            text-align: center;
            border-bottom: 3px solid #ffd700;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            font-family: 'Courier New', Courier, monospace;
            letter-spacing: 3px;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.2rem;
            color: #ccc;
        }

        /* Navigation */
        nav {
            background-color: #222;
            padding: 10px 0;
            text-align: center;
            border-bottom: 2px solid #ffd700;
        }

        nav a {
            color: #e0e0e0;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #ffd700;
        }

        /* Services Section */
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .service {
            background-color: #222;
            border: 1px solid #444;
            border-radius: 5px;
            width: 30%;
            margin: 10px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .service:hover {
            transform: translateY(-10px);
            box-shadow: 0 4px 10px rgba(255, 215, 0, 0.4);
        }

        .service h2 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #ffd700;
        }

        .service p {
            font-size: 1rem;
            line-height: 1.5;
            color: #ccc;
        }

        .service .price {
            font-size: 1.2rem;
            color: #ffd700;
            font-weight: bold;
            margin-top: 10px;
        }

        /* Footer */
        footer {
            background-color: #111;
            color: #e0e0e0;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
            border-top: 3px solid #ffd700;
        }

        footer p {
            margin: 0;
            font-size: 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .service {
                width: 45%;
            }
        }

        @media (max-width: 480px) {
            .service {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Scripts.DH</h1>
        <p>Scripts.DH are the best script makers for 2025 exploits! We use trustworthy executers to test them and make them amazing for our customers.</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="https://discord.gg/q5EpZy2qzX" target="_blank">Support</a>
    </nav>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="service">
            <h2>Da Hood Op Script</h2>
            <p>The features may include:</p>
            <ul>
                <li>Cash spawner</li>
                <li>Fly and anti-stomp</li>
                <li>Silent aim with Auto Lock</li>
                <li>OP kill aura (must have a gun equipped)</li>
            </ul>
            <p class="price">Only for $4.99</p>
        </div>
        <div class="service">
            <h2>Stand Script</h2>
            <p>This script allows you to get a ALT account to Kill, Drop cash, and do more! Any issues? Click support and DM Dexo_dev.</p>
        </div>
        <div class="service">
            <h2>Customer Support</h2>
            <p>We provide unparalleled support to ensure our customers get the most out of our products.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Scripts.DH. All rights reserved.</p>
    </footer>
</body>
</html>
