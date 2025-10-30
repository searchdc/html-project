<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Страница с фоном</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('avia2.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            height: 100vh;
            font-family: Arial, sans-serif;
        }

        .content {
            padding: 20px;
            color: white;
            text-align: center;
            background-color: rgba(0, 0, 0, 0.5);
            margin: 40px;
            border-radius: 100px;
        }

        button {
            background-color: #000000;
            color: white;
            padding: 15px 65px;
            border-radius: 10px;
            transition: all 200ms ease;
            border: none;
            cursor: pointer;
            font-size: 16px;
            display: flex;
            margin: 0 auto;
        }

        button:hover {
            background-color: #FFFFFF;
            color: black;
        }

        input {
            display: block;
            margin: 10px auto;
            padding: 10px;
            border-radius: 10px;
            border: none;
            width: 250px;
            text-align: center;
        }

        #form {
            display: none;
            text-align: center;
        }
    </style>
</head>
