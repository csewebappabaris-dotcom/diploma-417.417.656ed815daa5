<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu PDF</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f9;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      background: #4A90E2;
      color: white;
      width: 100%;
      text-align: center;
      padding: 20px 0;
      font-size: 22px;
      font-weight: bold;
    }

    .container {
      max-width: 900px;
      width: 95%;
      margin: 20px auto;
      background: white;
      box-shadow: 0px 2px 8px rgba(0,0,0,0.2);
      border-radius: 8px;
      overflow: hidden;
    }

    iframe {
      width: 100%;
      height: 600px;
      border: none;
    }

    .download {
      display: block;
      text-align: center;
      padding: 15px;
      background: #4A90E2;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }

    .download:hover {
      background: #357ABD;
    }
  </style>
</head>
<body>
  <header>📄 Visualizador de PDF</header>

  <div class="container">
    <iframe src="arquivo.pdf"></iframe>
    <a class="download" href="arquivo.pdf" download>⬇️ Baixar PDF</a>
  </div>
</body>
</html>
