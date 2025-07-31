<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SpeedyDrive - Car Rentals</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #007BFF;
      color: #fff;
      padding: 20px 0;
      text-align: center;
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
      margin: auto;
      background: #fff;
      margin-top: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    h2 {
      color: #007BFF;
      margin-bottom: 20px;
    }

    ul {
      list-style: square;
      padding-left: 20px;
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
      background: #333;
      color: white;
      margin-top: 40px;
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
    <h1>SpeedyDrive Car Rentals</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#cars">Available Cars</a>
      <a href="#book">Book a Car</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to SpeedyDrive!</h2>
    <p>Rent a car easily and affordably. Whether you're traveling for business or leisure, we have the perfect vehicle for you.</p>
  </section>

  <section id="cars">
    <h2>Available Cars</h2>
    <ul>
      <li><strong>Toyota Corolla</strong> - Compact, Fuel Efficient</li>
      <li><strong>Ford Explorer</strong> - SUV, Family Friendly</li>
      <li><strong>BMW 3 Series</strong> - Luxury, Smooth Ride</li>
      <li><strong>Fiat 500</strong> - Small, City Car</li>
    </ul>
  </section>

  <section id="book">
    <h2>Book a Car</h2>
    <form action="/submit-booking" method="post">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="car">Choose a car:</label>
      <select id="car" name="car">
        <option value="Toyota Corolla">Toyota Corolla</option>
        <option value="Ford Explorer">Ford Explorer</option>
        <option value="BMW 3 Series">BMW 3 Series</option>
        <option value="Fiat 500">Fiat 500</option>
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
    <p>Email: info@speedydrive.com</p>
    <p>Phone: +355 69 123 4567</p>
    <p>Address: Rruga e Durrësit, Tirana, Albania</p>
  </section>

  <footer>
    <p>&copy; 2025 SpeedyDrive. All rights reserved.</p>
  </footer>

</body>
</html>
