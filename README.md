<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f4f4f4; color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 40px;
      text-align: center;
    }
    header h1 { margin: 0; }
    nav {
      background: #34495e;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      max-width: 900px;
      margin: auto;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi, I'm Juan Dela Cruz</h1>
    <p>Web Developer | Designer | Freelancer</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a passionate developer who loves creating simple and elegant websites.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Project 1</h3>
        <p>Description of project 1.</p>
      </div>
      <div class="card">
        <h3>Project 2</h3>
        <p>Description of project 2.</p>
      </div>
      <div class="card">
        <h3>Project 3</h3>
        <p>Description of project 3.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:juandelacruz@example.com">juandelacruz@example.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Juan Dela Cruz. All rights reserved.</p>
  </footer>
</body>
</html>
