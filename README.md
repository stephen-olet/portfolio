<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Personal Portfolio or Project Showcase">
  <meta name="author" content="Varad Bhogayata">
  <title>Varad Bhogayata's Portfolio</title>
  <link rel="stylesheet" href="styles.css"> <!-- Link to a CSS file -->
</head>
<body>
  <!-- Header Section -->
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

  <!-- Main Content -->
  <main>
    <!-- Home Section -->
    <section id="home">
      <h1>Welcome to Varad Bhogayata's Portfolio</h1>
      <p>Explore my projects and achievements in web development and beyond.</p>
    </section>

    <!-- About Section -->
    <section id="about">
      <h2>About Me</h2>
      <p>I'm a passionate web developer and programmer with expertise in modern web technologies.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
      <h2>My Projects</h2>
      <div class="project-grid">
        <div class="project-item">
          <h3>Project 1</h3>
          <p>Description of the project.</p>
          <a href="https://github.com/varadbhogayata/project1" target="_blank">View on GitHub</a>
        </div>
        <div class="project-item">
          <h3>Project 2</h3>
          <p>Description of another project.</p>
          <a href="https://github.com/varadbhogayata/project2" target="_blank">View on GitHub</a>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact Me</h2>
      <form action="https://formspree.io/f/YOUR_EMAIL" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        
        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <!-- Footer Section -->
  <footer>
    <p>© 2025 Varad Bhogayata. All rights reserved.</p>
  </footer>
</body>
</html>
