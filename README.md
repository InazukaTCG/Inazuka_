<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Inazuka - Boutique en Ligne</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f8f8f8;
    }
    header {
      background-color: #001f3f;
      color: #FFD700;
      padding: 40px 20px;
      text-align: center;
    }
    nav {
      background-color: #003366;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 15px 20px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background-color: #FFD700;
      color: #003366;
    }
    section {
      padding: 40px;
      max-width: 1000px;
      margin: auto;
      background-color: white;
      margin-top: 20px;
      border-radius: 8px;
    }
    h2 {
      color: #001f3f;
    }
    footer {
      background-color: #001f3f;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .legal, .mentions {
      font-size: 0.9em;
      color: #aaa;
      margin-top: 10px;
    }
    .categories {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 20px;
      justify-content: center;
    }
    .categories a {
      background-color: #FFD700;
      color: #001f3f;
      text-decoration: none;
      padding: 10px 15px;
      border-radius: 5px;
    }
    .categories a:hover {
      background-color: #001f3f;
      color: #FFD700;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur Inazuka</h1>
    <p>Votre boutique en ligne de cartes Pokémon, goodies et plus encore !</p>
  </header>

  <nav>
    <a href="index.html">Accueil</a>
    <a href="cartes-fr.html">Cartes FR</a>
    <a href="cartes-jap.html">Cartes JAP</a>
    <a href="coffrets.html">Coffrets</a>
    <a href="boosters.html">Boosters</a>
    <a href="figurines.html">Figurines</a>
    <a href="protection.html">Protection</a>
    <a href="#contact">Contact</a>
    <a href="#infos">Infos légales</a>
  </nav>

  <section id="accueil">
    <h2>Accueil</h2>
    <p>Bienvenue sur <strong>Inazuka</strong>, votre destination en ligne pour tout ce qui concerne les cartes Pokémon, les goodies et bien plus encore.</p>
  </section>

  <section id="apropos">
    <h2>À propos</h2>
    <p>Chez Inazuka, nous sommes passionnés par l'univers Pokémon. Nous proposons une sélection de cartes, figurines, peluches et autres articles de collection pour les fans de tous âges.</p>
    <p>Notre objectif est de créer une communauté de collectionneurs et de passionnés en offrant des produits authentiques, livrés rapidement, avec un service client de qualité.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form>
      <label>Nom:<br><input type="text" name="nom" required></label><br><br>
      <label>Email:<br><input type="email" name="email" required></label><br><br>
      <label>Message:<br><textarea name="message" rows="5" required></textarea></label><br><br>
      <button type="submit" style="background-color: #FFD700; border: none; padding: 10px 20px; cursor: pointer;">Envoyer</button>
    </form>
  </section>

  <section id="infos">
    <h2>Informations légales</h2>
    <p>Nom de l'entreprise : Inazuka SARL</p>
    <p>Adresse : 123 Rue du Commerce, 75000 Paris, France</p>
    <p>SIRET : 123 456 789 00000</p>
    <p>Email professionnel : contact@inazuka.fr</p>
    <p class="legal">Ce site est en cours de développement. Tous les produits mentionnés sont à titre d'exemple.</p>
  </section>

  <footer>
    <div class="categories">
      <a href="cartes-fr.html">Cartes FR</a>
      <a href="cartes-jap.html">Cartes JAP</a>
      <a href="coffrets.html">Coffrets</a>
      <a href="boosters.html">Boosters</a>
      <a href="figurines.html">Figurines</a>
      <a href="protection.html">Protection</a>
      <a href="#contact">Contact</a>
      <a href="#infos">Infos légales</a>
    </div>
    <p>&copy; 2025 Inazuka. Tous droits réservés.</p>
    <p class="mentions">Mentions légales | Conditions générales de vente</p>
  </footer>
</body>
</html>
