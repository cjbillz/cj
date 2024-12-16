<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CJS Tech</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="history.html">History of the Internet</a></li>
        <li><a href="browserwars.html">Browser Wars</a></li>
        <li><a href="whyie.html">Why IE Sucks</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>Welcome to CJS Tech</h1>
    <p>Welcome to our tech site. Learn about the internet, browsers, and more!</p>

    <form id="inputForm" action="https://example.com" method="get">
      <label for="userInput">Enter a color to change the background:</label>
      <input type="text" id="userInput" name="color" placeholder="Enter a color" required>
      <button type="submit">Submit</button>
    </form>

    <section id="dynamicContent">
      <h2>Dynamic Content</h2>
      <button onclick="changeContent()">Click to change content</button>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 CJS Tech | All rights reserved.</p>
  </footer>
</body>
</html>
