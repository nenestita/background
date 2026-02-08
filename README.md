<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <style>
        body, html {
            margin: 0; 
            padding: 0; 
            width: 100%; 
            height: 100%; 
            background: #121212; 
            background-image: url('https://xatimg.com/image/MbGcCOEqZkY6.gif') !important;
            background-repeat: no-repeat;
            background-position: center center;
            background-size: cover;
            background-attachment: fixed;
            display: flex; 
            justify-content: center; 
            align-items: center;
            overflow: hidden; 
            font-family: 'Trebuchet MS', sans-serif; 
        }

        #xat-header, .header, #xat-footer, .footer, .user-name, .user-id {
            display: none !important;
        }

        .card {
            width: 550px;
            height: 350px;
            background: rgba(0, 0, 0, 0.85);
            border: 2px solid #8a2be2;
            border-radius: 20px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 0 30px rgba(138, 43, 226, 0.6);
            z-index: 1000;
        }

        .pfp { width: 80px; height: 80px; border-radius: 50%; border: 2px solid #8a2be2; margin-top: 10px; }
        .name { font-size: 26px; font-weight: bold; color: #8a2be2; font-family: sans-serif; margin: 10px 0; }
        .desc { font-size: 14px; color: #a366ff; font-weight: bold; font-family: sans-serif; padding: 0 40px; }
        .quote { font-size: 18px; color: #8a2be2; font-style: italic; font-weight: bold; font-family: sans-serif; }

        .icons { 
            background: rgba(26, 0, 51, 0.9);
            border-radius: 50px;
            padding: 12px;
            width: 320px;
            margin: 20px auto;
            display: flex;
            justify-content: space-around;
        }
        .icons img { width: 30px; height: 30px; transition: 0.3s; }
        .icons img:hover { transform: scale(1.2); }
    </style>
</head>
<body>
    <div class="card">
        <img src="https://xatimg.com/image/jErnhZ84UiT4.png" draggable="false" class="pfp">
        <div class="name">Hi i'm Tita</div>
        <p class="desc">You can find me on xat.com/Blog, xat.com/Assistance and xat.com/Chat.</p>
        <p class="quote">deen over dunya</p>
        <div class="icons">
            <a href="https://forum.xat.com/profile/55475/" target="_blank"><img src="https://xatimg.com/image/88aRECutI7NF.png"></a>
            <a href="https://www.youtube.com/watch?v=25MmCEpftKo" target="_blank"><img src="https://xatimg.com/image/vrKvF4ppWX7k.png"></a>
            <a href="https://www.twitch.tv/nenestita" target="_blank"><img src="https://xatimg.com/image/uNanyd1lgtLe.png"></a>
            <a href="https://xat.com/blog" target="_blank"><img src="https://xatimg.com/image/NycXn0QvBMnh.png"></a>
        </div>
    </div>
</body>
</html>
