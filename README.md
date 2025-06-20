<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CodeXsino | Web Developer & Tech Solutions</title>
  <style>
    :root {
      --primary: #0070f3;
      --dark: #1a1a1a;
      --light: #f4f4f4;
      --accent: #00ffcc;
      --text: #ffffff;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--dark);
      color: var(--text);
      Text-align: center;
    }
    header {
      background: #232635;
      padding: 1em 1.5em;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    .logo-container {
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .logo-container img {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      padding: 10 20px;
    }
    .logo-container h1 {
      margin: 0;
      font-size: 1.8em;
    }
    nav {
      background: #0e0e0e;
      padding: 10px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    nav a {
      color: var(--text);
      text-decoration: none;
    }
     .hero h2 {
      font-size: 2rem;
      color: #61dafb;
    }
    .grid {
      display: grid;
      gap: 20px;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    }
    .card {
      background: #2c2f33;
      padding: 20px;
      border-radius: 8px;
    }
     .card img {
      max-width: 100%;
      border-radius: 6px;
    }
    .card h3 {
      margin: 10px 0;
      color: #fff;
    }
    .tag {
      background: #444;
      color: #61dafb;
      display: inline-block;
      padding: 4px 8px;
      border-radius: 4px;
      font-size: 0.8em;
    }
    .btn {
      background: var(--primary);
      color: white;
      padding: 12px 25px;
      border: none;
      margin-top: 20px;
      border-radius: 5px;
      text-decoration: none;
      display: inline-block;
    }
    h3 {
      font-size: 1.8em;
      margin-bottom: 15px;
      border-bottom: 2px solid var(--accent);
      display: inline-block;
    }
    .services, .portfolio, .blog, .testimonials, .contact {
      background: #2a2a2a;
      margin-top: 20px;
      border-radius: 8px;
      padding: 20px;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      margin-bottom: 10px;
    }
    .portfolio img {
      width: 100%;
      max-width: 300px;
      border-radius: 8px;
      margin: 10px;
    }
    .testimonial {
      background: #333;
      padding: 15px;
      margin: 10px 0;
      border-left: 4px solid var(--primary);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      font-size: 0.9em;
    }
    a {
      color: var(--accent);
    }
  </style>
</head>
<body>

  <header>
    <div class="logo-container">
      <img src="logol.png" alt="CodeXsino Logo">
      <h1>CodeX sino</h1>
    </div>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Build the Web with CodeXsino</h2>
    <p>Your trusted partner for websites, apps, AI integration & automation.</p>
    <a href="https://wa.me/2347039968641" class="btn">DM on WhatsApp</a>
  </section>

  <section id="services" class="services">
    <h3>What we Do !!</h3>
    <ul>
      <li>✔️ Custom Website Development (HTML, CSS, JS)</li>
      <li>✔️ Web App Design & Deployment</li>
      <li>✔️ AI Programming & Automation Tools</li>
      <li>✔️ Secure Backend Systems & Databases</li>
      <li>✔️ Ethical Hacking & Cybersecurity Awareness</li>
      <li>✔️ UI/UX for Mobile & Desktop</li>
      <li>✔️ Freelance Projects & Tech Training</li>
    </ul>
  </section>

<section id="projects">
    <h2>My Projects Showcase</h2>
  <div class="grid">
    <div class="card">
      <img src="ion.jpg" alt="Project 1"/>
      <h3>My Portfolio Website</h3>
      <span class="tag">HTML/CSS/JS</span>
      <p>A clean responsive portfolio built from scratch with dark mode.</p>
    </div>
    <div class="card">
      <img src="showca.jpg" alt="Project 2"/>
      <h3>E-commerce App</h3>
      <span class="tag">React / Firebase</span>
      <p>Full-featured e-commerce app with cart, payments & admin dashboard.</p>
    </div>
    <div class="card">
      <img src="via.placeholder.com/300x200" alt="Project 3"/>
      <h3>Blog Platform</h3>
      <span class="tag">Node.js / MongoDB</span>
      <p>Secure blogging platform with authentication and markdown editor.</p>
    </div>
  </div>
</section>


  <section id="testimonials" class="testimonials">
    <h3>What Clients Say</h3>
    <div class="testimonial">
      <p>“CodeXsino helped me launch my business website in just 5 days. Great communication!” – Client A</p>
    </div>
    <div class="testimonial">
      <p>“Clean UI, fast delivery, and professional tech advice. Highly recommend.” – Client B</p>
    </div>
  </section>

  <section id="blog" class="blog">
    <h3>Tech Tips & News</h3>
    <ul>
      <li><strong>🚀 Learn JavaScript Basics in 1 Day</strong></li>
      <li><strong>🔐 Top 5 Security Mistakes Beginners Make</strong></li>
      <li><strong>📱 AI Tools for Developers in 2025</strong></li>
    </ul>
  </section>

  <section id="contact" class="contact">
    <h3>Contact Me</h3>
    <p>📧 Email: <a href="mailto:cybersino29@gmail.com">cybersino29@gmail.com</a></p>
    <p>💬 WhatsApp: <a href="https://wa.me/2347039968641">+234 703 996 8641</a></p>
    <p>📸 Instagram: <a href="https://instagram.com/codesino001">@codeXsino001</a></p>
     <iframe 
    src="https://docs.google.com/forms/d/e/1FAIpQLSc4TABc7LkdGVjopabFAUkIoskCrSrYJ4gUru5pneqi_3Qw7Q/viewform?usp=dialog" 
    width="100%" 
    height="600" 
    frameborder="0" 
    marginheight="0" 
    marginwidth="0">
    Loading…
  </iframe>
  </section>

  <footer>
    &copy; 2025 CodeXsino | Built by Hassan Isah | All rights reserved
  </footer>

</body>
</html>
