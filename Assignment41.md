breakpoints-multi-screen.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi Screen Layout</title>

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
            background: #2563eb;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            padding: 20px;
        }

        .card {
            background: white;
            padding: 25px;
            text-align: center;
            border-radius: 8px;
        }

        /* Tablet */
        @media (max-width: 768px) {
            .container {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        /* Mobile */
        @media (max-width: 480px) {
            .container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Responsive Website</h1>
        <p>Mobile, Tablet and Desktop</p>
    </header>

    <main class="container">
        <div class="card">
            <h2>HTML</h2>
            <p>Structure of a webpage.</p>
        </div>

        <div class="card">
            <h2>CSS</h2>
            <p>Style of a webpage.</p>
        </div>

        <div class="card">
            <h2>JavaScript</h2>
            <p>Interactive webpages.</p>
        </div>
    </main>

</body>
</html>
Responsive design: Website ko different screen sizes par properly display karta hai.



Media query: Screen width ke according CSS change karti hai.



max-width: 768px — Tablet-size screens ke liye layout adjust karta hai.



max-width: 480px — Mobile screens par cards ko single column mein dikhata hai.



grid-template-columns — Cards ke columns ki sankhya set karta hai.
