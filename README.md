<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F4F8FF;
            color: #333;
        }

        .profile-container {
            max-width: 800px;
            margin: 2rem auto;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #4A90E2, #D9BBF9);
            padding: 2rem;
            text-align: center;
            color: white;
        }

        .header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            margin-bottom: 1rem;
        }

        .header h1 {
            margin: 0;
            font-size: 2rem;
        }

        .header p {
            margin: 0;
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .info-section {
            display: flex;
            padding: 2rem;
            gap: 2rem;
        }

        .info-section div {
            flex: 1;
        }

        .info-section h2 {
            margin-bottom: 1rem;
            color: #4A90E2;
        }

        .skills {
            padding: 2rem;
        }

        .skills h2 {
            color: #4A90E2;
        }

        .skill {
            margin-bottom: 1rem;
        }

        .skill-name {
            margin-bottom: 0.5rem;
        }

        .progress-bar {
            height: 10px;
            background: #E4E9FF;
            border-radius: 5px;
            overflow: hidden;
        }

        .progress-bar span {
            display: block;
            height: 100%;
            background: linear-gradient(135deg, #4A90E2, #D9BBF9);
            width: 80%; /* Change percentage for different skills */
        }

        .social {
            text-align: center;
            padding: 2rem;
        }

        .social a {
            margin: 0 10px;
            display: inline-block;
            width: 40px;
            height: 40px;
            line-height: 40px;
            background: #D9BBF9;
            color: white;
            border-radius: 50%;
            text-decoration: none;
            transition: all 0.3s;
        }

        .social a:hover {
            background: #4A90E2;
        }

        .footer {
            background: #F4F8FF;
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="profile-container">
        <!-- Header -->
        <div class="header">
            
        </div>

        <!-- Información Personal -->
        <div class="info-section">
            <div>
                <h2>Información</h2>
                <p><strong>Edad:</strong> 30 años</p>
                <p><strong>Ubicación:</strong> Ciudad de México</p>
                <p><strong>Ocupación:</strong> Desarrollador Web</p>
            </div>
            <div>
                <h2>Biografía</h2>
                <p>Apasionado por la tecnología y el diseño, disfruto crear soluciones innovadoras que hagan la vida más sencilla y hermosa.</p>
            </div>
        </div>

        <!-- Habilidades -->
        <div class="skills">
            <h2>Habilidades</h2>
            <div class="skill">
                <div class="skill-name">HTML & CSS</div>
                <div class="progress-bar"><span style="width: 95%;"></span></div>
            </div>
            <div class="skill">
                <div class="skill-name">JavaScript</div>
                <div class="progress-bar"><span style="width: 85%;"></span></div>
            </div>
            <div class="skill">
                <div class="skill-name">React</div>
                <div class="progress-bar"><span style="width: 70%;"></span></div>
            </div>
        </div>

        <!-- Redes Sociales -->
        <div class="social">
            <a href="#">F</a>
            <a href="#">T</a>
            <a href="#">I</a>
        </div>

        <!-- Pie de Página -->
        <div class="footer">
            <p>"La creatividad es la inteligencia divirtiéndose." - Albert Einstein</p>
        </div>
    </div>
</body>
</html>
