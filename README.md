<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yanıp Sönen Yazı</title>
    <style>
        .blink {
            font-size: 24px;
            font-weight: bold;
            color: red;
            animation: blink-animation 1s steps(5, start) infinite;
        }

        @keyframes blink-animation {
            to {
                visibility: hidden;
            }
        }
    </style>
</head>
<body>

    <p class="blink">Readme!</p>

</body>
</html>
