<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Game Hub</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0f172a;
  color: white;
}

header {
  padding: 20px;
  text-align: center;
  background: #1e293b;
  font-size: 28px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 20px;
}

.card {
  background: #1e293b;
  padding: 20px;
  border-radius: 12px;
  transition: 0.2s;
}

.card:hover {
  transform: scale(1.05);
  background: #334155;
}

a {
  text-decoration: none;
  color: white;
  font-size: 18px;
}
</style>
</head>

<body>

<header>🎮 My Game Hub</header>

<div class="grid">
  <div class="card"><a href="games/clicker/">Clicker Game</a></div>
  <div class="card"><a href="games/snake/">Snake Game</a></div>
</div>

</body>
</html>
