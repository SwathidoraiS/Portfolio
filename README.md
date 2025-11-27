# Ex01 Portfolio
# Name : Swathi S
# Reg N0 : 212223040220
## Date:13/08/2025

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
# index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section"><br>
    <br>
    <h1>Welcome to My Portfolio</h1>
    <h1>Swathi S</h1>
    <h3>B.E. CSE,III Year</h3><br>
    <img src="meee.jpg" alt="My Photo" style="width: 160px;" class="profile-photo"><br><br><br>
    <h4>
        
    <p>I am Swathi , a third-year Computer Science and Engineering student pursuing a BE degree.</p>
    <p>I am passionate about web development and have an interest in Full Stack developement .</p>
    <p>I enjoy building innovative projects and enhancing my skills in technology.</p>
    <p>I am enthusiastic about collaborating on projects, solving problems,<br><br> and contributing to open-source communities as I develop as a software professional.</p>
    </h4>
    
  </section>

  <section id="about" class="section">
    <br><br>
    <h2>About Me</h2><br>
    <p>I am a Computer Science and Engineering student passionate about web development and Full Stack Development.</p>
    <p>Skilled in HTML, CSS, and basic JavaScript, with the ability to create clean, responsive, and user-friendly webpages.</p>
    <p>Experienced with Python and Java, actively developing logical thinking and problem-solving abilities.</p>
    <p>I am committed to continuous learning, and I actively explore new technologies and programming languages to expand my expertise.</p>
    <p>My goal is to become a proficient full-stack developer and leverage technology to solve real-world problems.</p>
    <p>My interests include full-stack development, AI integration in web apps, and developing user-centric designs.</p>
    
  </section>

  <section id="education" class="section">
    <br><br>
    <h2>Education</h2>
    <center>
      <table style="padding: 30px; border: #333;">
        <tr>
            <th>Batch</th>
            <th>Institution</th>
            <th>Course</th>
            <th>Percentage</th>
        </tr>
        <tr>
            <td>2024-2028</td>
            <td>Saveetha Engineering College</td>
            <td>BE Computer Science and Engineering</td>
            <td>80%</td>
        </tr>
        <tr>
            <td>2022-2023</td>
            <td>St.Marys's Higher Sec School</td>
            <td>12th - Higher Secondary Education</td>
            <td>84%</td>
        </tr>
    </table>
    </center>
  </section>

  <section id="skills" class="section">
    <br><br>
    <h2>Skills</h2><br>
    <h2>Technical Skills</h2><br>
<h4>
  I) Programming:   C, Python,Java,SQL
</h4>
<h4>
 II) Web Development:   HTML, CSS, JavaScript,React
</h4>
<h4>
 III) Core CS:   DSA, OOP, DBMS, OS
</h4>
<br>
    
    <h2>Soft Skills</h2><br>
    <h4>I) Communication</h4>
    <h4>II)Team collaborater</h4>
    <h4>III)Probelm-Solving</h4>
    
</section>

  

  <section id="contact" class="section">
    <br><br>
    <h2>Contact Me</h2><br><br>
    <p>Email: swathiselladorai@gmail.com</p>
    <p>LinkedIn: <a href="#">www.linkedin.com/in/swathidorai</a></p>
    <p>GitHub: <a href="#">https://github.com/SwathidoraiS</a></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
  

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>
</section>
  
</body>
</html>
```
# style.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
    color: white; /* Text color, adjust if needed */
}

/* Table styling */
table {
    width: 70%;
    margin: auto;
    border-collapse: collapse;
    background: rgba(0, 0, 0, 0.5); /* Slight translucent background for table readability */
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
    border-radius: 8px;
    overflow: hidden;
    color: white;
}
th, td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: center;
}
th {
    background-color: rgba(255, 221, 153, 0.7);
    color: black;
}

/* Navbar */
nav {
    background: linear-gradient(90deg, #333, #555);
    padding: 10px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 8px rgba(0,0,0,0.7);
}
nav ul {
    list-style-type: none;
    text-align: center;
}
nav ul li {
    display: inline;
    margin: 0 20px;
}
nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    transition: 0.3s;
}
nav a:hover {
    color: #ffcc00;
    text-shadow: 0 0 5px #fff;
}

/* Sections */
.section {
    padding: 80px 20px;
    min-height: 100vh;
    text-align: center;
    position: relative;
    color: white; /* Adjust text color if needed based on images */
}

/* Background images without overlays or colors */

#home {
    background: url('port.avif') no-repeat center center/cover;
}

#about {
    background: url('port.avif') no-repeat center center/cover;
}

#education {
    background: url('port.avif') no-repeat center center/cover;
}

#skills {
    background: url('port.avif') no-repeat center center/cover;
}

#contact {
    background: url('port.avif') no-repeat center center/cover;
}

/* Footer */
footer {
    background: linear-gradient(90deg, #333, #555);
    color: white;
    text-align: center;
    padding: 10px 0;
}

/* Profile image */
.profile-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-top: 20px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.5);
    object-fit: cover;
    transition: transform 0.3s ease-in-out;
}
.profile-photo:hover {
    transform: scale(1.05);
}
```


## OUTPUT

<img width="1919" height="969" alt="image" src="https://github.com/user-attachments/assets/25b5f004-be8b-4d79-9d6c-60de95f6f7fc" />

<img width="1919" height="972" alt="image" src="https://github.com/user-attachments/assets/83516775-ce30-488e-a8e9-d9b29b66d88c" />

<img width="1918" height="968" alt="image" src="https://github.com/user-attachments/assets/0f7417d8-74a1-4a71-bad2-51d7998e2e8c" />

<img width="1919" height="971" alt="image" src="https://github.com/user-attachments/assets/94a62280-121f-4024-8efa-fd0191125e20" />

<img width="1913" height="973" alt="image" src="https://github.com/user-attachments/assets/40f89d55-65fd-436f-a3fd-c7c2b8065030" />







## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
