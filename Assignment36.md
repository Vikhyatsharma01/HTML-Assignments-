grid-photo-gallery.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid Photo Gallery</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background: #f4f4f4;
        }

        h1 {
            text-align: center;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .gallery img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }

        @media (max-width: 600px) {
            .gallery {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>
<body>

    <h1>My Photo Gallery</h1>

    <div class="gallery">
        <img src="https://picsum.photos/id/10/400/300" alt="Forest">
        <img src="https://picsum.photos/id/11/400/300" alt="Nature">
        <img src="https://picsum.photos/id/12/400/300" alt="Mountain">
        <img src="https://picsum.photos/id/13/400/300" alt="Landscape">
        <img src="https://picsum.photos/id/14/400/300" alt="River">
        <img src="https://picsum.photos/id/15/400/300" alt="Beach">
    </div>

</body>
</html>
