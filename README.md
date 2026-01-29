<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Club Informatique - Université Alassane Ouattara</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
        }
        header {
            background: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #0055aa;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
            background: white;
            margin: 10px;
            border-radius: 5px;
        }
        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>

<body>

<header>
    <h1>Club Informatique</h1>
    <p>Université Alassane Ouattara</p>
</header>

<nav>
    <a href="#about">À propos</a>
    <a href="#objectifs">Objectifs</a>
    <a href="#equipe">Équipe</a>
    <a href="#activites">Activités</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>Présentation du club</h2>
    <p>
        Le Club Informatique de l’Université Alassane Ouattara forme les étudiants 
        aux technologies numériques, au développement web, à la programmation et au multimédia.
    </p>
</section>

<section id="objectifs">
    <h2>Nos objectifs</h2>
    <ul>
        <li>Former en informatique moderne</li>
        <li>Organiser des ateliers pratiques</li>
        <li>Créer des projets innovants</li>
        <li>Préparer aux métiers du numérique</li>
    </ul>
</section>

<section id="equipe">
    <h2>Équipe dirigeante</h2>
    <p>Président : YEDE N’GUESSAN EVANE</p>
    <p>Secrétaire : KARAMBIRI HAMZAT</p>
    <p>Trésorier : KIPOUTE VICTORIA</p>
</section>

<section id="activites">
    <h2>Nos activités</h2>
    <p>
        ✔ Initiation à l'informatique     
        ✔ Formation en world, excel...
        ✔ Programmations
        ✔ Competitions   
    </p>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Téléphone : 0140880607</p>
    <p>Email : hamzakarambiri@gmail.com</p>
</section>

<footer>
    <p>© 2026 Club Informatique - Université Alassane Ouattara</p>
</footer>

</body>
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Club Informatique - Université Alassane Ouattara</title>
    <style>
        /* Styles généraux */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
        }

        /* Image en arrière-plan */
        body {
            background-image: url('images/photo_club.jpg'); /* mettez le chemin de votre image ici */
            background-size: cover;       /* couvre tout l'écran */
            background-position: center;  /* centrée */
            background-repeat: no-repeat;
            color: white;                 /* texte blanc pour contraste */
        }

        /* Conteneur du texte centré */
        .hero-content {
            text-align: center;
            position: absolute;
            top: 50%;          /* centre verticalement */
            left: 50%;         /* centre horizontalement */
            transform: translate(-50%, -50%);
            background-color: rgba(0, 0, 0, 0.5); /* fond semi-transparent pour lisibilité */
            padding: 40px;
            border-radius: 15px;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.5em;
        }

        /* Bouton d'action */
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            font-size: 1.2em;
            color: white;
            background-color: #0077cc;
            border: none;
            border-radius: 10px;
            text-decoration: none;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #005fa3;
        }

        /* Responsive pour petits écrans */
        @media (max-width: 768px) {
            h1 { font-size: 2em; }
            p { font-size: 1.2em; }
            .hero-content { padding: 20px; }
        }
    </style>
</head>
<body>
    <div class="hero-content">
        <h1>Bienvenue au Club Informatique</h1>
        <p>Apprenez, innovez et collaborez avec nous !</p>
        <a href="#contact" class="btn">Rejoignez-nous</a>
    </div>
</body>
</html>
