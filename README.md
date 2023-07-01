# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            display: flex;
            flex-direction: column;
            
            justify-content: space-around;
            height: 100vh;
            font-size: 20px;
            margin: 0;
        }

        .navigation {
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            margin-bottom: 20px;
        }

        .navigation li {
            margin: 0 20px;
        }

        section {
           
            flex-direction: row;
            justify-content: space-around;

            margin-bottom: 40px;
        }
       

    </style>
</head>
<body>
    <ul class="navigation">
        
    <section id="About">
        <h2>About</h2>
        <li><a href="about.html">About</a></li>

        
    </section>

    <section id="Resume">
        <h2>Resume</h2>
        <li><a href="resume.html">Resume</a></li>

        
    </section>

    <section id="Skills">
        <h2>Skills</h2>
        <li><a href="skills.html">Skills</a></li>

        
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <li><a href="contact.html">Contact</a></li>
        
      
    </ul>
    

    <section id="home">
        <h1>Welcome to HARI SREENIJA Portfolio</h1>
        <p>Happy to see you here</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a passionate web developer with a keen eye for design and a love for creating immersive digital experiences.</p>
    </section>

    

    <footer>
        <p>&copy; 2023 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
