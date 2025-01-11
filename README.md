<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Funsphere Menu</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        .header {
            background-color: #000;
            color: #fff;
            padding: 10px 20px;
            display: flex;
            align-items: center;
        }

        .header h1 {
            font-family: 'Arial', sans-serif;
            font-size: 1.5rem;
            margin: 0;
        }

        .menu-icon {
            width: 30px;
            margin-right: 10px;
        }

        .container {
            text-align: center;
            padding: 20px;
        }

        .description {
            background-color: #fff;
            border: 2px solid #ccc;
            border-radius: 10px;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            max-width: 500px;
            color: #666;
            font-size: 1rem;
        }

        .game-item {
            margin: 20px 0;
            display: inline-block;
            text-align: center;
        }

        .game-item img {
            width: 200px;
            height: auto;
            border-radius: 10px;
        }

        .play-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #ffcc00;
            color: #000;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .play-button:hover {
            background-color: #ffc107;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <div class="header">
        <img src="https://i.postimg.cc/d1cmzX8n/20250110-182712.png" alt="Menu Icon" class="menu-icon">
        <h1>FUNSPHERE</h1>
    </div>

    <!-- Container -->
    <div class="container">
        <!-- Description -->
        <div class="description">
            Description...
        </div>

        <!-- Game Item -->
        <div class="game-item">
            <img src="https://i.postimg.cc/k4rF050k/20250111-153350.png" alt="Snake Game">
            <br>
            <a href="snake-game.html" class="play-button">PLAY</a>
        </div>
    </div>
</body>
</html>
