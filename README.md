<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundraising Site</title>
    <script src="https://cdn.jsdelivr.net/npm/stripe-js"></script>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Support Our Project</h1>
        
        <!-- Таймер -->
        <div id="timer">00:00:00:00</div>
        
        <!-- Шкала заполнения -->
        <div class="progress-container">
            <span>$0</span>
            <div class="progress-bar" id="progress-bar"></div>
            <span>$1,000,000</span>
        </div>
        
        <!-- Оплата -->
        <button id="donate-button">Donate Now</button>
        
        <!-- Поле для ника Instagram -->
        <input type="text" id="instagram-nick" placeholder="Enter your Instagram Nickname" disabled>
        
        <!-- Видео -->
        <div class="video-container">
            <video id="fund-video" controls>
                <source src="video.mp4" type="video/mp4">
            </video>
            <select id="language-select">
                <option value="en">English</option>
                <option value="ua">Українська</option>
            </select>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>




<!---
Underwatermusk/Underwatermusk is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
