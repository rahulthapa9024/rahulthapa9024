<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rahul – Portfolio</title>

  <style>
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: white;
    }

    /* Background */
    .bg {
      position: fixed;
      inset: 0;
      background-image: url("https://i.redd.it/48zd8xe6k49a1.jpg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      z-index: -1;
    }

    /* Overlay for readability */
    .overlay {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.55);
    }

    /* Content */
    .hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }

    h1 {
      font-size: clamp(2.5rem, 5vw, 4rem);
      margin-bottom: 16px;
      font-weight: 700;
    }

    p {
      font-size: 1.1rem;
      opacity: 0.9;
      margin-bottom: 30px;
    }

    .socials {
      display: flex;
      gap: 16px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .socials a {
      text-decoration: none;
      color: white;
      padding: 12px 22px;
      border-radius: 999px;
      border: 1px solid rgba(255,255,255,0.4);
      backdrop-filter: blur(6px);
      transition: all 0.3s ease;
      font-weight: 500;
    }

    .socials a:hover {
      background: white;
      color: black;
      transform: translateY(-2px);
    }
  </style>
</head>

<body>
  <div class="bg"></div>
  <div class="overlay"></div>

  <section class="hero">
    <div>
      <h1>Hi, I'm Rahul 👋</h1>
      <p>Full-Stack Developer • React • Node • AI & ML</p>

      <div class="socials">
        <a href="https://twitter.com/your_username" target="_blank">X</a>
        <a href="https://linkedin.com/in/your_username" target="_blank">LinkedIn</a>
        <a href="https://github.com/your_username" target="_blank">GitHub Portfolio</a>
      </div>
    </div>
  </section>
</body>
</html>
