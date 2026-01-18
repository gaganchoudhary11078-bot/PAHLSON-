<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pahlson International School | Official Website</title>
    <style>
        /* --- CSS STYLES --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        /* Navigation */
        nav {
            background: #002147; /* Navy Blue */
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 10%;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            letter-spacing: 1px;
        }

        .logo span {
            color: #D4AF37; /* Gold */
        }

        .nav-links {
            list-style: none;
            display: flex;
        }

        .nav-links li {
            margin-left: 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: 0.3s;
        }

        .nav-links a:hover {
            color: #D4AF37;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1541339907198-e08756dedf3f?q=80&w=2070&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin-bottom: 2rem;
        }

        .cta-btn {
            background: #D4AF37;
            color: #002147;
            padding: 12px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: 0.3s;
        }

        .cta-btn:hover {
            background: white;
        }

        /* Info Section */
        .info-section {
            padding: 50px 10%;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            background: #f9f9f9;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            text-align: center;
            border-top: 5px solid #002147;
        }

        .card h3 {
            margin-bottom: 15px;
            color: #002147;
        }

        /* Footer */
        footer {
            background: #002147;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">PAHLSON <span>INTERNATIONAL</span></div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#academics">Academics</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header class="hero" id="home">
        <h1>Welcome to Pahlson International</h1>
        <p>Providing a world-class education that inspires students to innovate, lead, and succeed in a global environment.</p>
        <a href="#contact" class="cta-btn">Enquire Today</a>
    </header>

    <section class="info-section">
        <div class="card">
            <h3>Excellence</h3>
            <p>Our students consistently rank among the top performers in academics and extra-curricular activities.</p>
        </div>
        <div class="card">
            <h3>Global Vision</h3>
            <p>Preparing students for a connected world with advanced language programs and cultural exchange.</p>
        </div>
        <div class="card">
            <h3>Modern Campus</h3>
            <p>Equipped with smart classrooms, advanced science labs, and world-standard sports facilities.</p>
        </div>
    </section>

    <footer id="contact">
        <p>&copy; 2026 Pahlson International School. All Rights Reserved.</p>
        <p>Contact: info@pahlsoninternational.edu | Phone: +123 456 7890</p>
    </footer>

</body>
</html>

