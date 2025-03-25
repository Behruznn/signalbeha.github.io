# signalbeha.github.io
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0"/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Libre+Franklin:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles/style.css">
  <link rel="stylesheet" href="styles/home.css">
  <title> @SIGNAL_TJ_BOT</title>
</head>

<body id="body">
    <div class="container">
      <img class="bot-logo" src="assets/icons/bot-logo.png"></img>
      <h1 id="chooseGameText" class="choose-game">CHOOSE A GAME</h1>
        
      <div class="games-container">
        <a class="game-link" href="./mines.html">
          <div class="game-logo-square">
            <img class="game-logo" src="assets/images/mines.jpg"/>
          </div>
          <p class="game-name">MINES</p>
        </a>

        <a class="game-link" href="./bombucks.html">
          <div class="game-logo-square">
            <img class="game-logo" src="assets/images/bombucks.jpg"/>
          </div>
          <p class="game-name">BOMBUCKS</p>
        </a>

        <a class="game-link" href="./lucky_jet.html">
          <div class="game-logo-square">
            <img class="game-logo" src="assets/images/lucky-jet.jpg"/>
          </div>
          <p class="game-name">LUCKY JET</p>
        </a>

        <a class="game-link" href="./royal_mines.html">
          <div class="game-logo-square">
            <img class="game-logo" src="assets/images/royal-mines.jpg"/>
          </div>
          <p class="game-name">ROYAL MINES</p>
        </a>

      </div>
      
      <a href="https://t.me/tajwinnerr" id="helpButton" class="help-button">SUPPORT</a>
      
      <video autoplay loop muted playsinline width="100%" height="100%" src="assets/videos/cells.MP4" type="video/mp4" class="bgvideo" id="bgvideo"></video> 
    </div>
    
  <audio id="clickSoundEffect" src="assets/audio/click.mp3" preload="auto" volume="0.2"></audio>

  <script src="https://telegram.org/js/telegram-web-app.js"></script>
  <script src="scripts/sctipt.js"></script>
  <script src="scripts/home.js"></script>
</body>

</html>
