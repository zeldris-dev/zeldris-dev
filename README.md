<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .card {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 300px;
        }

        .card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .card h2 {
            margin-bottom: 10px;
        }

        .card p {
            margin-bottom: 10px;
        }

        .card a {
            text-decoration: none;
            color: #007bff;
            transition: color 0.3s;
        }

        .card a:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="card">
        <img src="https://avatars.githubusercontent.com/u/12345678?v=4" alt="Foto de Perfil">
        <h2>Seu Nome</h2>
        <p>Desenvolvedor Full Stack</p>
        <p>GitHub: <a href="https://github.com/seu_usuario" target="_blank">@seu_usuario</a></p>
        <p>Twitter: <a href="https://twitter.com/seu_usuario" target="_blank">@seu_usuario</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/seu_usuario/" target="_blank">seu_usuario</a></p>
    </div>
</body>
</html>
