
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sir Picture - Studio créatif</title>
  <style>
    body { margin: 0; font-family: 'Segoe UI', sans-serif; background-color: #000; color: #fff; }
    header { background-color: #ff5c00; padding: 20px; text-align: center; }
    header h1 { margin: 0; font-size: 2.8em; }
    header p { margin: 8px 0 0; }
    nav { text-align: center; margin: 20px 0; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; font-weight: bold; }
    .hero { padding: 60px 20px; text-align: center; }
    .hero h2 { font-size: 2.2em; margin-bottom: 20px; }
    .cta { background-color: #ff5c00; color: #000; padding: 15px 30px; border: none; font-size: 1.1em; cursor: pointer; margin-top: 20px; }
    .section { padding: 60px 20px; max-width: 1000px; margin: auto; }
    .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; margin-top: 30px; }
    .card { background-color: #111; padding: 20px; border-radius: 10px; text-align: center; border: 1px solid #ff5c00; }
    .card img { width: 100%; border-radius: 6px; margin-top: 10px; }
    footer { text-align: center; padding: 30px; background-color: #111; color: #aaa; }
    .whatsapp { color: #25d366; font-weight: bold; }
  </style>
</head>
<body>

  <header>
    <h1>Sir Picture</h1>
    <p>Transformez vos idées en images</p>
  </header>

  <nav>
    <a href="#services">Nos Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Photo. Vidéo. Graphisme. Motion Design.</h2>
    <p>Votre studio créatif 360° basé au Sénégal</p>
    <button class="cta">Réserver maintenant</button>
  </section>

  <section id="services" class="section">
    <h2>Nos Services</h2>
    <div class="services">
      <div class="card">
        <h3>Shooting Photo</h3>
        <p>Portraits pro, événements, book personnel.</p>
        <img src="images/shooting_photo.png" alt="Shooting Photo">
      </div>
      <div class="card">
        <h3>Vidéo</h3>
        <p>Clips musicaux, interviews, publicités.</p>
        <img src="images/video.png" alt="Vidéo">
      </div>
      <div class="card">
        <h3>Motion Design</h3>
        <p>Animations modernes et percutantes.</p>
        <img src="images/motion_design.png" alt="Motion Design">
      </div>
      <div class="card">
        <h3>Graphisme & Retouche</h3>
        <p>Création visuelle et amélioration photo.</p>
        <img src="images/graphisme.png" alt="Graphisme et Retouche">
      </div>
    </div>
  </section>

  <section id="portfolio" class="section">
    <h2>Quelques-unes de nos réalisations</h2>
    <p>Voici un aperçu de nos projets récents. Chaque image raconte une histoire unique.</p>
    <div class="services">
      <img src="images/shooting_photo.png" alt="Portfolio 1" class="card">
      <img src="images/video.png" alt="Portfolio 2" class="card">
      <img src="images/motion_design.png" alt="Portfolio 3" class="card">
      <img src="images/graphisme.png" alt="Portfolio 4" class="card">
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contactez-nous</h2>
    <p>📱 WhatsApp : <span class="whatsapp">+221 76 605 56 86</span></p>
    <p>📧 Email : contact@sirpicture.com</p>
    <p>📅 <a href="https://tally.so" target="_blank" style="color:#ff5c00;">Réserver via le formulaire</a></p>
  </section>

  <footer>
    &copy; 2025 Sir Picture - Tous droits réservés
  </footer>

</body>
</html>
