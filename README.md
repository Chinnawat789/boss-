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
    <!-- Header Section -->
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
            <p><strong>Address:</strong> 1234 Web Dev Street, City, Country</p>
            <p><strong>Profession:</strong> Freelance Web Developer</p>
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
