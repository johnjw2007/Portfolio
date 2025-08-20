# Ex01 Portfolio
## Date: 20.08.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

##exp1.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John's Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>John Wilfred Thomas J W's Profile</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to My Portfolio</h2>
    <img src="C:\Users\johnj\Desktop\Modern Web\Exp 1\Photo.jpeg" alt="John" class="profile-pic">
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi! I am John Wilfred Thomas J W, an undergraduate student at Saveetha Engineering College, pursuing Information Technology.  
    Passionate about technology, I enjoy exploring programming languages like Python, C, C++, and web development with HTML, CSS, and MySQL.  
    I am a fast learner and eager to build innovative projects that solve real-world problems.  
    My interests include software development, problem-solving, and continuous learning.  
    I enjoy working in teams, sharing ideas, and collaborating to create impactful solutions.  
    Outside academics, I like improving my creative skills and exploring emerging technologies.  
    I aim to grow into a skilled software developer and contribute to the tech industry with dedication and passion.  .</p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <p><strong>Saveetha Engineering College</strong><br>B.E CSE</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul class="skills">
      <li>Python</li>
      <li>C</li>
      <li>C++</li>
      <li>HTML</li>
      <li>CSS</li>
      <li>MySQL</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>A simple personal portfolio website showcasing my details, skills, and projects.</p>
      <a href="https://github.com/johnjw2007" target="_blank">View on GitHub</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:johnjw2007@gmail.com">johnjw2007@gmail.com</a></p>
    <p>GitHub: <a href="https://github.com/johnjw2007" target="_blank">github.com/johnjw2007</a></p>
    <p>LinkedIn: <a href="www.linkedin.com/in/john-jw" target="_blank">linkedin.com/in/john-jw</a></p>
  </section>

  <footer>
    <p>© 2025 John. All rights reserved.</p>
  </footer>
</body>
</html>
```
##style.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background: #f4f4f9;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 15px 20px;
  text-align: center;
}

header h1 {
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

nav ul li {
  margin: 5px 10px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #f4d03f;
}

section {
  padding: 40px 20px;
  text-align: center;
}

section h2 {
  margin-bottom: 20px;
  color: #222;
}

.profile-pic {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  margin: 20px 0;
  border: 4px solid #333;
}

.skills {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.skills li {
  background: #333;
  color: #fff;
  margin: 5px;
  padding: 10px 15px;
  border-radius: 20px;
}

.project-card {
  background: #fff;
  padding: 20px;
  margin: 10px auto;
  border-radius: 10px;
  max-width: 400px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.project-card a {
  display: inline-block;
  margin-top: 10px;
  text-decoration: none;
  color: #0077b6;
  font-weight: bold;
}

.project-card a:hover {
  color: #005f73;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
```
## OUTPUT

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/789714eb-a153-4457-99ab-a01efd7360ce" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/2706a829-31bc-44c8-a822-957b664b9660" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
