<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TechSolutions | Web Development & Automation</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

<header class="header">
  <div class="container">
    <h1 class="logo">TechSolutions</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Services</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </div>
</header>

<section class="hero">
  <div class="container">
    <h2>Modern Websites & Smart Automation for Growing Businesses</h2>
    <p>
      I build fast, responsive websites and AI-powered tools that help businesses
      automate tasks, improve efficiency, and scale confidently.
    </p>
    <a href="#" class="btn">View Services</a>
  </div>
</section>

<section class="services">
  <div class="container">
    <h3 class="section-title">What I Do</h3>

    <div class="grid">
      <div class="card">
        <h4>Web Development</h4>
        <p>Clean, responsive, and high-performance websites built with modern technologies.</p>
      </div>

      <div class="card">
        <h4>AI & Automation</h4>
        <p>Smart automation, chatbots, and AI integrations that save time and reduce manual work.</p>
      </div>

      <div class="card">
        <h4>Reliable Delivery</h4>
        <p>Clear communication, scalable solutions, and projects delivered on time.</p>
      </div>
    </div>
  </div>
</section>

<section class="trust">
  <div class="container">
    <h3>Why Work With Me?</h3>
    <ul>
      <li>✔ Clean & maintainable code</li>
      <li>✔ Mobile-first responsive design</li>
      <li>✔ Client-focused problem solving</li>
      <li>✔ Secure and scalable solutions</li>
    </ul>
  </div>
</section>

<footer class="footer">
  <p>© 2026 TechSolutions • Web Development & Automation</p>
</footer>

</body>
</html>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, sans-serif;
  color: #1e293b;
  background: #f8fafc;
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

.header {
  background: #020617;
  padding: 1rem 0;
}

.logo {
  color: #fff;
  margin: 0;
}

.header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: #cbd5f5;
  margin-left: 20px;
  text-decoration: none;
  font-weight: 500;
}

nav a:hover {
  color: #fff;
}

.hero {
  background: linear-gradient(135deg, #1e3a8a, #2563eb);
  color: #fff;
  padding: 5rem 0;
  text-align: center;
}

.hero h2 {
  font-size: 2.2rem;
  max-width: 800px;
  margin: auto;
}

.hero p {
  max-width: 700px;
  margin: 1.5rem auto;
  font-size: 1.1rem;
}

.btn {
  display: inline-block;
  padding: 12px 28px;
  background: #fff;
  color: #1e3a8a;
  border-radius: 30px;
  font-weight: 600;
  text-decoration: none;
}

.services {
  padding: 4rem 0;
}

.section-title {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 1.8rem;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}

.card {
  background: #fff;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

.card h4 {
  margin-top: 0;
  color: #1e3a8a;
}

.trust {
  background: #e2e8f0;
  padding: 3rem 0;
}

.trust ul {
  list-style: none;
  padding: 0;
  max-width: 600px;
  margin: auto;
}

.trust li {
  padding: 10px 0;
  font-size: 1.05rem;
}

.footer {
  background: #020617;
  color: #94a3b8;
  text-align: center;
  padding: 1rem;
}
