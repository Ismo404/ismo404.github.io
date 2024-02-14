<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ismo404 - Minecraft Developer Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
    <style>
        html, body {
            height: 100%;
            margin: 0;
            padding: 0;
            background-color: #1FB53D;
            font-family: Arial, sans-serif;
        }

        .container {
            position: relative;
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .title-container {
            text-align: center;
            z-index: 10;
            position: absolute;
            width: 100%;
            top: 20px;
        }

        .title {
            font-size: 2.5em;
            color: black;
            font-family: 'Press Start 2P', cursive;
        }

        .content {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            padding: 20px;
        }

        .textbox {
            font-family: "VT323", monospace;
            background-color: #12682D;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            color: white;
            width: 350px;
            box-sizing: border-box;
        }

        .textbox p {
            font-size: 30px;
        }

        .textbox .emojis {
            font-size: 20px;
        }

        .button {
            padding: 10px 20px;
            font-size: 16px;
            font-weight: bold;
            text-align: center;
            text-decoration: none;
            background-color: #12682D; /* Dark green color */
            color: #fff;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #0a401d; /* Darker green on hover */
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="title-container">
            <h1 class="title">Ismo404</h1>
        </div>
        <div class="content">
            <div class="textbox">
                <link rel="preconnect" href="https://fonts.googleapis.com">
                <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
                <link href="https://fonts.googleapis.com/css2?family=VT323&display=swap" rel="stylesheet">

                <h1>🚀 Professional Minecraft Developer</h1>
                <p>
                    Hey there! I'm Ismo404, a passionate Minecraft Java plugin developer.
                    <br>🎮 I create awesome plugins to enhance the Minecraft experience.
                    <br>💡 Let's turn ideas into reality! ✨
                </p>
                <p class="emojis">
                    ☕ Java | 🛠️ Spigot | 🎨 Creative
                </p>
            </div>
            <a href="https://github.com/Ismo404" class="button" target="_blank">GitHub</a>
        </div>
    </div>
</body>

</html>