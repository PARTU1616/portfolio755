<!DOCTYPE html>
<html>
<head>
  <title>My Portfolio</title>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #232931;
      color: #ffffff;
    }

    /* Header Styles */
    header { 
      background-color: #131921;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: 32px;
      color: #ffffff;
    }

    nav {
      margin-top: 20px;
    }

    nav ul {
      list-style-type: none;
      padding: 0;
      text-align: center;
    }

    nav ul li {
      display: inline-block;
      margin-right: 10px;
    }

    nav ul li a {
      color: #ffffff;
      text-decoration: none;
      padding: 8px 16px;
      border-radius: 4px;
      background-color: #131921;
      transition: background-color 0.3s ease;
    }

    nav ul li a:hover {
      background-color: #0c0f12;
    }

    /* Section Styles */
    section {
      padding: 50px;
    }

    h2 {
      color: #ffffff;
      font-size: 24px;
      margin-bottom: 20px;
    }

    p {
      font-size: 18px;
      line-height: 1.5;
    }

    /* About Section Styles */
    #about {
      background-color: #293241;
      text-align: center;
    }

    #about img {
      max-width: 300px;
      height: auto;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    hr {
      border: none;
      border-top: 1px solid #536162;
      margin: 20px 0;
    }

    /* Projects Section Styles */
    #projects {
      background-color: #3d5a80;
      text-align: center;
    }

    .project {
      display: inline-block;
      margin: 100px;
      text-align: left;
    }

    .project img {
      width: 380px;
      height: 340px;
    }

    .project h3 {
      margin-top: 10px;
      font-size: 20px;
    }

    /* Skills Section Styles */
    #skills {
      background-color: #152f3e;
      text-align: center;
    }

    #skills ul {
      list-style-type: none;
      padding: 0;
    }

    #skills li {
      font-size: 20px;
      margin-bottom: 10px;
    }

    /* Contact Section Styles */
    #contact {
      background-color: #2e0101;
      text-align: center;
      padding-bottom: 50px;
    }

    form {
      max-width: 400px;
      margin: 0 auto;
    }

    label {
      display: block;
      margin-bottom: 10px;
      font-size: 20px;
    }

    input,
    textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      font-size: 16px;
      border-radius: 4px;
      border: none;
    }

    input[type="submit"] {
      background-color: #293241;
      color: #ffffff;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    input[type="submit"]:hover {
      background-color: #0c0f12;
    }

    /* Footer Styles */
    footer {
      background-color: #131921;
      color: #ffffff;
      padding: 20px;
      text-align: center;
    }

    footer p {
      margin: 0;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#activities">Activities</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h1>About Me</h1>
    <p>Prathmesh Galugade</p>
    <img src="WhatsApp Image 2023-06-30 at 13.28.35.jpg " alt="Profile Picture">
    <hr>
    <p>I am a computer engineering student from MIT Academy of Engineering, Alandi, Pune.  I have a passion for coding and enjoy working on projects that involve problem-solving and creativity.</p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <p>
      
      <strong>CET Percentile - 95 Percentile</strong><br><br>
      <strong>JEE Percentile - 89 Percentile</strong><br><br>
     
      <strong>HSC - YC College , Urun Islampur</strong><br>
      Percentage - 87%<br><br>
      <strong>SSC - Islampur Highschool Islampur</strong><br>
      Percentage - 95%<br><br>
    </p>
  </section>

  <section id="activities">
    <h2>Extra Curricular Activities</h2>
    <p>I am also a state-level cricket player and have actively participated in various tournaments and championships.</p>
  </section>

  <section id="projects">
    <h1>Projects</h1>
    <div class="project">
      <img src="37f71fac25ae487599ecd637c11e3392.jpeg.jpg" alt="Project 1"><br>
      <h3>Project 1 - Applied Mechanics <br> Parachute Making Model</h3>
      
    </div>
    <div class="project">
      <img src="WhatsApp Image 2023-06-30 at 13.34.49.jpg" alt="Project 2"><br>
      <h3>Project 2 - Graphics Model Making</h3>
      
    </div>
  </section>

  <section id="skills">
    <h1>Skills</h1>
    <ul>
      <li>HTML</li><br>
      <li>CSS</li><br>
      <li>JavaScript</li><br>
      <li>Python</li><br>
    </ul>
  </section>

  <section id="contact">
    <h1>Contact Me</h1><br>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
      <input type="submit" value="Submit">
    </form>
  </section>

  <footer>
    <p>&copy; 2023 My Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>
