<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ProVia – Profesional • Viață • Viziune</title>
  <meta name="description" content="Coaching de viață și consultanță în carieră cu Andreea Luchian – descoperă-ți potențialul, atinge echilibrul și încrederea în tine." />
  <meta name="keywords" content="coaching, consultanță carieră, dezvoltare personală, Andreea Luchian, leadership, viață profesională" />
  <meta name="author" content="Andreea Luchian" />
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fffaf7;
      color: #2f2f2f;
    }
    header {
      background-color: #a58adf;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav {
      background: #f3f0f9;
      text-align: center;
      padding: 1rem;
    }
    nav a {
      margin: 0 1rem;
      color: #4b3a78;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    footer {
      text-align: center;
      background: #f3f0f9;
      padding: 1rem;
      font-size: 0.9rem;
    }
    .btn {
      display: inline-block;
      padding: 0.7rem 1.5rem;
      background: #7e64c1;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      margin-top: 1rem;
    }
    .btn:hover {
      background: #5b4891;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-top: 1rem;
    }
    input, textarea {
      padding: 0.8rem;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }
    input[type="submit"] {
      background-color: #7e64c1;
      color: white;
      border: none;
      cursor: pointer;
    }
    input[type="submit"]:hover {
      background-color: #5b4891;
    }
    <a href="#contact" class="btn">Programează o sesiune</a>
  </header>

    <h3>Pachete disponibile:</h3>
    <ul>
      <li>Sesiune unică – 150 lei</li>
      <li>Pachet 4 sesiuni – 500 lei</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Completează formularul de mai jos sau scrie-mi direct pe email.</p>
    <form name="contact" method="POST" data-netlify="true">
      <input type="text" name="nume" placeholder="Numele tău" required>
      <input type="email" name="email" placeholder="Emailul tău" required>
      <textarea name="mesaj" rows="5" placeholder="Mesajul tău..." required></textarea>
      <input type="submit" value="Trimite mesajul">
    </form>
    <p>Sau trimite un email la: <a href="mailto:andreealuchian240@yahoo.com">andreealuchian240@yahoo.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 ProVia – Toate drepturile rezervate.</p>
  </footer>
</body>
</html>
