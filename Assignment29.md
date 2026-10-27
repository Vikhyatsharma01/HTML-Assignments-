fix-overflow.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fix Overflow</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        .box {
            width: 250px;
            height: 100px;
            border: 2px solid navy;
            padding: 10px;
            margin-bottom: 20px;
        }

        .fixed {
            overflow: auto;
        }
    </style>
</head>
<body>

    <h1>CSS Overflow Example</h1>

    <h2>Overflow Fixed</h2>

    <div class="box fixed">
        This is a long paragraph to demonstrate how overflow works.
        When the content is larger than the box, a scrollbar appears
        if necessary, allowing users to read all the text.
        This additional text makes the content longer.
    </div>

    <p>The overflow: auto property adds scrollbars only when needed.</p>

</body>
</html>
