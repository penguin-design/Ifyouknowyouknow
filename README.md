<!DOCTYPE html>
<html>
<head>
<title>Happy Birthday Pikachu</title>
<style>
body {
    background: linear-gradient(to right, #ffcc00, #ff9900);
    text-align: center;
    font-family: Arial;
    padding: 50px;
}
.card {
    background: white;
    padding: 30px;
    border-radius: 20px;
}
h1 { color: orange; font-size: 40px; }
p { font-size: 20px; }

img {
    width: 200px;
    border-radius: 20px;
    margin: 15px 0;
}

button {
    padding: 10px 20px;
    font-size: 18px;
    background: yellow;
    border: none;
    border-radius: 10px;
    margin-top: 10px;
}
</style>
</head>

<body>

<div class="card">

<h1>🎂 Happy Birthday Pikachu ⚡</h1>

<img src="pikachu.png" alt="Pikachu">

<p>Born on 10th December 💛</p>
<p>Stay cute, stay electric!</p>

<button onclick="playMusic()">🎵 Play Music</button>
<button onclick="wish()">Click for Surprise</button>

</div>

<!-- BACKGROUND MUSIC -->
<audio id="bg-music" loop>
  <source src="music.mp3" type="audio/mpeg">
</audio>

<script>
function wish() {
    alert("⚡ Pika Pika! Happy Birthday Pikachu! ⚡");
}

function playMusic() {
    document.getElementById("bg-music").play();
}
</script>

</body>
</html>}
</style>
</head>

<body>

<div class="card">

<h1>🎂 Happy Birthday Pikachu ⚡</h1>

<img src="pikachu.jpg" alt="Pikachu">

<p>Born on 10th December 💛</p>
<p>Stay cute, stay electric!</p>

<button onclick="playMusic()">🎵 Play Music</button>
<button onclick="wish()">Click for Surprise</button>

</div>

<!-- BACKGROUND MUSIC -->
<audio id="bg-music" loop>
  <source src="Voh Dekhnay Mein.mp3" type="audio/mpeg">
</audio>

<script>
function wish() {
    alert("⚡ Pika Pika! Happy Birthday Pikachu! ⚡");
}

function playMusic() {
    document.getElementById("bg-music").play();
}
</script>

</body>
</html>
