<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>InfoTechStore</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0d1117;
      color: #c9d1d9;
    }

    header {
      background: #161b22;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 6px rgba(0,0,0,0.6);
    }

    header img {
      height: 60px;
    }

    nav a {
      color: #c9d1d9;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #58a6ff;
      border-bottom: 2px solid #58a6ff;
      padding-bottom: 3px;
    }

    .hero {
      padding: 80px 20px;
      text-align: center;
      background: linear-gradient(rgba(13,17,23,0.8), rgba(22,27,34,0.95)),
                  url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1920&q=80');
      background-size: cover;
      background-position: center;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 20px;
      background: linear-gradient(90deg,#58a6ff,#1f6feb);
      color: #fff;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 4px 12px rgba(0,0,0,0.5);
      transition: all .3s;
    }
    .btn:hover {
      background: linear-gradient(90deg,#1f6feb,#58a6ff);
      transform: scale(1.05);
    }

    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2rem;
      border-bottom: 2px solid #58a6ff;
      display: inline-block;
      padding-bottom: 10px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #161b22;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.5);
      transition: transform 0.2s, box-shadow 0.3s;
      text-align: center;
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.7);
    }

    .card img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .footer {
      background: #161b22;
      padding: 30px;
      text-align: center;
      border-top: 2px solid #58a6ff;
    }

    .footer a {
      color: #58a6ff;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <!-- Header com logos -->
  <header>
    <img src="logo_infotech.jpg" alt="InfoTechStore Logo">
    <nav>
      <a href="#placas-video">Placas de Vídeo</a>
      <a href="#processadores">Processadores</a>
      <a href="#ram">Memórias RAM</a>
      <a href="#ssds">SSDs</a>
      <a href="#placas-mae">Placas-Mãe</a>
      <a href="#gabinetes">Gabinetes</a>
      <a href="#fontes">Fontes</a>
      <a href="#perifericos">Periféricos</a>
      <a href="#contato">Contato</a>
    </nav>
    <img src="logo_apollo12.jpg" alt="Colégio Apollo 12 Logo">
  </header>

  <!-- Hero -->
  <section class="hero">
    <h1>Bem-vindo à InfoTechStore</h1>
    <p>Hardware de alta performance, periféricos modernos e parcerias de confiança.</p>
    <a href="https://wa.me/5521964676217" class="btn">Fale no WhatsApp</a>
  </section>

  <!-- Categorias -->
  <section id="placas-video">
    <h2>Placas de Vídeo</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81Z-1C7mDUL._AC_SL1500_.jpg" alt="RTX 3060">
        <h3>NVIDIA RTX 3060</h3>
        <p>8GB GDDR6 – Excelente custo/benefício para games e edição.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81c5jHBbJjL._AC_SL1500_.jpg" alt="RX 6600">
        <h3>AMD RX 6600</h3>
        <p>8GB GDDR6 – Ótimo desempenho em 1080p/1440p.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <section id="processadores">
    <h2>Processadores</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81rj8F1OVaL._AC_SL1500_.jpg" alt="Ryzen 5 5600X">
        <h3>Ryzen 5 5600X</h3>
        <p>6 núcleos, 12 threads – Potência para jogos e multitarefas.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/71jG+e7roXL._AC_SL1500_.jpg" alt="Intel i5-12400F">
        <h3>Intel i5-12400F</h3>
        <p>6 núcleos, 12 threads – Performance incrível em games.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <section id="ram">
    <h2>Memórias RAM</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/71jM7WcIebL._AC_SL1500_.jpg" alt="RAM 16GB">
        <h3>Memória RAM 16GB DDR4</h3>
        <p>3200MHz – Alto desempenho para jogos e multitarefa.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81dqA9XhDHL._AC_SL1500_.jpg" alt="RAM 8GB">
        <h3>Memória RAM 8GB DDR4</h3>
        <p>2666MHz – Ideal para upgrades rápidos e acessíveis.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <section id="ssds">
    <h2>SSDs / Armazenamento</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/61vQ9rXSV-L._AC_SL1500_.jpg" alt="SSD NVMe">
        <h3>SSD NVMe 1TB</h3>
        <p>Alta velocidade de leitura e gravação.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/71vZqXhA3eL._AC_SL1500_.jpg" alt="HD 1TB">
        <h3>HD 1TB</h3>
        <p>Armazenamento confiável e acessível.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <section id="placas-mae">
    <h2>Placas-Mãe</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81hFJ93p3aL._AC_SL1500_.jpg" alt="B450M">
        <h3>Placa-Mãe B450M</h3>
        <p>Compatível com Ryzen – Ideal para builds custo/benefício.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81Rka3f5TUL._AC_SL1500_.jpg" alt="Z690">
        <h3>Placa-Mãe Z690</h3>
        <p>Compatível com Intel 12ª Geração – Desempenho máximo.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <section id="gabinetes">
    <h2>Gabinetes</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/71FqkP9FkDL._AC_SL1500_.jpg" alt="Gabinete RGB">
        <h3>Gabinete Gamer RGB</h3>
        <p>Vidro temperado e iluminação RGB.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81bK0jCS8jL._AC_SL1500_.jpg" alt="Gabinete ATX">
        <h3>Gabinete ATX</h3>
        <p>Espaçoso e elegante, ideal para upgrades futuros.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <section id="fontes">
    <h2>Fontes</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81+9I0zqFAL._AC_SL1500_.jpg" alt="Fonte 500W">
        <h3>Fonte 500W</h3>
        <p>80 Plus Bronze – Eficiência e segurança garantida.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81ZRySUdk-L._AC_SL1500_.jpg" alt="Fonte 650W">
        <h3>Fonte 650W</h3>
        <p>80 Plus Gold – Máxima eficiência para PCs potentes.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <section id="perifericos">
    <h2>Periféricos</h2>
    <div class="grid">
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/71kr3WAj1FL._AC_SL1500_.jpg" alt="Teclado Mecânico">
        <h3>Teclado Mecânico</h3>
        <p>Switches vermelhos – resposta rápida e iluminação RGB.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/71bcMZtM5XL._AC_SL1500_.jpg" alt="Headset Gamer">
        <h3>Headset Gamer</h3>
        <p>Som Surround 7.1 – Confortável para longas jogatinas.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/81bIU6U8x3L._AC_SL1500_.jpg" alt="Mouse Gamer">
        <h3>Mouse Gamer RGB</h3>
        <p>Sensor de alta precisão com DPI ajustável.</p>
        <a href="https://wa.me/5521964676217" class="btn">Comprar</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer" id="contato">
    <p>Entre em contato:</p>
    <a href="https://wa.me/5521964676217">WhatsApp</a> |
    <a href="mailto:dutralucasdutra29@gmail.com">Email</a> |
    <a href="https://instagram.com/luca_sdutra">Instagram</a>
  </footer>

</body>
</html>
# infotechstore.githu.io
