<!DOCTYPE html>
<html>
<head>
  <title>Contact Me!</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    /* Add this style within the head section or link it from an external stylesheet */
    .dropbtn {
      padding: 50px 50px; /* Increase the padding to make the button bigger */
      font-size: 30px; /* Increase font size for larger text */
      border: none;
      cursor: pointer;
    }
    /* Centering the menu */
    header {
      text-align: center;
    }

    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      display: inline-block; /* Align the menu items horizontally */
    }

    nav ul li {
      display: inline;
      margin-right: 20px;
    }

    nav ul li a {
      color: #0099ff;
      text-decoration: none;
      font-weight: bold;
    }

    /* Other styles */
    /* ... */
  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li class="dropdown">
          <a href="#" class="dropbtn">Menu</a>
          <div class="dropdown-content">
            <a href="about.html">About Me</a>
            <a href="contact.html">Contact Me</a>
            <a href="Fixed Website hahha.html">Random Build Generator</a>
            <a href="home.html">Home</a>
          </div>
        </li>
      </ul>
    </nav>
  </header>


  <h1>Press the Button</h1>
  <button onclick="generateRandomBuild()">Randomize</button>
  
  <div id="buildDisplay">
    <!-- Random build will be displayed here -->
  </div>

  <!-- About Section -->
  <section id="about">
    <div class="about-content">
      <h2>About Us</h2>
      <p>Welcome to Random Build Generator! This website helps you create random builds for various purposes.</p>
      <p>Our aim is to provide an easy way to experiment with different item combinations for champions in games like League of Legends.</p>
      <p>Feel free to use the "Randomize" button to generate new builds or customize the items and champions to suit your needs.</p>
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html>
