#index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Happy Birthday Chinni 💖</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            color: white;
            text-align: center;
            overflow-x: hidden;
        }

        h1 {
            font-size: 3em;
            margin-top: 40px;
            animation: glow 2s infinite alternate;
        }

        @keyframes glow {
            from { text-shadow: 0 0 10px #fff; }
            to { text-shadow: 0 0 30px #ffeb3b; }
        }

        .card {
            background: rgba(255, 255, 255, 0.2);
            margin: 30px auto;
            padding: 25px;
            border-radius: 20px;
            width: 90%;
            max-width: 600px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        }

        p {
            font-size: 1.2em;
            line-height: 1.8;
        }

        .emoji {
            font-size: 2em;
            animation: bounce 1.5s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .footer {
            margin-top: 30px;
            font-size: 1em;
            opacity: 0.9;
        }

        button {
            margin-top: 20px;
            padding: 12px 25px;
            font-size: 1em;
            border: none;
            border-radius: 30px;
            background: #ff4081;
            color: white;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        button:hover {
            background: #f50057;
        }
    </style>
</head>
<body>

    <h1>🎉 Happy Birthday Chinni 😘 🎂</h1>

    <div class="card">
        <p>
            Dear <b>Chinni 💖</b>,<br><br>
            On this special day, I just want to say how lucky I am to have you as my best friend 🤗.  
            You understand me, support me, and always stand by me 🌈.  
            Your smile makes everything better 😊✨.
        </p>

        <p>
            May your life be filled with happiness, success, love, and endless smiles 💐💫.  
            Never stop being the amazing person you are 🌸.
        </p>

        <div class="emoji">🎂🎁💖🥳🎉</div>

        <button onclick="alert('You are the best, Chinni 😘💖')">
            Click for a Surprise 🎁
        </button>
    </div>

    <div class="footer">
        With lots of love & friendship 💕<br>
        — Your Best Friend 🤍
    </div>

</body>
</html>
