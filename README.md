
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 20px;
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: #333;
        }

        .paintings {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .painting {
            width: 200px;
            text-align: center;
        }

        .painting img {
            max-width: 100%;
            border-radius: 8px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Портфолио Художника</h1>
    </header>

    <section id="bio">
        <h2>Биография</h2>
        <p>Здесь вы можете представить свою биографию и рассказать о своем искусстве.</p>
    </section>

    <section id="portfolio">
        <h2>Портфолио</h2>
        <div class="paintings">
            <div class="painting">
                <img src="[path/to/painting1.jpg](https://github.com/TorchWoold/Anuchin/blob/main/01%20-%20%D0%91%D1%80%D0%B8%D0%B3%20%D0%9D%D0%90%D0%94%D0%95%D0%96%D0%94%D0%90%20(1991%20-%202004).jpg)" alt="Живопись 1">
                <p>Подпись к картине 1</p>
            </div>
            <div class="painting">
                <img src="path/to/painting2.jpg" alt="Живопись 2">
                <p>Подпись к картине 2</p>
            </div>
            <!-- Добавьте больше блоков .painting по мере необходимости -->
        </div>
    </section>

    <!-- Добавьте дополнительные разделы, если необходимо -->

</body>
</html>
