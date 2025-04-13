# git-pages-test

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фото Галерея</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f4f4f4;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-gap: 10px;
            width: 90%;
            max-width: 1200px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            display: block;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="gallery">
        <img src="https://via.placeholder.com/300" alt="Фото 1">
        <img src="https://via.placeholder.com/300" alt="Фото 2">
        <img src="https://via.placeholder.com/300" alt="Фото 3">
        <img src="https://via.placeholder.com/300" alt="Фото 4">
        <img src="https://via.placeholder.com/300" alt="Фото 5">
        <img src="https://via.placeholder.com/300" alt="Фото 6">
        <img src="https://via.placeholder.com/300" alt="Фото 7">
        <img src="https://via.placeholder.com/300" alt="Фото 8">
        <img src="https://via.placeholder.com/300" alt="Фото 9">
        <img src="https://via.placeholder.com/300" alt="Фото 10">
        <img src="https://via.placeholder.com/300" alt="Фото 11">
        <img src="https://via.placeholder.com/300" alt="Фото 12">
        <img src="https://via.placeholder.com/300" alt="Фото 13">
        <img src="https://via.placeholder.com/300" alt="Фото 14">
        <img src="https://via.placeholder.com/300" alt="Фото 15">
        <img src="https://via.placeholder.com/300" alt="Фото 16">
    </div>
</body>
</html>
