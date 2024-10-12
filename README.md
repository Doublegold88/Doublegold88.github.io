<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Game - Privacy Policy</title>
    <style>
        :root {
            --light-bg: #f0f0f0;
            --light-text: #000;
            --dark-bg: #1e1e1e;
            --dark-text: #fff;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: var(--light-bg);
            color: var(--light-text);
            margin: 0;
            padding: 0;
            transition: all 0.3s ease;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-align: center;
        }

        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }

        h1, h2 {
            text-align: center;
        }

        .theme-toggle {
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }

        .theme-toggle button {
            padding: 10px;
            margin: 0 5px;
            border: none;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            font-size: 16px;
            border-radius: 5px;
        }

        .dark-mode {
            background-color: var(--dark-bg);
            color: var(--dark-text);
        }

        .items {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }

        .item {
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 10px;
            width: 45%;
            background-color: white;
        }

        .dark-mode .item {
            background-color: #333;
            color: white;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #4CAF50;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Game Privacy Policy</h1>
    </header>

    <section>
        <h2>Privacy Policy</h2>
        <p>We value your privacy. Your data will never be shared with third parties without your consent. All information collected is solely for improving your gaming experience.</p>

        <h2>Game Features</h2>
        <ul>
            <li>Exciting levels and challenges</li>
            <li>Real-time multiplayer support</li>
            <li>Leaderboards and achievements</li>
            <li>In-game purchases</li>
        </ul>

        <h2>Items for Sale</h2>
        <div class="items">
            <div class="item">
                <h3>Item 1</h3>
                <p>Description of the item.</p>
                <p>Price: $2.99</p>
            </div>
            <div class="item">
                <h3>Item 2</h3>
                <p>Description of the item.</p>
                <p>Price: $5.99</p>
            </div>
        </div>
    </section>

    <div class="theme-toggle">
        <button onclick="setLightMode()">Light Mode</button>
        <button onclick="setDarkMode()">Dark Mode</button>
    </div>

    <footer>
        <p>© 2024 Your Game. All rights reserved.</p>
    </footer>

    <script>
        function setDarkMode() {
            document.body.classList.add('dark-mode');
        }

        function setLightMode() {
            document.body.classList.remove('dark-mode');
        }
    </script>
</body>
</html>
