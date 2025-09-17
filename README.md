<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MEC Web</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: linear-gradient(135deg, #1e1e2f, #3e3e6e);
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        h1 {
            font-size: 50px;
            margin: 0;
        }

        p {
            font-size: 18px;
            margin: 5px 0 20px 0;
            color: #bbb;
        }

        .button {
            background: linear-gradient(90deg, #6a00f4, #00f6ff);
            border: none;
            padding: 15px 40px;
            font-size: 18px;
            font-weight: bold;
            color: #fff;
            border-radius: 15px;
            cursor: pointer;
            transition: 0.3s;
            margin-bottom: 20px;
        }

        .button:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px #00f6ff;
        }

        .description {
            font-size: 16px;
            color: #ddd;
            max-width: 600px;
            line-height: 1.5;
        }
    </style>
</head>
<body>
    <h1>Welcome to MEC</h1>
    <p>MultiExec Center</p>
    <button class="button" onclick="goDiscord()">Go to Discord</button>
    <p class="description">
        <!-- ใส่คำอธิบายของคุณตรงนี้ -->
        This is a hub for many famous executors, including Delta X, KRNL, Arceus X, and Ronix. Join us on Discord!✅
    </p>

    <script>
        function goDiscord() {
            
            window.location.href = "https://discord.gg/Ub6cka2SNy";
        }
    </script>
</body>
</html>
