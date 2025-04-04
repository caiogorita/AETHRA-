<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AETHRA | Luxo Ressignificado</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Montserrat:wght@300;500&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      background-color: #0a0f1c;
      color: #ffffff;
      font-family: 'Montserrat', sans-serif;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 2rem 4rem;
      background-color: #0a0f1c;
    }
    header img {
      height: 60px;
    }
    nav a {
      margin: 0 1rem;
      color: #d4af37;
      text-decoration: none;
      font-weight: 300;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffffff;
    }
    .hero {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1606813902954-0f67c3a05c63') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 4rem;
      color: white;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 1rem 2rem;
    }
    section {
      padding: 6rem 4rem;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #d4af37;
    }
    p {
      font-size: 1.1rem;
      line-height: 1.7;
      color: #e0e0e0;
    }
    .values {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.6);
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.03);
    }
    footer {
      background-color: #0a0f1c;
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #d4af37;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="#about">Sobre</a>
      <a href="#mission">Missão</a>
      <a href="#vision">Visão</a>
      <a href="#values">Valores</a>
    </nav>
  </header>  <section class="hero">
    <h1>Luxo Ressignificado pelos Elementos</h1>
  </section>  <section id="about">
    <h2>Sobre a AETHRA</h2>
    <p>
      A AETHRA nasceu para reescrever os códigos do luxo. Fundada por Aléthea Von Kallias, une arte, ciência e consciência ambiental para criar experiências aéreas e automotivas que são tão sustentáveis quanto sublimes. Cada detalhe, da costura invisível à luz que dança com o humor do passageiro, é pensado para quem quer voar — mesmo com os pés no chão.
    </p>
    <div class="gallery">
      <img src="https://blog.paitomotors.com.br/wp-content/uploads/2020/12/post_thumbnail-9cc533c0e725c8cd219edbebe3d483ec.jpeg" alt="Carro de luxo dourado" />
      <img src="https://th.bing.com/th/id/R.97031b7ab62455db14de2849620c9078?rik=hWQpDpyLGoUN6A&pid=ImgRaw&r=0" alt="Avião executivo azul" />
      <img src="https://th.bing.com/th/id/R.813f93f9f1e6d232ff32b38e6e4e1679?rik=kHvMu5Y6VnmRVA&pid=ImgRaw&r=0" alt="Interior de avião de luxo" />
      <img src="https://s1.1zoom.me/big3/208/Ferrari_Sunrises_and_442416.jpg" alt="Carro conceito azul escuro" />
    </div>
  </section>  <section id="mission">
    <h2>Missão</h2>
    <p>
      Redefinir o luxo por meio da inovação sustentável, oferecendo experiências exclusivas que unem elegância, tecnologia de ponta e respeito absoluto ao planeta.
    </p>
  </section>  <section id="vision">
    <h2>Visão</h2>
    <p>
      Ser a referência global em mobilidade de luxo regenerativa, liderando a transformação do setor com design visionário, impacto positivo e experiências sensoriais inesquecíveis.
    </p>
  </section>  <section id="values">
    <h2>Valores</h2>
    <div class="values">
      <p><strong>Sustentabilidade de Alto Padrão</strong><br>Cada detalhe causa o menor impacto e o maior legado positivo.</p>
      <p><strong>Inovação com Propósito</strong><br>Tecnologia a serviço do conforto e da regeneração ambiental.</p>
      <p><strong>Elegância Atemporal</strong><br>Estética e materiais que transcendem tendências.</p>
      <p><strong>Experiência Total</strong><br>Cada interação é uma obra sensorial.</p>
      <p><strong>Transparência e Ética</strong><br>Rastreabilidade, respeito e verdade.</p>
      <p><strong>Exclusividade Responsável</strong><br>Luxo com significado, raro e positivo.</p>
    </div>
  </section>  <footer>
    © 2025 AETHRA. Todos os direitos reservados.
  </footer>
</body>
</html>
