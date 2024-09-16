<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Header -->
<header>
  <h2>My Portfolio</h2>
</header>

<!-- Navigation Menu -->
<div class="navbar">
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</div>

<!-- About Section -->
<section id="about">
  <h1>About Me</h1>
  <p>Hello! I'm [Your Name], a passionate developer with skills in web design and development. Below are some of the projects I've worked on.</p>
</section>

<!-- Projects Section -->
<section id="projects">
  <h2>My Projects</h2>
  <div class="row">
    <div class="column">
      <div class="card">
        <img src="project1.jpg" alt="Project 1" style="width:100%">
        <div class="container">
          <h2>Project 1</h2>
          <p class="title">A brief description of Project 1.</p>
        </div>
      </div>
    </div>
    <div class="column">
      <div class="card">
        <img src="project2.jpg" alt="Project 2" style="width:100%">
        <div class="container">
          <h2>Project 2</h2>
          <p class="title">A brief description of Project 2.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact">
  <h2>Contact Me</h2>
  /* Basic styling */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px 0;
}

.navbar {
  display: flex;
  justify-content: center;
  background-color: #444;
}

.navbar a {
  padding: 14px 20px;
  display: block;
  color: white;
  text-align: center;
  text-decoration: none;
}

.navbar a:hover {
  background-color: #ddd;
  color: black;
}

section {
  padding: 20px;
}

#projects .row {
  display: flex;
  justify-content: space-around;
}

.column {
  flex: 30%;
  padding: 10px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 16px;
}

h1, h2 {
  text-align: center;
}

  <p>Email: your-email@example.com</p>
</section>

</body>
</html>
