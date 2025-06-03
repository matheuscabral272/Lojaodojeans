<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lojão do Jeans</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f2f2f2;
    }
    header {
      background-color: #1a1a1a;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #333;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 15px 20px;
      text-decoration: none;
      transition: background 0.3s;
    }
    nav a:hover {
      background-color: #444;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section-title {
      text-align: center;
      font-size: 28px;
      margin-bottom: 20px;
      color: #1a1a1a;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 4px;
    }
    .product h3 {
      margin: 10px 0;
    }
    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .whatsapp {
      display: inline-block;
      margin-top: 10px;
      background-color: #25D366;
      padding: 10px 20px;
      border-radius: 50px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .whatsapp:hover {
      background-color: #1ebd57;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Lojão do Jeans</h1>
    <p>Moda Masculina, Feminina e Infantil para toda a família!</p>
  </header>

  <nav>
    <a href="#masculino">Masculino</a>
    <a href="#feminino">Feminino</a>
    <a href="#infantil">Infantil</a>
    <a href="#localizacao">Localização</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="masculino">
    <h2 class="section-title">Moda Masculina</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/250x300?text=Jeans+Masculino" alt="Jeans Masculino">
        <h3>Calça Jeans Slim</h3>
        <p>Conforto e estilo para o dia a dia.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x300?text=Camisa+Jeans" alt="Camisa Jeans">
        <h3>Camisa Jeans</h3>
        <p>Ideal para todas as ocasiões.</p>
      </div>
    </div>
  </section>

  <section id="feminino">
    <h2 class="section-title">Moda Feminina</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/250x300?text=Short+Jeans+Feminino" alt="Short Feminino">
        <h3>Short Jeans</h3>
        <p>Estilo e liberdade para o verão.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x300?text=Jaqueta+Jeans" alt="Jaqueta Jeans">
        <h3>Jaqueta Jeans</h3>
        <p>Perfeita para dias mais frescos.</p>
      </div>
    </div>
  </section>

  <section id="infantil">
    <h2 class="section-title">Moda Infantil</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/250x300?text=Calça+Infantil" alt="Calça Infantil">
        <h3>Calça Jeans Infantil</h3>
        <p>Durável e confortável para os pequenos.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x300?text=Conjunto+Infantil" alt="Conjunto Infantil">
        <h3>Conjunto Jeans</h3>
        <p>Moda divertida e estilosa para crianças.</p>
      </div>
    </div>
  </section>

  <section id="localizacao">
    <h2 class="section-title">Nossa Localização</h2>
    <p style="text-align:center;">Estamos localizados em Olho d'Água das Cunhãs - MA</p>
    <p style="text-align:center;"><a href="Av.Zezico Costa, 81 - centro, Olho d'Água das Cunhãs - MA, 65706-000" target="_blank">Abrir no Google Maps</a></p>
    <iframe src="https://Av.Zezico Costa, 81 - centro, Olho d'Água das Cunhãs - MA, 65706-000"></iframe>
  </section>

  <section id="contato">
    <h2 class="section-title">Fale Conosco</h2>
    <p style="text-align:center;">Entre em contato pelo WhatsApp:</p>
    <p style="text-align:center;">
      <a class="whatsapp" href="https://wa.me/5582988837207" target="_blank">📱 (82) 98883-7207</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Lojão do Jeans. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
