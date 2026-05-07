<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Prepzo</title>

<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0b0b0b;
    color: white;
  }

  header {
    padding: 20px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .logo {
    font-size: 26px;
    font-weight: bold;
  }

  .hero {
    text-align: center;
    padding: 100px 20px 60px;
  }

  .hero h1 {
    font-size: 60px;
    margin: 0;
  }

  .hero p {
    color: #aaa;
    font-size: 18px;
    margin-top: 10px;
  }

  .btn {
    margin-top: 25px;
    padding: 12px 22px;
    border: none;
    border-radius: 10px;
    background: white;
    color: black;
    font-weight: bold;
    cursor: pointer;
  }

  .section {
    max-width: 1000px;
    margin: auto;
    padding: 60px 20px;
  }

  .section h2 {
    text-align: center;
    margin-bottom: 30px;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 20px;
  }

  .card {
    background: #151515;
    padding: 20px;
    border-radius: 15px;
    transition: 0.2s;
  }

  .card:hover {
    transform: scale(1.03);
    background: #1c1c1c;
  }

  footer {
    text-align: center;
    padding: 30px;
    color: #666;
    border-top: 1px solid #222;
  }
</style>
</head>

<body>

<header>
  <div class="logo">Prepzo</div>
</header>

<div class="hero">
  <h1>Prepzo</h1>
  <p>Study Smarter with AI</p>
  <p>Your Study Companion for notes, AI tools & revision.</p>
  <button class="btn">Explore Resources</button>
</div>

<div class="section">
  <h2>What You Get</h2>
  <div class="grid">

    <div class="card">
      <h3>📘 Revision Notes</h3>
      <p>Quick summaries for exams and last-minute revision.</p>
    </div>

    <div class="card">
      <h3>🤖 AI Tools</h3>
      <p>Use AI to understand concepts and solve doubts faster.</p>
    </div>

    <div class="card">
      <h3>📅 Study Planners</h3>
      <p>Timetables and planning tools to stay consistent.</p>
    </div>

    <div class="card">
      <h3>⚡ Exam Tips</h3>
      <p>Smart tricks and strategies to score better.</p>
    </div>

  </div>
</div>

<footer>
  © 2026 Prepzo • Built for students
</footer>

</body>
</html>
