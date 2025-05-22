
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ASFAND SUBHAN | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: #fff;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    .banner {
      background: url('https://via.placeholder.com/1500x400') no-repeat center/cover;
      color: white;
      padding: 120px 20px;
    }

    .banner h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }

    .about img {
      width: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      border-radius: 4px;
      margin-bottom: 15px;
    }

    .contact form {
      max-width: 500px;
      margin: 0 auto;
      text-align: left;
    }

    .contact label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    .contact input, .contact textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .contact button {
      background: #333;
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 4px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .contact button:hover {
      background: #555;
    }

    footer {
      padding: 20px;
      background: #eee;
      text-align: center;
    }

  </style>
</head>

<body>

  <header>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About Me</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="banner">
    <h1>Hello, I'm ASFAND SUBHAN</h1>
    <p>Welcome to my personal portfolio website</p>
  </section>

  <section id="about" class="about">
    <h2>About Me</h2>
    <img src="images/profile.jpg" alt="ASFAND SUBHAN">
    <p>Hi, I'm ASFAND SUBHAN, a passionate developer who loves creating web applications and digital experiences. I specialize in HTML, CSS, JavaScript, and building clean, responsive, modern websites.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="Project 1">
        <h3>Project Title 1</h3>
        <p>Short description of the project.</p>
        <a href="#" target="_blank">View Project</a>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="Project 2">
        <h3>Project Title 2</h3>
        <p>Short description of the project.</p>
        <a href="#" target="_blank">View Project</a>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="Project 3">
        <h3>Project Title 3</h3>
        <p>Short description of the project.</p>
        <a href="#" target="_blank">View Project</a>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form action="https://formsubmit.co/asfandsubhan515@gmail.com" method="POST">
      <label>Name</label>
      <input type="text" name="name" required>

      <label>Email</label>
      <input type="email" name="email" required>

      <label>Message</label>
      <textarea name="message" rows="5" required></textarea>

      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 ASFAND SUBHAN. All rights reserved.</p>
  </footer>

</body>
</html>
