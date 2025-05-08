<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Abhey Singh Guram</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #1a1a1a;
      color: #f0e6d2;
      scroll-behavior: smooth;
    }

    header {
      background-color: #000;
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .dragon-container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100px;
      margin-bottom: 10px;
    }

    .dragon {
      height: 100px;
      animation: float 6s ease-in-out infinite;
    }

    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #f0e6d2;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      background-color: #111;
      margin: 10px 0 0 0;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: #f0e6d2;
      text-decoration: none;
      padding: 10px;
      display: block;
    }

    nav ul li a:hover {
      background-color: #333;
    }

    .carousel {
      overflow: hidden;
      height: 400px;
      position: relative;
    }

    .slides {
      display: flex;
      width: 300%;
      animation: slide 15s infinite;
    }

    .slides img {
      width: 100vw;
      height: 400px;
      object-fit: cover;
    }

    @keyframes slide {
      0% { margin-left: 0; }
      33% { margin-left: -100vw; }
      66% { margin-left: -200vw; }
      100% { margin-left: 0; }
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    section h2 {
      color: #d4af37;
      border-bottom: 1px solid #444;
      padding-bottom: 5px;
    }

    ul li {
      margin-bottom: 10px;
    }

    footer {
      background-color: #000;
      text-align: center;
      padding: 15px;
      color: #f0e6d2;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <div class="dragon-container">
      <img src="https://media.tenor.com/nUgsxiJK2mUAAAAi/dragon-fire-breath.gif" alt="Lego Dragon" class="dragon" />
    </div>
    <h1>Abhey Singh Guram</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#research">Research</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#journal">Journal</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="carousel" id="home">
    <div class="slides">
      <img src="images/carousel1.jpg" alt="Mountains">
      <img src="images/carousel2.jpg" alt="Forest">
      <img src="images/carousel3.jpg" alt="Castle">
    </div>
  </section>

  <section>
    <h2>Welcome</h2>
    <p>Hi! I’m Abhey, a soon-to-be graduate of Beloit College with a triple major in Quantitative Economics, Political Science, and Environmental Studies. I love solving climate problems through research and plan to pursue a Ph.D. My life also revolves around food, mountains, and good stories.</p>
  </section>

  <section id="research">
    <h2>📄 Research</h2>
    <ul>
      <li><strong>Understanding Incentives in Renewable Energy</strong> – A look at how policy impacts adoption rates. [Link]</li>
      <li><strong>Economic Trade-offs in Climate Policy</strong> – Published in Environmental Economics Review. [Link]</li>
    </ul>
  </section>

  <section id="projects">
    <h2>🎒 Projects & Work</h2>
    <ul>
      <li><strong>Carbon Footprint Calculator</strong> – Developed a Python tool to measure emissions at individual level.</li>
      <li><strong>Political Mapping Dashboard</strong> – Interactive D3-based visualization for political trends.</li>
    </ul>
  </section>

  <section id="journal">
    <h2>🏕️ Travel & Photo Journal</h2>
    <p>I document my travels across the U.S., with photos of hikes, food spots, and historic places. Here's a preview:</p>
    <ul>
      <li><strong>Yosemite National Park</strong> – The granite cathedrals of nature.</li>
      <li><strong>New Orleans</strong> – Jazz, jambalaya, and joy.</li>
      <li><strong>Boston</strong> – A scholar’s dream city.</li>
    </ul>
  </section>

  <section id="contact">
    <h2>💌 Contact</h2>
    <p>Want to collaborate or just say hi? Drop me an email at <strong>abhey@example.com</strong> or connect with me on LinkedIn at <strong>linkedin.com/in/abhey</strong>.</p>
  </section>

  <footer>
    &copy; 2025 Abhey Singh Guram · All Rights Reserved
  </footer>

</body>
</html>
