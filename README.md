<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moja Osobista Strona</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0e0e0;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        header {
            text-align: center;
            background-color: #4b0082;
            color: white;
            padding: 20px;
        }
        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .card {
            background-color: #8a2be2;
            margin: 10px;
            border-radius: 10px;
            overflow: hidden;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        img {
            width: 100%;
            height: auto;
        }
        h2 {
            margin: 10px 0;
        }
        p {
            padding: 0 10px 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Witaj na mojej stronie!</h1>
    <p>Tu znajdziesz moje zdjęcia oraz opisy.</p>
</header>

<section>
    <div class="card">
        <img src="zdjecie1.jpg" alt="Opis zdjęcia 1">
        <h2>Tytuł zdjęcia 1</h2>
        <p>Opis zdjęcia 1 w kolorach fioletowo-niebieskich.</p>
    </div>
    <div class="card">
        <img src="zdjecie2.jpg" alt="Opis zdjęcia 2">
        <h2>Tytuł zdjęcia 2</h2>
        <p>Opis zdjęcia 2 w kolorach fioletowo-niebieskich.</p>
    </div>
    <div class="card
