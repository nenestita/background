<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xatspace Tita</title>
    <style>
        /* Configuration de base */
        body, html {
            margin: 0 !important;
            padding: 0 !important;
            width: 100% !important;
            height: 100% !important;
            background-color: #000 !important;
            overflow: hidden !important;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Trebuchet MS', sans-serif;
        }

        /* L'OVERLAY : C'est lui qui affiche le GIF et cache le haut de xat */
        .full-background {
            position: fixed !important;
            top: -200px !important; /* Remonte pour cacher le nom et l'id */
            left: 0 !important;
            width: 100% !important;
            height: calc(100% + 200px) !important;
            background-image: url('https://xatimg.com/image/MbGcCOEqZkY6.gif') !important;
            background-size: cover !important;
            background-position: center center !important;
            background-repeat: no-repeat !important;
            z-index: 999999 !important; /* Priorité maximale */
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* TA CARTE VIOLETTE */
        .card {
            width: 550px;
            height: 350px;
            background: rgba(0, 0, 0, 0.85) !important; /* Noir transparent */
            border: 2px solid #8a2be2 !important;
            border-radius: 20px !important;
            padding: 20px !important;
            text-align: center !important;
            box-shadow: 0 0 30px rgba(138, 43, 226, 0.6) !important;
            margin-top: 180px !important; /* Compense la remontée de l'overlay */
            position: relative !important;
        }

        /* PHOTO DE PROFIL */
        .profile-img { 
            width: 80px; 
            height: 80px; 
            border-radius: 50%; 
            border: 2px solid #8a2be2; 
            margin-top: 10px;
            object-fit: cover;
        }

        /* TEXTES */
        .name { font-size: 28px; font-weight: bold; color: #8a2be2; margin-top: 10px; }
        
        .desc { font-size: 15px; color: #a366ff; font-weight: bold; margin: 15px 40px; line-height: 1.4; }
        
        .quote { font-size: 18px; color: #8a2be2; font-style: italic; font-weight: bold; margin-bottom: 25px; }

        /* BARRE D'ICÔNES */
        .icon-bar {
            background: rgba(26, 0, 51, 0.9);
            border: 1px solid #8a2be2;
            border-radius: 50px;
            width: 320px;
            margin: 0 auto;
            padding: 12px;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .icon-bar a { display: inline-block; transition: transform 0.3s; }
        .icon-bar a:hover { transform: scale(1.2); }
        .icon-bar img { width: 32px; height: 32px; display: block; }

        a { text-decoration: none; }
    </style>
</head>
<body>

    <div class="full-background">
        
        <div class="card">
            <img src="https://xatimg.com/image/jErnhZ84UiT4.png" class="profile-img">
            
            <div class="name">Hi i'm Tita</div>
            
            <div class="desc">You can find me on xat.com/Blog, xat.com/Assistance and xat.com/Chat.</div>
            
            <div class="quote">deen over dunya</div>

            <div class="icon-bar">
                <a href="https://forum.xat.com/profile/55475/" target="_blank">
                    <img src="https://xatimg.com/image/88aRECutI7NF.png" alt="Forum">
                </a>
                <a href="https://www.youtube.com/watch?v=25MmCEpftKo" target="_blank">
                    <img src="https://xatimg.com/image/vrKvF4ppWX7k.png" alt="YouTube">
                </a>
                <a href="https://www.twitch.tv/nenestita" target="_blank">
                    <img src="https://xatimg.com/image/uNanyd1lgtLe.png" alt="Twitch">
                </a>
                <a href="https://xat.com/blog" target="_blank">
                    <img src="https://xatimg.com/image/NycXn0QvBMnh.png" alt="Blog">
                </a>
            </div>
        </div>
        
    </div>

</body>
</html>
