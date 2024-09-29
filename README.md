<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karma's Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212; /* Dark mode background */
            color: #ffffff; /* Light text for dark mode */
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        h1 {
            color: #fff;
        }

        .section {
            margin-top: 30px;
            text-align: center;
            border: 1px solid #444;
            padding: 20px;
            border-radius: 10px;
            width: 90%;
        }

        .button-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }

        .robux-button, .file-button {
            background-color: #32CD32;
            border: none;
            color: white;
            width: 60px; /* Width for circular buttons */
            height: 60px; /* Height for circular buttons */
            border-radius: 50%; /* Make buttons circular */
            cursor: pointer;
            transition: background-color 0.3s ease;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 14px;
        }

        .robux-button:hover, .file-button:hover {
            background-color: #228B22;
        }

        .robux-button:active, .file-button:active {
            background-color: #006400;
        }

        .info-text {
            margin-top: 20px;
            text-align: center;
            color: #ccc;
        }
    </style>
</head>
<body>

    <div class="section">
        <h2>[ Donations ]</h2>
        <div class="button-container">
            <a href="https://www.roblox.com/game-pass/734003161/2" class="robux-button">2</a>
            <a href="https://www.roblox.com/game-pass/715207775/3" class="robux-button">3</a>
            <a href="https://www.roblox.com/game-pass/733743166/unnamed" class="robux-button">4</a>
            <a href="https://www.roblox.com/game-pass/680780328/tiny-donation" class="robux-button">5</a>
            <a href="https://www.roblox.com/game-pass/715079769/10" class="robux-button">10</a>
            <a href="https://www.roblox.com/game-pass/715083839/15" class="robux-button">15</a>
            <a href="https://www.roblox.com/game-pass/680503855/Very-small-donation" class="robux-button">25</a>
            <a href="https://www.roblox.com/game-pass/680522814/Small-donation" class="robux-button">100</a>
            <a href="https://www.roblox.com/game-pass/680534795/Big-donation" class="robux-button">287</a>
            <a href="https://www.roblox.com/game-pass/680571695/donation" class="robux-button">650</a>
            <a href="https://www.roblox.com/game-pass/680753379/HUGE-DONATION" class="robux-button">1500</a>
            <a href="https://www.roblox.com/game-pass/715624037/2k" class="robux-button">2000</a>
            <a href="https://www.roblox.com/game-pass/715160732/2-5k" class="robux-button">2500</a>
            <a href="https://www.roblox.com/game-pass/715135804/3k" class="robux-button">3000</a>
            <a href="https://www.roblox.com/game-pass/715225777/3-5k" class="robux-button">3500</a>
            <a href="https://www.roblox.com/game-pass/715625060/4k" class="robux-button">4000</a>
            <a href="https://www.roblox.com/game-pass/715310655/4-5k" class="robux-button">4500</a>
            <a href="https://www.roblox.com/game-pass/715331723/5k" class="robux-button">5000</a>
            <a href="https://www.roblox.com/game-pass/716091182/6k" class="robux-button">6000</a>
            <a href="https://www.roblox.com/game-pass/716059250/7k" class="robux-button">7000</a>
            <a href="https://www.roblox.com/game-pass/715913214/8k" class="robux-button">8000</a>
            <a href="https://www.roblox.com/game-pass/715645580/9k" class="robux-button">9000</a>
            <a href="https://www.roblox.com/game-pass/715959258/10k" class="robux-button">10000</a>
        </div>
        <p class="info-text">If you want to remake a purchase, simply go to your inventory, remove the game pass, and re-buy it!</p>
    </div>

    <div class="section">
        <h2>[ File Purchases ]</h2>
        <p class="info-text">Roblox Game files</p>
        <div class="button-container">
            <a href="https://example.com/v4-high-quality" class="file-button">V4</a> <!-- Add the correct link for the file here -->
        </div>
        <p class="info-text">Quality Determines Price in Robux.</p>
    </div>

</body>
</html>
