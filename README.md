# resume-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chrissie Lazaro | Resume</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background-color: #ffffff;
      color: #333333;
    }

    nav.navbar {
      background-color: #fff;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .hero {
      background: linear-gradient(120deg, #f6d365, #fda085);
      color: #333;
      padding: 100px 0;
      text-align: center;
    }

    .hero h1 {
      font-weight: 700;
      font-size: 3rem;
    }

    section {
      padding: 60px 0;
    }

    h2.section-title {
      border-bottom: 3px solid #fda085;
      display: inline-block;
      margin-bottom: 30px;
      font-weight: 600;
    }

    footer {
      background-color: #f8f9fa;
      color: #666;
      text-align: center;
      padding: 30px 0;
      font-size: 0.9rem;
    }

    a {
      color: #fda085;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li::before {
      content: "• ";
      color: #fda085;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Chrissie Lazaro</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#experience">Experience</a></li>
          <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="container">
      <h1>Chrissie Lazaro</h1>
      <h4>Account Manager / Head of Marketing</h4>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2 class="section-title">About Me</h2>
      <p>
        With a background spanning social media, content, events, PR, and multi-channel strategy, I’ve led campaigns end-to-end — combining creative storytelling with data-driven results. Prior roles across PR, marketing, and stakeholder engagement have sharpened my ability to connect brands with audiences in ways that inspire action.
      </p>
      <p>
        I hold a Bachelor’s in Communication (PR & Advertising) and am passionate about using marketing to help mission-led businesses grow their presence and scale their impact.
      </p>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="bg-light">
    <div class="container">
      <h2 class="section-title">Skills</h2>
      <ul>
        <li>Fluent in Greek</li>
        <li>Excellent communication and interpersonal skills</li>
        <li>Social media strategy & content creation</li>
        <li>Marketing campaign management</li>
        <li>Public relations & stakeholder engagement</li>
      </ul>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience">
    <div class="container">
      <h2 class="section-title">Experience</h2>
      <ul>
        <li><strong>Account Manager / Head of Marketing</strong> – Led end-to-end campaigns, overseeing brand strategy, content direction, and cross-channel execution.</li>
        <li><strong>Waitress, Retail & Pharmacy Roles</strong> – Built strong customer service, communication, and multitasking skills in fast-paced environments.</li>
        <li><strong>PR Internships</strong> – Assisted with media outreach, event coordination, and press release development.</li>
      </ul>
    </div>
  </section>

  <!-- Education Section -->
  <section id="education" class="bg-light">
    <div class="container">
      <h2 class="section-title">Education</h2>
      <ul>
        <li><strong>Bachelor of Communications (PR & Advertising)</strong> – University</li>
        <li><strong>High School Diploma</strong></li>
      </ul>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container text-center">
      <h2 class="section-title">Contact</h2>
      <p><strong>Email:</strong> <a href="mailto:chrissie.lazaro@hotmail.com">chrissie.lazaro@hotmail.com</a></p>
      <p>You can also connect with me on <a href="#">LinkedIn</a> or explore my work on <a href="#">GitHub</a>.</p>
    </div>
  </section>

  <footer>
    <p>© 2025 Chrissie Lazaro | Built with Bootstrap 5</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
