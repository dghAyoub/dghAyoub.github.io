# dghAyoub.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nom de votre entreprise</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-size: 16px;
        }
        section {
            padding: 30px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .service, .team-member {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }
        .service img, .team-member img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin-right: 20px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Nom de votre entreprise</h1>
    <p>Votre slogan ici</p>
</header>

<nav>
    <a href="#home">Accueil</a>
    <a href="#about">À propos</a>
    <a href="#services">Services</a>
    <a href="#team">Équipe</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Bienvenue chez Nom de votre entreprise</h2>
    <p>Nous sommes spécialisés dans [secteur d'activité] et nous offrons des services de qualité pour aider votre entreprise à se développer et à réussir. Découvrez nos services ci-dessous et contactez-nous pour en savoir plus !</p>
</section>

<section id="about">
    <h2>À propos de nous</h2>
    <p>Nom de votre entreprise a été fondée en [année] avec l'objectif de [mission de l'entreprise]. Depuis, nous avons aidé de nombreuses entreprises à [résultat principal ou bénéfice des services]. Nous croyons fermement en [valeurs fondamentales de l'entreprise].</p>
</section>

<section id="services">
    <h2>Nos Services</h2>
    <div class="service">
        <img src="service1.jpg" alt="Service 1">
        <div>
            <h3>Service 1</h3>
            <p>Description du service 1. Ce service permet de [bénéfice ou solution].</p>
        </div>
    </div>
    <div class="service">
        <img src="service1.jpg" alt="Service 2">
        <div>
            <h3>Service 2</h3>
            <p>Description du service 2. Ce service offre [bénéfice ou solution].</p>
        </div>
    </div>
    <!-- Ajoutez d'autres services si nécessaire -->
</section>

<section id="team">
    <h2>Notre Équipe</h2>
    <div class="team-member">
        <img src="service1.jpg" alt="Membre 1">
        <div>
            <h3>Nom du membre 1</h3>
            <p>Poste : [Poste de l'employé]</p>
            <p>Description du membre 1. [Compétences et expertise]</p>
        </div>
    </div>
    <div class="team-member">
        <img src="service1.jpg" alt="Membre 2">
        <div>
            <h3>Nom du membre 2</h3>
            <p>Poste : [Poste de l'employé]</p>
            <p>Description du membre 2. [Compétences et expertise]</p>
        </div>
    </div>
    <!-- Ajoutez d'autres membres de l'équipe si nécessaire -->
</section>

<section id="contact">
    <h2>Contactez-nous</h2>
    <p>Nous serions ravis de discuter de vos besoins et de comment nous pouvons vous aider. N'hésitez pas à nous contacter via le formulaire ci-dessous.</p>
    <form class="contact-form">
        <input type="text" placeholder="Votre nom" required>
        <input type="email" placeholder="Votre e-mail" required>
        <textarea placeholder="Votre message" rows="5" required></textarea>
        <button type="submit">Envoyer</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Nom de votre entreprise. Tous droits réservés.</p>
</footer>

</body>
</html>
