<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Loay Marouf | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: Inter, sans-serif;
  background: #0d1117;
  color: #e6edf3;
}

/* TOP HEADER */
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 50px;
  border-bottom: 1px solid #30363d;
}

.logo {
  font-weight: bold;
  color: #58a6ff;
}

.nav a {
  color: #e6edf3;
  margin-left: 20px;
  text-decoration: none;
}

/* HERO */
.hero {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 60px 50px;
  flex-wrap: wrap;
}

.hero-text {
  max-width: 600px;
}

.hero h1 {
  font-size: 42px;
  margin-bottom: 10px;
}

.hero p {
  color: #8b949e;
  line-height: 1.6;
}

.avatar {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  border: 3px solid #58a6ff;
  object-fit: cover;
}

/* BADGES */
.badges span {
  background: #161b22;
  padding: 5px 10px;
  margin: 5px;
  border-radius: 6px;
  display: inline-block;
  font-size: 12px;
  border: 1px solid #30363d;
}

/* SECTION */
.section {
  padding: 40px 50px;
}

.title {
  font-size: 22px;
  border-left: 4px solid #58a6ff;
  padding-left: 10px;
  margin-bottom: 20px;
}

/* PROJECTS */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
}

.card {
  background: #161b22;
  padding: 20px;
  border-radius: 10px;
  border: 1px solid #30363d;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
  border-color: #58a6ff;
}

/* FOOTER */
.footer {
  text-align: center;
  padding: 30px;
  border-top: 1px solid #30363d;
  color: #8b949e;
}
</style>
</head>

<body>

<!-- HEADER -->
<div class="header">
  <div class="logo">LOAY MAROUF</div>
  <div class="nav">
    <a href="#">About</a>
    <a href="#">Projects</a>
    <a href="#">Contact</a>
  </div>
</div>

<!-- HERO -->
<div class="hero">
  <div class="hero-text">
    <h1>Full Stack Developer 👨‍💻</h1>
    <p>
      Computer Science graduate specialized in building scalable web applications
      using ASP.NET Core, React, Node.js, and real-time systems.
    </p>

    <div class="badges">
      <span>React</span>
      <span>ASP.NET Core</span>
      <span>Node.js</span>
      <span>SQL Server</span>
      <span>MongoDB</span>
      <span>WebSocket</span>
    </div>
  </div>

  <img class="avatar" src="https://github.com/loaywe.png" />
</div>

<!-- ABOUT -->
<div class="section">
  <div class="title">About Me</div>
  <p style="color:#8b949e;">
    Passionate developer with experience in building real-time systems, auction platforms,
    and full-stack enterprise applications. Focused on clean architecture and performance.
  </p>
</div>

<!-- PROJECTS -->
<div class="section">
  <div class="title">Projects</div>

  <div class="grid">

    <div class="card">
      <h3>We Mazad</h3>
      Real-time auction system with WebSocket + Stripe integration.
    </div>

    <div class="card">
      <h3>Employee System</h3>
      ASP.NET Core + React full management system.
    </div>

    <div class="card">
      <h3>Evaluation System</h3>
      PHP + MySQL performance tracking system.
    </div>

    <div class="card">
      <h3>Path Finder</h3>
      Dijkstra algorithm visualization tool.
    </div>

  </div>
</div>

<!-- FOOTER -->
<div class="footer">
  Built with ❤️ by Loay Marouf | Open for opportunities
</div>

</body>
</html>
