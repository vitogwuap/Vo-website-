Vo Am
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>VO ENT</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #111;
      color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background: #000;
      text-align: center;
      padding: 3rem 1rem;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
    }
    section {
      padding: 2rem 1rem;
      text-align: center;
    }
    a.button, .buy-button, button {
      display: inline-block;
      margin: 1rem;
      padding: 1rem 2rem;
      background: #f00;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      border: none;
      cursor: pointer;
    }
    input[type="text"], input[type="email"], input[type="tel"] {
      padding: 0.75rem;
      margin: 0.5rem;
      border-radius: 4px;
      border: none;
      width: 80%;
      max-width: 400px;
    }
    iframe {
      max-width: 100%;
      border: none;
    }
    .item {
      background: #222;
      padding: 1rem;
      margin: 1rem auto;
      max-width: 500px;
      border-radius: 8px;
    }
    .item img {
      max-width: 100%;
      border-radius: 5px;
    }
    .footer {
      background: #222;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>VO ENT</h1>
    <p>Music • Movement • Merch</p>
  </header>

  <!-- Music Links -->
  <section>
    <h2>🎧 Listen</h2>
    <a class="button" href="https://music.apple.com/us/artist/vito-gwuap/1504520516" target="_blank">Apple Music</a>
    <a class="button" href="https://youtube.com/playlist?list=RDEM-9iAf3ma2Wp8VUDcb8fSig&playnext=1&si=KRoc4nwE3lmD-nbF" target="_blank">YouTube Playlist</a>
  </section>

  <!-- Social Media -->
  <section>
    <h2>📸 Follow</h2>
    <a class="button" href="https://www.instagram.com/officialvitogwuap?igsh=MWNjNTY5eW16bXZlaA==" target="_blank">Instagram</a>
  </section>

  <!-- Lead Capture Form -->
  <section id="signup">
    <h2>📬 Get Exclusive Drops</h2>
    <form action="https://formspree.io/f/yourformid" method="POST">
      <input type="text" name="name" placeholder="Your Name" required><br>
      <input type="email" name="email" placeholder="Email Address" required><br>
      <input type="tel" name="phone" placeholder="Phone Number" required><br>
      <button type="submit">Join</button>
    </form>
  </section>

  <!-- Video Section -->
  <section id="videos">
    <h2>🎬 Music Videos</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/your_video_id" allowfullscreen></iframe>
  </section>

  <!-- Music Store -->
  <section id="music">
    <h2>🛒 Buy Music</h2>
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

  <!-- About -->
  <section>
    <h2>🧑‍🎤 About VO ENT</h2>
    <p>VO ENT is a creative brand powered by raw energy, music, and street culture. Stay tuned for new drops, exclusive content, and the next wave from Vito Gwuap.</p>
  </section>

  <div class="footer">
    &copy; 2025 VO ENT. All rights reserved.
  </div>
</body>
</html>
