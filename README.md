# GOLDIND
GOLD JEWELLERY PROJECT 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="styles.css" />
  <title>My Portfolio</title>
</head>
<body>
  <header>
    <h1>Hello, I'm <span class="highlight">Your Name</span></h1>
    <p>Web Developer & Learner</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm passionate about coding and building cool things on the web.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Project 1 - Description</li>
      <li>Project 2 - Description</li>
    </ul>
  </section>

  <footer>
    <p>Contact: youremail@example.com</p>
  </footer>
</body>
</html>
* {
  box-sizing: border-box;
  font-family: sans-serif;
  margin: 0;
  padding: 0;
}

body {
  background: #f5f5f5;
  color: #222;
  min-height: 100vh;
  line-height: 1.6;
}

header {
  background: #333;
  color: #fff;
  padding: 2rem 1rem;
  text-align: center;
}.highlight {
  color: #38b6ff;
}

section {
  margin: 2rem auto;
  max-width: 600px;
  padding: 1rem;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
}

h2 {
  color: #38b6ff;
  margin-bottom: 1rem;
}

footer {
  text-align: center;
  padding: 1rem;
  color: #fff;
  background: #222;
  position: fixed;
  width: 100%;
  bottom: 0;
}