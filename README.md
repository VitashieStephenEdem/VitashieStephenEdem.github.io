<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0; 
            padding: 0;
            background-color: #f5f5f5;
            scroll-behavior: smooth; /* Enables smooth scrolling */
        }

        /* Header Styling */
        header {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        header h1 {
            color: white;
            margin: 0;
        }

        /* Navigation Bar */
        nav {
            background-color: #444;
            overflow: hidden;
        }

        nav a {
            float: left;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Section Content Styling */
        .content {
            padding: 60px;
            text-align: center;
        }

        .content img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Footer Styling */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My GitHub Portfolio</h1>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#portfolio">Portfolio</a>
        <a href="https://github.com/chuqudee" target="_blank">GitHub</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Me Section -->
    <div class="content" id="about">
        <h2>About Me</h2>
        <p>Hello! I am a passionate data scientist and developer who loves creating projects and exploring new technologies.</p>
        <img src="your-profile-picture.jpg" alt="My Profile Picture">
    </div>

    <!-- Projects Section -->
    <div class="content" id="projects">
        <h2>Projects</h2>
        <p>Check out some of my recent work:</p>
        <a href="https://github.com/your-username/project1" target="_blank">
            <img src="project1-image.jpg" alt="Project 1">
        </a>
        <a href="https://github.com/your-username/project2" target="_blank">
            <img src="project2-image.jpg" alt="Project 2">
        </a>
	<a href="https://github.com/your-username/project2" target="_blank">
            <img src="project2-image.jpg" alt="Project 3">
        </a>
    </div>

    <!-- Portfolio Section -->
    <div class="content" id="portfolio">
        <h2>Portfolio</h2>
        <p>Visit my portfolio for more work and insights.</p>
        <a href="https://your-portfolio-website.com" target="_blank">View Portfolio</a>
    </div>

    <!-- Footer Section -->
    <footer id="contact">
        <p>Contact me: <a href="mailto:mikel.okreafor@gmail.com">your-email@example.com</a></p>
    </footer>

</body>
</html>
