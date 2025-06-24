<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Biblioteca Digital</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #4b0082;
      color: white;
      text-align: center;
      padding: 30px 10px;
    }

    main {
      max-width: 1000px;
      margin: 30px auto;
      padding: 0 20px;
    }

    h2 {
      color: #4b0082;
    }

    .ebook-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .ebook {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      transition: transform 0.2s;
    }

    .ebook:hover {
      transform: scale(1.03);
    }

    .ebook a {
      text-decoration: none;
      color: #4b0082;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #777;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Biblioteca Digital</h1>
    <p>Bem-vindo à sua coleção de e-books favoritos!</p>
  </header>

  <main>
    <h2>📚 E-books disponíveis</h2>
    <div class="ebook-grid">
      <div class="ebook">
        <h3>Livro 1</h3>
        <a href="https://link-do-livro1.com" target="_blank">Ler agora</a>
      </div>
      <div class="ebook">
        <h3>Livro 2</h3>
        <a href="https://link-do-livro2.com" target="_blank">Ler agora</a>
      </div>
      <div class="ebook">
        <h3>Livro 3</h3>
        <a href="https://link-do-livro3.com" target="_blank">Ler agora</a>
      </div>
    </div>
  </main>

  <footer>
    © 2025 Biblioteca Digital. Todos os direitos reservados.
  </footer>

</body>
</html>
