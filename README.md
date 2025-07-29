<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>World Soccer Manager</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>World Soccer Manager</h1><div id="chooseTeam" class="card">
  <h2>Escolha seu time</h2>
  <select id="teamSelect"></select>
  <button onclick="startGame()">Começar</button>
</div>

<div id="gamePanel" style="display: none;">
  <div class="info">
    <p><strong>Time:</strong> <span id="currentTeamName"></span></p>
    <p><strong>Moedas:</strong> <span id="coins">0</span></p>
    <p><strong>Kits médicos:</strong> <span id="kits">6</span></p>
  </div>

  <div class="store card">
    <h2>Loja</h2>
    <div class="store-item">2 kits médicos - R$4,99</div>
    <div class="store-item">10 kits médicos - R$9,99</div>
    <div class="store-item">200 moedas - R$4,99</div>
    <div class="store-item">1000 moedas - R$9,99</div>
    <p style="font-size: 0.8em; color: gray;">(Simulação visual apenas)</p>
  </div>

  <div class="league card">
    <h2>Liga</h2>
    <ul id="leagueTable"></ul>
  </div>
</div>

  </div>  <script src="script.js"></script></body>
</html>
