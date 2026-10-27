
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid Auto Fit Products</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            margin: 20px;
        }

        h1 {
            text-align: center;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 5px #ccc;
        }

        .card button {
            background: #2563eb;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>Our Products</h1>

    <div class="products">
        <div class="card">
            <h2>Laptop</h2>
            <p>Price: ₹40,000</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <h2>Headphones</h2>
            <p>Price: ₹1,500</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <h2>Keyboard</h2>
            <p>Price: ₹800</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <h2>Mouse</h2>
            <p>Price: ₹500</p>
            <button>Buy Now</button>
        </div>
    </div>

</body>
</html>
grid-auto-fit-products.html
