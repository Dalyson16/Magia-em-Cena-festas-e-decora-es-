# Magia-em-Cena-festas-e-decora-es-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Magia em Cena Festas e Decorações</title>
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body { line-height: 1.6; color: #333; }
    header {
      background: #000;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    header img {
      height: 80px;
    }
    .hero {
      background: url('SUA_IMAGEM_BANNER_AQUI.jpg') center/cover no-repeat;
      height: 50vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }
    .hero h2 {
      background: rgba(0,0,0,0.6);
      padding: 20px;
      border-radius: 10px;
      font-size: 1.8em;
    }
    section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .galeria img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 15px 20px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .whatsapp:hover {
      background: #1ebd5a;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Magia em Cena Festas e Decorações" />
  </header>

  <div class="hero">
    <h2>Decorando sonhos, criando momentos mágicos.</h2>
  </div>

  <section>
    <h3 style="text-align:center; margin-bottom:30px;">Nossas Decorações</h3>
    <div class="galeria">
      <img src="stitch1.jpg" alt="Decoração Stitch" />
      <img src="monstros.jpg" alt="Decoração Monstros S.A." />
      <img src="cinderela.jpg" alt="Decoração Cinderela" />
      <img src="moana.jpg" alt="Decoração Moana" />
      <img src="babyshark.jpg" alt="Decoração Baby Shark" />
      <img src="stitch2.jpg" alt="Decoração Stitch Balões" />
      <img src="princesas.jpg" alt="Decoração Princesas" />
    </div>
  </section>

  <footer>
    <p>Siga-nos no Instagram: <a href="https://instagram.com/magiaemcenafestas" target="_blank" style="color:#d45d79;">@magiaemcenafestas</a></p>
    <p>&copy; 2025 Magia em Cena Festas e Decorações</p>
  </footer>

  <a class="whatsapp" href="https://wa.me/5531991035173" target="_blank">
    💬 WhatsApp
  </a>

</body>
</html>
