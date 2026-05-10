# cap
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GLR-036 Squadron - Civil Air Patrol</title>

  <style>
    :root {
      --cap-blue: #002D62;
      --cap-red: #C8102E;
      --cap-light: #f4f7fb;
      --cap-dark: #07162b;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: var(--cap-light);
      color: #111;
    }

    /* HEADER */
    header {
      background: linear-gradient(90deg, var(--cap-blue), #001a3a);
      color: white;
      padding: 25px 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .logo {
      width: 70px;
      height: 70px;
    }

    header h1 {
      margin: 0;
      font-size: 28px;
    }

    header p {
      margin: 3px 0 0;
      color: #dbe6ff;
      font-size: 14px;
    }

    /* NAV */
    nav {
      background: var(--cap-dark);
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      padding: 14px 18px;
      text-decoration: none;
      font-weight: bold;
      font-size: 14px;
    }

    nav a:hover {
      background: var(--cap-red);
    }

    /* SECTIONS */
    section {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    h2 {
      color: var(--cap-blue);
      border-left: 5px solid var(--cap-red);
      padding-left: 10px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      margin-top: 10px;
    }

    ul {
      margin-top: 10px;
    }

    /* BUTTON */
    .button {
      display: inline-block;
      padding: 10px 15px;
      background: var(--cap-red);
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      margin-top: 10px;
    }

    .button:hover {
      background: #a50f24;
    }

    footer {
      background: var(--cap-dark);
      color: #bbb;
      text-align: center;
      padding: 20px;
      font-size: 13px;
    }
  </style>
</head>

<body>

<header>
  <!-- CAP-STYLE EMBLEM (simple vector star) -->
  <svg class="logo" viewBox="0 0 100 100">
    <circle cx="50" cy="50" r="48" fill="#002D62" stroke="white" stroke-width="2"/>
    <polygon points="50,10 61,40 95,40 67,58 78,88 50,70 22,88 33,58 5,40 39,40"
      fill="#C8102E" stroke="white" stroke-width="2"/>
  </svg>

  <div>
    <h1>GLR-036 Squadron</h1>
    <p>[Civil Air Patrol](chatgpt://generic-entity?number=0) • Springfield, Illinois</p>
  </div>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#mission">Mission</a>
  <a href="#cadet">Cadet Program</a>
  <a href="#activities">Activities</a>
  <a href="#resources">Resources</a>
  <a href="#join">Join</a>
</nav>

<section id="home">
  <h2>Welcome</h2>
  <div class="card">
    Welcome to the GLR-036 Squadron of the Civil Air Patrol. Our squadron develops leadership, discipline, and aerospace knowledge while serving the community and supporting emergency services.
  </div>
</section>

<section id="mission">
  <h2>Mission</h2>
  <div class="card">
    The Civil Air Patrol has three core missions:
    <ul>
      <li>Cadet Programs – Leadership and character development</li>
      <li>Aerospace Education – STEM, aviation, and space learning</li>
      <li>Emergency Services – Search and rescue and disaster relief support</li>
    </ul>
  </div>
</section>

<section id="cadet">
  <h2>Cadet Program</h2>
  <div class="card">
    The Cadet Program is designed for youth ages 12–21 and builds leadership through a structured rank system.
    <ul>
      <li>Leadership training and responsibility</li>
      <li>Drill and ceremonies</li>
      <li>Physical fitness development</li>
      <li>Aerospace education</li>
    </ul>
  </div>
</section>

<section id="activities">
  <h2>Activities</h2>
  <div class="card">
    Cadets participate in:
    <ul>
      <li>Weekly squadron meetings</li>
      <li>Drill and leadership labs</li>
      <li>Aerospace education classes</li>
      <li>Community service projects</li>
      <li>Encampments and field training exercises</li>
    </ul>
  </div>
</section>

<section id="resources">
  <h2>Resources</h2>
  <div class="card">
    Helpful cadet materials:
    <ul>
      <li>Uniform standards</li>
      <li>Promotion requirements</li>
      <li>Study guides</li>
      <li>Fitness standards</li>
    </ul>
  </div>
</section>

<section id="join">
  <h2>Join GLR-036</h2>
  <div class="card">
    Interested in joining? New cadets are encouraged to attend a meeting and learn more about the program.
    <br>
    <a class="button" href="#">Learn More</a>
  </div>
</section>

<footer>
  GLR-036 Squadron • Springfield, Illinois • Civil Air Patrol
</footer>

</body>
</html>
