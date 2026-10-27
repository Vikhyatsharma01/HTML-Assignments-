box-model-annotated.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Box Model</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            text-align: center;
        }

        .box {
            width: 200px;
            background-color: lightblue;
            padding: 20px;
            border: 5px solid navy;
            margin: 30px auto;
        }
    </style>
</head>
<body>

    <h1>CSS Box Model</h1>

    <div class="box">
        <h2>Content</h2>
        <p>This is the content area.</p>
    </div>

    <h3>Box Model Properties</h3>
    <p><b>Content:</b> The actual text or image.</p>
    <p><b>Padding:</b> Space around the content.</p>
    <p><b>Border:</b> The boundary around padding and content.</p>
    <p><b>Margin:</b> Space outside the border.</p>

</body>
</html>
