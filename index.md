<!DOCTYPE html>
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
  .title-container {
    text-align: center;
    position: absolute;
    width: 100%;
    top: 20px;
    z-index: 10;
  }
  .title {
    font-size: 2.5em;
    color: black;
    font-family: 'Press Start 2P', cursive;
  }
  .textbox {
    font-family: "VT323", monospace;
    background-color: #12682D;
    padding: 20px;
    margin: 0;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    color: white;
    width: 350px;
    height: 100vh;
    box-sizing: border-box;
    position: relative;
  }

  .textbox p {
    font-size: 30px;
  }

  .textbox .emojis {
    font-size: 20px;
  }

  /* Styling for links */
  .emojis a {
    color: #1FB53D;
    text-decoration: none;
  }

  .emojis a:hover,
  .emojis a:active {
    color: #1FB53D;
  }

  /* Styling for rounded rectangle */
  .rounded-rectangle {
    background-color: black;
    padding: 2px;
    border-radius: 10px;
    margin-top: 5px;
  }

  #customMenu {
    display: none;
    position: absolute;
    background-color: #12682D;
    border-radius: 5px;
    padding: 20px;
    length: 100px;
    font-size: 20px;
    color: white;
    z-index: 1000;
  }

  #customMenu a {
    display: block;
    padding: 8px;
    length: 100px;
    color: white;
    text-decoration: none;
    cursor: pointer;
  }

  #customMenu a:hover {
    background-color: #1FB53D;
  }
</style>

<!-- Script for Ctrl + Shift + I popup -->
<script>
  document.addEventListener('keydown', function (event) {
    // Check if the key combination is Ctrl + Shift + I
    if (event.ctrlKey && event.shiftKey && event.key === 'I') {
      // Show your custom popup or perform any other action
      alert('What are you trying to do?');
      // Prevent the default browser behavior for Ctrl + Shift + I (opens browser dev tools)
      event.preventDefault();
    }
  });
</script>

</head>
<body>

<div class="title-container">
  <h1 class="title">Ismo404</h1>
</div>
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
    <div class="rounded-rectangle">
        <p class="emojis">
            <a href="mailto:Ismo404notfound@gmail.com">📧 Gmail</a> | <a href="https://www.spigotmc.org/members/ismo404.1969157/" target="_blank">🛠️ Spigot</a> | <a href="https://github.com/Ismo404" target="_blank">🐱‍👤 Github</a>
        </p>
    </div>
    <div id="customMenu">
        <a id="githubOption" href="https://github.com/Ismo404" target="_blank">Go to GitHub</a>
        <a id="contactOption" href="mailto:Ismo404notfound@gmail.com">Contact Me</a>
        <a id="spigotOption" href="https://www.spigotmc.org/members/ismo404.1969157/" target="_blank">Visit Spigot</a>
    </div>
</div>

</body>
</html>
