landing-skeleton-desktop.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desktop Landing Skeleton</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: #222;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
            background: #1e293b;
            color: white;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
            background: #e2e8f0;
        }

        .content {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 20px;
            padding: 30px;
        }

        .box {
            background: #f1f5f9;
            padding: 25px;
            border-radius: 8px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #1e293b;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h2>My Website</h2>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section class="hero" id="home">
            <h1>Welcome to Our Website</h1>
            <p>A simple desktop landing page layout.</p>
        </section>

        <section class="content" id="about">
            <div class="box">
                <h2>Main Content</h2>
                <p>This area contains the main information.</p>
            </div>

            <div class="box">
                <h2>Sidebar</h2>
                <p>This area contains additional information.</p>
            </div>
        </section>
    </main>

    <footer id="contact">
        <p>© 2026 My Website</p>
    </footer>

</body>
</html>
