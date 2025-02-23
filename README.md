<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Web de Pierre Grandett</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #0d1117;
            color: #c9d1d9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #161b22;
            color: #58a6ff;
            padding: 20px;
            font-size: 1.8em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        section {
            margin: 20px auto;
            padding: 20px;
            background: linear-gradient(135deg, #1f2937, #3b4252);
            box-shadow: 0px 0px 15px rgba(88, 166, 255, 0.5);
            width: 80%;
            border-radius: 10px;
        }
        footer {
            background-color: #161b22;
            color: #58a6ff;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .social-links img {
            width: 50px;
            margin: 10px;
            transition: transform 0.3s ease, filter 0.3s ease;
            filter: brightness(0.8);
        }
        .social-links img:hover {
            transform: scale(1.1);
            filter: brightness(1);
        }
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        Hola, soy <a href="https://github.com/DevelUps">Pierre Grandett</a> 👋
    </header>
    <img src="https://i.imgur.com/weNbhGZ.png" alt="Pierre Grandett" style="width:150px; border-radius: 50%; margin: 20px auto; display: block;">
    
    <section>
        <h2>Sobre mí</h2>
        <p>⭐ QA Software Engineer (SDET) y especialista en analítica de datos.</p>
        <p>📲 Experto en pruebas manuales y automatizadas.</p>
        <p>🎥 Compartiendo conocimientos sobre QA y Automatización.</p>
        <p>✏️ Publicaciones técnicas en mi blog.</p>
        <p>📗 Autor de contenido sobre testing y automatización.</p>
    </section>
    
    <section>
        <h2>Redes Sociales</h2>
        <div class="social-links">
            <a href="https://github.com/DevelUps" target="_blank">
                <img src="https://img.shields.io/github/followers/DevelUps?style=social" alt="GitHub">
            </a>
            <a href="https://www.linkedin.com/in/pierregett/" target="_blank">
                <img src="https://img.shields.io/badge/-LinkedIn-blue?style=social&logo=linkedin" alt="LinkedIn">
            </a>
        </div>
    </section>
    
    <section>
        <h2>GitHub Analytics</h2>
        <p align="center">
            <a href="https://github.com/DevelUps">
                <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=DevelUps&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
                <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=DevelUps&layout=compact&langs_count=8&theme=tokyonight"/>
            </a>
        </p>
    </section>
    
    <footer>
        <p>&copy; 2025 Pierre Grandett</p>
    </footer>
</body>
</html>
