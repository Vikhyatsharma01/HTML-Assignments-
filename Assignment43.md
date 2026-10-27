grid-and-flex-landing.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid and Flex Landing Page</title>

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
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #1e293b;
            color: white;
            padding: 15px 30px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 15px;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background: #dbeafe;
        }

        .hero button {
            background: #2563eb;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 5px;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 25px;
        }

        .card {
            background: white;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
        }

        footer {
            background: #1e293b;
            color: white;
            text-align: center;
            padding: 15px;
        }

        @media (max-width: 500px) {
            header {
                flex-direction: column;
            }

            nav a {
                margin: 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h2>My Website</h2>
        <nav>
            <a href="#home">Home</a>
            <a href="#features">Features</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section class="hero" id="home">
            <h1>Welcome to My Website</h1>
            <p>Learning modern web design with HTML and CSS.</p>
            <button>Get Started</button>
        </section>

        <section class="features" id="features">
            <div class="card">
                <h3>Flexbox</h3>
                <p>Arrange items in a row or column.</p>
            </div>

            <div class="card">
                <h3>CSS Grid</h3>
                <p>Create layouts with rows and columns.</p>
            </div>

            <div class="card">
                <h3>Responsive Design</h3>
                <p>Make websites work on different screens.</p>
            </div>
        </section>
    </main>

    <footer id="contact">
        <p>© 2026 My Website</p>
    </footer>

</body>
</html>
