<!DOCTYPE html>
<html lang="lv">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Marina Brice</title>
  <link href="https://fonts.googleapis.com/css2?family=Futura:wght@300;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #E8DEDE;
      font-family: 'Futura', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }

    h1 {
      color: #000;
      font-size: 70px;
      margin: 0;
      opacity: 0;
      animation: fadeIn 2s ease-in forwards;
    }

    p.subtitle {
      font-weight: bold;
      font-size: 17px;
      color: #000;
      margin: 20px 0 40px;
    }

    .button-container {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .nav-button {
      background-color: transparent;
      border: 1px solid black;
      color: black;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      transition: background-color 0.3s, color 0.3s;
    }

    .nav-button:hover {
      background-color: black;
      color: white;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <h1>Marina Brice</h1>
  <p class="subtitle">Klīniskā psiholoģe, kognitīvi biheiviorālā (KBT) terapeite</p>
  <div class="button-container">
    <a href="par-mani.html"><button class="nav-button">Par mani</button></a>
    <a href="pakalpojumi.html"><button class="nav-button">Pakalpojumi</button></a>
    <a href="kontakti.html"><button class="nav-button">Kontakti</button></a>
    <a href="papildmateriali.html"><button class="nav-button">Papildmateriāli</button></a>
  </div>
</body>
</html>
