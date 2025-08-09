# MDAP-EX_01-Portfolio
## Date: 09/08/2025

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
## HTML Code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" />
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="name">JAYARAJ</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <a href="https://github.com/Jayarajbalaji">
            <button class="git-btn">GitHub</button>
        </a>
    </header>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="img-con">
            <img src="./jayaraj.jpg" alt="Profile Picture" />
        </div>
        <div class="description">
            <h3>Hi, I am</h3>
            <h1>JAYARAJ</h1>
            <h4>Python Developer</h4>
            <div class="social-media">
                <a href="https://github.com/Jayarajbalaji"><i class="fab fa-github"></i></a>
                <a href="https://www.linkedin.com/in/jayaraj-b-5b135a344/"><i class="fab fa-linkedin"></i></a>
            </div>
            <div class="abt-btn">
                <button id="Resume" class="r-btn">Resume</button>
                <a href="#contact"><button class="c-btn">Contact Me</button></a>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="skills-container">
            <div class="askill"><h2 class="h-1">Skills</h2></div>
            <div class="experience">
                <div class="front">
                    <h3>Programming Language</h3>
                    <ul>
                        <li>C program</li>
                        <li>Java</li>
                        <li>Python</li>
                    </ul>
                </div>
                <div class="back">
                    <h3>Extracurricular Activities</h3>
                    <ul>
                        <li>NCC</li>
                        <li>NSS</li>
                        <li>Fine Arts Club as Vice Secretary</li>
                    </ul>
                </div>
                <div class="tools">
                    <h3>Language</h3>
                    <ul>
                        <li>English</li>
                        <li>Tamil</li>
                        <li>Telegu</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="projects-container">
            <div class="aproj"><h2 class="h-1">Projects</h2></div>
            <div class="card-info">
                <!-- Project 1 -->
                <div class="card">
                    <img src="./p1.jpg" alt="Project 1" />
                    <h3>Mobile Application</h3>
                    <div class="pro-btn">
                        <a href="https://github.com/Jayarajbalaji/Balsamiq"><button class="g-btn">Github</button></a>
                    </div>
                </div>               
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2 class="section-title">Contact Me</h2>
        <div class="contact-container">
            <div class="contact-info">
                <h3>Let's Connect!</h3>
                <p>Feel free to reach out. Whether you have a project in mind, want to collaborate, or just say hello, I’m always open to new opportunities.</p>
                <div class="contact-socials">
                    <a href="https://github.com/Jayarajbalaji" class="socialicon"><i class="fab fa-github"></i></a>
                    <a href="https://www.linkedin.com/in/jayaraj-b-5b135a344/" class="socialicon"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
            <form class="contact-form">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required />
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required />
                </div>
                <div class="form-group">
                    <label for="subject">Message</label>
                    <input type="text" id="subject" name="Message" required />
                </div>
                <button type="submit" class="submit-btn">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-logo">
                <h2>JAYARAJ</h2>
                <p>Passionate Python Developer creating innovative digital solutions with clean, efficient code and user-centered design.</p>
            </div>
            <div class="footer-links">
                <div class="footer-section">
                    <h4>Quick Links</h4>
                    <a href="#about">About</a>
                    <a href="#skills">Experience</a>
                    <a href="#projects">Projects</a>
                    <a href="#contact">Contact</a>
                </div>
                <div class="footer-section">
                    <h4>Resources</h4>
                    <a href="#">Resume</a>
                    <a href="#">Skills</a>
                    <a href="#">Certifications</a>
                    <a href="#">Blog</a>
                </div>
            </div>
            <div class="footer-social">
                <h4>Connect With Me</h4>
                <div class="social-icons">
                    <a href="https://github.com/Jayarajbalaji" class="social-icon"><i class="fab fa-github"></i></a>
                    <a href="https://www.linkedin.com/in/jayaraj-b-5b135a344/" class="social-icon"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <a href="#"><p id="thanks" class="credit">Designed and Developed  by JAYARAJ</p></a>
        </div>
    </footer>
    <!-- Script -->
    <script src="./script.js"></script>
