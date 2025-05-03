# Earth-warrior
The fighting for saving the humanity
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Earth Warrior</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="warrior" onclick="warriorAction()">🌍⚔️</div>
    <p id="message">Click the warrior to activate its power!</p>

    <script src="script.js"></script>
</body>
</html>
/* styles.css */
body {
    text-align: center;
    font-family: Arial, sans-serif;
    background-color: #1a3d1a;
    color: white;
}

.warrior {
    font-size: 100px;
    cursor: pointer;
    text-shadow: 0 0 15px green;
}

.warrior:hover {
    transform: scale(1.1);
}
// script.js
function warriorAction() {
    document.getElementById("message").innerText = "The Earth Warrior stands ready to protect!";
    alert("🌍 Earth Warrior Activated!");
}
