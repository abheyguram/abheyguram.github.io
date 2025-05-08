<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Abhey Singh Guram, Beloit College senior in Political Science, Quantitative Economics, and Environmental Studies, focusing on climate and economic research." />
  <meta name="keywords" content="Abhey Guram, portfolio, economics, political science, climate research, Beloit College" />
  <title>Abhey Singh Guram</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Lora:wght@400;500&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Lora', serif;
      background: #f8efe4; /* Ivory */
      color: #333;
      line-height: 1.9;
      scroll-behavior: smooth;
    }

    header {
      background: #2e4a3e; /* Sage green */
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      border-bottom: 1px solid #d4a373; /* Gold */
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5em;
      font-weight: 700;
      color: #f8efe4;
      letter-spacing: 1px;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin-top: 15px;
      gap: 25px;
    }

    nav ul li a {
      font-family: 'Lora', serif;
      color: #f8efe4;
      text-decoration: none;
      font-size: 1.1em;
      padding: 5px 10px;
      transition: color 0.3s, background 0.3s;
    }

    nav ul li a:hover, nav ul li a:focus {
      color: #d4a373;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 5px;
      outline: none;
    }

    .hero {
      position: relative;
      height: 500px;
      overflow: hidden;
      text-align: center;
      padding: 80px 20px;
      background: #f8efe4; /* Fallback */
      border-bottom: 1px solid #d4a373;
    }

    .carousel {
      position: absolute;
      top: 0;
      left: 0;
      width: 300%;
      height: 100%;
      display: flex;
      animation: slide 15s infinite ease-in-out;
    }

    .carousel img {
      width: 33.33%;
      height: 100%;
      object-fit: cover;
      filter: sepia(20%);
    }

    @keyframes slide {
      0% { transform: translateX(0); }
      33.33% { transform: translateX(-33.33%); }
      66.67% { transform: translateX(-66.67%); }
      100% { transform: translateX(0); }
    }

    .hero img.profile {
      width: 120px;
      height: 120px;
      clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
      border: 3px solid #d4a373;
      margin-bottom: 20px;
      object-fit: cover;
      filter: sepia(20%);
      position: relative;
      z-index: 1;
    }

    .hero h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5em;
      font-weight: 500;
      color: #2e4a3e;
      margin-bottom: 10px;
      position: relative;
      z-index: 1;
    }

    .hero p {
      max-width: 600px;
      margin: 0 auto;
      font-size: 1.2em;
      color: #555;
      position: relative;
      z-index: 1;
    }

    section {
      max-width: 800px;
      margin: 40px auto;
      padding: 25px;
      background: #fff;
      border: 1px solid #d4a373;
      border-radius: 5px;
      position: relative;
      background-image: url('https://via.placeholder.com/100x100?text=Geometric+Pattern');
      background-repeat: repeat;
      background-size: 50px;
      background-opacity: 0.1;
    }

    section h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2em;
      color: #2e4a3e;
      margin-bottom: 20px;
      text-align: center;
      border-bottom: 1px solid #d4a373;
      padding-bottom: 10px;
    }

    .card {
      padding: 15px;
      margin-bottom: 20px;
      border-left: 2px solid #d4a373;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateX(5px);
    }

    .card h3 {
      font-family: 'Lora', serif;
      font-size: 1.5em;
      color: #333;
      margin-bottom: 10px;
    }

    .card p, .card ul {
      color: #555;
      font-size: 1.1em;
    }

    ul li {
      margin-bottom: 10px;
      padding-left: 20px;
      position: relative;
    }

    ul li::before {
      content: '✧';
      position: absolute;
      left: 0;
      color: #d4a373;
    }

    a {
      color: #2e4a3e;
      text-decoration: none;
      border-bottom: 1px solid #d4a373;
    }

    a:hover {
      color: #d4a373;
      border-color: #2e4a3e;
    }

    .cta {
      display: inline-block;
      color: #2e4a3e;
      border: 1px solid #d4a373;
      padding: 10px 20px;
      border-radius: 5px;
      margin-top: 20px;
      font-family: 'Lora', serif;
      transition: background 0.3s, color 0.3s;
    }

    .cta:hover {
      background: #d4a373;
      color: #fff;
      border-color: #d4a373;
    }

    footer {
      background: #2e4a3e;
      color: #f8efe4;
      text-align: center;
      padding: 15px;
      font-family: 'Lora', serif;
      font-size: 1em;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2em;
      }

      nav ul {
        flex-wrap: wrap;
        gap: 15px;
      }

      nav ul li {
        margin: 5px;
      }

      .hero {
        height: 400px;
        padding: 60px 15px;
      }

      .hero h2 {
        font-size: 2em;
      }

      .hero img.profile {
        width: 100px;
        height: 100px;
      }

      section {
        margin: 20px;
        padding: 20px;
      }

      section h2 {
        font-size: 1.8em;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Abhey Singh Guram</h1>
    <nav>
      <ul>
        <li><a href="#home" aria-label="Home">Home</a></li>
        <li><a href="#research" aria-label="Research">Research</a></li>
        <li><a href="#projects" aria-label="Projects">Projects</a></li>
        <li><a href="#journal" aria-label="Travels">Travels</a></li>
        <li><a href="#books" aria-label="Books">Books</a></li>
        <li><a href="#references" aria-label="References">References</a></li>
        <li><a href="#contact" aria-label="Contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="carousel">
      <img src="https://via.placeholder.com/1920x500?text=Minnesota+Wilderness" alt="Minnesota Wilderness Travel Photo" loading="lazy" />
      <img src="https://via.placeholder.com/1920x500?text=Punjab+Villages" alt="Punjab Villages Travel Photo" loading="lazy" />
      <img src="https://via.placeholder.com/1920x500?text=New+York+Cityscape" alt="New York Cityscape Travel Photo" loading="lazy" />
    </div>
    <img src="https://via.placeholder.com/120?text=Profile+Pic" alt="Abhey Singh Guram Portrait" class="profile" loading="lazy" />
    <h2>About Me</h2>
    <p>I’m a recent graduate from Beloit College with triple major in Political Science, Quantitative Economics, and Environmental Studies. I’m interested in political economy, environmental justice, and development policy—especially how strategic decision-making and structural inequalities shape outcomes in global governance and rural economies.
    I’ve developed a strong interest in how policy, power, and economics intersect. I’m now looking to take that curiosity further in graduate school, where I hope to deepen my training in political economy and applied research to inform real-world change.

 <section id="research">
  <h2>Research</h2>

  <div class="card">
    <h3>Climate Negotiations & Game Theory</h3>
    <p>
      Authored <em>"Asymmetric Power, Impatience, and the Climate Commons"</em> (2025), a game-theoretic analysis of global climate negotiations. Forthcoming in <a href="https://about.illinoisstate.edu/critique/" target="_blank">Critique: A Worldwide Student Journal of Politics</a>. <a href="#">[PDF Link]</a>
    </p>
  </div>

  <div class="card">
    <h3>Agrarian Distress in Punjab</h3>
    <p>
      Led 2022 field research surveying 346 small and marginal farmers across rural Punjab, India. Analyzed links between economic stress, mental health, and substance use using econometric and psychological tools. Paper in progress. <a href="#">[PDF Link]</a>
    </p>
  </div>

  <div class="card">
    <h3>Eco-Entrepreneurship & Policy</h3>
    <p>
      Co-authored <em>"Eco-Entrepreneurship and (Unintended?) Rent Seeking"</em> (2024) for the Miller Upton Forum, examining sustainability policy and rent-seeking behavior. Under review for publication. <a href="#">[PDF Link]</a>
    </p>
  </div>
</section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="card">
      <h3>Himalayan Kitchen</h3>
      <p>Led a 2022-2023 project at Beloit College, serving South Asian food and tripling customers.</p>
    </div>
    <div class="card">
      <h3>Venture Capital Course</h3>
      <p>Created case studies in 2023 for a new course on finance and market trends.</p>
    </div>
    <div class="card">
      <h3>Waste Management</h3>
      <p>Saved Beloit College $100,000 yearly as Sustainability Assistant (2021-2023).</p>
    </div>
  </section>

  <section id="journal">
    <h2>Travels</h2>
    <div class="card">
      <p>My travels inspire my work. Here are some highlights:</p>
      <ul>
        <li><strong>Minnesota Wilderness</strong> – Researched environmental justice in 2023, learning survival skills.</li>
        <li><strong>St. Louis & New York</strong> – Led a 2022 student trip to network with alumni.</li>
        <li><strong>Punjab, India</strong> – Studied farmers’ challenges in 2022, connecting with my roots.</li>
      </ul>
    </div>
  </section>

  <section id="books">
    <h2>Books I’m Reading</h2>
    <div class="card">
      <ul>
        <li><a href="https://www.amazon.com/Eco-Emancipation/dp/1234567890" target="_blank">Eco-Emancipation</a> – Exploring environmental liberation.</li>
        <li><a href="https://www.amazon.com/Slow-Violence/dp/1234567891" target="_blank">Slow Violence</a> – Examining gradual environmental harm.</li>
        <li><a href="https://www.amazon.com/Book-Title/dp/1234567892" target="_blank">Book Title</a> – A compelling read on sustainability.</li>
      </ul>
    </div>
  </section>

  <section id="references">
    <h2>References</h2>
    <div class="card">
      <h3>Bob Elder</h3>
      <p>Professor, Department Chair<br>
      Email: <a href="mailto:elder@beloit.edu">elder@beloit.edu</a><br>
      Phone: 608-363-2285<br>
      Office: 104E, School of Business, Pearsons<br>
      <a href="https://www.beloit.edu/live/profiles/44-bob-elder" target="_blank">Profile</a></p>
    </div>
    <div class="card">
      <h3>Pablo Toral</h3>
      <p>Professor of Environmental Studies and International Relations, Co-Chair of Environmental Studies<br>
      Pronouns: he/him/his<br>
      Email: <a href="mailto:toralp@beloit.edu">toralp@beloit.edu</a><br>
      Phone: 608-363-2166<br>
      Office: Room 112A, Morse-Ingersoll Hall<br>
      <a href="https://www.beloit.edu/live/profiles/294-pablo-toral" target="_blank">Profile</a></p>
    </div>
    <div class="card">
      <h3>Randi Mogul</h3>
      <p>Director of Residential Life<br>
      Pronouns: she/her/hers<br>
      Email: <a href="mailto:mogulr@beloit.edu">mogulr@beloit.edu</a><br>
      Phone: 608-363-2350<br>
      Office: Porter Hall<br>
      <a href="https://www.beloit.edu/live/profiles/7270-randi-mogul" target="_blank">Profile</a></p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="card">
      <p>Email me at <strong>abheyguram@gmail.com</strong> or connect on <a href="https://linkedin.com/in/abheyguram" target="_blank">LinkedIn</a>.</p>
      <a href="mailto:abheyguram@gmail.com" class="cta">Get in Touch</a>
    </div>
  </section>

  <footer>
    © 2025 Abhey Singh Guram · Built with Elegance
  </footer>
</body>
</html>
