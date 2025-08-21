# axomaycosmetics-
Cruelty-free Vegan Mexican-American Cosmetics 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Glow by Grande</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #ffb6c1;
      color: white;
      padding: 2rem 0;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
    }

    .container {
      max-width: 1000px;
      margin: 3rem auto;
      padding: 0 1rem;
    }

    .intro, .services {
      margin-bottom: 3rem;
    }

    .intro h2, .services h2 {
      font-size: 2rem;
      color: #e91e63;
      margin-bottom: 1rem;
    }

    .services ul {
      list-style: none;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .services li {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
      transition: transform 0.2s;
    }

    .services li:hover {
      transform: translateY(-5px);
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Glow by Grande</h1>
    <p>Modern beauty with a sustainable touch</p>
  </header>

  <div class="container">
    <section class="intro">
      <h2>About Us</h2>
      <p>Glow by Grande is a Mexican-American owned beauty brand that celebrates diverse beauty through eco-conscious makeup. We’re passionate about cruelty-free cosmetics that empower confidence and creativity in every face we touch.</p>
    </section>

    <section class="services">
      <h2>Our Services</h2>
      <ul>
        <li>
          <strong>Makeup Consultations</strong>
          <p>Get personalized recommendations based on your skin tone, preferences, and lifestyle.</p>
        </li>
        <li>
          <strong>Event Makeup</strong>
          <p>Stunning looks for weddings, parties, and special occasions using clean beauty products.</p>
        </li>
        <li>
          <strong>Eco-Friendly Product Line</strong>
          <p>Shop our signature line of vegan, cruelty-free makeup developed with sustainability in mind.</p>
        </li>
        <li>
          <strong>Workshops & Tutorials</strong>
          <p>Learn to master makeup techniques in a fun and supportive environment, both online and in person.</p>
        </li>
      </ul>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Glow by Grande. All rights reserved.</p>
  </footer>
</body>
</html>

About.html  Code  ( About Section on Website)

<section id="about" class="about" aria-labelledby="about-title">
  <div class="about__container">
    <h2 id="about-title" class="about__heading">About Us</h2>
    <p class="about__text">
      Our mission is to redefine beauty through compassion and inclusivity. We are a cruelty-free brand dedicated to creating high-quality cosmetics that celebrate the unique beauty of every individual. By challenging conventional standards, we inspire confidence and empower a global community, proving that ethical practices and stunning results can go together.
    </p>
  </div>
</section>

<style>
  :root{
    --bg: #0f0f10;
    --card: #17181c;
    --text: #e9e9ee;
    --muted: #b7b7c3;
    --accent: #9b6bff;
  }
  .about{
    background: linear-gradient(145deg, var(--bg), #121318);
    color: var(--text);
    padding: 4rem 1.25rem;
  }
  .about__container{
    max-width: 900px;
    margin: 0 auto;
    background: var(--card);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 20px;
    padding: 2rem clamp(1rem, 3vw, 2.25rem);
    box-shadow: 0 10px 30px rgba(0,0,0,0.25);
  }
  .about__heading{
    font-size: clamp(1.5rem, 2.6vw, 2.25rem);
    line-height: 1.15;
    margin: 0 0 1rem;
    letter-spacing: 0.2px;
    display: inline-flex;
    gap: .6rem;
    align-items: center;
  }
  .about__heading::before{
    content: "";
    width: .75rem;
    height: .75rem;
    border-radius: 50%;
    background: var(--accent);
    box-shadow: 0 0 0 6px rgba(155,107,255,0.15);
  }
  .about__text{
    font-size: clamp(1rem, 1.35vw, 1.125rem);
    line-height: 1.8;
    color: var(--muted);
    margin: 0;
  }
</style>

Index.html Code 


Style.Css Code : (Services & Skills section)
<section id="services" class="services" aria-labelledby="services-title">
  <div class="services__container">
    <h2 id="services-title" class="services__heading">Our Services & Skills</h2>
    <div class="services__grid">
      
      <div class="services__card">
        <h3 class="services__card-title">Makeup Services</h3>
        <p class="services__card-text">
          From natural everyday looks to bold artistic styles, we offer cruelty-free, vegan makeup artistry inspired by Mexican-American culture and traditions.
        </p>
      </div>
      
      <div class="services__card">
        <h3 class="services__card-title">Custom Shade Matching</h3>
        <p class="services__card-text">
          We specialize in inclusive shade ranges that celebrate diverse skin tones, ensuring everyone finds their perfect match with compassion and care.
        </p>
      </div>
      
      <div class="services__card">
        <h3 class="services__card-title">Eco-Friendly Products</h3>
        <p class="services__card-text">
          Our cosmetics are vegan, cruelty-free, and sustainably packaged, proving that beauty can be ethical and environmentally conscious.
        </p>
      </div>
      
      <div class="services__card">
        <h3 class="services__card-title">Workshops & Training</h3>
        <p class="services__card-text">
          We empower our community through makeup workshops, teaching techniques and skills that inspire confidence and creativity.
        </p>
      </div>
      
    </div>
  </div>
</section>

<style>
  :root {
    --bg: #0f0f10;
    --card: #1a1b20;
    --text: #e9e9ee;
    --muted: #b7b7c3;
    --accent: #ff6b81; /* vibrant pink/red inspired by Mexican culture */
    --accent2: #ffa94d; /* warm tone for balance */
  }

  .services {
    background: linear-gradient(160deg, var(--bg), #17181c);
    padding: 4rem 1.25rem;
    color: var(--text);
  }

  .services__container {
    max-width: 1100px;
    margin: 0 auto;
  }

  .services__heading {
    font-size: clamp(1.6rem, 2.8vw, 2.4rem);
    text-align: center;
    margin-bottom: 3rem;
    letter-spacing: 0.5px;
    color: var(--accent);
    position: relative;
  }

  .services__heading::after {
    content: "";
    display: block;
    width: 60px;
    height: 4px;
    background: var(--accent2);
    margin: 0.5rem auto 0;
    border-radius: 3px;
  }

  .services__grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
  }

  .services__card {
    background: var(--card);
    border: 1px solid rgba(255, 255, 255, 0.08);
    border-radius: 16px;
    padding: 2rem;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    transition: transform 0.25s ease, box-shadow 0.25s ease;
  }

  .services__card:hover {
    transform: translateY(-8px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.35);
  }

  .services__card-title {
    font-size: 1.3rem;
    margin-bottom: 1rem;
    color: var(--accent);
  }

  .services__card-text {
    font-size: 1rem;
    line-height: 1.7;
    color: var(--muted);
  }
</style>

Technical Requirement Code: ( koi fish animation)

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Koi Fish Yin Yang</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: #0f0f10;
  }

  .yin-yang {
    position: relative;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    animation: spin 12s linear infinite;
  }

  /* Half black / white background for yin yang */
  .yin-yang::before,
  .yin-yang::after {
    content: "";
    position: absolute;
    width: 100%;
    height: 50%;
    left: 0;
    border-radius: 100px 100px 0 0;
  }

  .yin-yang::before {
    top: 0;
    background: white;
    border-bottom: 4px solid #000;
  }

  .yin-yang::after {
    bottom: 0;
    background: black;
    border-top: 4px solid #fff;
    border-radius: 0 0 100px 100px;
  }

  /* Koi "heads" */
  .fish {
    position: absolute;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
  }

  .fish.white {
    left: 50%;
    background: white;
    border: 4px solid black;
  }

  .fish.black {
    right: 50%;
    background: black;
    border: 4px solid white;
  }

  /* Fish "tails" */
  .fish::before {
    content: "";
    position: absolute;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }

  .fish.white::before {
    background: black;
  }

  .fish.black::before {
    background: white;
  }

  /* Spinning animation */
  @keyframes spin {
    0% { transform: rotate(0deg);}
    100% { transform: rotate(360deg);}
  }
</style>
</head>
<body>
  <div class="yin-yang">
    <div class="fish white"></div>
    <div class="fish purple"></div>
  </div>
</body>
</html>
