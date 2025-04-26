# MDAP-EX_01-Portfolio
## Date:

### Name : VIKRAM K
### Reg No : 212222040180
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
#### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Montserrat:wght@700;800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <nav class="navbar" id="">
        <ul>
            <li id="title"><a href="#" style="font-size: x-large;">Portfolio</a></li>
            <li><a href="#home">About</a></li>
            <li><a href="#skill">Skills</a></li>
            <li><a href="#project">Project</a></li>
            <li><a href="#contact">Contact As</a></li>
            
        </ul>
    </nav>

    <!-- Home -->
    <section id="home">
        <div class="main">
            <h1 class="title"><span>Hello , </span>I am<br>Vikram</h1>
            <button class="btn">Let's See</button>
            <div class="social-icons">
                <a href="https://github.com/VIKRAMK21062005" class="social-icon"><i class="fab fa-github"></i></a>
                <a href="https://www.linkedin.com/in/vikram-k2161/" class="social-icon"><i class="fab fa-linkedin-in"></i></a>
                <a href="https://www.linkedin.com/in/vikram-k2161/" class="social-icon"><i class="fab fa-twitter"></i></a>
            </div>
            <div class="img">
                <img src="images/its-me.png" alt="">
            </div>
        </div>
    </section>
    <section id="Project">
        <div class="main">
            <div class="content">
                
            </div>
        </div>

    </section>  

    <!-- Skills -->
     <section id="skill">
            <div class="s-space">
                <div class="s-head" id="s-title">
                    <h2><a href="#">Skills</a></h2>
                </div>
                <div class="s-container">
                    <div class="s-title">
                        <h3>Front-End</h3>
                        <div class="content">
                            <li>
                                <ul>HTML</ul>
                                <ul>CSS</ul>
                                <ul>JAVASCRIPT</ul>
                                <ul>BOOTSTRAP</ul>
                            </li>
                        </div>
                    </div>
                    <div class="s-title">
                        <h3>Back-End</h3>
                        <div class="content">
                            <li>
                                <ul>Node.js</ul>
                                <ul>Spring Boot</ul>
                                <ul>Express.js</ul>
                            </li>
                        </div>
                    </div>
                    <div class="s-title">
                        <h3>DataBase</h3>
                        <div class="content">
                            <li>
                                <ul>MySQl</ul>
                                <ul>SQL</ul>
                                <ul>Mango-DB</ul>
                            </li>
                        </div>
                    </div>
                    <div class="s-title">
                        <h3>Programming Language</h3>
                        <div class="content">
                            <li>
                                <ul>C</ul>
                                <ul>PYTHON</ul>
                                <ul>JAVA</ul>
                            </li>
                        </div>
                    </div>
                </div>
            </div>
     </section>
    
    <!-- Project -->

    <section class="project" id="project">
        <div class="p-space">
            <div class="p-head">
                <h2><a href="#">Projects</a></h2>
            </div>
            <div class="p-container">
                <div class="p-title">
                    <img src="images/project1.png" alt="Task Management">
                    <h3>Alumni Bridge</h3>
                    <div class="content">
                        <p>Alumni Bridge is a web platform connecting students and alumni for networking, mentorship, and career opportunities.
                        </p>
                    </div>
                </div>
                <div class="p-title">
                    <img src="images/project2.png" alt="Portfolio Website">
                    <h3>Movie Recommendation System</h3>
                    <div class="content">
                        <p>A Movie Recommendation System that suggests films based on user preferences and viewing history using machine learning.</p>
                    </div>
                </div>
                <div class="p-title">
                    <img src="images/project3.png" alt="Weather App">
                    <h3>Weather App</h3>
                    <div class="content">
                        <p>A weather forecast app that fetches real-time weather data using an API.</p>
                    </div>
                </div>
                <div class="p-title">
                    <img src="images/image.jpg" alt="Chat Application">
                    <h3>Chat Application</h3>
                    <div class="content">
                        <p>A real-time messaging app using WebSockets for instant communication.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
      <!-- footer   -->
       <footer>
        <div class="f-begin" id="contact">
            <div class="heading"><h2><a href="#">Contact Me</a></h2></div>
            <div class="f-btn">
                <a href="resume.pdf" download class="btn" id="resumeBtn">Download Resume</a>
                <a href="saveetha@gmail.com" class="btn"> Contact Me</a>
                <a href="linkned-In" target="_blank" class="btn">LinkedIn</a>

            </div>
        </div>
       
        <button id="backtop"><a href="#">Back to Top</a>
            </button><br><br>
            <div class="f-just">
                <span>
                    Created By <a href="#"> &copy --Vikram K</a> | <span class="far fa-copyright">2025 If You Doubt Flat Out!</span>
                </span>
            </div>
        
       </footer>
       <script src="script.js"></script>
