<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bang Gang - Official Videos</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Bang Gang</h1>
    <p>All Our Latest Vibes in One Place</p>
    <div class="social-links">
      <a href="https://www.tiktok.com/@bang_gang._" target="_blank">TikTok</a>
      <a href="https://www.instagram.com/bang_gang_og/" target="_blank">Instagram</a>
    </div>
  </header>

  <main>
    <h2>Our Videos</h2>
    <section class="video-gallery">

      <!-- TikTok Video Example -->
      <div class="video">
        <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@bang_gang._/video/123456789" data-video-id="123456789" style="max-width: 325px; min-width: 220px;">
          <section>Loading TikTok...</section>
        </blockquote>
      </div>

      <!-- Instagram Video Example -->
      <div class="video">
        <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/p/XXXXXXXXXX/" data-instgrm-version="14" style="max-width: 325px; min-width: 220px;">
        </blockquote>
      </div>

      <!-- Add more videos like above -->

    </section>
  </main>

  <footer>
    <p>© 2025 Bang Gang. All Rights Reserved.</p>
  </footer>

  <!-- TikTok Embed Script -->
  <script async src="https://www.tiktok.com/embed.js"></script>
  <!-- Instagram Embed Script -->
  <script async src="//www.instagram.com/embed.js"></script>
</body>
</html>
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background: #000;
  color: #fff;
  text-align: center;
}

header {
  padding: 40px 20px;
}

header h1 {
  font-size: 4rem;
  color: #0ff;
  text-shadow: 0 0 20px #0ff;
  margin-bottom: 10px;
}

header p {
  font-size: 1.3rem;
  margin-bottom: 20px;
}

.social-links a {
  margin: 0 15px;
  color: #ff00ff;
  text-decoration: none;
  font-size: 1.2rem;
  text-shadow: 0 0 15px #ff00ff;
}

main h2 {
  margin-top: 20px;
  font-size: 2rem;
  color: #fff;
  text-shadow: 0 0 10px #0ff;
}

.video-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 30px 10px;
}

.video {
  background: #111;
  padding: 15px;
  border-radius: 12px;
  box-shadow: 0 0 15px #0ff;
}

footer {
  padding: 20px;
  color: #888;
  font-size: 0.9rem;
}