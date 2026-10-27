grid-header-sidebar-products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid Products Layout</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        header {
            background: #2563eb;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .layout {
            display: grid;
            grid-template-columns: 200px 1fr;
            gap: 20px;
            padding: 20px;
        }

        aside {
            background: #e2e8f0;
            padding: 15px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
        }

        .card {
            background: #f8fafc;
            padding: 20px;
            text-align: center;
            border: 1px solid #ddd;
            border-radius: 8px;
        }

        @media (max-width: 600px) {
            .layout {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>My Store</h1>
    </header>

    <div class="layout">
        <aside>
            <h2>Categories</h2>
            <p>Electronics</p>
            <p>Accessories</p>
            <p>Computers</p>
        </aside>

        <main>
            <h2>Our Products</h2>

            <div class="products">
                <div class="card">
                    <h3>Laptop</h3>
                    <p>₹40,000</p>
                </div>

                <div class="card">
                    <h3>Headphones</h3>
                    <p>₹1,500</p>
                </div>

                <div class="card">
                    <h3>Keyboard</h3>
                    <p>₹800</p>
                </div>

                <div class="card">
                    <h3>Mouse</h3>
                    <p>₹500</p>
                </div>
            </div>
        </main>
    </div>

</body>
</html>
