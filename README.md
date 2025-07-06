<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Charity: Water</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    /* These will work only if fonts are locally installed or self-hosted */
    @font-face {
      font-family: 'Georgia Pro';
      src: local('Georgia Pro'), serif;
    }
    @font-face {
      font-family: 'Proxima Nova';
      src: local('Proxima Nova'), sans-serif;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">🌟 Charity:Water</div>
    <nav>
      <a href="#">About Us</a>
      <a href="#">Our Mission</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h1>Turn Your Activism Into Lasting Impact With Clean Water</h1>
      <p>Join charity: water to fund clean water solutions that drive environmental justice, public health, and systemic change: powered by 100% transparency and real results.</p>
      <div class="cta-buttons">
        <button class="secondary">Make a Difference Today</button>
        <button class="primary">Donate</button>
      </div>
    </div>
    <div class="hero-image">
      <img src="https://images.unsplash.com/photo-1572284339313-0d9034c3bcef" alt="Child with clean water">
    </div>
  </section>

  <section class="gallery">
    <img src="https://images.unsplash.com/photo-1599379441339-18c3945d70a6" alt="Water collection">
    <img src="https://images.unsplash.com/photo-1606788075764-9e9a9435d3aa" alt="Clean water in glass">
    <img src="https://images.unsplash.com/photo-1600077104057-2c4179cdd4d3" alt="Water impact">
  </section>
</body>
</html>
/* Base Styles */
body {
  font-family: 'Proxima Nova', Arial, sans-serif;
  margin: 0;
  background-color: #FFF5DC; /* Soft beige */
  color: #000;
}

h1, h2, h3 {
  font-family: 'Georgia Pro', Georgia, serif;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
  background-color: #FFF5DC;
}

.logo {
  font-weight: bold;
  font-size: 1.5em;
}

nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #88AEBF; /* Brand blue */
  font-weight: 600;
}

/* Hero Section */
.hero {
  display: flex;
  flex-wrap: wrap;
  padding: 40px;
  gap: 40px;
}

.hero-text {
  flex: 1;
  min-width: 300px;
}

.hero-text h1 {
  font-size: 2.8em;
  margin-bottom: 20px;
  line-height: 1.2;
}

.hero-text p {
  font-size: 1.1em;
  line-height: 1.6;
  margin-bottom: 30px;
}

.cta-buttons {
  display: flex;
  gap: 10px;
}

button.primary {
  background-color: #F4C542; /* Warm yellow */
  border: none;
  padding: 12px 20px;
  font-weight: bold;
  color: white;
  border-radius: 5px;
  cursor: pointer;
}

button.secondary {
  background-color: #88AEBF; /* Muted blue */
  border: none;
  padding: 12px 20px;
  font-weight: bold;
  color: white;
  border-radius: 5px;
  cursor: pointer;
}

.hero-image img {
  width: 100%;
  max-width: 500px;
  border-radius: 10px;
}

/* Gallery Section */
.gallery {
  display: flex;
  justify-content: center;
  gap: 10px;
  padding: 20px;
  background-color: #FFF5DC;
  flex-wrap: wrap;
}

.gallery img {
  width: 30%;
  max-width: 300px;
  border-radius: 8px;
  object-fit: cover;
}
