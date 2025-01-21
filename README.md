<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name | Web Developer Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>Hi, I’m [Your Name], a beginner web developer passionate about creating user-friendly websites.</p>
    <a href="#projects" class="btn">See My Work</a>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I specialize in building responsive, modern websites using HTML, CSS, and JavaScript. I enjoy solving problems and learning new technologies.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1: Business Website</h3>
      <p>Description: A clean, responsive website for a fictional coffee shop.</p>
      <a href="https://example.com" target="_blank">View Project</a>
    </div>
    <div class="project">
      <h3>Project 2: Landing Page</h3>
      <p>Description: A single-page promotional website for a fictional product.</p>
      <a href="https://example.com" target="_blank">View Project</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Your Name. All rights reserved.</p>
  </footer>
</body>
</html>
