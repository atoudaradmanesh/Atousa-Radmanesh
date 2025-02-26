<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sara's Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to bottom, #1e3c72, #2a5298, #f5af19, #ff512f);
            color: white;
            text-align: center;
        }
        header {
            padding: 50px 20px;
            font-size: 2em;
            font-weight: bold;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        footer {
            margin-top: 50px;
            padding: 20px;
            font-size: 1.2em;
            background: rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>
    <header>Sara's Portfolio</header>
    <div class="container">
        <p>Welcome to my portfolio. I am a multi-disciplinary artist inspired by the colors of the sky.</p>
        <div class="gallery">
            <img src="your-artwork-1.jpg" alt="Artwork 1">
            <img src="your-artwork-2.jpg" alt="Artwork 2">
            <img src="your-artwork-3.jpg" alt="Artwork 3">
        </div>
    </div>
    <footer>Contact: your.email@example.com | Instagram: @yourhandle</footer>
</body>
</html>
