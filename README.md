# codesoft_portfolio
i developed portfolio using  html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        header p {
            margin: 5px 0;
            font-size: 18px;
        }

        section {
            padding: 40px;
        }

        #about img {
            width: 200px;
            border-radius: 50%;
            display: block;
            margin: 0 auto 20px;
        }

        #skills ul {
            list-style: none;
            padding: 0;
        }

        #skills li {
            display: inline-block;
            margin-right: 20px;
        }

        #projects .project-card {
            margin-bottom: 40px;
        }

        #projects img {
            width: 100%;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Your Name</h1>
        <p>Web Developer & Designer</p>
    </header>

    <!-- About Section -->
    <section id="about">
        <img src="your-photo.jpg" alt="Your Name">
        <h2>About Me</h2>
        <p>
            Write a short bio highlighting your skills and experience.
        </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Web Development</li>
            <li>HTML/CSS</li>
            <li>JavaScript</li>
            <li>UI/UX Design</li>
            <!-- Add more skills here -->
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <!-- Add project cards with titles, descriptions, and images here -->
        <div class="project-card">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project Title 1</h3>
            <p>Project description goes here.</p>
        </div>
        <div class="project-card">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project Title 2</h3>
            <p>Project description goes here.</p>
        </div>
        <!-- Add more project cards as needed -->
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <h2>Resume</h2>
        <p>Download my resume <a href="your-resume.pdf" target="_blank">here</a>.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: your.email@example.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
