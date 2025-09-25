# DR-Anton<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Поздравление для Семейкина Антона Юрьевича</title>
  <style>
    body {
      margin: 0;
      font-family: "Georgia", serif;
      background: linear-gradient(to bottom, #3a2c0a, #1a1205);
      color: #f5d76e;
      text-align: center;
      min-height: 100vh;
      overflow: hidden;
    }
    h1 {
      font-size: 3em;
      color: #ffd700;
      text-shadow: 0 0 15px #ffcc00, 0 0 30px #ff9900;
      animation: shine 3s infinite alternate;
      margin-top: 80px;
    }
    h2 {
      margin-top: 10px;
      font-size: 2em;
      color: #fff8dc;
    }
    .big40 {
      font-size: 8em;
      font-weight: bold;
      background: linear-gradient(45deg, #ffd700, #fff8dc, #ffa500);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 30px #ffcc00, 0 0 60px #ff9900;
      animation: pulse 2s infinite alternate;
      margin: 20px 0;
    }
    p {
      margin-top: 20px;
      font-size: 1.3em;
      line-height: 1.5;
      color: #f0e68c;
    }
    .gold-nugget {
      position: absolute;
      width: 60px;
      height: 60px;
      background: radial-gradient(circle at 30% 30%, #ffd700, #b8860b);
      border-radius: 50%;
      animation: float 10s infinite;
      opacity: 0.7;
    }
    .gold-nugget:nth-child(1) { top: 10%; left: 15%; animation-delay: 0s; }
    .gold-nugget:nth-child(2) { top: 40%; left: 70%; animation-delay: 2s; }
    .gold-nugget:nth-child(3) { top: 70%; left: 30%; animation-delay: 4s; }
    .gold-nugget:nth-child(4) { top: 20%; left: 80%; animation-delay: 6s; }

    @keyframes shine {
      0% { text-shadow: 0 0 10px #ffcc00; }
      100% { text-shadow: 0 0 25px #ff9900, 0 0 50px #ffd700; }
    }
    @keyframes float {
      0% { transform: translateY(0px) rotate(0deg); }
      50% { transform: translateY(-20px) rotate(180deg); }
      100% { transform: translateY(0px) rotate(360deg); }
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      100% { transform: scale(1.1); }
    }

    /* Салют */
    .firework {
      position: absolute;
      border-radius: 50%;
      animation: explode 1.5s ease-out infinite;
    }
    @keyframes explode {
      0% {
        width: 2px; height: 2px;
        opacity: 1;
        transform: translateY(0);
      }
      100% {
        width: 120px; height: 120px;
        opacity: 0;
        transform: translateY(-50px);
      }
    }
  </style>
</head>
<body>
  <!-- Золотые самородки -->
  <div class="gold-nugget"></div>
  <div class="gold-nugget"></div>
  <div class="gold-nugget"></div>
  <div class="gold-nugget"></div>

  <!-- Салют (несколько вспышек) -->
  <div class="firework" style="top:20%; left:30%; background: radial-gradient(circle, #ff4500, transparent); animation-delay: 0s;"></div>
  <div class="firework" style="top:40%; left:60%; background: radial-gradient(circle, #ffff00, transparent); animation-delay: 0.5s;"></div>
  <div class="firework" style="top:60%; left:40%; background: radial-gradient(circle, #00ffcc, transparent); animation-delay: 1s;"></div>
  <div class="firework" style="top:30%; left:80%; background: radial-gradient(circle, #ff00ff, transparent); animation-delay: 1.2s;"></div>

  <h1>Семейкин Антон Юрьевич!</h1>
  <div class="big40">40</div>
  <h2>С Юбилеем!</h2>
  <p>
    40 лет — золотой рубеж,<br>
    возраст силы, мудрости и новых побед!<br><br>
    Пусть жизнь сияет ярче слитков,<br>
    а удача добывается легко, словно золото<br>
    в твоих руках!<br><br>
    Счастья, здоровья и неиссякаемой энергии!
  </p>

  <!-- Музыка -->
  <audio controls autoplay loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    Ваш браузер не поддерживает аудио.
  </audio>
  <p style="font-size:0.9em; color:#aaa;">(Здесь можно вставить ссылку на Flipsyde – Happy Birthday)</p>
</body>
</html>
