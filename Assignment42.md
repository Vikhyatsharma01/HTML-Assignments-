responsive-audit-fix.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Audit Fix</title>

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
            padding: 20px;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
        }

        .card {
            flex: 1 1 250px;
            min-width: 0;
            background: white;
            padding: 20px;
            border-radius: 8px;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        footer {
            background: #2563eb;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Responsive Website</h1>
        <p>Works on Mobile, Tablet and Desktop</p>
    </header>

    <main class="container">
        <section class="card">
            <h2>Mobile</h2>
            <p>Content adjusts to small screens.</p>
            <img src="https://picsum.photos/400/200" alt="Nature">
        </section>

        <section class="card">
            <h2>Tablet</h2>
            <p>Cards wrap when space is limited.</p>
            <img src="https://picsum.photos/401/200" alt="Landscape">
        </section>

        <section class="card">
            <h2>Desktop</h2>
            <p>Cards display side by side.</p>
            <img src="https://picsum.photos/402/200" alt="Mountains">
        </section>
    </main>

    <footer>
        <p>Responsive Audit Complete</p>
    </footer>

</body>
</html>

