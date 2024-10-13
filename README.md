<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Кофейня Мурка</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #6f4c3e;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
        }
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 10px;
        }
        h2 {
            text-align: center;
            font-size: 1.8em;
        }
        .product {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 20px 0;
            padding: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        .product img {
            width: 150px;  /* Фиксированная ширина */
            height: 150px; /* Фиксированная высота */
            border-radius: 5px;
            margin-bottom: 15px;
        }
        .product h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #6f4c3e;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        /* Адаптация для телефонов */
        @media (min-width: 600px) {
            .product {
                flex-direction: row;
                text-align: left;
            }
            .product img {
                margin-right: 20px; /* Отступ между изображением и текстом */
                margin-bottom: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Кофейня Мурка</h1>
        <nav>
            <a href="#">Главная</a>
            <a href="#">Меню</a>
            <a href="#">Контакты</a>
        </nav>
    </header>
    <div class="container">
        <h2>Наши товары</h2>
        <div class="product">
            <img src="https://avatars.mds.yandex.net/i?id=7fa01bf85db24c36d5fd260106547876_l-8567697-images-thumbs&n=13" alt="Дристание коня">
            <div>
                <h3>Дристание коня</h3>
                <p>Неповторимый вкус и аромат, который порадует каждого.</p>
            </div>
        </div>
        <div class="product">
            <img src="https://avatars.mds.yandex.net/i?id=3ea348be8e4b6c62b720358ed3c4d6d0_l-5370410-images-thumbs&n=13" alt="Яйцо Матвея Жданова в печи">
            <div>
                <h3>Яичко Матвея Жданова в печи</h3>
                <p>Секретный рецепт от шеф-повара.</p>
            </div>
        </div>
        <div class="product">
            <img src="https://avatars.mds.yandex.net/i?id=7d626bf3e12b97ed9c84dceced4cd480_l-5288739-images-thumbs&n=13" alt="Очко коровы Муки">
            <div>
                <h3>Очко коровы Муки</h3>
                <p>Попробуйте этот уникальный деликатес.</p>
            </div>
        </div>
        <div class="product">
            <img src="https://steamuserimages-a.akamaihd.net/ugc/2238913464890425659/526804F6C6273AD145C681747A3B3AF98D762BFF/?imw=512&amp;imh=341&amp;ima=fit&amp;impolicy=Letterbox&amp;imcolor=%23000000&amp;letterbox=true" alt="Кофе из желчи Майи">
            <div>
                <h3>Кофе из желчи Майи</h3>
                <p>Настоящий экзотический вкус для настоящих гурманов.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>Контактная информация: Мурочка Урочка, 88005553535, улица Срак 15</p>
        <p>Кофейня Мурка © 2024</p>
    </footer>
</body>
</html>
