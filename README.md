# modcraft.github.io
> Official website for Ultimate Mod Craft — Your complete world of Minecraft mods, from powerful add-ons to rare creations.
<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ultimate Mod Craft</title>
  <style>
    :root{
      --bg: #2c2f33;
      --accent: #3ba55d;
      --text: #ffffff;
      --card: #23272a;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family: Arial, Helvetica, sans-serif;
      background: var(--bg);
      color: var(--text);
      display:flex;
      flex-direction:column;
      align-items:center;
      padding:20px;
    }
    header img{
      max-width:300px;
      margin-bottom:20px;
    }
    h1{
      font-size:26px;
      margin-bottom:10px;
      text-align:center;
    }
    p{
      font-size:16px;
      max-width:600px;
      text-align:center;
      margin-bottom:20px;
    }
    .mod-image{
      max-width:800px;
      width:100%;
      border-radius:10px;
      margin-bottom:20px;
    }
    a.download-btn{
      display:inline-block;
      padding:12px 20px;
      background: var(--accent);
      color:#fff;
      text-decoration:none;
      border-radius:8px;
      font-weight:bold;
      transition: background 0.2s;
    }
    a.download-btn:hover{
      background:#2d7f47;
    }
  </style>
</head>
<body>
  <header>
    <img src="ultimate-logo.png" alt="Ultimate Mod Craft Logo">
  </header>
  <h1>Ultimate Mod Craft</h1>
  <p>Your complete world of Minecraft mods, from powerful add-ons to rare creations, everything you need to make your game legendary!</p>
  <img class="mod-image" src="bedrock-ui-screenshot.jpg" alt="Bedrock UI+ Screenshot">
  <a class="download-btn" href="Bedrock-Ui+-Beta-v0.6.5.mcpack" download>Download Mods</a>
</body>
</html>
