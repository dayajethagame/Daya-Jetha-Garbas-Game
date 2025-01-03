<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Daya Dance Game</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div id="game-container">
    <!-- Header -->
    <header>
      <h1>Step Up with Daya and Jethalal</h1>
      <p>Follow Daya's Garba steps and help Jethalal impress her!</p>
    </header>

    <!-- Character Selection -->
    <div id="character-selection">
      <h2>Select Your Character</h2>
      <div class="characters">
        <button id="daya-btn" class="character-btn">Play as Daya</button>
        <button id="jetha-btn" class="character-btn">Play as Jethalal</button>
      </div>
    </div>

    <!-- Gameplay Area -->
    <div id="game-area" class="hidden">
      <div id="instructions">
        <p id="step">Daya is performing steps... Get ready!</p>
      </div>
      <div id="characters">
        <img id="daya" src="daya.png" alt="Daya" class="hidden">
        <img id="jetha" src="jetha.png" alt="Jethalal" class="hidden">
      </div>
      <div id="controls">
        <button class="control-btn" id="left-btn">⬅️</button>
        <button class="control-btn" id="jump-btn">⬆️</button>
        <button class="control-btn" id="right-btn">➡️</button>
      </div>
    </div>

    <!-- Scoreboard -->
    <div id="scoreboard" class="hidden">
      <h2>Your Score: <span id="score">0</span></h2>
      <button id="restart-btn">Restart Game</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
