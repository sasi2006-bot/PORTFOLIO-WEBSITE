# PORTFOLIO-WEBSITE
NM Project
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Vennila — Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
  <meta name="description" content="Portfolio of Vennila — CSE student, developer." />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="logo" href="#home">Vennila</a>
      <nav id="nav" class="nav">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
        <a class="resume-btn" href="resume.pdf" download>Download Resume</a>
      </nav>
      <button id="nav-toggle" class="nav-toggle" aria-label="Toggle navigation">☰</button>
    </div>
  </header>

  <main>
    <!-- Home -->
    <section id="home" class="hero">
      <div class="container hero-inner">
        <div class="hero-text">
          <h1>Hi, I'm <span>Vennila</span></h1>
          <p>Computer Science student · Aspiring Frontend Developer · Passionate about building useful apps</p>
          <div class="hero-ctas">
            <a class="btn" href="#projects">View Projects</a>
            <a class="btn btn-outline" href="#contact">Contact Me</a>
          </div>
        </div>
        <div class="hero-image">
          <img src="assets/profile.jpg" alt="Vennila profile picture" />
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="about">
      <div class="container">
        <h2>About Me</h2>
        <div class="about-grid">
          <div>
            <p><strong>Name:</strong> Vennila</p>
            <p><strong>College:</strong> Sardar Raja College of Engineering</p>
            <p><strong>Department:</strong> CSE</p>
            <p><strong>Goal:</strong> Become a frontend/software developer to support my family</p>
          </div>
          <div>
            <p>I enjoy learning algorithms, building small web apps, and improving my frontend skills. I’m currently preparing projects and practicing programming for placement opportunities.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="projects">
      <div class="container">
        <h2>Projects</h2>
        <div class="projects-grid" id="projects-grid">
          <article class="card">
            <img src="assets/project1.png" alt="Project 1 screenshot" />
            <h3>Interactive Form Validation</h3>
            <p>Client-side form validation with real-time feedback and accessible UI.</p>
            <div class="card-links">
              <a href="https://github.com/yourusername/repo1" target="_blank" rel="noopener">GitHub</a>
              <a href="#" target="_blank" rel="noopener">Live</a>
            </div>
          </article>

          <article class="card">
            <img src="assets/project2.png" alt="Project 2 screenshot" />
            <h3>Portfolio Website</h3>
            <p>Responsive portfolio website built using HTML, CSS and JavaScript.</p>
            <div class="card-links">
              <a href="https://github.com/yourusername/portfolio" target="_blank" rel="noopener">GitHub</a>
              <a href="#" target="_blank" rel="noopener">Live</a>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="skills">
      <div class="container">
        <h2>Skills</h2>
        <div class="skills-list">
          <div class="skill">
            <p>HTML</p>
            <div class="progress"><span style="width:95%"></span></div>
          </div>
          <div class="skill">
            <p>CSS</p>
            <div class="progress"><span style="width:90%"></span></div>
          </div>
          <div class="skill">
            <p>JavaScript</p>
            <div class="progress"><span style="width:85%"></span></div>
          </div>
          <div class="skill">
            <p>Algorithms & Data Structures</p>
            <div class="progress"><span style="width:80%"></span></div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact">
      <div class="container contact-inner">
        <div class="contact-form">
          <h2>Contact Me</h2>
          <form id="contactForm" novalidate>
            <label>
              <span>Name</span>
              <input type="text" id="name" name="name" required />
              <small class="error" id="error-name"></small>
            </label>

            <label>
              <span>Email</span>
              <input type="email" id="email" name="email" required />
              <small class="error" id="error-email"></small>
            </label>

            <label>
              <span>Message</span>
              <textarea id="message" name="message" rows="5" required></textarea>
              <small class="error" id="error-message"></small>
            </label>

            <button type="submit" class="btn">Send Message</button>
          </form>
        </div>

        <div class="contact-info">
          <h3>Get in touch</h3>
          <p><strong>Email:</strong> <a href="mailto:vennila@example.com">vennila@example.com</a></p>
          <p><strong>Phone:</strong> +91-XXXXXXXXXX</p>
          <div class="socials">
            <a href="#" target="_blank" rel="noopener">GitHub</a>
            <a href="#" target="_blank" rel="noopener">LinkedIn</a>
            <a href="#" target="_blank" rel="noopener">Instagram</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Vennila — Sardar Raja College of Engineering</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
