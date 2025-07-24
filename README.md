<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ProVia - Dezvoltare personală și consultanță în carieră</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header, footer {
      background-color: #3b3b98;
      color: white;
      padding: 1em;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1em;
      text-decoration: none;
    }
    main {
      padding: 2em;
    }
    section {
      margin-bottom: 2em;
    }
    form {
      max-width: 500px;
      margin: auto;
    }
    input, textarea {
      width: 100%;
      padding: 0.5em;
      margin: 0.5em 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #3b3b98;
      color: white;
      padding: 0.7em 1.5em;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #2f2f72;
    }
  </style>
</head>
<body>
  <header>
    <h1>ProVia</h1>
    <p>Descoperă potențialul tău. Crește. Reușește.</p>
    <nav>
      <a href="#despre">Despre</a>
      <a href="#servicii">Servicii</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="despre">
      <h2>Despre ProVia</h2>
      <p>ProVia este spațiul unde dezvoltarea personală și consultanța în carieră prind contur. Misiunea noastră este să te ajutăm să capeți încredere în tine și să îți urmezi direcția profesională cu claritate și curaj.</p>
    </section>

    <section id="servicii">
      <h2>Servicii</h2>
      <ul>
        <li>Consiliere vocațională și de carieră</li>
        <li>Coaching pentru încredere în sine</li>
        <li>Discuții libere</li>
          <li>Metode de menținere a motivației</li>
    <section id="contact">
      <h2>Contact</h2>
      <p>Ai o întrebare sau vrei să te înscrii la o sesiune? Trimite-ne un mesaj:</p>
      <form action="mailto:andreealuchian240@yahoo.com" method="post" enctype="text/plain">
        <label for="nume">Nume:</label>
        <input type="text" id="nume" name="Nume" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="Email" required>

        <label for="mesaj">Mesajul tău:</label>
        <textarea id="mesaj" name="Mesaj" rows="5" required></textarea>

        <button type="submit">Trimite</button>
      </form>
      <p>Sau scrie-ne direct la: <strong>andreealuchian240@yahoo.com</strong></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 ProVia. Toate drepturile rezervate.</p>
  </footer>
</body>
</html>

