<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Charity: Water</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Georgia&display=swap" rel="stylesheet" />
</head>
<body>
  <header>
    <div class="logo">
      <img src="https://raw.githubusercontent.com/jessr020/Charity-Water-Landing-Page/main/images/logo-yellow-box.png" alt="Charity:Water Logo" />
      <span>Charity:Water</span>
    </div>
    <nav>
      <a href="#">About Us</a>
      <a href="#">Our Mission</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-left">
      <h1>Turn Your Activism Into Lasting Impact With Clean Water</h1>
      <p>
        Join charity: water to fund clean water solutions that drive environmental justice, public health, and systemic change: powered by 100% transparency and real results.
      </p>
      <div class="buttons">
        <button class="secondary">Make a Difference Today</button>
        <button class="primary">DONATE</button>
      </div>
    </div>
    <div class="hero-right">
      <img src="https://raw.githubusercontent.com/jessr020/Charity-Water-Landing-Page/main/images/charity_water_Tanzania_TaraShupePhotography_0258.jpg" alt="Child washing with clean water" />
    </div>
  </section>

  <section class="gallery">
    <img src="https://raw.githubusercontent.com/jessr020/Charity-Water-Landing-Page/main/images/JS_20140424_3157.jpg" alt="Buckets of dirty water" />
    <img src="https://raw.githubusercontent.com/jessr020/Charity-Water-Landing-Page/main/images/Zimbabwe_2022_CG-0486.jpg" alt="Hand holding clean water" />
  </section>
</body>
</html>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Proxima Nova', sans-serif;
  background-color: #FFF9E9; /* Cream */
  color: #000000; /* Black text */
  line-height: 1.6;
}

/* Header */
header {
  background-color: #FFF9E9;
  padding: 1.5rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  display: flex;
  align-items: center;
  font-weight: bold;
  font-size: 1.4rem;
  color: #000;
}

.logo img {
  height: 32px;
  margin-right: 10px;
}

nav a {
  margin-left: 2rem;
  color: #4f9ec9;
  font-weight: bold;
  text-decoration: none;
  font-size: 1.1rem;
}

/* Hero Section */
.hero {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  padding: 3rem 2rem;
  background-color: #FFF9E9;
}

.hero-left {
  flex: 1;
  max-width: 600px;
}

.hero-left h1 {
  font-family: Georgia, serif;
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: #000;
}

.hero-left p {
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
  color: #000;
}

.buttons {
  display: flex;
  gap: 1rem;
}

button.primary {
  background-color: #FDD340; /* Bright yellow */
  color: #000;
  border: none;
  padding: 0.75rem 1.5rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
}

button.secondary {
  background-color: #C2E7F4; /* Sky blue */
  color: #000;
  border: none;
  padding: 0.75rem 1.5rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
}

.hero-right {
  flex: 1;
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}

.hero-right img {
  width: 100%;
  max-width: 500px;
  border-radius: 10px;
  object-fit: cover;
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
  border: 3px solid #FDD340;
}

/* Gallery */
.gallery {
  display: flex;
  gap: 1.5rem;
  padding: 2rem;
  background-color: #fff;
  justify-content: center;
  flex-wrap: wrap;
}

.gallery img {
  width: 100%;
  max-width: 400px;
  border-radius: 10px;
  object-fit: cover;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.gallery img[alt="Buckets of dirty water"] {
  border: 4px solid #999;
}

.gallery img[alt="Hand holding clean water"] {
  border: 4px solid #C2E7F4;
}

