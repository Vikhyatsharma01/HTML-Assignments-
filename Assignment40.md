grid-project-portfolio.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f1f5f9;
        }

        header {
            background: #1e293b;
            color: white;
            text-align: center;
            padding: 25px;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 25px;
        }

        section {
            background: white;
            padding: 20px;
            border-radius: 8px;
        }

        h2 {
            color: #2563eb;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #1e293b;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>Vikhyat Sharma</h1>
        <p>BCA Artificial Intelligence Student</p>

        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
        </nav>
    </header>

    <main class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I am learning web development and programming.</p>
        </section>

        <section id="skills">
            <h2>My Skills</h2>
            <p>HTML, CSS, Java and Python basics.</p>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <p>My Study Hub and Personal Portfolio.</p>
        </section>
    </main>

    <footer>
        <p>© 2026 My Portfolio</p>
    </footer>

</body>
</html>
