<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nimse Farm - Thomson Seedless Grapes</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-image: url('grapes.jpg'); /* Header background image */
      background-size: cover;
      background-position: center;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px #000;
    }
    header h1 {
      font-size: 3em;
      background-color: rgba(0, 0, 0, 0.5);
      padding: 20px;
      border-radius: 10px;
    }
    .about, .contact, .gallery {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .about img {
      width: 200px;
      border-radius: 50%;
    }
    .about-content {
      display: flex;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .gallery img {
      width: 30%;
      margin: 10px;
      border-radius: 10px;
      object-fit: cover;
    }
    .contact p {
      font-size: 1.2em;
      margin: 10px 0;
    }
    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 10px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Nimse Farm</h1>
  </header>

  <section class="about">
    <h2>About Our Farm</h2>
    <div class="about-content">
      <img src="owner.jpg" alt="Farm Owner" />
      <div>
        <p><strong>Owner:</strong> Amit Ravindra Nimse</p>
        <p><strong>Location:</strong> Dindori, Taluka Niphad, District Nashik</p>
        <p><strong>Speciality:</strong> Thomson Seedless Grapes</p>
      </div>
    </div>
  </section>

  <section class="gallery">
    <h2>Our Grapes</h2>
    <img src="grapes.jpg" alt="Grapes" />
    <img src="harvest1.jpg" alt="Harvesting" />
    <img src="harvest2.jpg" alt="Packed Grapes" />
  </section>

  <section class="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 9588623716</p>
    <p><strong>Instagram:</strong> <a href="https://www.instagram.com/amitnimse17" target="_blank">@amitnimse17</a></p>
  </section>

  <footer>
    &copy; 2025 Nimse Farm. All rights reserved.
  </footer>
</body>
</html>
