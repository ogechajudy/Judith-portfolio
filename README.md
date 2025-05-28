<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Judith Moraa | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Judith Moraa</h1>
    <p>Front-End Developer | Tech Enthusiast</p>
    <p><em>Scroll down to see my work ↓</em></p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m Judith Moraa, a front-end developer passionate about clean design, interactivity, and user-friendly web experiences. I'm currently learning HTML, CSS, and JavaScript, and I love building cool things on the web!</p>
  </section>

  <section id="skills">
    <h2>My Skills</h2>
    <ul>
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript (Basics)</li>
      <li>Responsive Design</li>
      <li>Git & GitHub</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <div class="project-card">
      <h3>To-Do App</h3>
      <p>A simple to-do list using JavaScript.</p>
      <a href="#">View Project</a> | <a href="#">GitHub</a>
    </div>

    <div class="project-card">
      <h3>Recipe Page</h3>
      <p>A static HTML/CSS page displaying my favorite recipes.</p>
      <a href="#">View Project</a> | <a href="#">GitHub</a>
    </div>

    <div class="project-card">
      <h3>Weather App</h3>
      <p>A weather forecast app using an API and JavaScript basics.</p>
      <a href="#">View Project</a> | <a href="#">GitHub</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:judith@example.com">judith@example.com</a></p>
    <p>GitHub: <a href="https://github.com/ogechajudy" target="_blank">ogechajudy</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/YOUR_LINK" target="_blank">My Profile</a></p>
  </section>

  <footer>
    <p>© 2025 Judith Moraa. Built with ❤️ using HTML & CSS.</p>
  </footer>
</body>
</html>
body {
  font-family: sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
  color: #333;
}

header {
  background: #333;
  color: white;
  padding: 2rem;
  text-align: center;
}

section {
  padding: 2rem;
  max-width: 800px;
  margin: 0 auto;
}

.project-card {
  background: blue;
  padding: 1rem;
  margin-bottom: 1rem;
  border-left: 5px solid #0077cc;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.project-card a {
  color: #0077cc;
  text-decoration: none;
  font-weight: bold;
}

.project-card a:hover {
  text-decoration: underline;
}

#skills ul {
  list-style: square;
  padding-left: 2rem;
}

footer {
  background: #333;
  color: blue;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  body {
    padding: 1rem;
  }

  .project-card {
    margin-bottom: 1.5rem;
  }

  header, footer {
    text-align: center;
  }
}
