landing-responsive-final.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Landing Page</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f8fafc;
            color: #1e293b;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            background: #1e293b;
            color: white;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 15px;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
            background: #dbeafe;
        }

        .hero button {
            background: #2563eb;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            padding: 25px;
        }

        .card {
            background: white;
            padding: 25px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 5px #ddd;
        }

        footer {
            background: #1e293b;
            color: white;
            text-align: center;
            padding: 15px;
        }

        @media (max-width: 768px) {
            .features {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 500px) {
            header {
                flex-direction: column;
                padding: 15px;
            }

            nav a {
                margin: 5px;
            }

            .features {
                grid-template-columns: 1fr;
            }

            .hero {
                padding: 35px 15px;
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
            <h1>Build Your Future</h1>
            <p>Learn, create and grow with modern web development.</p>
            <button>Get Started</button>
        </section>

        <section class="features" id="features">
            <div class="card">
                <h3>HTML</h3>
                <p>Create webpage structures.</p>
            </div>

            <div class="card">
                <h3>CSS</h3>
                <p>Design beautiful webpages.</p>
            </div>

            <div class="card">
                <h3>Responsive Design</h3>
                <p>Support mobile, tablet and desktop.</p>
            </div>
        </section>
    </main>

    <footer id="contact">
        <p>© 2026 My Website | All Rights Reserved</p>
    </footer>

</body>
</html>
