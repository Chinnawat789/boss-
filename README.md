<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John Doe's Online Resume</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="container">
    <header>
      <h1>John Doe</h1>
      <p>Web Developer | Designer | Content Creator</p>
    </header>
    
    <!-- Profile Section -->
    <section class="profile">
      <table>
        <tr>
          <td class="profile-image">
            <img src="profile.jpg" alt="John Doe's Profile Picture" style="border-radius: 50%;">
          </td>
          <td class="profile-info">
            <h2>John Doe</h2>
            <p>Web Developer | Recent Graduate</p>
            <p>University of Web Development | Computer Science</p>
          </td>
        </tr>
      </table>
    </section>

    <!-- Skills Section -->
    <section class="skills">
      <h2>Skills & Strengths</h2>
      <table>
        <thead>
          <tr>
            <th>Skill</th>
            <th>Beginner</th>
            <th>Intermediate</th>
            <th>Advanced</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>HTML5</td>
            <td><span class="strength filled"></span></td>
            <td><span class="strength filled"></span></td>
            <td><span class="strength"></span></td>
          </tr>
          <tr>
            <td>CSS3</td>
            <td><span class="strength filled"></span></td>
            <td><span class="strength filled"></span></td>
            <td><span class="strength"></span></td>
          </tr>
          <tr>
            <td>JavaScript</td>
            <td><span class="strength filled"></span></td>
            <td><span class="strength filled"></span></td>
            <td><span class="strength"></span></td>
          </tr>
        </tbody>
      </table>
      <p class="skill-level-explanation">
        <span class="strength filled"></span> - Experienced
        <span class="strength"></span> - Learning
      </p>
    </section>

    <!-- About Me Section -->
    <section class="about">
      <h2>About Me</h2>
      <p>I am a passionate and recent graduate with a strong foundation in web development. Eager to learn and contribute to creative projects. I am highly motivated and possess excellent problem-solving skills.</p>
      
      <!-- Adding Address and Profession -->
      <p><strong>Address:</strong> 1234 Web Dev Street, City, Country</p>
      <p><strong>Profession:</strong> Freelance Web Developer</p>
    </section>

    <!-- Experience Section -->
    <section class="experience">
      <h2>Experience</h2>
      <p>Additional experience details would go here...</p>
    </section>

    <!-- Footer with contact info -->
    <footer>
      <p>
        <a href="https://github.com/johndoe" target="_blank">GitHub</a> |
        <a href="contact.html">Contact</a>
      </p>
    </footer>
  </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact John Doe</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="container">
    <header>
      <h1>John Doe</h1>
      <p>Web Developer | Designer | Content Creator</p>
    </header>
    
    <!-- Contact Form Section -->
    <section class="contact-form">
      <h2>Get in Touch</h2>
      <form action="contact-form-handler.php" method="post">
        <ul>
          <li>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
          </li>
          <li>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
          </li>
          <li>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
          </li>
          <!-- Adding Address and Additional Info fields -->
          <li>
            <label for="address">Address:</label>
            <input type="text" id="address" name="address" required>
          </li>
          <li>
            <label for="additional">Additional Information:</label>
            <textarea id="additional" name="additional"></textarea>
          </li>
          <li>
            <button type="submit">Send Message</button>
          </li>
        </ul>
      </form>
    </section>
    
    <!-- Footer with links -->
    <footer>
      <p>
        <a href="https://github.com/johndoe" target="_blank">GitHub</a> |
        <a href="index.html">Back to Resume</a>
      </p>
    </footer>
  </div>

</body>
</html>
/* General Styling */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f9;
  margin: 0;
  padding: 0;
}

.container {
  width: 80%;
  margin: 0 auto;
  padding: 20px;
}

/* Header Styling */
header {
  text-align: center;
  margin-bottom: 30px;
}

header h1 {
  font-size: 2.5rem;
  margin: 0;
}

header p {
  font-size: 1.2rem;
  color: #666;
}

/* Profile Section Styling */
.profile {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 30px;
}

.profile-image img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
}

.profile-info {
  margin-left: 20px;
}

.profile-info h2 {
  font-size: 2rem;
  margin: 0;
}

.profile-info p {
  font-size: 1.1rem;
  color: #444;
}

/* Skills Section Styling */
.skills table {
  width: 100%;
  border-collapse: collapse;
}

.skills th, .skills td {
  padding: 10px;
  text-align: left;
}

.skills th {
  background-color: #333;
  color: white;
}

.skills td {
  background-color: #f9f9f9;
}

.strength {
  display: inline-block;
  width: 20px;
  height: 20px;
  background-color: #ddd;
  border-radius: 50%;
  margin-right: 5px;
}

.strength.filled {
  background-color: #4caf50;
}

/* About Section Styling */
.about {
  margin-bottom: 30px;
}

/* Footer Styling */
footer {
  text-align: center;
  margin-top: 40px;
}

footer a {
  text-decoration: none;
  color: #333;
  margin: 0 10px;
}

footer a:hover {
  text-decoration: underline;
}

/* Contact Form Styling */
.contact-form form {
  list-style: none;
  padding: 0;
}

.contact-form li {
  margin-bottom: 15px;
}

.contact-form label {
  display: block;
  font-weight: bold;
}

.contact-form input, .contact-form textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.contact-form button {
  padding: 10px 15px;
  background-color: #4caf50;
  border: none;
  border-radius: 4px;
  color: white;
  font-size: 1rem;
}

.contact-form button:hover {
  background-color: #45a049;
}
