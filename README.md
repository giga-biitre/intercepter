<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Intercepter</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  <link rel="icon" type="image/svg" href="assets/images/favicon.svg"/>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
</head>

<body>
  <!--<audio> elements go in here-->
  <div id="audio-wrapper"></div>

  <script src="https://cdn.jsdelivr.net/npm/howler@2.2.3/dist/howler.min.js"></script>
  <script src="libraries/p5.min.js"></script>
  <script src="libraries/matter.min.js"></script>
  <script src="libraries/pd.js"></script>
  <script src="libraries/bower_components/pathfinding/pathfinding-browser.min.js"></script>

  <script src="game/config/vars.js"></script>
  <script src="game/config/preload.js"></script>
  <script src="game/config/util.js"></script>
  <script src="game/config/levels.js"></script>
  
  <script src="game/environment/audio.js"></script>
  <script src="game/environment/particle.js"></script>
  <script src="game/environment/bullet.js"></script>

  <script src="game/interface/button.js"></script>
  
  <script src="game/body/body.js"></script>
  <script src="game/body/block.js"></script>
  <script src="game/body/unit.js"></script>
  <script src="game/body/player.js"></script>
  <script src="game/body/item.js"></script>
  <script src="game/body/base.js"></script>
  <script src="game/body/turret.js"></script>
  

  <script src="game/interface/gameui.js"></script>
  
  <script src="game/scenes/menu.js"></script>
  <script src="game/scenes/game.js"></script>
  <script src="game/scenes/cut.js"></script>
  <script src="game/scenes/fail.js"></script>
  <script src="game/scenes/succeed.js"></script>
  <script src="game/scenes/win.js"></script>
  <script src="game/scenes/powerups.js"></script>
  
  
  <script src="game/run.js"></script> 
</body>

</html>
