<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <title>KV</title>
</head>
<style>
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

nav {
  background-color: #333;
  padding: 10px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

nav li {
  float: left;
  margin-right: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-bottom: 2px solid transparent; /* Add a transparent border bottom initially */
}

nav a:hover {
  border-bottom: 2px solid white;
}

header {
  background-color: lightgrey;
  text-align: center;
  padding: 50px;
}

main {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  padding: 20px;
}

.left-column, .right-column {
  width: 45%;
  margin-bottom: 20px;
}

@media (max-width: 768px) {
  main {
    flex-direction: column;
    align-items: center;
  }

  .left-column, .right-column {
    width: 100%;
  }
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
  position: fixed;
  bottom: 0;
  width: 100%;
}

/* Remove bullet points and add hover effect */
.right-column ul {
  list-style: none;
  padding: 0;
}

.right-column ul li {
  background-color: #f0f0f0;
  margin-bottom: 5px;
  padding: 10px;
  transition: background-color 0.3s;
}

.right-column ul li:hover {
  background-color: #ddd;
}

/* Style the contact link as a button */
nav a.contact-button {
  background-color: #333;
  color: white;
  padding: 8px 16px;
  border-radius: 5px;
}

nav a.contact-button:hover {
  background-color: #555;
}
</style>
<body>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="https://www.youtube.com/@keyboardmasters6554" target = "_blank">YT Music Channel</a></li>
      <li><a href="https://www.youtube.com/@kavinsmelody8395/shorts" target = "_blank">YT Short Story</a></li>
      <li><a href="#" class="contact-button">Contact - Kavin 8072846215</a></li>
    </ul>
  </nav>

  <!-- Header Section -->
  <header>
    <img src="https://t4.ftcdn.net/jpg/02/87/57/35/360_F_287573540_JkaqQrIdNOQQj9M7aLV7pAmjekPrCpEL.jpg" width="180px" alt="Logo">
  </header>

  <!-- Main Content Section -->
  <main>
    <section class="left-column">
      <h2>About Us</h2>
      <p>Kavin and Vels Website. We sell stories, compose music, narrate stories. Interested people can buy our stories.</p>
    </section>

    <section class="right-column">
      <h2>Our Services</h2>
      <ul >
        <li><a href="hf.html" target = "_blank">History Fiction</a></li>
        <li><a href="#">Thriller</a></li>
        <li><a href="#">Mystery</a></li>
        <li><a href="#">Sci-Fi</a></li>
      </ul>
    </section>
  </main>

  <!-- Footer Section -->
  <footer>
    &copy; 2023 Kavin and Vels. All rights reserved.
  </footer>

</body>
</html>
