
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>PIT STOP DA CERVEJA</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff8e1; /* Amarelo claro */
      color: #4e342e; /* Marrom escuro */
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #ffeb3b; /* Amarelo */
      padding: 20px;
      text-align: center;
      color: #4e342e;
    }

    h1, h2 {
      margin: 0 0 10px 0;
    }

    section {
      padding: 20px;
    }

    .chat-section, .email-section, .bebidas-section, .map-section {
      margin-bottom: 40px;
      border-top: 2px solid #8d6e63;
      padding-top: 20px;
    }

    .bebidas-section ul {
      list-style-type: none;
      padding: 0;
    }

    .bebidas-section li {
      padding: 5px 0;
      border-bottom: 1px dashed #8d6e63;
    }

    footer {
      background-color: #4e342e;
      color: white;
      text-align: center;
      padding: 10px;
    }

    input, textarea, button {
      padding: 10px;
      margin-top: 10px;
      width: 100%;
      max-width: 400px;
      display: block;
    }

    button {
      background-color: #ffeb3b;
      border: none;
      cursor: pointer;
      font-weight: bold;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: 0;
    }

    .translate-container {
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>PIT STOP DA CERVEJA</h1>
    <p>Distribuidora e Conveniência - Exu-PE</p>
  </header>

  <!-- Chat de Atendimento -->
  <section class="chat-section">
    <h2>Chat de Atendimento</h2>
    <form action="https://formspree.io/f/SEU_CODIGO_AQUI" method="POST">
      <label for="nome">Nome:</label>
      <input type="text" name="nome" id="nome" required>

      <label for="mensagem">Mensagem:</label>
      <textarea name="mensagem" id="mensagem" rows="4" required></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <!-- Chat WhatsApp -->
  <section class="chat-section">
    <h2>Bate-Papo pelo WhatsApp</h2>
    <p>Precisa de atendimento rápido? Fale com a gente pelo WhatsApp!</p>
    <a href="https://wa.me/5587988419369" target="_blank">
      <button>Falar no WhatsApp</button>
    </a>
  </section>

  <!-- Lista de Bebidas -->
  <section class="bebidas-section">
    <h2>Lista de Bebidas</h2>
    <ul>
      <li>🍺 Skol 350ml</li>
      <li>🍺 Brahma 600ml</li>
      <li>🍺 Heineken Long Neck</li>
      <li>🍷 Vinho Tinto Suave</li>
      <li>🥃 Whisky Johnnie Walker</li>
      <li>🍸 Vodka Smirnoff</li>
      <li>🥤 Coca-Cola 2L</li>
      <li>🧃 Suco de Laranja Natural</li>
    </ul>
  </section>

  <!-- Cadastro de Email -->
  <section class="email-section">
    <h2>Cadastre seu Email</h2>
    <form action="https://formspree.io/f/SEU_CODIGO_AQUI" method="POST">
      <input type="email" name="email" placeholder="Digite seu e-mail" required>
      <button type="submit">Cadastrar</button>
    </form>
  </section>

  <!-- Google Maps -->
  <section class="map-section">
    <h2>Onde Estamos</h2>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3949.9822357284785!2d-39.727326725630176!3d-7.504113475629516!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7a1718f535799a9%3A0xe236c50f91d8858f!2sR.%20Lulu%20Moreira%2C%2071%20-%20Centro%2C%20Exu%20-%20PE%2C%2056270-000!5e0!3m2!1spt-BR!2sbr!4v1692499886464!5m2!1spt-BR!2sbr"
      allowfullscreen="" loading="lazy">
    </iframe>
  </section>

  <!-- Google Tradutor -->
  <div class="translate-container">
    <div id="google_translate_element"></div>
  </div>

  <footer>
    <p>&copy; 2025 PIT STOP DA CERVEJA - Todos os direitos reservados</p>
  </footer>

  <!-- Google Translate Script -->
  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({
        pageLanguage: 'pt',
        includedLanguages: 'en,es,fr,it,de'
      }, 'google_translate_element');
    }
  </script>
  <script src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
</body>
</html>
