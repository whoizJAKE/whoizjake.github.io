<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jacob Hmaiddout</title>
    <style>
        /* timming et les couleursssss */
        body {
            background: linear-gradient(45deg, #ff0000, #ff7300, #ffd900, #00ff44, #754b6d, #4800ff, #817e27);
            background-size: 400% 400%;
            animation: gradientAnimation 15s ease infinite;
            margin: 0;
            padding: 20px;
            font-family: Arial, sans-serif;
            color: rgb(0, 0, 0);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* BACKGROUND animée lol */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, #ff0000, #ff7300, #ffd900, #00ff44, #754b6d, #4800ff, #817e27);
            background-size: 400% 400%;
            animation: gradientAnimation 15s ease infinite;
            z-index: -1;
        }

        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* la nouvelles Top Social Bar */
        .top-social-bar {
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: rgba(0,0,0,0.1);
            padding: 10px 0;
            gap: 20px;
        }

        .top-social-bar a {
            display: inline-block;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            background-color: rgb(238, 5, 5);
            color: black;
            text-align: center;
            line-height: 30px;
            font-size: 14px;
            font-weight: bold;
            transition: transform 0.3s ease;
        }

        .top-social-bar a:hover {
            transform: scale(1.2);
        }

        h1 {
            color: rgb(0, 0, 0);
            text-align: center;
        }

        /* Reste du css en haut est pareil*/
        /* ... (previous CSS code) */
        footer .footer-socials {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 10px;
        }

        footer .footer-socials a {
            display: inline-block;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            background-color: rgb(238, 5, 5);
            color: black;
            text-align: center;
            line-height: 30px;
            font-size: 14px;
            font-weight: bold;
            transition: transform 0.3s ease;
        }

        footer .footer-socials a:hover {
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <nav class="nav-bar">
        <a href="https://jacobhmaiddout.com">Home</a>
        <a href="plus sur moi">About Me</a>
<body>
    <!-- MY Newwwwww Top Social Bar -->
    <div class="top-social-bar">
        <a href="https://x.com/Jacob_hmaiddout" target="_blank" title="X (formerly Twitter)">X</a>
        <a href="https://www.instagram.com/jacob_hmaiddout/" target="_blank" title="Instagram">IG</a>
        <a href="https://www.facebook.com/jacob.hmaiddout/?locale=fr_CA" target="_blank" title="Facebook">FB</a>
        <a href="https://github.com/whoizJAKE" target="_blank" title="GitHub">Git</a>
        <a href="https://www.linkedin.com/in/jacob-hma%C3%AFddout-06226925b/" target="_blank" title="LinkedIn">LkI</a>
        <a href="https://vs.co/lz3exrac" target="_blank" title="VSCO">V</a>
    </div>

    <!-- MODIF QUE JE VIEN DE FAIRE POUR ADD MES SOCIALS LINK ON TOP -->
    <header>
        <h1>Jacob Hmaiddout</h1>
    </header>
    
<h2>Plus sur moi</h2>
<p>        
<h2>CV</h2>
<p>
    Pour accéder à mon CV, vous pouvez le télécharger ci-dessous:<br>
    To access my CV, you can download it below: 
    <a href="https://raw.githubusercontent.com/whoizJAKE/whoizJAKE.github.io/main/CV%20UPDATE%202024.pdf" download>Download CV</a>

<h2>Mes projets</h2>
<p>
    My future projects and ideas will be added here... I'll probably include some photos and more details soon. 
</p>
<p>
    In the meantime, if you'd like to send me some BTC, feel free!<br>
    <strong>Wallet:</strong> bc1qegmu3pxwnju04wrc7lm4vkuej6k9aftwkqd932
</p>
<p>Thanks! :)</p>
<h2>Socials</h2>
    <footer>
    <footer>
        <p>Contact: <a href="mailto:jico0x7@gmail.com">jico0x7@gmail.com</a>  
            
            <a href="tel:819-829-2436">+819-829-2436</a> (landline)  
            or  
            <a href="tel:8196409235">+819-640-9235</a> (mobile)
        </p>
        
        <div class="footer-socials">
            <a href="https://x.com/Jacob_hmaiddout" target="_blank" title="X (formerly Twitter)">X</a>
            <a href="https://www.instagram.com/jacob_hmaiddout/" target="_blank" title="Instagram">IG</a>
            <a href="https://www.facebook.com/jacob.hmaiddout/?locale=fr_CA" target="_blank" title="Facebook">FB</a>
            <a href="https://github.com/whoizJAKE" target="_blank" title="GitHub">Git</a>
            <a href="https://www.linkedin.com/in/jacob-hma%C3%AFddout-06226925b/" target="_blank" title="LinkedIn">LkI</a>
            <a href="https://vs.co/lz3exrac" target="_blank" title="VSCO">V</a>
        </div>
    </footer>

