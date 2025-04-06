<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GOLDEN FIRM - Accueil</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(90deg, #0A0A2A, #000, #FFF);
            color: #333;
        }
        header {
            background: #222;
            color: #fff;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .logo {
            width: 80px;
            height: auto;
        }
        .header-content {
            display: flex;
            align-items: center;
            gap: 20px;
        }
        .header-content h1 {
            margin: 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            gap: 15px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .services {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        .service {
            background: #222;
            color: white;
            padding: 20px;
            border-radius: 8px;
            width: 300px;
            text-align: center;
            transition: transform 0.3s, background 0.3s;
        }
        .service:hover {
            background: #444;
            transform: scale(1.05);
        }
        .service img {
            width: 100%;
            height: 180px;
            border-radius: 5px;
            object-fit: cover;
        }
        .service a {
            display: block;
            margin-top: 10px;
            padding: 10px;
            background: #FFD700;
            color: #222;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .service a:hover {
            background: #FFC107;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <h1>GOLDEN FIRM</h1>
        </div>
        <img src="Image2.png" alt="Golden Firm Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="about.html">À propos</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section>
        <h2>Nos Services</h2>
        <div class="services">
            <div class="service">
                <img src="image1.webp" alt="Comptabilité">
                <h3>Comptabilité</h3>
                <p>Gérez vos finances avec précision et professionnalisme.</p>
                <a href="ensavoirpluscomptable.html">En savoir plus</a>
            </div>
            <div class="service">
                <img src="image1.webp" alt="Fiscalité">
                <h3>Fiscalité</h3>
                <p>Optimisation fiscale et conseils personnalisés.</p>
                <a href="ensavoirplus.html">En savoir plus</a>
            </div>
            <div class="service">
                <img src="imgg.jpg" alt="Audit Financier">
                <h3>Audit Financier</h3>
                <p>Évaluations rigoureuses pour une meilleure gestion.</p>
                <a href="ensavoirplusaudit.html">En savoir plus</a>
            </div>
        </div>
 </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>Golden Firm is an accounting expertise firm dedicated to supporting businesses with tailored and efficient solutions.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: contact@goldenfirm.com</p>
        <p>Phone: +221 77 423 45 </p>
    </section>

    </section>

    <footer>
        <p>&copy; 2025 Golden Firm - Tous droits réservés.</p>
    </footer>
</body>
</html>
