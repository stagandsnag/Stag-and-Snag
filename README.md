<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Stags and Snags</title>
  <style>
    body {
      font-family: Georgia, serif;
      background-color: #f4f1ec;
      color: #333;
      padding: 20px;
      line-height: 1.5;
    }
    .card {
      max-width: 400px;
      margin: auto;
      background: #e2d6c3;
      padding: 20px;
      border: 1px solid #ccc;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .front, .back {
      text-align: center;
      margin-bottom: 20px;
    }
    .front h1 {
      font-size: 1.8rem;
      color: #2e4a1e;
      margin: 0;
    }
    .front p {
      margin-top: 0.25rem;
      font-size: 1.1rem;
      color: #47502e;
    }
    .front .graphics {
      font-size: 4rem;
      margin-bottom: 10px;
    }
    .back h2 {
      font-size: 1.3rem;
      margin: 0;
    }
    .back a {
      color: #2e4a1e;
      text-decoration: none;
    }
    .qr-placeholder {
      margin-top: 15px;
      width: 150px;
      height: 150px;
      background: white;
      border: 2px dashed #aaa;
      display: inline-block;
    }
  </style>
</head>
<body>
  <main class="card" role="main" aria-label="Business card preview">
    <section class="front" aria-label="Front of card">
      <div class="graphics">🌲🦌🕊️</div>
      <h1>Stags and Snags</h1>
      <p>A sustainable way to your food</p>
    </section>
    <section class="back" aria-label="Back of card">
      <h2>James Robinson</h2>
      <a href="mailto:james@stagsandsnags.co.uk">james@stagsandsnags.co.uk</a>
      <div class="qr-placeholder" aria-label="Placeholder for QR code"></div>
    </section>
  </main>
</body>
</html>
