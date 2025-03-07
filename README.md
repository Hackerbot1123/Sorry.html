<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorry</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f8ff;
            font-family: 'Arial', sans-serif;
        }
        .container {
            text-align: center;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #ff6347;
        }
        p {
            color: #333;
            font-size: 1.2em;
        }
        .heart {
            color: #ff6347;
            font-size: 3em;
            animation: heartbeat 1.5s infinite;
        }
        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.3);
            }
        }
        button {
            padding: 10px 20px;
            font-size: 1em;
            border: none;
            border-radius: 5px;
            background-color: #ff6347;
            color: #fff;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #ff4500;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>I'm Sorry</h1>
        <p>Dear Best Friend,<br>
        I am truly sorry for what happened. Please forgive me.</p>
        <div class="heart">❤️</div>
        <button onclick="window.location.href='mailto:yourfriend@example.com?subject=Sorry&body=I am truly sorry for what happened. Please forgive me.'">Send an Email</button>
    </div>
</body>
</html>
