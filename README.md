<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>С Днем Матери, Мать!</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: url('https://avatars.mds.yandex.net/i?id=2cd1b72ae916caff98c0326d00847d6e5f9876ee-6580333-images-thumbs&ref=rim&n=33&w=375&h=250') no-repeat center center fixed;
            background-size: cover;
        }

        header {
            background-color: rgba(232, 73, 29, 0.8);
            padding: 20px;
            text-align: center;
            color: white;
        }

        main {
            text-align: center;
            padding: 20px;
            position: relative;
            z-index: 1;
        }

        img {
            max-width: 60%; /* Уменьшенный размер изображения */
            height: auto;
            border-radius: 10px;
            animation: rotate 4s infinite linear; /* Уменьшенная скорость вращения */
            position: relative;
            z-index: 2;
        }

        @keyframes rotate {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }

        p {
            font-size: 55px; /* Увеличенный размер текста */
            color: pink; /* Розовый цвет текста */
            position: relative;
            z-index: 2;
        }

        footer {
            color: darkpink; /* Темно-розовый цвет текста */
            text-align: left;
            position: fixed;
            bottom: 0;
            left: 0;
            padding: 5px;
            z-index: 1;
            font-size: 16px; /* Увеличенный размер текста */
        }

        /* Сердце */
        .heart {
            position: absolute;
            top: 70%;
            left: 70%;
            transform: translate(-50%, -50%);
            width: 200px;
            height: 180px;
            background-color: rgba(255, 0, 0, 0.7);
            clip-path: polygon(50% 0%, 100% 35%, 84% 64%, 50% 100%, 16% 64%, 0% 35%);
            z-index: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>С Днем мамери!!!!</h1>
    </header>

    <main>
        <div class="heart"></div>
        <img src="https://gas-kvas.com/uploads/posts/2023-01/1674118869_gas-kvas-com-p-risunok-s-dnem-materi-nadpis-13.jpg" alt="Поздравительное изображение">
        <p>Всех мамочек в День матери
        Спешим поздравить мы!
        Улыбка, радость, счастье пусть
        Встречают в день весны!
        </p>
    </main>

    <footer>
        <p>С любовью, ваш Пес Песович</p>
    </footer>

</body>
</html>
