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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<img src="image.jpg" alt="Image" class="square-image">
    <!-- Header / Home -->
    <header id="home">
        <div class="header-content">
            <h1>Hi, I'm JAYARAJ B</h1>
            <h2>Python Developer</h2>
            <a href="#projects" class="btn">View My Work</a>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- About -->
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a passionate developer with a versatile background in web development.
             I thrive on building interactive applications and crafting innovative solutions that push the boundaries of technology and creativity.
             My interests also extend to exploring  PCB design and UI/UX design, where I enjoy blending functionality with thoughtful user experience.</p>
    </section>

    <!-- Projects -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <img src="p1.jpg" alt="Machine Learning Project">
                <h3>Mobile Application</h3>
                <p>Built a classification model with UI&UX design.</p>
            </div>

        </div>
    </section>

    <!-- Skills -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>C</li>
            <li>Python</li>
            <li>PCB Design</li>
            <li>HTML & CSS</li>
        </ul>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: jayaraj.bf1@gmail.com</p>
        <p>GitHub: <a href="https://github.com/Jayarajbalaji" target="_blank">github.com/JAYARAJ</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/jayaraj-b-5b135a344/" target="_blank">linkedin.com/in/JAYARAJ</a></p>
    </section>

    <footer>
        <p>© 2025 JAYARAJ | Portfolio</p>
    </footer>

</body>
</html>
```
## CSS Code
```

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: url('a1.jpg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
}

.header-content h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.header-content h2 {
    font-size: 1.5rem;
    margin-bottom: 20px;
}

.btn {
    background: #ff5722;
    padding: 10px 20px;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}


nav {
    background: #333;
    position: sticky;
    top: 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    margin: 0;
    padding: 10px 0;
}

nav ul li a {
    color: white;
    padding: 10px 15px;
    text-decoration: none;
}

nav ul li a:hover {
    background: #ff5722;
    border-radius: 5px;
}


section {
    padding: 50px;
    text-align: center;
}


.project-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.project-card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    width: 300px;
    padding: 15px;
    transition: transform 0.2s ease-in-out;
}

.project-card:hover {
    transform: scale(1.05);
}

.project-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}


#skills ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    list-style: none;
    gap: 15px;
    padding: 0;
}

#skills li {
    background: #ff5722;
    color: white;
    padding: 10px 15px;
    border-radius: 5px;
}


#contact a {
    color: #ff5722;
    text-decoration: none;
}


footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 15px;
}

```
## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/24e4b568-7612-4ab3-bc96-29706ab6504d" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d009fc0c-6df6-41b8-850f-3d483472acd1" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/1e4334d4-e28d-4d1d-be68-6f354481c933" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
