
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Catalogue - Boucéau de Games</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #ff6f61, #f2f2f2); /* Dégradé du rouge au gris clair */
      color: #222;
      line-height: 1.6;
    }

    nav {
      background-color: rgba(51, 51, 51, 0.8); /* Fond semi-transparent */
      padding: 15px 0;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 40px;
      flex-wrap: wrap;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 1.1em;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #ff6347;
    }

    h2 {
      text-align: center;
      font-size: 3em;
      margin-top: 50px;
      color: #333;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    .game-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      max-width: 1200px;
      margin: 50px auto;
      padding: 0 20px;
    }

    .game-card {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.1);
      width: 320px;
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      position: relative;
    }

    .game-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    }

    .game-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-bottom: 2px solid #ddd;
      border-top-left-radius: 16px;
      border-top-right-radius: 16px;
    }

    .game-card h3 {
      font-size: 1.8em;
      color: #333;
      margin-top: 15px;
      font-weight: 600;
    }

    .game-card p {
      font-size: 1em;
      color: #666;
      padding: 0 20px;
      margin: 20px 0;
    }

    .game-card a {
      display: inline-block;
      margin-bottom: 20px;
      padding: 12px 24px;
      background: #ff6347;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 8px;
      transition: background 0.3s ease;
      font-size: 1.1em;
    }

    .game-card a:hover {
      background: #e55339;
    }

    .game-card a:active {
      transform: scale(0.98);
    }

    .game-card::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0,0,0,0.1);
      border-radius: 16px;
      z-index: -1;
      transition: background 0.3s ease;
    }

    .game-card:hover::before {
      background: rgba(0,0,0,0.15);
    }

    footer {
      background: rgba(51, 51, 51, 0.8); /* Fond semi-transparent */
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 50px;
    }

    @media screen and (max-width: 768px) {
      .game-grid {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <!-- Menu de navigation -->
  <nav>
    <ul>
      <li><a href="#accueil">Accueil</a></li>
      <li><a href="#catalogue">Catalogue</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Titre principal -->
  <h2 id="accueil">🎮 Nos jeux populaires</h2>

  <!-- Catalogue de jeux -->
  <div class="game-grid" id="catalogue">

    <!-- Snake avec nouvelle image -->
    <div class="game-card">
      <img src="/mnt/data/th (1).jpg" alt="Snake">
      <h3>Snake</h3>
      <p>Le jeu rétro incontournable ! Mangez les pommes pour grandir et évitez de vous mordre la queue.</p>
      <a href="https://sukuna3340.github.io/snackphone/" target="_blank">Jouer</a>
    </div>

    <!-- Subway Surfers avec nouvelle image -->
    <div class="game-card">
      <img src="/mnt/data/f12d9c75-3573-4f51-83b8-e5ceb5cd0617.png" alt="Subway Surfers">
      <h3>Subway Surfers</h3>
      <p>Faites des courses effrénées sur les rails, esquivez les trains et collectez des pièces !</p>
      <a href="https://poki.com/fr/g/subway-surfers" target="_blank">Jouer</a>
    </div>

    <!-- Minecraft -->
    <div class="game-card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/c1/Minecraft_Logo.svg" alt="Minecraft">
      <h3>Minecraft</h3>
      <p>Explorez un monde infini, minez des ressources et construisez des structures incroyables avec des blocs !</p>
      <a href="https://www.minecraft.net/fr-fr" target="_blank">Voir</a>
    </div>

  </div>

  <!-- Pied de page -->
  <footer id="contact">
    © 2025 Boucéau de Games - Tous droits réservés.
  </footer>

</body>
</html>
