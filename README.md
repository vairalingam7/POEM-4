<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Advanced Mind Map - Wild Animals</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: radial-gradient(circle, #1e3c72, #2a5298);
        color: white;
        overflow: hidden;
    }

    h1 {
        text-align: center;
        margin-top: 20px;
    }

    .mindmap {
        position: relative;
        width: 100vw;
        height: 90vh;
    }

    .node {
        position: absolute;
        padding: 12px 16px;
        border-radius: 12px;
        text-align: center;
        cursor: pointer;
        transition: transform 0.3s, box-shadow 0.3s;
    }

    .node:hover {
        transform: scale(1.1);
        box-shadow: 0 0 15px white;
    }

    .center {
        top: 40%;
        left: 45%;
        background: #feca57;
        color: black;
        font-weight: bold;
    }

    .lion { top: 10%; left: 20%; background: #ff6b6b; }
    .tiger { top: 10%; right: 20%; background: #ff9f43; }
    .leopard { top: 70%; left: 20%; background: #1dd1a1; }
    .bear { top: 70%; right: 20%; background: #5f27cd; }
    .others { top: 25%; left: 5%; background: #341f97; }
    .theme { top: 25%; right: 5%; background: #10ac84; }
    .tone { bottom: 5%; left: 45%; background: #ee5253; }

    svg {
        position: absolute;
        width: 100%;
        height: 100%;
        z-index: -1;
    }

    line {
        stroke: white;
        stroke-width: 2;
        stroke-dasharray: 5;
        animation: dash 2s linear infinite;
    }

    @keyframes dash {
        to {
            stroke-dashoffset: -10;
        }
    }
</style>
</head>

<body>

<h1>🐾 How to Tell Wild Animals</h1>

<div class="mindmap">

    <!-- Lines -->
    <svg>
        <line x1="50%" y1="45%" x2="20%" y2="15%" />
        <line x1="50%" y1="45%" x2="80%" y2="15%" />
        <line x1="50%" y1="45%" x2="20%" y2="75%" />
        <line x1="50%" y1="45%" x2="80%" y2="75%" />
        <line x1="50%" y1="45%" x2="5%" y2="30%" />
        <line x1="50%" y1="45%" x2="95%" y2="30%" />
        <line x1="50%" y1="45%" x2="50%" y2="95%" />
    </svg>

    <!-- Nodes -->
    <div class="node center">Wild Animals</div>

    <div class="node lion">
        🦁 Lion<br>Roars loudly
    </div>

    <div class="node tiger">
        🐯 Tiger<br>Eats you
    </div>

    <div class="node leopard">
        🐆 Leopard<br>Jumps again & again
    </div>

    <div class="node bear">
        🐻 Bear<br>Tight deadly hug
    </div>

    <div class="node others">
        🐊 Others<br>
        Hyena ௭ laughs<br>
        Crocodile ௭ tears<br>
        Chameleon ௭ changes color
    </div>

    <div class="node theme">
        🎯 Themes<br>
        Humour<br>
        Irony<br>
        Awareness
    </div>

    <div class="node tone">
        🎭 Tone<br>
        Funny<br>
        Playful<br>
        Light
    </div>

</div>

</body>
</html>
