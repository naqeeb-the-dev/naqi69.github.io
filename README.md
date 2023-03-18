<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

/* Navigation Bar Styles */
nav {
  background-color: #333;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: space-around;
align-items: center;
margin: 0;
padding: 0;
}

nav ul li a {
color: #fff;
text-decoration: none;
font-size: 18px;
padding: 10px;
transition: all 0.3s ease-in-out;
}

nav ul li a:hover {
background-color: #fff;
color: #333;
}

/* Header Styles */
header {
background-image: url(header-bg.jpg);
background-size: cover;
background-position: center;
height: 400px;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
color: #fff;
}

header h1 {
font-size: 48px;
margin: 0;
padding: 0;
}

header p {
font-size: 24px;
margin: 20px 0;
padding: 0;
}

/* About Section Styles */
#about {
background-color: #f2f2f2;
padding: 40px 0;
display: flex;
justify-content: center;
align-items: center;
}

#about .avatar {
width: 200px;
height: 200px;
border-radius: 50%;
overflow: hidden;
margin-right: 40px;
}

#about .avatar img {
width: 100%;
height: 100%;
object-fit: cover;
}

#about p {
font-size: 20px;
line-height: 1.5;
margin: 0;
}

/* Project Section Styles */
#projects {
padding: 40px 0;
}

.project-grid {
display: flex;
flex-wrap: wrap;
justify-content: center;
}

.project-item {
width: 300px;
margin: 20px;
border-radius: 10px;
overflow: hidden;
}

.project-item img {
width: 100%;
height: 200px;
object-fit: cover;
}

.project-item h3 {
font-size: 24px;
margin: 20px;
}

/* Reviews Section Styles */
#reviews {
background-color: #f2f2f2;
padding: 40px 0;
}

.review-grid {
display: flex;
flex-wrap: wrap;
justify-content: center;
}

.review-item {
width: 300px;
margin: 20px;
border-radius: 10px;
overflow: hidden;
text-align: center;
}

.review-item img {
width: 100px;
height: 100px;
border-radius: 50%;
margin: 20px;
}

.review-item p {
font-size: 18px;
margin: 20px;
}

.review-item h4 {
font-size: 20px;
margin: 0;
padding: 0;
}

/* Contact Section Styles */
#contact {
padding: 40px 0;
}

#contact form {
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
}

#contact label {
font-size: 20px;
margin: 20px;
}

#contact input,
#contact textarea {
width: 100%;
padding: 10px;
font-size: 18px;
margin: 10px 0;
border-radius: 5px;
border: none;
}

#contact button {
padding: 10px 20px;
font-size: 20
px;
background-color: #333;
color: #fff;
border: none;
border-radius: 5px;
cursor: pointer;
transition: all 0.3s ease-in-out;
}

#contact button:hover {
background-color: #fff;
color: #333;
}

/* Pricing Section Styles */
#pricing {
padding: 40px 0;
}

.pricing-grid {
display: flex;
flex-wrap: wrap;
justify-content: center;
}

.pricing-item {
width: 300px;
margin: 20px;
border-radius: 10px;
overflow: hidden;
text-align: center;
}

.pricing-item h3 {
font-size: 24px;
margin: 20px;
}

.pricing-item ul {
list-style: none;
margin: 0;
padding: 0;
}

.pricing-item li {
font-size: 18px;
margin: 10px 0;
}

.pricing-item .price {
font-size: 36px;
margin: 20px;
}

.pricing-item button {
padding: 10px 20px;
font-size: 20px;
background-color: #333;
color: #fff;
border: none;
border-radius: 5px;
cursor: pointer;
transition: all 0.3s ease-in-out;
}

.pricing-item button:hover {
background-color: #fff;
color: #333;
}

/* Footer Styles */
footer {
background-color: #333;
color: #fff;
padding: 40px 0;
text-align: center;
}

footer p {
margin: 0;
padding: 0;
}

footer a {
color: #fff;
text-decoration: none;
transition: all 0.3s ease-in-out;
}

footer a:hover {
color: #f2f2f2;
}

/* Responsive Styles */
@media screen and (max-width: 768px) {
header {
height: 300px;
}

header h1 {
font-size: 36px;
}

header p {
font-size: 18px;
}

#about {
flex-direction: column;
text-align: center;
}

#about .avatar {
margin: 0 auto 20px auto;
}

.project-grid {
justify-content: space-around;
}

.project-item {
margin: 20px 0;
}

.review-grid {
justify-content: space-around;
}

.review-item {
margin: 20px 0;
}

.pricing-grid {
justify-content: space-around;
}

.pricing-item {
margin: 20px 0;
}
}
</style>
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
