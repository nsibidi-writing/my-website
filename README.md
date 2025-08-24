# my-website
Simple website 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Simple Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: white;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: #4CAF50;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    footer {
      background: #f4f4f4;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Hi! I'm building this simple website to showcase my work and ideas. 
      This is a clean and modern layout that works on both mobile and desktop devices.
    </p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <p>
      I offer web development, design consultation, and digital strategy services.
    </p>
    <a href="#contact" class="btn">Work With Me</a>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email me at: <a href="mailto:yourname@email.com">yourname@email.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 My Simple Website | All Rights Reserved</p>
  </footer>
</body>
</html>
