---
layout: default
title: Demi Plié Confecções | Alta Costura e Estilo
lang: pt-BR
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Montserrat:wght@300;400;600&display=swap');

  :root {
    --pink-light: #fff5f7;
    --pink-medium: #fce4ec;
    --pink-accent: #d81b60;
    --pink-soft: #f06292;
    --text-color: #4a4a4a;
    --white: #ffffff;
  }

  body {
    font-family: 'Montserrat', sans-serif;
    color: var(--text-color);
    background-color: var(--white);
    margin: 0;
    line-height: 1.8;
  }

  h1, h2, h3 {
    font-family: 'Playfair Display', serif;
    color: var(--pink-accent);
  }

  .hero {
    background-color: var(--pink-light);
    padding: 100px 20px;
    text-align: center;
    border-bottom: 1px solid var(--pink-medium);
  }

  .hero h1 {
    font-size: 3.5rem;
    margin-bottom: 10px;
    letter-spacing: -1px;
  }

  .hero p {
    font-size: 1.2rem;
    color: var(--pink-soft);
    font-style: italic;
    font-weight: 300;
  }

  .nav-container {
    position: sticky;
    top: 0;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(5px);
    border-bottom: 1px solid var(--pink-light);
    padding: 15px 0;
    z-index: 1000;
    text-align: center;
  }

  .nav-container a {
    text-decoration: none;
    color: var(--text-color);
    margin: 0 20px;
    font-weight: 600;
    font-size: 0.9rem;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: color 0.3s ease;
  }

  .nav-container a:hover {
    color: var(--pink-accent);
  }

  .section {
    padding: 80px 20px;
    max-width: 1000px;
    margin: 0 auto;
    text-align: center;
  }

  .about-text {
    max-width: 700px;
    margin: 0 auto;
    font-size: 1.1rem;
  }

  .grid-portfolio {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 50px;
  }

  .card {
    background: var(--white);
    border: 1px solid var(--pink-light);
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(216, 27, 96, 0.1);
  }

  .card img {
    width: 100%;
    height: 350px;
    object-fit: cover;
    border-bottom: 1px solid var(--pink-light);
  }

  .card-info {
    padding: 20px;
  }

  .card-info h3 {
    font-size: 1.3rem;
    margin-bottom: 5px;
  }

  .card-info p {
    font-size: 0.9rem;
    color: #888;
  }

  .btn-gallery {
    display: inline-block;
    margin-top: 40px;
    padding: 15px 40px;
    background-color: var(--pink-accent);
    color: var(--white);
    text-decoration: none;
    border-radius: 50px;
    font-weight: 600;
    transition: background 0.3s ease;
  }

  .btn-gallery:hover {
    background-color: var(--pink-soft);
  }

  .separator {
    width: 50px;
    height: 2px;
    background: var(--pink-accent);
    margin: 20px auto;
  }

  footer {
    background: var(--pink-light);
    padding: 60px 20px;
    text-align: center;
    margin-top: 100px;
  }

  .social-icons {
    margin: 20px 0;
  }

  .social-icons a {
    margin: 0 15px;
    color: var(--pink-accent);
    font-size: 1.2rem;
    text-decoration: none;
  }
</style>

<div id="inicio" class="hero">
  <h1>Demi Plié Confecções</h1>
  <p>A harmonia perfeita entre o movimento e a costura.</p>
</div>

<nav class="nav-container">
  <a href="#inicio">Início</a>
  <a href="#sobre">Sobre</a>
  <a href="#portfolio">Portfólio</a>
  <a href="/galeria/">Galeria Completa</a>
</nav>

<div class="section" id="sobre">
  <h2>A Nossa Essência</h2>
  <div class="separator"></div>
  <div class="about-text">
    <p>Fundada com o propósito de unir a precisão técnica da alfaiataria com a leveza do ballet, a <strong>Demi Plié Confecções</strong> é especialista em transformar tecidos em expressões de arte. Cada ponto é executado com rigor, cada corte planejado para valorizar a silhueta, e cada peça finalizada com o cuidado que só o trabalho artesanal permite.</p>
    <p>✨ <em>Qualidade, Criatividade e Exclusividade em cada detalhe.</em></p>
  </div>
</div>

<div class="section" id="portfolio">
  <h2>Coleções & Destaques</h2>
  <div class="separator"></div>
  <p>Conheça uma seleção exclusiva dos nossos trabalhos mais recentes.</p>
  
  <div class="grid-portfolio">
    <div class="card">
      <img src="/images/look1.jpg" alt="Vestido Casual Chic">
      <div class="card-info">
        <h3>Linha Casual Chic</h3>
        <p>Leveza para o dia a dia com tecidos nobres.</p>
      </div>
    </div>
    <div class="card">
      <img src="/images/look2.jpg" alt="Alfaiataria Rosa">
      <div class="card-info">
        <h3>Alfaiataria Moderna</h3>
        <p>Cortes estruturados com tons pastéis.</p>
      </div>
    </div>
    <div class="card">
      <img src="/images/look3.jpg" alt="Vestido de Noite">
      <div class="card-info">
        <h3>Moda Festa</h3>
        <p>Brilho e sofisticação para momentos únicos.</p>
      </div>
    </div>
    <div class="card">
      <img src="/images/look4.jpg" alt="Blusa de Renda">
      <div class="card-info">
        <h3>Rendas & Bordados</h3>
        <p>Detalhes feitos à mão com delicadeza.</p>
      </div>
    </div>
    <div class="card">
      <img src="/images/look5.jpg" alt="Conjunto Minimalista">
      <div class="card-info">
        <h3>Minimalismo</h3>
        <p>A beleza da simplicidade em cada costura.</p>
      </div>
    </div>
    <div class="card">
      <img src="/images/look6.jpg" alt="Acessórios Têxteis">
      <div class="card-info">
        <h3>Acessórios</h3>
        <p>O toque final para o seu visual.</p>
      </div>
    </div>
  </div>

  <a href="/galeria/" class="btn-gallery">Acessar Galeria Completa</a>
  <p style="margin-top: 15px; font-size: 0.8rem; color: #aaa;">Explore todo o nosso acervo fotográfico em nossa página dedicada.</p>
</div>

<footer>
  <div class="section">
    <h3>Demi Plié Confecções</h3>
    <div class="separator"></div>
    <p>Onde a moda encontra a sua melhor forma.</p>
    <div class="social-icons">
      <a href="#">Instagram</a>
      <a href="#">WhatsApp</a>
      <a href="#">Pinterest</a>
    </div>
    <p style="font-size: 0.8rem; opacity: 0.7;">
      &copy; 2026 Demi Plié Confecções. Desenvolvido com 💖 para GitHub Pages.
    </p>
  </div>
</footer>
