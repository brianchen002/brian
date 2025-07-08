<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Foster-Inspired Site</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      color: #2a2a2a;
    }
    header {
      background: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
    }
    header h1 {
      color: #4b2e83;
      margin: 0;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #4b2e83;
      font-weight: 500;
    }
    .hero {
      background: linear-gradient(rgba(75,46,131,0.8), rgba(75,46,131,0.8)), url('https://source.unsplash.com/1600x600/?university');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 100px 40px;
      text-align: center;
    }
    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .section {
      display: flex;
      padding: 60px 40px;
      justify-content: space-around;
      background: #f7f7f7;
    }
    .card {
      width: 30%;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .card h3 {
      color: #4b2e83;
    }
    footer {
      background: #e0e0e0;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Welcome to My Site</h2>
    <p>Inspired by the Foster School of Business layout</p>
  </div>

  <div class="section">
    <div class="card" id="about">
      <h3>About Me</h3>
      <p>I'm a business analytics student passionate about data, design, and innovation.</p>
    </div>
    <div class="card" id="projects">
      <h3>Projects</h3>
      <p>Check out my Python, R, and data visualization projects.</p>
    </div>
    <div class="card" id="contact">
      <h3>Contact</h3>
      <p>Email me at: your.email@example.com</p>
    </div>
  </div>

  <footer>
    &copy; 2025 Brian Chen | This site is not affiliated with UW Foster
  </footer>
</body>
</html>
