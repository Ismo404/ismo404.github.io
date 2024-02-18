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
    position: relative; /* Added position:relative to handle the absolute position of the custom menu */
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
    padding: 10px;
    border-radius: 15px;
    margin-top: 10px;
  }

  #customMenu {
    display: none;
    position: absolute;
    background-color: #12682D;
    border-radius: 5px;
    padding: 8px;
    color: white;
    z-index: 1000;
  }

  #customMenu a {
    display: block;
    padding: 8px;
    color: white;
    text-decoration: none;
    cursor: pointer;
  }

  #customMenu a:hover {
    background-color: #1FB53D;
  }
</style>
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
    <p class="emojis">
        <a href="mailto:Ismo404notfound@gmail.com">📧 Gmail</a> | <a href="https://www.spigotmc.org/members/ismo404.1969157/" target="_blank">🛠️ Spigot</a> | <a href="https://github.com/Ismo404" target="_blank">🐱‍👤 Github</a>
    </p>
    <div class="rounded-rectangle">
        <div id="customMenu">
            <a id="githubOption" href="https://github.com/Ismo404" target="_blank">Go to GitHub</a>
            <a id="contactOption" href="mailto:Ismo404notfound@gmail.com">Contact Me</a>
            <a id="spigotOption" href="https://www.spigotmc.org/members/ismo404.1969157/" target="_blank">Visit Spigot</a>
        </div>
    </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const customMenu = document.getElementById('customMenu');
  
  document.addEventListener('contextmenu', function(event) {
    event.preventDefault(); // Prevent the default browser context menu
    
    // Position the custom menu at the cursor's position
    customMenu.style.left = event.clientX + 'px';
    customMenu.style.top = event.clientY + 'px';

    // Show the custom menu
    customMenu.style.display = 'block';
  });

  document.addEventListener('click', function() {
    // Hide the custom menu when clicking outside of it
    customMenu.style.display = 'none';
  });

  // Add click handlers for each menu option
  document.getElementById('githubOption').addEventListener('click', function() {
    window.location.href = 'https://github.com/Ismo404';
    customMenu.style.display = 'none';
  });

  document.getElementById('contactOption').addEventListener('click', function() {
    window.location.href = 'mailto:Ismo404notfound@gmail.com';
    customMenu.style.display = 'none';
  });

  document.getElementById('spigotOption').addEventListener('click', function() {
    window.location.href = 'https://www.spigotmc.org/members/ismo404.1969157/';
    customMenu.style.display = 'none';
  });
});
</script>

</body>
</html>
