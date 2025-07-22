<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Music Store</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🎵 Welcome to My Music & Merch Store 🎵</h1>
    <p>Watch videos, buy tracks, and shop exclusive merch!</p>
  </header>

  <!-- Lead Capture Form -->
  <section id="signup">
    <h2>Get Exclusive Drops</h2>
    <form action="https://formspree.io/f/yourformid" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Email Address" required>
      <input type="tel" name="phone" placeholder="Phone Number" required>
      <button type="submit">Join</button>
    </form>
  </section>

  <!-- Video Section -->
  <section id="videos">
    <h2>🎬 Music Videos</h2>
    <iframe width="560" height="315" src="https://https://youtu.be/3dH3_ZfnGRQ?si=mJrvEkkkKigGilU3/embed/your_video_id" frameborder="0" allowfullscreen></iframe>
  </section>

  <!-- Music Store -->
  <section id="music">
    <h2>🎧 Buy Music</h2>
    <div class="item">
      <img src="cover1.jpg" alt="Cover Art">
      <h3>Track Name 1</h3>
      <audio controls src="track1.mp3"></audio>
      <p>Price: $1.99</p>
      <a href="https://payhip.com/yourlink" class="buy-button">Buy & Download</a>
    </div>
  </section>

  <!-- Merch Store -->
  <section id="merch">
    <h2>🛍️ Merch</h2>
    <div class="item">
      <img src="shirt.jpg" alt="T-shirt">
      <h3>Logo Tee</h3>
      <p>$25.00</p>
      <a href="https://yourstorelink.com" class="buy-button">Buy Now</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Your Name – All rights reserved</p>
  </footer>
</body>
</html>

body {
  font-family: 'Arial', sans-serif;
  background-color: #111;
  color: #fff;
  margin: 0;
  padding: 0;
  text-align: center;
}

<section id="videos">
  <h2>🎬 My Music Videos</h2>

  <!-- Example YouTube Embed -->
  <div class="video">
    <iframe width="560" height="315" 
            src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
            title="YouTube video player" 
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen>
    </iframe>
  </div>

  <!-- Add more videos by repeating this block -->
  <div class="video">
    <iframe width="560" height="315"
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
            title="Your Video Title"
            frameborder="0"
            allow="autoplay; encrypted-media"
            allowfullscreen>
   
    </iframe>
  </div>
</section>
header {
  padding: 40px 20px;
  background-color: #1e1e1e;
}

section {
  padding: 40px 20px;
}

form input, form button {
  padding: 10px;
  margin: 5px;
  border: none;
  border-radius: 4px;
}

form button {
  background-color: #28a745;
  color: white;
  cursor: pointer;
}

.item {
  margin: 20px auto;
  padding: 20px;
  max-width: 300px;
  background-color: #222;
  border-radius: 8px;
}

.item img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

.buy-button {
  display: inline-block;
  margin-top: 10px;
  background-color: #007bff;
  color: white;
  padding: 10px;
  text-decoration: none;
  border-radius: 5px;
}
