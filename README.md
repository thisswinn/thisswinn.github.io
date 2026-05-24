<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
    }

    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    main {
      padding: 40px;
      text-align: center;
    }

    .card {
      background: white;
      padding: 20px;
      margin: 20px auto;
      max-width: 500px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    button {
      padding: 10px 15px;
      border: none;
      background: #111;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background: #333;
    }

    footer {
      text-align: center;
      padding: 15px;
      font-size: 12px;
      color: gray;
    }
  </style>
</head>

<body>

  <header>
    <h1>Website Gue</h1>
  </header>

  <main>
    <div class="card">
      <h2>halo</h2>
      <p>ini website pertama gue pakai HTML + CSS</p>
      <button onclick="alert('kepencet 😭')">klik aku</button>
    </div>
  </main>

  <footer>
    © 2026 My Website
  </footer>

</body>
</html>
