# Design.foot.13
Affiches de foot
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Design_Foot_13</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Police stylée -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">

  <style>
    * {margin:0; padding:0; box-sizing:border-box; font-family: 'Montserrat', sans-serif;}
    body {background:#0b1320; color:white; scroll-behavior:smooth;}
    a {color:white; text-decoration:none;}

    /* Header & menu */
    header {display:flex; justify-content:space-between; align-items:center; padding:20px 40px; background:linear-gradient(90deg,#001f3f,#003366); position:sticky; top:0; z-index:100;}
    header h1 {font-size:1.8rem;}
    nav a {margin-left:30px; font-weight:700; transition:0.3s;}
    nav a:hover {color:#ffcc00;}

    /* Sections */
    section {padding:80px 20px; max-width:1200px; margin:auto;}
    h2 {text-align:center; margin-bottom:50px; font-size:2rem; color:#ffcc00;}

    /* Galerie */
    .gallery {display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:25px;}
    .poster {border-radius:15px; overflow:hidden; box-shadow:0 10px 25px rgba(0,0,0,0.5); transition:transform 0.3s;}
    .poster:hover {transform:scale(1.05);}
    .poster img {width:100%; display:block;}
    .poster p {padding:15px; text-align:center; font-weight:bold; background:#111827;}

    /* Formulaire */
    form {max-width:500px; margin:auto; background:#111827; padding:40px; border-radius:20px;}
    input, textarea {width:100%; padding:15px; margin-bottom:20px; border:none; border-radius:12px; font-size:1rem;}
    textarea {height:130px; resize:none;}
    button {width:100%; padding:18px; border:none; border-radius:30px; font-size:1rem; font-weight:bold; cursor:pointer; background:#ffcc00; color:#0b1320; transition:0.3s;}
    button:hover {background:#e6b800; transform:scale(1.05);}

    /* Footer */
    footer {text-align:center; padding:30px; opacity:0.7; font-size:0.9rem; background:#001f3f;}
  </style>
</head>

<body>

<!-- Header + Menu -->
<header>
  <h1>Design_Foot_13</h1>
  <nav>
    <a href="#gallery">Galerie</a>
    <a href="#request">Demander une affiche</a>
    <a href="#about">En savoir plus</a>
  </nav>
</header>

<!-- Galerie -->
<section id="gallery">
  <h2>Mes affiches</h2>
  <div class="gallery">
    <div class="poster">
      <img src="OM.png" alt="Liverpool vs OM">
      <p>Liverpool vs OM</p>
    </div>
    <div class="poster">
      <img src="Derby.png" alt="Manchester United vs Manchester City">
      <p>Manchester United vs Manchester City</p>
    </div>
    <div class="poster">
      <img src="Nantes.png" alt="OM vs Nantes">
      <p>OM vs Nantes</p>
    </div>
    <div class="poster">
      <img src="Diop.png" alt="Affiche Sofiane Diop">
      <p>Sofiane Diop</p>
    </div>
    <div class="poster">
      <img src="inconnu.png" alt="Affiche ASC BATARELLE">
      <p>ASC BATARELLE</p>
    </div>
    <div class="poster">
      <img src="FRANCFORT.png" alt="Francfort vs Dortmund">
      <p>Francfort vs Dortmund</p>
    </div>
    <div class="poster">
      <img src="collab.png" alt="Bayeux vs OM">
      <p>Bayeux vs OM</p>
    </div>
  </div>
</section>

<!-- Formulaire de demande -->
<section id="request">
  <h2>Demander une affiche</h2>
  <form action="mailto:ilanmathe61@gmail.com" method="post" enctype="text/plain">
    <input type="text" name="Nom" placeholder="Ton nom" required>
    <input type="email" name="Email" placeholder="Ton email" required>
    <textarea name="Demande" placeholder="Décris ton affiche (match, joueur, style...)" required></textarea>
    <button type="submit">Envoyer ma demande</button>
  </form>
</section>

<!-- En savoir plus -->
<section id="about">
  <h2>En savoir plus</h2>
  <p style="max-width:700px; margin:auto; text-align:center; font-size:1.1rem; line-height:1.8;">
    Bonjour, moi c’est <strong>Design_Foot_13</strong> !<br>
    Je crée des affiches de foot payantes et j’ai eu l’honneur de collaborer avec <strong>l’Olympique de Marseille</strong>.<br>
    Si vous voulez une affiche personnalisée, n’hésitez pas à m’envoyer votre demande via le formulaire ci-dessus !
  </p>
</section>

<footer>
  © 2026 Design_Foot_13
</footer>

</body>
</html>
