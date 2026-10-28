<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Lab</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0f172a, #1e3a8a);
            color: white;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .container {
            padding: 40px;
        }

        h1 {
            font-size: 40px;
            margin-bottom: 15px;
            letter-spacing: 3px;
        }

        p {
            color: #cbd5e1;
            font-size: 16px;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 15px 35px;
            background: #38bdf8;
            color: #0f172a;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            border-radius: 8px;
            box-shadow: 0 0 15px #38bdf8;
            animation: pulse 1.5s infinite;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ffffff;
            transform: scale(1.1);
            box-shadow: 0 0 25px #ffffff;
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
                box-shadow: 0 0 10px #38bdf8;
            }

            50% {
                transform: scale(1.05);
                box-shadow: 0 0 25px #38bdf8;
            }

            100% {
                transform: scale(1);
                box-shadow: 0 0 10px #38bdf8;
            }
        }

        footer {
            position: absolute;
            bottom: 20px;
            color: #94a3b8;
            font-size: 12px;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>PERSONAL LAB</h1>

        <p>Welcome to my personal laboratory.</p>

        <a href="http://10.237.37.118:8000/" class="btn">
            CLICK ME
        </a>
    </div>

    <footer>
        &copy; 2026 Personal Lab | All Rights Reserved
    </footer>

</body>
</html>
