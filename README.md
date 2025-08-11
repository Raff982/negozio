<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Negozio di Telefonia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .brands {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
            background: white;
        }
        .brands img {
            height: 50px;
        }
        .services {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        h2 {
            text-align: center;
            margin-bottom: 10px;
        }
        iframe {
            width: 100%;
            height: 300px;
            border: 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            background: #e9ecef;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .social {
            text-align: center;
            margin-top: 20px;
        }
        .social a {
            display: inline-block;
            margin: 5px;
            text-decoration: none;
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            font-weight: bold;
        }
        .tiktok {
            background-color: black;
        }
        .instagram {
            background: linear-gradient(45deg, #feda75, #d62976, #962fbf, #4f5bd5);
        }
        /* Pulsante WhatsApp fisso */
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 20px;
            right: 20px;
            background-color: #25d366;
            color: white;
            border-radius: 50%;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
            z-index: 100;
        }
        .whatsapp-float i {
            margin-top: 15px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Negozio di Telefonia</h1>
        <p>Rivenditore autorizzato Fastweb, Sky Italia, Ho., Iliad, WindTre</p>
    </header>

    <section class="brands">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Fastweb_logo.svg" alt="Fastweb">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Sky_Italia_logo.svg" alt="Sky Italia">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/Ho._mobile_logo.svg" alt="Ho.">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/Iliad_logo.svg" alt="Iliad">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Wind_Tre_logo.svg" alt="WindTre">
    </section>

    <section class="services">
        <h2>Servizi Offerti</h2>
        <ul>
            <li>Vendita smartphone e accessori</li>
            <li>Attivazione SIM e offerte telefoniche</li>
            <li>Assistenza tecnica</li>
            <li>Pagamenti e ricariche</li>
        </ul>
    </section>

    <section class="services">
        <h2>Dove Siamo</h2>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2880.7093940570746!2d11.255814315716846!3d43.76987167911764!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x132a5409a25b1b8d%3A0x4a354ec3d8a7c64d!2sPiazza%20del%20Duomo%2C%20Firenze!5e0!3m2!1sit!2sit!4v1673623480262!5m2!1sit!2sit" allowfullscreen="" loading="lazy"></iframe>
    </section>

    <div class="social">
        <a class="tiktok" href="https://www.tiktok.com/@iltuoprofilo" target="_blank">🎵 TikTok</a>
        <a class="instagram" href="https://www.instagram.com/iltuoprofilo" target="_blank">📸 Instagram</a>
    </div>

    <!-- Pulsante WhatsApp con messaggio precompilato -->
    <a href="https://wa.me/393471234567?text=Ciao%2C%20vorrei%20informazioni%20sui%20vostri%20servizi" class="whatsapp-float" target="_blank" title="Chatta su WhatsApp">
        <i>💬</i>
    </a>

    <footer>
        <p>📞 Telefono: 0123 456789 | ✉ Email: info@negoziotelefonia.it</p>
        <p>&copy; 2025 Negozio di Telefonia</p>
    </footer>

</body>
</html>
