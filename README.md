
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SpeedyDrive - Car Rentals in Shkodër, Albania</title>

  <!-- SEO Meta Tags -->
  <meta name="description" content="SpeedyDrive offers car rentals in Shkodër, Albania. Switch between English and Albanian.">
  <meta name="robots" content="index, follow">
  <meta name="author" content="SpeedyDrive Car Rentals">

  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      background-color: #007BFF;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .language-switcher {
      margin-top: 10px;
    }

    .language-switcher button {
      background-color: white;
      color: #007BFF;
      border: none;
      padding: 6px 12px;
      margin: 5px;
      font-weight: bold;
      border-radius: 4px;
      cursor: pointer;
    }

    .language-switcher button:hover {
      background-color: #e6e6e6;
    }

    section {
      max-width: 1000px;
      margin: 20px auto;
      padding: 30px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    h2 {
      color: #007BFF;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      padding: 8px 0;
      border-bottom: 1px solid #ddd;
    }

    .available {
      color: green;
      font-weight: bold;
    }

    label {
      display: block;
      margin-top: 12px;
    }

    input, select {
      width: 100%;
      padding: 10px;
      margin-bottom: 12px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    input[type="submit"] {
      background-color: #007BFF;
      color: white;
      border: none;
      cursor: pointer;
    }

    input[type="submit"]:hover {
      background-color: #0056b3;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: white;
      margin-top: 40px;
    }

    .social-icons a {
      color: #0077B5;
      font-size: 24px;
      margin-right: 15px;
    }

    .hidden {
      display: none;
    }

    @media (max-width: 768px) {
      nav a {
        display: block;
        margin: 10px 0;
      }

      .language-switcher {
        margin-bottom: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>SpeedyDrive Car Rentals – Shkodër, Albania</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#cars">Cars</a>
      <a href="#book">Book</a>
      <a href="#contact">Contact</a>
    </nav>

    <div class="language-switcher">
      <button onclick="setLanguage('en')">🇬🇧 English</button>
      <button onclick="setLanguage('sq')">🇦🇱 Shqip</button>
    </div>
  </header>

  <!-- English Content -->
  <section class="lang en" id="home">
    <h2>Welcome to SpeedyDrive!</h2>
    <p>Rent your ideal car quickly and affordably. Whether you're planning a business trip or a relaxing holiday, we have the right vehicle for you.</p>
  </section>

  <section class="lang en" id="cars">
    <h2>Available Cars</h2>
    <ul>
      <li><strong>Audi A7</strong> – <span class="available">Available</span></li>
      <li><strong>Volkswagen Golf 6</strong> – <span class="available">Available</span></li>
      <li><strong>Mercedes-Benz C-Class</strong> – <span class="available">Available</span></li>
    </ul>
  </section>

  <section class="lang en" id="book">
    <h2>Book a Car</h2>
    <form>
      <label>Full Name:</label>
      <input type="text" required>
      <label>Email:</label>
      <input type="email" required>
      <label>Pick-up Date:</label>
      <input type="date">
      <label>Drop-off Date:</label>
      <input type="date">
      <input type="submit" value="Book Now">
    </form>
  </section>

  <section class="lang en" id="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 00355692352601</p>
    <p><strong>Address:</strong> <a href="https://maps.app.goo.gl/hgiUoCLy3EKmhfJo9" target="_blank">Rruga Pogej, Shkodër</a></p>
    <div class="social-icons">
      <a href="https://www.instagram.com/autocar_rental_47" target="_blank" title="Instagram">
        <i class="fab fa-instagram"></i>
      </a>
    </div>
  </section>

  <!-- Albanian Content -->
  <section class="lang sq hidden" id="home">
    <h2>Mirësevini në SpeedyDrive!</h2>
    <p>Merr me qira makinën tuaj në mënyrë të shpejtë dhe të lehtë. Për punë apo pushime, kemi makinën që ju duhet.</p>
  </section>

  <section class="lang sq hidden" id="cars">
    <h2>Makina në dispozicion</h2>
    <ul>
      <li><strong>Audi A7</strong> – <span class="available">Në dispozicion</span></li>
      <li><strong>Volkswagen Golf 6</strong> – <span class="available">Në dispozicion</span></li>
      <li><strong>Mercedes-Benz C-Class</strong> – <span class="available">Në dispozicion</span></li>
    </ul>
  </section>

  <section class="lang sq hidden" id="book">
    <h2>Rezervo një Makinë</h2>
    <form>
      <label>Emri i Plotë:</label>
      <input type="text" required>
      <label>Email:</label>
      <input type="email" required>
      <label>Data e Marrjes:</label>
      <input type="date">
      <label>Data e Kthimit:</label>
      <input type="date">
      <input type="submit" value="Rezervo Tani">
    </form>
  </section>

  <section class="lang sq hidden" id="contact">
    <h2>Na Kontaktoni</h2>
    <p><strong>Tel:</strong> 00355692352601</p>
    <p><strong>Adresa:</strong> <a href="https://maps.app.goo.gl/hgiUoCLy3EKmhfJo9" target="_blank">Rruga Pogej, Shkodër</a></p>
    <div class="social-icons">
      <a href="https://www.instagram.com/autocar_rental_47" target="_blank" title="Instagram">
        <i class="fab fa-instagram"></i>
      </a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 SpeedyDrive. All rights reserved. | Të gjitha të drejtat e rezervuara.</p>
  </footer>

  <!-- Language Toggle Script -->
  <script>
    function setLanguage(lang) {
      document.querySelectorAll('.lang').forEach(el => el.classList.add('hidden'));
      document.querySelectorAll('.lang.' + lang).forEach(el => el.classList.remove('hidden'));
    }
    setLanguage('en');
  </script>

</body>
</html>
