flex-wrap-products.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flex Wrap Products</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            padding: 20px;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .card {
            background-color: white;
            width: 180px;
            padding: 15px;
            text-align: center;
            border: 1px solid #ccc;
            border-radius: 8px;
        }

        .card button {
            background-color: navy;
            color: white;
            padding: 8px 15px;
            border: none;
        }
    </style>
</head>
<body>

    <h1>Our Products</h1>

    <div class="products">
        <div class="card">
            <h2>Laptop</h2>
            <p>Price: ₹35,000</p>
            <button type="button">View</button>
        </div>

        <div class="card">
            <h2>Headphones</h2>
            <p>Price: ₹1,500</p>
            <button type="button">View</button>
        </div>

        <div class="card">
            <h2>Keyboard</h2>
            <p>Price: ₹800</p>
            <button type="button">View</button>
        </div>

        <div class="card">
            <h2>Mouse</h2>
            <p>Price: ₹500</p>
            <button type="button">View</button>
        </div>
    </div>

</body>
</html>
lexbox: CSS layout system jo items ko row ya column mein arrange karta hai.



display: flex: Flex layout activate karta hai.



flex-wrap: wrap: Jagah kam hone par items ko agli line mein bhejta hai.



gap: Items ke beech space deta hai.



justify-content: center: Items ko horizontally center karta hai.
