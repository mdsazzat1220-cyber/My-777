# My-777
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Demo Game Site</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
    }
    header {
      background: #000;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      color: #ffcc00;
      margin: 0;
    }
    nav button {
      background: #ffcc00;
      border: none;
      padding: 8px 15px;
      margin-left: 10px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }
    .banner {
      background: linear-gradient(90deg, #222, #444);
      padding: 20px;
      text-align: center;
    }
    .banner h2 {
      color: #ffcc00;
      margin: 0;
    }
    .menu {
      display: flex;
      justify-content: center;
      background: #222;
      padding: 10px;
    }
    .menu div {
      margin: 0 15px;
      cursor: pointer;
      font-weight: bold;
    }
    .games {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .game {
      background: #222;
      border-radius: 10px;
      padding: 10px;
      text-align: center;
      transition: transform 0.2s;
    }
    .game:hover {
      transform: scale(1.05);
    }
    .game img {
      max-width: 100%;
      border-radius: 8px;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 15px;
      font-size: 14px;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>DEMO JILI</h1>
    <nav>
      <button>Login</button>
      <button>Sign Up</button>
    </nav>
  </header>  <div class="banner">
    <h2>🎉 Welcome Bonus 1000 Coins 🎉</h2>
    <p>Join now & start playing demo games!</p>
  </div>  <div class="menu">
    <div>HOT</div>
    <div>
