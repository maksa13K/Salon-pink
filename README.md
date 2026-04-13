# Salon-pink
<!DOCTYPE html>
<html lang="bs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Studio Salon Pink | Banja Luka</title>
    <style>
        /* CSS Styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fffafb;
            color: #333;
        }
        
        header {
            background-color: #ff69b4; /* Hot Pink */
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            letter-spacing: 2px;
        }

        nav {
            margin-top: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 1.1em;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffe4e1;
        }

        .hero {
            background-color: #ffe4e1; /* Misty Rose */
            text-align: center;
            padding: 60px 20px;
            border-bottom: 3px solid #ffb6c1;
        }

        .hero h2 {
            color: #c71585; /* Medium Violet Red */
            font-size: 2.2em;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2em;
            max-width: 600px;
            margin: 0 auto 30px auto;
            line-height: 1.6;
        }

        .btn {
            background-color: #c71585;
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 25px;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #ff1493; /* Deep Pink */
        }

        .services-section {
            padding: 50px 20px;
            text-align: center;
        }

        .services-section h2 {
            color: #ff69b4;
            font-size: 2em;
            margin-bottom: 40px;
        }

        .services-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .service-card {
            background-color: white;
            border: 2px solid #ffc0cb; /* Pink */
            border-radius: 10px;
            padding: 30px 20px;
            width: 250px;
            box-shadow: 0 4px 8px rgba(255, 105, 180, 0.15);
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-10px);
        }

        .service-card h3 {
            color: #c71585;
        }

        .location-section {
            background-color: #fff0f5; /* Lavender Blush */
            padding: 50px 20px;
            text-align: center;
        }

        .location-section h2 {
            color: #ff69b4;
        }

        footer {
            background-color: #333;
            color: #ffc0cb;
            text-align: center;
            padding: 30px 20px;
        }

        footer p {
            margin: 5px 0;
        }
    </style>
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>STUDIO SALON PINK</h1>
        <nav>
            <a href="#pocetna">Početna</a>
            <a href="#usluge">Usluge</a>
            <a href="#lokacija">Lokacija</a>
            <a href="#kontakt">Kontakt</a>
        </nav>
    </header>

    <!-- Hero / Welcome Section -->
    <section id="pocetna" class="hero">
        <h2>Otkrijte svoju najljepšu stranu</h2>
        <p>Vaše omiljeno mjesto za ljepotu, njegu i opuštanje u srcu Banja Luke. Prepustite se rukama naših profesionalaca.</p>
        <a href="#kontakt" class="btn">Zakažite svoj termin</a>
    </section>

    <!-- Services Section -->
    <section id="usluge" class="services-section">
        <h2>Naše Usluge</h2>
        <div class="services-container">
            <div class="service-card">
                <h3>💇‍♀️ Frizerske usluge</h3>
                <p>Šišanje, feniranje, svečane frizure, pramenovi i najnovije tehnike farbanja kose.</p>
            </div>
            <div class="service-card">
                <h3>💅 Manikir & Pedikir</h3>
                <p>Ojačavanje, izlivanje noktiju, trajni lak i spa pedikir za vaše savršene nokte.</p>
            </div>
            <div class="service-card">
                <h3>💄 Šminkanje</h3>
                <p>Profesionalni makeup za vjenčanja, mature i sve vaše posebne prilike.</p>
            </div>
        </div>
    </section>

    <!-- Location Section -->
    <section id="lokacija" class="location-section">
        <h2>Pronađite nas u Banjoj Luci</h2>
        <p>Posjetite nas i uživajte u predivnom ambijentu našeg salona.</p>
        <p><strong>Adresa:</strong> Gospodska ulica bb, 78000 Banja Luka (Primjer adrese)</p>
        <p><strong>Radno vrijeme:</strong> Ponedjeljak - Subota: 09:00 - 20:00</p>
    </section>

    <!-- Footer / Contact -->
    <footer id="kontakt">
        <h2>Kontaktirajte nas</h2>
        <p>📞 Telefon: +387 65 123 456</p>
        <p>✉️ Email: info@studiosalonpink.ba</p>
        <p>📱 Instagram: @studiosalonpink_bl</p>
        <br>
        <p>&copy; 2026 Studio Salon Pink Banja Luka. Sva prava zadržana.</p>
    </footer>

</body>
</html>