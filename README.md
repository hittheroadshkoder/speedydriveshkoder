<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SpeedyDrive - Car Rentals</title>
  <!-- Font Awesome for social icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
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
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: 20px auto;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    h2 {
      color: #007BFF;
      margin-bottom: 20px;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      padding: 8px 0;
      border-bottom: 1px solid #ddd;
    }

    .available {
      color: green;
      font-weight: bold;
    }

    .unavailable {
      color: red;
      font-weight: bold;
    }

    form label {
      display: block;
      margin-bottom: 6px;
      margin-top: 12px;
    }

    input[type="text"],
    input[type="email"],
    input[type="date"],
    select {
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
      padding: 12px 20px;
      border-radius: 4px;
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
      margin-right: 15px;
      color: #0077B5;
      font-size: 24px;
    }

    .social-icons a:hover {
      opacity: 0.7;
    }

    @media (max-width: 768px) {
      section {
        padding: 20px 10px;
      }

      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>SpeedyDrive Car Rentals Shkodër, Albania</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#cars">Available Cars</a>
      <a href="#book">Book a Car</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to SpeedyDrive!</h2>
    <p>Rent your ideal car quickly and affordably. Whether you're planning a business trip or a relaxing holiday, we have the right vehicle for you.</p>
  </section>

  <section id="cars">
    <h2>Available Cars</h2>
    <ul>
      <li>1. <strong>Audi A7</strong> – <span class="available">Available</span></li>
      <li>2. <strong>Audi A4</strong> – <span class="available">Available</span></li>
      <li>3. <strong>Mercedes-Benz C-Class</strong> – <span class="available">Available</span></li>
      <li>4. <strong>Mercedes-Benz E-Class</strong> – <span class="available">Available</span></li>
      <li>5. <strong>Mercedes-Benz A-Class</strong> – <span class="available">Available</span></li>
      <li>6. <strong>Porsche Cayenne</strong> – <span class="available">Available</span></li>
      <li>7. <strong>Volkswagen G-E-T-T-A</strong> – <span class="available">Available</span></li>
      <li>8. <strong>Volkswagen Golf 5</strong> – <span class="available">Available</span></li>
      <li>9. <strong>Volkswagen Golf 6</strong> – <span class="available">Available</span></li>
      <li>10. <strong>Ford Focus</strong> – <span class="available">Available</span></li>
      <li>11. <strong>Seat Altea</strong> – <span class="available">Available</span></li>
      <li>12. <strong>Nissan QASHQAI</strong> – <span class="available">Available</span></li>
    </ul>
  </section>

  <section id="book">
    <h2>Book a Car</h2>
    <form action="/submit-booking" method="post">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="car">Choose a Car:</label>
      <select id="car" name="car">
        <option value="Audi A7">Audi A7</option>
        <option value="Audi A4">Audi A4</option>
        <option value="Mercedes-Benz C-Class">Mercedes-Benz C-Class</option>
        <option value="Mercedes-Benz E-Class">Mercedes-Benz E-Class</option>
        <option value="Mercedes-Benz A-Class">Mercedes-Benz A-Class</option>
        <option value="Porsche Cayenne">Porsche Cayenne</option>
        <option value="Volkswagen G-E-T-T-A">Volkswagen G-E-T-T-A</option>
        <option value="Volkswagen Golf 5">Volkswagen Golf 5</option>
        <option value="Volkswagen Golf 6">Volkswagen Golf 6</option>
        <option value="Ford Focus">Ford Focus</option>
        <option value="Seat Altea">Seat Altea</option>
        <option value="Nissan QASHQAI">Nissan QASHQAI</option>
      </select>

      <label for="pickup">Pick-Up Date:</label>
      <input type="date" id="pickup" name="pickup">

      <label for="dropoff">Drop-Off Date:</label>
      <input type="date" id="dropoff" name="dropoff">

      <input type="submit" value="Book Now">
    </form>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 00355692352601</p>
    <p><strong>Address:</strong> <a href="https://maps.app.goo.gl/hgiUoCLy3EKmhfJo9" target="_blank">Rruga Pogej, Shkodër 4001</a></p>
    <div class="social-icons">
      <a href="https://www.instagram.com/autocar_rental_47?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" title="Instagram">
        <i class="fab fa-instagram"></i>
      </a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 SpeedyDrive. All rights reserved.</p>
  </footer>

</body>
</html>
