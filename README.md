# cartadeniver
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Para você, amor</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #ffd6e0, #ffe2f0);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      color: #333;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    button {
      background-color: #ff8fa3;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 1.2em;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background-color: #ff6f91;
    }

    .carta {
      display: none;
      max-width: 600px;
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0,0,0,0.2);
      margin-top: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

  <h1>Para você, meu amor ❤️</h1>
  <button onclick="mostrarCarta()">Clique para abrir a cartinha</button>

  <div class="carta" id="carta">
    <p>Oi, meu amor!</p>
    <p>Hoje é seu dia e eu só quero agradecer por ter você na minha vida. Você é o meu porto seguro, meu sorriso fácil, e a melhor parte dos meus dias.</p>
    <p>Que esse novo ciclo venha com muitos sonhos realizados, momentos felizes e muito amor. Te amo demais! Feliz aniversário! 🎂💖</p>
    <p>Com todo meu amor,</p>
    <p>Karol 💌</p>
  </div>

  <script>
    function mostrarCarta() {
      document.getElementById('carta').style.display = 'block';
    }
  </script>

</body>
</html>
