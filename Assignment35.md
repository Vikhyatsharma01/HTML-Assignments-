flex-navbar-hero.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flex Navbar Hero</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #222;
            color: white;
            padding: 15px 30px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 15px;
        }

        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            min-height: 300px;
            background: #e8f0ff;
            padding: 30px;
        }

        .hero button {
            padding: 10px 20px;
            background: #2563eb;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <nav>
        <h2>My Website</h2>
        <div>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section class="hero" id="home">
        <div>
            <h1>Welcome to My Website</h1>
            <p>Learning HTML and CSS with Flexbox.</p>
            <button>Get Started</button>
        </div>
    </section>

</body>
</html>
