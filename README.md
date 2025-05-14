<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Simple portfolio landing page of Iqrar Ali, a web developer with expertise in Java, HTML, CSS, and JavaScript.">
    <title>Iqrar Ali - Portfolio Landing Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 3rem 1rem;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        .container {
            width: 80%;
            max-width: 1000px;
            margin: auto;
            padding: 2rem 0;
        }
        section {
            background: #fff;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        section h2 {
            color: #2c3e50;
            margin-bottom: 1rem;
        }
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
        }
        .project-card {
            background: #f9f9f9;
            padding: 1rem;
            border-radius: 5px;
            text-align: center;
        }
        .project-card h3 {
            margin-bottom: 0.5rem;
        }
        .project-card p {
            font-size: 0.9rem;
            margin-bottom: 0.5rem;
        }
        .project-card a {
            color: #3498db;
            text-decoration: none;
        }
        .project-card a:hover {
            text-decoration: underline;
        }
        .skills ul {
            list-style: none;
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
        }
        .skills li {
            background: #3498db;
            color: #fff;
            padding: 0.5rem;
            border-radius: 3px;
            font-size: 0.9rem;
        }
        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            background: #3498db;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background: #2980b9;
        }
        footer {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }
        @media (max-width: 768px) {
            .container {
                width: 90%;
            }
            header h1 {
                font-size: 2rem;
            }
            header p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Iqrar Ali</h1>
        <p>Web Developer | Java, HTML, CSS, JavaScript</p>
    </header>
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I'm Iqrar Ali, a web developer with 1 year of experience in building responsive websites and backend solutions. Skilled in Java, HTML, CSS, and JavaScript, I'm passionate about creating user-friendly applications and eager to contribute to Ij-Agency's projects.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Todo List App</h3>
                    <p>A task management app with user authentication.</p>
                    <p><strong>Tech:</strong> Java, Spring Boot, HTML, CSS, JavaScript</p>
                    <p><a href="#">View Project</a></p>
                </div>
                <div class="project-card">
                    <h3>Personal Blog</h3>
                    <p>A responsive blog with dynamic content.</p>
                    <p><strong>Tech:</strong> HTML, CSS, JavaScript</p>
                    <p><a href="#">View Project</a></p>
                </div>
            </div>
        </section>
        <section id="skills">
            <h2>Skills</h2>
            <ul class="skills">
                <li>Java</li>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Reach out to discuss opportunities!</p>
            <p>Email: <a href="mailto:iqrara52@gmail.com">iqrara52@gmail.com</a></p>
            <p><a href="#" class="btn">View Full Portfolio</a></p>
        </section>
    </div>
    <footer>
        <p>© 2025 Iqrar Ali. All rights reserved.</p>
    </footer>
</body>
</html>
