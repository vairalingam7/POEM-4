<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>How to Tell Wild Animals</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(-45deg, #74ebd5, #ACB6E5, #ff9a9e, #fad0c4);
    background-size: 400% 400%;
    animation: bgMove 10s infinite alternate;
}

/* Background animation */
@keyframes bgMove {
    0% {background-position: left;}
    100% {background-position: right;}
}

/* Header */
header {
    text-align: center;
    padding: 20px;
    color: white;
    background: rgba(0,0,0,0.6);
}

/* Section */
.section {
    background: white;
    margin: 20px auto;
    padding: 20px;
    width: 85%;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    animation: fadeIn 1s ease-in;
}

/* Fade animation */
@keyframes fadeIn {
    from {opacity: 0; transform: translateY(20px);}
    to {opacity: 1; transform: translateY(0);}
}

/* Mindmap */
.mindmap {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.node {
    background: #0984e3;
    color: white;
    margin: 15px;
    padding: 15px;
    border-radius: 12px;
    width: 180px;
    text-align: center;
    transition: 0.4s;
}

.node:hover {
    transform: scale(1.1) rotate(2deg);
    background: #6c5ce7;
}

/* Images */
.node img {
    width: 100%;
    height: 100px;
    object-fit: cover;
    border-radius: 10px;
}

/* Button */
button {
    padding: 10px 15px;
    border: none;
    background: #00b894;
    color: white;
    border-radius: 8px;
    cursor: pointer;
}

button:hover {
    background: #019875;
}

.hidden {
    display: none;
}
</style>
</head>

<body>

<!-- 🎵 Background Music -->
<audio autoplay loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

<header>
    <h1>🐾 How to Tell Wild Animals</h1>
    <h3>By Carolyn Wells</h3>
</header>

<!-- Summary -->
<div class="section">
    <h2>📖 Summary</h2>
    <p>
        This poem humorously explains how to identify wild animals in dangerous situations.
        It uses irony and fun descriptions to make learning interesting.
    </p>
</div>

<!-- Mindmap with Images -->
<div class="section">
    <h2>🧠 Mind Map</h2>
    <div class="mindmap">

        <div class="node">
            <img src="lion.jpg">
            🦁 Lion<br>Roars loudly
        </div>

        <div class="node">
            <img src="tiger.jpg">
            🐯 Tiger<br>Stripes & danger
        </div>

        <div class="node">
            <img src="leopard.jpg">
            🐆 Leopard<br>Spots & attack
        </div>

        <div class="node">
            <img src="bear.jpg">
            🐻 Bear<br>Deadly hug
        </div>

        <div class="node">
            <img src="crocodile.jpg">
            🐊 Crocodile<br>Tears
        </div>

        <div class="node">
            <img src="hyena.jpg">
            😂 Hyena<br>Laughs
        </div>

        <div class="node">
            <img src="chameleon.jpg">
            🦎 Chameleon<br>Color change
        </div>

    </div>
</div>

<!-- Themes -->
<div class="section">
    <h2>🎯 Themes</h2>
    <ul>
        <li>Humour in danger</li>
        <li>Irony</li>
        <li>Wildlife awareness</li>
    </ul>
</div>

<!-- Tone -->
<div class="section">
    <h2>🎭 Tone</h2>
    <ul>
        <li>Humorous</li>
        <li>Playful</li>
        <li>Light-hearted</li>
    </ul>
</div>

<!-- Interactive -->
<div class="section">
    <h2>✨ Fun Fact</h2>
    <button onclick="showFact()">Click Me</button>
    <p id="fact" class="hidden">
        You identify animals only after they attack 😄 (funny but dangerous!)
    </p>
</div>

<script>
function showFact() {
    document.getElementById("fact").classList.toggle("hidden");
}
</script>

</body>
</html>
