<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#past-projects">Past Projects</a></li>
      <li><a href="#current-projects">Current Projects</a></li>
      <li><a href="#reviews">Reviews</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="#pricing">Pricing</a></li>
    </ul>
  </nav>

  <!-- About Me -->
  <section id="about">
    <div class="container">
      <img src="avatar.jpg" alt="Avatar">
      <h1>John Doe</h1>
      <p>Hi, I'm a full-stack developer with 5 years of experience in building web applications. I specialize in JavaScript, React, Node.js, and MongoDB.</p>
    </div>
  </section>

  <!-- Past Projects -->
  <section id="past-projects">
    <div class="container">
      <h2>Past Projects</h2>
      <div class="project-grid">
        <div class="project-item">
          <img src="project1.jpg" alt="Project 1">
          <h3>Project 1</h3>
        </div>
        <div class="project-item">
          <img src="project2.jpg" alt="Project 2">
          <h3>Project 2</h3>
        </div>
        <div class="project-item">
          <img src="project3.jpg" alt="Project 3">
          <h3>Project 3</h3>
        </div>
        <div class="project-item">
          <img src="project4.jpg" alt="Project 4">
          <h3>Project 4</h3>
        </div>
      </div>
    </div>
  </section>

  <!-- Current Projects -->
  <section id="current-projects">
    <div class="container">
      <h2>Current Projects</h2>
      <div class="project-grid">
        <div class="project-item">
          <img src="project5.jpg" alt="Project 5">
          <h3>Project 5</h3>
        </div>
        <div class="project-item">
          <img src="project6.jpg" alt="Project 6">
          <h3>Project 6</h3>
        </div>
        <div class="project-item">
          <img src="project7.jpg" alt="Project 7">
          <h3>Project 7</h3>
        </div>
        <div class="project-item">
          <img src="project8.jpg" alt="Project 8">
          <h3>Project 8</h3>
        </div>
      </div>
    </div
</section>
  <!-- Reviews -->
  <section id="reviews">
    <div class="container">
      <h2>User Reviews</h2>
      <div class="review-grid">
        <div class="review-item">
          <img src="avatar1.jpg" alt="User 1">
          <p>"John is an amazing developer. He is very professional and always delivers high-quality work."</p>
          <h4>User 1</h4>
        </div>
        <div class="review-item">
          <img src="avatar2.jpg" alt="User 2">
          <p>"I hired John for a complex project and he exceeded my expectations. His attention to detail and problem-solving skills are unmatched."</p>
          <h4>User 2</h4>
        </div>
        <div class="review-item">
          <img src="avatar3.jpg" alt="User 3">
          <p>"Working with John was a pleasure. He is very easy to communicate with and always kept me updated on the progress of the project."</p>
          <h4>User 3</h4>
        </div>
      </div>
    </div>
  </section>
  <!-- Contact -->
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form action="submit-form.php" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </div>
  </section>
  <!-- Pricing -->
  <section id="pricing">
    <div class="container">
      <h2>Pricing</h2>
      <div class="pricing-grid">
        <div class="pricing-item">
          <h3>Basic</h3>
          <ul>
            <li>1 project</li>
            <li>Up to 10 pages</li>
            <li>Basic support</li>
          </ul>
          <p class="price">$100</p>
        </div>
        <div class="pricing-item">
          <h3>Standard</h3>
          <ul>
            <li>3 projects</li>
            <li>Up to 30 pages</li>
            <li>Priority support</li>
          </ul>
          <p class="price">$200</p>
        </div>
        <div class="pricing-item">
          <h3>Premium</h3>
          <ul>
            <li>Unlimited projects</li>
            <li>Up to 100 pages</li>
            <li>Premium support</li>
          </ul>
          <p class="price">$300</p>
        </div>
      </div>
    </div>
  </section>
</body>
</html>
