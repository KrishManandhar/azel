<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Azel!</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-image: url('Azel.jpg.jpg');
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
            overflow: hidden;
        }
        .message {
            text-align: center;
            color: white;
            font-size: 4em;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            z-index: 10;
            margin-bottom: 20px;
        }
        .letter {
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            max-width: 500px;
            text-align: center;
            font-size: 1.2em;
            color: #333;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            z-index: 10;
        }
        .heart {
            position: absolute;
            width: 50px;
            height: 50px;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="red"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/></svg>') no-repeat center;
            background-size: contain;
            animation: float 6s infinite ease-in-out;
        }
        @keyframes float {
            0% { transform: translateY(0) scale(1); opacity: 1; }
            50% { transform: translateY(-100px) scale(1.2); opacity: 0.8; }
            100% { transform: translateY(0) scale(1); opacity: 1; }
        }
        .balloon {
            position: absolute;
            width: 60px;
            height: 80px;
            background: radial-gradient(circle at top, #ff5555, #aa0000);
            border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
            cursor: pointer;
            animation: balloonFloat 4s infinite ease-in-out;
        }
        .balloon::before {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 0;
            height: 0;
            border-left: 5px solid transparent;
            border-right: 5px solid transparent;
            border-bottom: 10px solid #aa0000;
        }
        @keyframes balloonFloat {
            0% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0); }
        }
        .popped {
            display: none;
        }
    </style>
</head>
<body>
    <div class="message">Happiest Birthday Azel Baby ❤️😘</div>
    <div class="letter">
        My Dearest Azel,<br><br>
        Happy Birthday, my love! Today is all about you, me; your प्यारो बच्चा. Your smile lights up my world, and your love makes every moment sweeter. I’m so grateful for you; here’s to celebrating you today and always.<br><br>
        Forever Yours,<br>
        Krish ❤️
    </div>
   </body>
   </html>
