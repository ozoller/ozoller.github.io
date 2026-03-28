# ozoller.github.io
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SG BBM Bietigheim | Profis & Talentschmiede</title>
    <style>
        :root {
            --sg-red: #e30613;
            --dark-bg: #1a1a1a;
            --white: #ffffff;
            --grey: #f4f4f4;
            --hnet-blue: #004a99; /* Farbe für Handball.net Button */
        }

        body { font-family: 'Arial', sans-serif; margin: 0; line-height: 1.6; }

        header {
            background: var(--dark-bg);
            color: white;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 4px solid var(--sg-red);
            position: sticky; top: 0; z-index: 100;
        }

        nav a { color: white; text-decoration: none; margin-left: 20px; font-weight: bold; }
        nav a:hover { color: var(--sg-red); }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://sgbbm.de/files/SGBBM/Bilder/News/23-24/Maenner/Teamfoto_23-24.jpg') center/cover;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .section { padding: 50px 10%; }
        .section-title { border-left: 6px solid var(--sg-red); padding-left: 15px; text-transform: uppercase; margin-bottom: 30px; }

        /* Jugend-Kacheln */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; }
        
        .card { 
            background: var(--grey); 
            border-radius: 10px; 
            overflow: hidden; 
            transition: 0.3s;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        
        .card:hover { transform: translateY(-5px); }
        
        .card-content { padding: 20px; }
        
        .btn-hnet {
            display: inline-block;
            background: var(--hnet-blue);
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 0.9rem;
            margin-top: 10px;
            font-weight: bold;
        }

        .btn-hnet:hover { opacity: 0.9; }

        footer { background: var(--dark-bg); color: white; padding: 30px 10%; text-align: center; }
    </style>
</head>
<body>

<header>
    <div style="font-size: 1.5rem; font-weight: 900;">SG BBM <span style="color:var(--sg-red)">BIETIGHEIM</span></div>
    <nav>
        <a href="#profi">Männer 1</a>
        <a href="#jugend">Talentschmiede</a>
        <a href="#">Tickets</a>
        <a href="#">Fanshop</a>
    </nav>
</header>

<section class="hero">
    <h1 style="font-size: 3.5rem; margin: 0;">WIR SIND DIE BLUEREDS</h1>
    <p style="font-size: 1.2rem;">Tradition. Leidenschaft. Zukunft.</p>
</section>

<section class="section" id="jugend">
    <h2 class="section-title">SG Talentschmiede (Jugend)</h2>
    <p>Unsere Jugendmannschaften sind das Herzstück des Vereins. Hier reifen die Bundesliga-Stars von morgen.</p>
    
    <div class="grid">
        <div class="card">
            <div class="card-content">
                <h3>männliche A-Jugend (U19)</h3>
                <p>Jugendbundesliga - Die höchste deutsche Spielklasse für unsere Top-Talente.</p>
                <a href="https://www.handball.net/vereine/handball4all.wuerttemberg.114" target="_blank" class="btn-hnet">Spielplan auf Handball.net ↗</a>
            </div>
        </div>

        <div class="card">
            <div class="card-content">
                <h3>männliche B-Jugend</h3>
                <p>Regionalliga BW - Leistungshandball auf höchstem Niveau.</p>
                <a href="https://www.handball.net/vereine/handball4all.wuerttemberg.114" target="_blank" class="btn-hnet">Tabelle auf Handball.net ↗</a>
            </div>
        </div>

        <div class="card">
            <div class="card-content">
                <h3>weibliche Jugend</h3>
                <p>Von der A-Jugend Oberliga bis zu den kleinsten Nachwuchsteams.</p>
                <a href="https://www.handball.net/vereine/handball4all.wuerttemberg.114" target="_blank" class="btn-hnet">Alle Teams entdecken ↗</a>
            </div>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2026 SG BBM Bietigheim | <a href="#" style="color:var(--sg-red)">Impressum</a> | <a href="#" style="color:var(--sg-red)">Datenschutz</a></p>
    <p>Besuche uns auf: <b>handball.net</b></p>
</footer>

</body>
</html>