</body>
</html>
```
## CSS Code
```
@import url('https://fonts.googleapis.com/css2?family=Big+Shoulders+Stencil:opsz,wght@10..72,100..900&family=Noto+Sans:ital,wght@0,100..900;1,100..900&family=Outfit:wght@100..900&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
* {
  margin: 0;
  padding: 0;
  font-family: 'Courier New', Courier, monospace;
  text-decoration: none;
  list-style: none;
  scroll-behavior: smooth;
}
/* Header */
header {
  margin: 20px auto;
  height: 40px;
  width: 650px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-radius: 45px;
  background-color: rgb(254, 244, 232);
}
.name {
  font-size: 1.2rem;
  padding: 10px;
  font-weight: bold;
  cursor: pointer;
  color: rgb(239, 155, 77);
  transition: transform 0.3s ease;
}
.name:hover {
  transform: scale(1.1);
}
nav ul {
  display: flex;
  gap: 20px;
}
nav ul li {
  position: relative;
}
nav ul a {
  color: black;
  font-size: 1rem;
  padding: 5px 8px;
  transition: color 0.3s ease;
}
nav ul a:hover {
  color: rgb(239, 155, 77);
}
nav ul a::after {
  content: "";
  position: absolute;
  width: 0;
  height: 2px;
  bottom: -2px;
  left: 0;
  background-color: rgb(239, 155, 77);
  transition: width 0.3s ease;
}
nav ul a:hover::after {
  width: 100%;
}
.git-btn {
  padding: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 20px;
  margin: 10px;
  border-radius: 15px;
  background-color: #f0f0f0;
  color: #333;
  border: none;
  transition: all 0.3s ease;
  cursor: pointer;
}
.git-btn:hover {
  background: linear-gradient(to right, #cba911, #fc7725);
  color: white;
  box-shadow: 0 4px 15px rgba(230, 143, 14, 0.4);
  transform: translateY(-2px);
}
/* About */
.about {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 100px;
  width: auto;
}
.img-con {
  width: 600px;
  height: 600px;
}
.img-con img {
  object-fit: cover;
  border-radius: 10%;
}
.img-con img:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 15px rgba(230, 143, 14, 0.4);
}
.description {
  text-align: start;
}
.description h3 {
  font-size: 1.5rem;
  font-weight: bold;
  margin-bottom: 10px;
  color: rgb(241, 198, 119);
}
.description h1 {
  font-size: 3.5rem;
  font-weight: bold;
  margin-bottom: 10px;
  color: rgb(132, 130, 128);
}
.description h4 {
  font-size: 25px;
  font-weight: bold;
  margin-bottom: 10px;
  color: rgb(241, 198, 119);
}
.social-media i {
  margin-right: 10px;
  font-size: 2rem;
  color: rgb(241, 198, 119);
  cursor: pointer;
}
.abt-btn {
  margin-top: 20px;
  display: flex;
  gap: 20px;
}
.abt-btn .r-btn,
.abt-btn .c-btn {
  font-size: 1rem;
  padding: 12px 20px;
  background-color: #e0dddd;
  border: none;
  border-radius: 30px;
  color: rgb(241, 198, 119);
  cursor: pointer;
  font-weight: bold;
  transition: all 0.3s ease-in-out;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}
.abt-btn .r-btn:hover,
.abt-btn .c-btn:hover {
  background-color: #f0f0f0;
  color: rgb(241, 141, 119);
  transform: scale(1.05);
  box-shadow: 3px 3px 12px rgba(0, 0, 0, 0.2);
}
/* Skills */
.skills {
  padding: 80px 20px;
  text-align: center;
}
.skills-container {
  max-width: 900px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.askill .h-1 {
  font-size: 32px;
  font-weight: bold;
  color: #333;
  margin-bottom: 20px;
}
.experience {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 20px;
}
.front, .back, .tools {
  background-color: rgb(241, 198, 119);
  color: white;
  padding: 50px;
  border-radius: 5px;
  box-shadow: 0 4px 15px rgba(230, 143, 14, 0.4);
  border: #333 2px solid;
  transition: all 0.3s ease;
  width: 100%;
}
.front:hover, .back:hover, .tools:hover {
  background-color: rgb(250, 213, 146);
  box-shadow: 0 6px 20px rgba(230, 143, 14, 0.6);
}
.front h3, .back h3, .tools h3 {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
  position: relative;
  padding-bottom: 10px;
  transition: color 0.3s ease;
}
.front h3::after, .back h3::after, .tools h3::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 50px;
  height: 3px;
  background-color: white;
  transition: width 0.3s ease;
}
.front:hover h3, .back:hover h3, .tools:hover h3 {
  color: rgb(80, 80, 80);
}
.front:hover h3::after, .back:hover h3::after, .tools:hover h3::after {
  width: 100px;
  background-color: rgb(80, 80, 80);
}
.front ul li, .back ul li, .tools ul li {
  text-align: start;
  padding: 5px 0;
  transition: transform 0.3s ease, color 0.3s ease;
}
.front:hover ul li, .back:hover ul li, .tools:hover ul li {
  transform: translateX(10px);
  color: rgb(80, 80, 80);
}
/* Projects */
.projects {
  padding: 80px 20px;
  text-align: center;
}
.projects-container {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.projects-container .aproj {
  font-size: 32px;
  font-weight: bold;
  color: #333;
}
.card-info {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}
.card {
  width: 300px;
  background: linear-gradient(135deg, rgb(248, 186, 110), rgb(179, 179, 179));
  border-radius: 10px;
  overflow: hidden;
  position: relative;
  box-shadow: 0 4px 15px rgba(32, 31, 31, 0.4);
  transition: transform 0.3s ease;
}
.card:hover {
  transform: scale(1.05);
}
.card img {
  width: 100%;
  height: auto;
  padding: 10px;
  background-color: rgb(208, 207, 206);
}
.card h3 {
  color: #f0f0f0;
  padding: 10px;
  background-color: #333;
}
.pro-btn button {
  padding: 10px 20px;
  border: none;
  background-color: rgb(241, 198, 119);
  color: white;
  font-weight: bold;
  cursor: pointer;
  border-radius: 5px;
  transition: all 0.3s ease;
}
.pro-btn button:hover {
  background-color: rgb(252, 183, 85);
  box-shadow: 0 4px 15px rgba(230, 143, 14, 0.4);
}
/* Contact */
.contact {
  padding: 80px 20px;
  background-color: #f9f9f9;
}
.contact-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  max-width: 1000px;
  margin: 0 auto;
  gap: 30px;
}
.contact-info {
  flex: 1;
}
.section-title {
  font-size: 2rem;
  margin-bottom: 20px;
}
.contact-info h3 {
  font-size: 1.2rem;
  margin-bottom: 5px;
  color: #333;
}
.contact-info p {
  margin-bottom: 15px;
  color: #666;
}
.contact-socials .socialicon {
  font-size: 1.5rem;
  color: rgb(241, 198, 119);
  margin-right: 15px;
}
.contact-form {
  flex: 1;
}
.form-group {
  margin-bottom: 15px;
}
.form-group input {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}
.submit-btn {
  background-color: rgb(241, 198, 119);
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
.submit-btn:hover {
  background-color: rgb(252, 183, 85);
}
/* Footer */
footer {
  background-color: #333;
  color: white;
  padding: 40px 20px;
}
.footer-content {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 30px;
}
.footer-logo h2 {
  margin-bottom: 10px;
}
.footer-links, .footer-social {
  display: flex;
  flex-direction: column;
}
.footer-section h4 {
  margin-bottom: 10px;
  font-size: 1.1rem;
  border-bottom: 1px solid #555;
  padding-bottom: 5px;
}
.footer-section a {
  color: #ccc;
  margin-bottom: 5px;
  transition: color 0.3s ease;
}
.footer-section a:hover {
  color: white;
}
.social-icons {
  display: flex;
  gap: 15px;
}
.social-icon i {
  font-size: 1.5rem;
  color: #ccc;
  transition: color 0.3s ease;
}
.social-icon i:hover {
  color: rgb(241, 198, 119);
}
.footer-bottom {
  text-align: center;
  margin-top: 30px;
  font-size: 0.9rem;
  color: #aaa;
}
```
## OUTPUT
<img width="1893" height="1012" alt="image" src="https://github.com/user-attachments/assets/a9dec608-dd13-48e7-bdf2-b00e4cb43efb" />
<img width="1876" height="1132" alt="image" src="https://github.com/user-attachments/assets/02138e11-853c-4d29-be6c-e98f29615687" />
<img width="1884" height="1191" alt="image" src="https://github.com/user-attachments/assets/1f15c80e-6e05-4d21-b8f4-60195b7c584b" />
<img width="1897" height="418" alt="image" src="https://github.com/user-attachments/assets/1ee2fca4-11da-4d21-9fa2-ab70d1a4f79e" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
