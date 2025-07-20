<!DOCTYPE html>
<html>
<head>
  
  <title>My Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background-color: #f0f0f0;
      color: #333;
    }

    /* Header */
    header {
      background-color: #111;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    .logo {
      font-size: 26px;
      font-weight: bold;
    }

    .tagline {
      font-size: 14px;
      color: #aaa;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 10px;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }

    /* Hero */
    .hero {
      background-color: #444;
      color: #fff;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      padding: 40px 20px;
    }

    .hero-content {
      flex: 1;
      padding: 20px;
    }

    .hero-content h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .hero-content p {
      margin-bottom: 20px;
      max-width: 500px;
    }

    .hero-content button {
      background: #007bff;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }

    .hero-image img {
      max-width: 300px;
      border-radius: 10px;
    }

    /* About */
    .about {
      display: flex;
      flex-wrap: wrap;
      padding: 40px 20px;
      background-color: white;
    }

    .about-image img {
      max-width: 250px;
      border-radius: 10px;
      margin: 20px;
    }

    .about-text {
      flex: 1;
      padding: 20px;
    }

    .about-text h2 {
      margin-bottom: 10px;
    }

    .resume-button {
      display: inline-block;
      margin-top: 15px;
      background-color: #007bff;
      color: white;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 5px;
    }

    /* Skills */
    .skills, .projects, .contact {
      padding: 40px 20px;
      background-color: #fff;
      margin-top: 20px;
    }

    .skills ul {
      list-style-type: square;
      padding-left: 20px;
    }

    .projects .project {
      margin-bottom: 20px;
    }

    .projects img {
      width: 100%;
      max-width: 400px;
      border-radius: 10px;
      margin-top: 10px;
    }

    /* Contact */
    .contact p {
      margin: 8px 0;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background-color: #222;
      color: white;
      margin-top: 30px;
    }

    footer a {
      color: #61dafb;
      text-decoration: none;
    }

  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">Online Portfolio</div>
    <p class="tagline">Just another My Blog site</p>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About Me</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Skill</a></li>
        <li><a href="#">Testimonial</a></li>
        <li><a href="#">Experience</a></li>
        <li><a href="#">Works</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h2>Ishanvi Saxena</h2>
      <p>Hi, I’m a passionate web developer and Integrated MCA student. I love building web pages and exploring creative solutions in tech.</p>
      <button>Hire Me</button>
    </div>
    <div class="hero-image">
      <img src="pic.jpg" alt="Profile Image" />
    </div>
  </section>

  <!-- About Section -->
  <section class="about">
    <div class="about-image">
      <img src="pic.jpg" alt="About Me Image" />
    </div>
    <div class="about-text">
      <h2>About Me</h2>
      <p>I am a developer blending creative coding with problem-solving. With hands-on experience in HTML, CSS, and Python, I enjoy turning ideas into digital reality.</p>
      <p>I’m also exploring the world of AI and always eager to contribute to meaningful tech solutions. Let’s build something amazing together!</p>
      <a class="resume-button" href="Ishanvi-Resume.pdf" download>Download Resume</a>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5 & CSS3</li>
      <li>Python (Basics)</li>
      <li>MS Office</li>
      <li>Problem-Solving</li>
      <li>Teamwork & Collaboration</li>
    </ul>
  </section>

  <!-- Projects Section -->
  <section class="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Online Bookstore Website</h3>
      <p>A static HTML & CSS project simulating an online bookstore. Features Home, Catalog, Cart, Payment, and Order Confirmation pages.</p>
      <img src="store.jpg" alt="Online Bookstore Project" />
    </div>
  </section>

  <!-- Contact Section -->
  <section class="contact">
    <h2>Contact</h2>
    <p>Email: ishanvi@example.com</p>
    <p>Phone: +91-9876543210</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Ishanvi Saxena. All rights reserved.</p>
    <a href="#">Portfolio Demo – Click Here</a>
  </footer>

</body>
</html>
