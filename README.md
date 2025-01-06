<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOVIEMAZA - Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
        }
        header {
            background-color: #4682b4;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            padding: 14px 16px;
            text-align: center;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        /* Media query for responsive design */
        @media (max-width: 600px) {
            nav a {
                float: none;
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to MOVIEMAZA</h1>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <main>
        <section id="home">
            <h2>Welcome!</h2>
            <p>Hello, I'm MOVIEMAZA. This is my personal website where you can learn more about me and my work.</p>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>I am a passionate developer with an interest in web development, AI, and technology. I love to build websites and create innovative solutions to solve real-world problems.</p>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch, feel free to email me at: <a href="mailto:pandeysaksham876@gmail.com">pandeysaksham876@gmail.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 MOVIEMAZA. All Rights Reserved.</p>
    </footer>
</body>
</html>
