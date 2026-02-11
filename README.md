<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Alexis Sureau - Portfolio</title>

    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            background: #0a0a0a;
            color: #e5e5e5;
            font-family: 'Inter', sans-serif;
        }

        .hero {
            background-image: url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80');
            background-size: cover;
            background-position: center;
            padding: 120px 20px;
            text-align: center;
            position: relative;
        }

        .hero::after {
            content: "";
            position: absolute;
            inset: 0;
            background: rgba(0,0,0,0.6);
        }

        .hero-content {
            position: relative;
            z-index: 2;
        }

        .hero h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3rem;
            color: #4caf50;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .section {
            max-width: 1100px;
            margin: 60px auto;
            padding: 0 20px;
        }

        h2 {
            font-family: 'Orbitron', sans-serif;
            color: #4caf50;
            border-left: 4px solid #4caf50;
            padding-left: 12px;
            margin-bottom: 25px;
        }

        .grid {
            display: grid;
            gap: 25px;
        }

        .grid-2 {
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        }

        .card {
            background: #111;
            padding: 25px;
            border-radius: 12px;
            border: 1px solid #1f1f1f;
            box-shadow: 0 0 15px rgba(76, 175, 80, 0.15);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 25px rgba(76, 175, 80, 0.35);
        }

        .contact a {
            color: #4caf50;
            font-weight: bold;
            text-decoration: none;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #050505;
            margin-top: 60px;
            border-top: 2px solid #4caf50;
        }
    </style>
</head>

<body>

    <!-- HERO -->
    <section class="hero">
        <div class="hero-content">
            <h1>Alexis Sureau</h1>
            <p>Futur étudiant en BTS SIO SLAM • Développeur débutant</p>
        </div>
    </section>

    <!-- À PROPOS -->
    <section class="section">
        <h2>À propos</h2>
        <div class="card">
            <p>
                Je m'appelle Alexis, je débute dans le développement web et je vais intégrer le 
                <strong>BTS SIO option SLAM</strong> à Ynov Montpellier.
                Après plusieurs années dans la logistique, je me reconvertis dans l’informatique pour
                construire une carrière dans le développement.
            </p>
        </div>
    </section>

    <!-- COMPÉTENCES -->
    <section class="section">
        <h2>Compétences</h2>

        <div class="grid grid-2">
            <div class="card">
                <h3>Compétences techniques</h3>
                <p>
                    * HTML / CSS (bases)<br>
                    * JavaScript (début)<br>
                    * Node.js / Express (début)<br>
                    * Git / GitHub<br>
                    * Visual Studio Code
                </p>
            </div>

            <div class="card">
                <h3>Compétences professionnelles</h3>
                <p>
                    * Organisation, gestion des priorités<br>
                    * Travail en équipe et autonomie<br>
                    * Rigueur, respect des procédures<br>
                    * Résolution de problèmes<br>
                    * Adaptation rapide
                </p>
            </div>
        </div>
    </section>

    <!-- PROJETS (les 3 que tu vas faire) -->
    <section class="section">
        <h2>Projets</h2>

        <div class="grid grid-2">
            <div class="card">
                <h3>Mini-site HTML/CSS</h3>
                <p>
                    Site vitrine simple pour apprendre la structure d’une page web, le HTML et le CSS.
                </p>
            </div>

            <div class="card">
                <h3>Mini API Node.js</h3>
                <p>
                    Petite API avec Express, une route JSON, pour découvrir le backend et Node.js.
                </p>
            </div>

            <div class="card">
                <h3>Script serveur</h3>
                <p>
                    Script JavaScript simple pour automatiser une tâche côté serveur (message régulier).
                </p>
            </div>
        </div>
    </section>

    <!-- PARCOURS -->
    <section class="section">
        <h2>Parcours professionnel</h2>

        <div class="card">
            <p>
                * Magasinier (2022–2026) – Bréguiboul Distribution<br>
                * Missions intérim (2015–2022) – ViaPost, Metro, Gouiran, etc.<br><br>
                Expérience : préparation de commandes, gestion de stock, rigueur, autonomie, travail en équipe.
            </p>
        </div>
    </section>

    <!-- CENTRES D’INTÉRÊT (avec les serveurs Minecraft ici seulement) -->
    <section class="section">
        <h2>Centres d’intérêt</h2>

        <div class="card">
            <p>
                * Jeux vidéo<br>
                * Gestion de serveurs Minecraft (configuration, plugins, permissions, organisation de serveurs)<br>
                * Sport<br>
                * Apprentissage du développement et des nouvelles technologies
            </p>
        </div>
    </section>

    <!-- CONTACT -->
    <section class="section contact">
        <h2>Contact</h2>

        <div class="card">
            <p>Email : <strong>Alexis.sureau.34@gmail.com</strong></p>

            <p>
                École :  
                <a href="https://www.ynov.com/campus/montpellier/" target="_blank">
                    Ynov Campus Montpellier
                </a>
            </p>

            <p>
                Formation BTS SIO SLAM :  
                <a href="https://www.ynov.com/formations/informatique/bts-sio/" target="_blank">
                    BTS SIO – Option SLAM
                </a>
            </p>
        </div>
    </section>

    <footer>
        © 2026 - Portfolio d'Alexis Sureau
    </footer>

</body>
</html>