</body>
</html>
```
#### style.css
```
@import url('https://fonts.googleapis.com/css2?family=Anton&family=Dancing+Script:wght@400..700&family=Sevillana&display=swap');

:root{
    --font1:'Anton',sans-serif;
    --font2:'Courier New', Courier, monospace;
}

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    font-family:var(--font1);
    list-style: none;
    scroll-behavior: smooth;
}

.navbar{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: black;
    position: fixed;
    top: 0;
    position: relative;
    
}


.navbar ul{
    display: flex;
    list-style: none;
    margin: 20px 0px;
    width: 100%;
    padding: 10px 0px;
    justify-content: space-between;
}

.navbar ul li a{
    color: white;
    padding: 8px 25px;
     font-family: sans-serif;
    font-size: 1.1rem;
    font-weight:bold;
}


#title{
    margin-right: auto;
    font-size: xx-large;
    font-weight: bold;
}

#title span{
    font-size: x-large;
    font-weight: 600;
}
.navbar ul #title{
    left: 0;
    text-align: left;
    color: rgb(215, 185, 11);
    position: relative;
}


.navbar ul li a:hover{
    background-color: white;
    color: black;
    border-radius: 50px;
    box-shadow: 0 0 10px white;
}

/* Home */

#home{
    display: flex;
    position: relative;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    color: white;
    background: url('images/image.jpg') no-repeat center center/cover;
}

#home .main {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    position: absolute;
    top: 10%;
    right: 10%;
    gap: 20px;
}
.title {
    font-family: sans-serif;
    font-size: 3rem;
    text-align: left; 
    margin: 0 20px;
    width: max-content;
}
.img img {
    width: 490px;
    height: 480px;
    opacity: 0; 
    transition: opacity 0.5s ease-in-out;
    border-radius: 50%;
}

.btn {
    padding: 12px 20px;
    background-color: transparent;
    border: 2px solid white;
    color: white;
    font-size: 1rem;
    font-weight: bold;
    border-radius: 25px;
    text-transform: uppercase;
    cursor: pointer;
}

.btn:hover ~ .img img {
    opacity: 1; 
    flex-direction: row-reverse;
}

.social-icons {
    display: flex;
}

.social-icon {
    width: 40px;
    height: 40px;
    background-color: rgb(7, 7, 7);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-right: 15px;
    font-size: 1.2rem;
    color: white;
    box-shadow: 0 0 10px;
}

.social-icon:hover {
    background-color: gray;
    color: white;
    transform: translateY(-3px);
    
} 

/* skill */

#skill {
    text-align: center;
    padding: 60px 20px;
    background-color: black;
    color: white;
    
}

.project .s-space{
    top: 0;
}
.s-head h2 {
    font-size: 2rem;
    color: yellow;
    margin-bottom: 30px;
}

.s-head h2 a {
    text-decoration: none;
    color: yellow;
}

.s-head h2 a:hover {
    color: orange;
}

.s-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    font-family: var(--font2);
}

.s-title {
    background: rgb(20, 20, 20);
    padding-top: 15px;
    width: 280px;
    border-radius: 10px;
    box-shadow: 0 0 5px rgb(9, 208, 29);
    text-align: center;
    transition: transform 0.3s ease-in-out;
}


.s-title h3 {
    margin-bottom: 10px;
    color: cyan;
    font-family: var(--font2);
}
.s-title .content ul li {
    font-size: 14px;
    color: white;
    list-style: circle;
    font-family: var(--font2);
    list-style: none;
}

.s-title .s-head h2{
    color: orange;
}
.s-title .content p {
    font-size: 14px;
    color: white;
}
/* project */

.project {
    text-align: center;
    padding: 60px 20px;
    background-color: black;
    color: white;
}

