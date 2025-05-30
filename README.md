<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>O'Vieux Jaru - Épicerie Locale</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 2rem;
      background: #f5f5f5;
      color: #333;
    }
    header {
      text-align: center;
      margin-bottom: 2rem;
    }
    img.logo {
      max-width: 150px;
      border-radius: 50%;
    }
    h1 {
      font-size: 2rem;
      margin-top: 1rem;
    }
    section {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      margin-bottom: 1.5rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    form input, form textarea, form button {
      display: block;
      width: 100%;
      margin-top: 0.5rem;
      margin-bottom: 1rem;
      padding: 0.5rem;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>

  <header>
    <img src="OvieuxJaru_512x512.png" alt="Logo O'Vieux Jaru" class="logo">
    <h1>O'Vieux Jaru</h1>
    <p>Épicerie locale du Jura – Légumes, savons, boissons artisanales</p>
  </header>

  <section>
    <h2>Horaires (exemple)</h2>
    <ul>
      <li>Lundi à vendredi : 9h - 12h / 15h - 19h</li>
      <li>Samedi : 9h - 13h</li>
      <li>Dimanche : fermé</li>
    </ul>
  </section>

  <section>
    <h2>Suivez-nous sur Facebook</h2>
    <p>
      👉 <a href="https://www.facebook.com/profile.php?id=61576133551515" target="_blank">Page Facebook O'Vieux Jaru</a>
    </p>
  </section>

  <section>
    <h2>Contact</h2>
    <form>
      <label>Nom :</label>
      <input type="text" value="Malandain Armand" disabled>

      <label>Votre e-mail :</label>
      <input type="email" placeholder="votre@email.com">

      <label>Message :</label>
      <textarea placeholder="Votre message..."></textarea>

      <button type="submit">Envoyer</button>
    </form>
  </section>

</body>
</html>
