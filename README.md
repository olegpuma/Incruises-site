<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <title>InCruises Club</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Перемикач мов -->
  <div class="language-toggle">
    <select id="language" class="form-select form-select-sm">
      <option value="uk">🇺🇦 UA</option>
      <option value="en">🇺🇸 EN</option>
    </select>
  </div>

  <!-- Hero -->
  <section class="hero text-white text-center py-5">
    <div class="container">
      <h1 id="hero-title"></h1>
      <p class="lead" id="hero-subtitle"></p>
      <a id="cta-button" class="btn btn-light btn-lg" target="_blank">Join</a>
    </div>
  </section>

  <!-- About -->
  <section class="py-5">
    <div class="container">
      <h2 class="text-center" id="about-title"></h2>
      <p class="text-center" id="about-text"></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-4 bg-light">
    <p>&copy; 2025 InCruises Site by Олег</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

  


