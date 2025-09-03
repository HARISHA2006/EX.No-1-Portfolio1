# Ex:01 Portfolio
## Date : 01.09.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)
a
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

# Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>DESIGNER Portfolio</title>
 <link rel="stylesheet" href="STYLE.CSS">
</head>
<body>

 <!-- Hero Section -->
 <header class="hero">
   <div class="container">
     <h1>HI FRNDS, I'M <span class="highlight">HARISHA</span></h1>
     <p class="tagline"> DESIGNER | ARTIST</p>
     <a href="#contact" class="btn">CONTACT ME</a>
   </div>
 </header>

 <!-- About Section -->
 <section id="about" class="section" style="background-image: url(DESIN.jpeg);">
   <div class="container" >
     <h2>ABOUT ME</h2>
     <p class="para">I’m a passionate artist skilled in bringing imagination to life through colors, forms, and emotions. I love transforming complex feelings into simple, beautiful, and intuitive creations that connect deeply with people.</p>
     <p class="para h">Creativity | Imagination | Drawing | Sketching | Painting | Observation Skills | Visual Storytelling </p>
   </div>
 </section>

 <!-- Skills Section -->
 <section id="skills" class="section skills-section" style="background-image: url(SKILL.jpg);background-repeat: no-repeat;background-size: cover;">
   <div class="container">
     <h2  class="skill">Skills</h2>
     <div class="skills-grid">
       <div class="skill-card">Creativity</div>
       <div class="skill-card">Imagination </div>
       <div class="skill-card">Drawing </div>
       <div class="skill-card">Sketching</div>
       <div class="skill-card">Painting</div>
       <div class="skill-card">Observation Skills</div>
       <div class="skill-card">Visual Storytelling</div>
       <div class="skill-card">Patience</div>
     </div>
   </div>
 </section>

<!-- Project Cards Section -->
<div class="project-grid">

   <div class="project-card">
       <img src="DESIGNN.jpg" alt="Project 1">
       <h3>DESIGNER</h3>
     <p>A designer’s portfolio is a curated collection of design work that shows your style, skills, and creativity</p>
     <a href="#" class="btn">View Project</a>
   </div>
 
   <div class="project-card">
     <img src="CREATIVE.webp" alt="CREATIVITY">
     <h3>CREATIVITY</h3>
     <p>Creativity is the power to transform the invisible (ideas, emotions) into the visible (art, design, experiences).</p>
     <a href="#" class="btn">View Project</a>
   </div>
 
   <div class="project-card">
     <img src="PORT.jpg" alt="Portfolio Website">
     <h3>Portfolio Website</h3>
     <p>A portfolio website is your digital gallery — a place where you showcase your best artworks</p>
     <a href="#" class="btn">View Project</a>
   </div>
 
 </div>
 

 <!-- Contact Section -->
 <section id="contact" class="section" style="background-image: url(CONTACT.webp);background-repeat: no-repeat;background-size: cover    ;">
   <div class="container">
     <h2 class="para">Contact Me</h2>
     <p class="para">If you're looking to build your product, feel free to reach out!</p>
     <p class="para"> Email: <a href="mailto:youremail@example.com">harisanthosh2006@example.com</a></p>
     <p class="para">LinkedIn: <a href="#" target="_blank">linkedin.com/in/harishasanthosh</a></p>
     <p class="para">GitHub: <a href="#" target="_blank">github.com/harishasanthosh0311</a></p>
   </div>
 </section>

 <!-- Footer -->
 <footer class="footer" >
   <div class="container">
     <p>&copy; 2025 /Harisha S. Made with 🎨 for the Web.</p>
   </div>
 </footer>

</body>
</html>




```

# Style.css

```


/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Global Styles */
  body {
    font-family: 'Poppins', sans-serif;
    color: #222;
    background: #f0f2f5;
  }
  
  .container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
    padding: 40px 20px;
  }
  
  a {
    text-decoration: none;
  }
  
  /* Hero Section */
  .hero {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
      url('ARTIST.jpeg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 160px 20px;
  }
  
  .hero h1 {
    font-size: 50px;
    margin-bottom: 10px;
  }
  
  .highlight {
    color: #f309cc;
  }
  
  .tagline {
    font-size: 24px;
    margin-bottom: 30px;
    color: #ccc;
  }
  
  .btn {
    background: linear-gradient(90deg, #51b1c5, #3e7bc1);
    color: #fff;
    padding: 14px 32px;
    border-radius: 30px;
    font-weight: bold;
    transition: background 0.4s;
  }
  
  .btn:hover {
    background: linear-gradient(90deg, #0078ff, #00d4ff);
  }
  
  /* Sections */
  .section {
    padding: 80px 0;
  }
  .para{
    color: rgb(224, 233, 203);
  }
  .h{
    font-weight: 1000;
  }
  
  .section h2 {
    font-size: 36px;
    margin-bottom: 20px;
    text-align: center;
    color: #0dfef2;
  }
  
  /* Skills Section */
  .skills-section {
    background: #fff;
  }
  .skill{
    color: white;
    font-size: large;
  }
  
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }
  
  .skill-card {
    background: linear-gradient(135deg, #ea00ff 0%, #468aa1 100%);
    color: #fff;
    padding: 20px;
    text-align: center;
    border-radius: 8px;
    font-weight: bold;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s;
  }
  
  .skill-card:hover {
    transform: scale(1.05);
  }
  
  /* Projects Section */
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 40px;
  }
  
  .project-card {
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 6px 20px rgba(0,0,0,0.1);
    transition: transform 0.3s;
    text-align: center;
    height: 370px;
  }
  
  .project-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }
  
  .project-card h3 {
    margin: 15px 0 10px;
    font-size: 22px;
  }
  
  .project-card p {
    padding: 0 15px 20px;
    font-size: 15px;
    color: #555;
  }
  
  .project-card .btn {
    margin-bottom: 20px;
  }
  
  /* Contact Section */
  #contact a {
    color: #871bf3;
  }
  .par{
    color: rgb(225, 37, 37);
  }
  
  /* Footer */
  .footer {
    background: #222;
    color: #dfd7d7;
    text-align: center;
    padding: 20px;
    font-size: 14px;
  }
  


```


## OUTPUT
<img width="1897" height="930" alt="image" src="https://github.com/user-attachments/assets/0ee0a156-e93a-417a-8146-fb8a689f2d02" />

<img width="1897" height="930" alt="image" src="https://github.com/user-attachments/assets/40d58acc-91fd-4b9a-b236-b509199008f8" />

<img width="1898" height="884" alt="image" src="https://github.com/user-attachments/assets/b67f2e81-128c-49c7-84d6-70e8522be96b" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