.project .p-space{
    top: 0;
}
.p-head h2 {
    font-size: 2rem;
    color: yellow;
    margin-bottom: 30px;
}

.p-head h2 a {
    text-decoration: none;
    color: yellow;
    transition: color 0.3s ease-in-out;
}

.p-head h2 a:hover {
    color: orange;
}

.p-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.p-title {
    background: rgb(20, 20, 20);
    padding: 15px;
    width: 280px;
    border-radius: 10px;
    box-shadow: 0 0 5px yellow;
    text-align: center;
    transition: transform 0.3s ease-in-out;
}

.p-title:hover {
    transform: scale(1.05);
}

.p-title img {
    width: 100%;
    height: 180px;
    border-radius: 10px;
    object-fit: cover;
    margin-bottom: 10px;
}

.p-title h3 {
    margin-bottom: 10px;
    color: cyan;
}

.p-title .content p {
    font-size: 14px;
    color: white;
}

/* footer */

footer {
    background: black;
    padding: 20px;
    color: white;
    text-align: center;
    position: relative;
    font-family: sans-serif;
    font-weight: 300;
}

footer span a {
    color: red;
    font-weight: bold;
    text-decoration: none;
    
}
footer .f-just{
    background-color: gray;
    padding: 20px;
}

footer .f-begin{
    font-family: 'Courier New', Courier, monospace;
}

.f-btn {
    margin-top: 15px;
}

.f-btn .btn {
    display: inline-block;
    padding: 10px 20px;
    background: red;
    color: white;
    font-size: 1rem;
    font-weight:lighter;
    border-radius: 25px;
    text-decoration: none;
    margin: 5px;
    transition: 0.3s ease-in-out;
    font-family: 'Courier New', Courier, monospace;
}

.f-btn .btn:hover {
    background: yellow;
    color: black;
    box-shadow: 0 0 10px white;
}

#backtop {
    margin-top: 20px;
    padding: 10px 20px;
    background: white;
    color: black;
    border: none;
    font-weight: bold;
    border-radius: 20px;
    cursor: pointer;
    transition: 0.3s ease-in-out;
}

#backtop:hover {
    background: yellow;
    color: black;
    box-shadow: 0 0 10px white;
}


@media screen and (max-width: 600px) {
    /* Navbar */
    .navbar ul {
        flex-direction: column;
        align-items: center;
    }

    .navbar ul li {
        margin: 10px 0;
    }

    /* Home Section */
    .main {
        flex-direction: column;
        text-align: center;
    }

    .main h1 {
        font-size: 24px;
    }

    .btn {
        padding: 10px 15px;
        font-size: 14px;
    }

    .social-icons {
        display: flex;
        justify-content: center;
    }

    .img img {
        width: 80%;
        margin-top: 20px;
    }

    /* Skills & Projects */
    .s-container, 
    .p-container {
        flex-direction: column;
        align-items: center;
    }

    .p-title img {
        width: 100%;
    }

    /* Footer */
    .f-begin {
        text-align: center;
    }

    .f-btn {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .f-btn .btn {
        margin-bottom: 10px;
    }

    #backtop {
        width: 100%;
    }
}
```
#### script.js
```
document.addEventListener("DOMContentLoaded", function () {
  const seeBtn = document.querySelector(".btn");

  seeBtn.addEventListener("click", function () {
      alert("Hello, I am Vikram K, a passionate Full-Stack Developer! 🚀");
  });
});

document.addEventListener("DOMContentLoaded", function () {
  let resumeBtn = document.getElementById("resumeBtn");
  resumeBtn.onclick = function (event) {
      event.preventDefault();
      alert("Resume is not available for download at the moment.\n\nWhich resume do you want? 😂\nCall this number: 100 📞");
  };
});
```
## OUTPUT

### NavBar:

![image](https://github.com/user-attachments/assets/35885ac0-8d18-4bb6-95c3-9b738e33c0f7)

### About:

![image](https://github.com/user-attachments/assets/b451e3b8-fca9-4f36-b9f8-26eec3e7e13f)

### Skills & Projects:

![image](https://github.com/user-attachments/assets/f7d7acb6-7168-4233-bdcd-0fd01a0bbab1)

### Contact:

![Screenshot 2025-03-23 220221](https://github.com/user-attachments/assets/706dc014-8a14-4259-8c4a-1d05533e829e)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
