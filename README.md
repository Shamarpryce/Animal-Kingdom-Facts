<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Animal Kingdom - Featuring the Red Panda</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f7f7f7;
      color: #333;
    }
    header {
      background-color: #6a1b1a;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    .hero img {
      display: block;
      width: 80%;
      max-width: 600px;
      height: auto;
      margin: 0 auto;
      border-radius: 10px;
    }
    section {
      padding: 2rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    .intro {
      background-color: #fff7f0;
      padding: 2rem;
      border-left: 5px solid #f57c00;
      margin-top: 2rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    .red-panda {
      background: #fff;
      border-left: 6px solid #e53935;
      padding: 1rem;
      margin-top: 2rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .red-panda img {
      width: 80%;
      max-width: 400px;
      display: block;
      margin: 1rem auto;
      border-radius: 10px;
    }
    .animal-sections {
      background-color: #f0f0f0;
      padding-top: 2rem;
    }
    .animal-group {
      background: white;
      margin-bottom: 2rem;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }
    .animal-group img {
      width: 80%;
      max-width: 400px;
      height: auto;
      display: block;
      margin: 0.5rem auto;
      border-radius: 8px;
    }
    .fun-facts {
      background-color: #e8f5e9;
      padding: 2rem;
      margin: 2rem auto;
      max-width: 1000px;
      border-left: 5px solid #43a047;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    .fun-facts ul {
      list-style: square inside;
      line-height: 1.6;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    @media (max-width: 768px) {
      header h1 {
        font-size: 1.8rem;
      }
      .red-panda, .intro, .animal-group, .fun-facts {
        padding: 1rem;
      }
      .animal-group img, .red-panda img, .hero img {
        width: 95%;
      }
      body {
        font-size: 16px;
      }
    }
    @media (max-width: 480px) {
      header h1 {
        font-size: 1.5rem;
      }
      header p {
        font-size: 1rem;
      }
      .animal-group h3, .red-panda h2, .intro h2, .fun-facts h2 {
        font-size: 1.2rem;
      }
      .animal-group img, .red-panda img, .hero img {
        max-width: 100%;
        width: 100%;
      }
      body {
        font-size: 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to the Animal Kingdom</h1>
    <p>Explore the diversity of life on Earth — with a special spotlight on the Red Panda!</p>
  </header>

  <section class="hero">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/50/RedPandaFullBody.JPG" alt="Red Panda" />
  </section>

  <section class="intro">
    <h2>🌐 What is the Animal Kingdom?</h2>
    <p>The Animal Kingdom includes all multicellular, eukaryotic, heterotrophic organisms — from insects to elephants. Animals are classified based on structure, reproduction, and habitat.</p>
  </section>

  <section class="red-panda">
    <h2>🐾 Meet the Red Panda</h2>
    <p>The red panda (<i>Ailurus fulgens</i>) is native to the Himalayas and southwestern China. It has reddish-brown fur, a ringed tail, and a masked face. Although called a "panda", it's not closely related to the giant panda.</p>
    <ul>
      <li>Diet: Bamboo, berries, eggs, insects</li>
      <li>Habitat: Temperate forests</li>
      <li>Status: Endangered</li>
    </ul>
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Red_Panda_Adirondack.jpg" alt="Cute Red Panda"/>
  </section>

  <section class="animal-sections">
    <h2>🌍 Explore the Animal Kingdom</h2>

    <div class="animal-group">
      <h3>Mammals</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg" alt="Lion"/>
      <p>Mammals are warm-blooded, have hair or fur, and most give birth to live young. They nurse their babies with milk.</p>
      <ul>
        <li>Examples: Lions, whales, elephants, bats</li>
        <li>Live in forests, oceans, deserts, tundras</li>
      </ul>
    </div>

    <div class="animal-group">
      <h3>Birds</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/57/Bald_Eagle_Portrait.jpg" alt="Bald Eagle"/>
      <p>Birds have feathers, wings, and beaks. Most can fly and they lay eggs.</p>
      <ul>
        <li>Examples: Eagles, penguins, parrots, owls</li>
        <li>Found on all continents</li>
      </ul>
    </div>

    <div class="animal-group">
      <h3>Reptiles</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Green_Iguana_Luc_Viatour.jpg" alt="Green Iguana"/>
      <p>Reptiles are cold-blooded and covered in scales. Most lay eggs on land.</p>
      <ul>
        <li>Examples: Snakes, lizards, turtles, crocodiles</li>
        <li>Found in warm climates</li>
      </ul>
    </div>

    <div class="animal-group">
      <h3>Amphibians</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/e5/Common_tree_frog.jpg" alt="Common Tree Frog"/>
      <p>Amphibians begin life in water and usually go through metamorphosis. Their skin must stay moist.</p>
      <ul>
        <li>Examples: Frogs, toads, salamanders</li>
        <li>Live near water or damp areas</li>
      </ul>
    </div>

    <div class="animal-group">
      <h3>Fish</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Goldfish3.jpg" alt="Goldfish"/>
      <p>Fish live in water and breathe through gills. They are cold-blooded and have fins.</p>
      <ul>
        <li>Examples: Goldfish, salmon, sharks, tuna</li>
        <li>Live in oceans, rivers, lakes</li>
      </ul>
    </div>

    <div class="animal-group">
      <h3>Insects</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Monarch_Butterfly_Danaus_plexippus.jpg" alt="Monarch Butterfly"/>
      <p>Insects have 6 legs and most have wings. They're the most diverse group in the animal kingdom.</p>
      <ul>
        <li>Examples: Butterflies, ants, bees, beetles</li>
        <li>Found almost everywhere</li>
      </ul>
    </div>
  </section>

  <section class="fun-facts">
    <h2>🧠 Animal Kingdom Fun Facts</h2>
    <ul>
      <li>Blue whales are the largest animals to ever live.</li>
      <li>Octopuses have 3 hearts and 9 brains.</li>
      <li>Ants can carry up to 50x their body weight.</li>
      <li>Some frogs freeze in winter and thaw in spring!</li>
      <li>Red pandas clean themselves like cats.</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Animal Kingdom | Featuring the Red Panda</p>
  </footer>
</body>
</html>
