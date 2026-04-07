# Aprendendo-front-end

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Fernando Toledo de Oliveira</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #1e3c72, #2a5298);
            margin: 0;
            padding: 0;
            color: #333;
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }

        .box {
            background: white;
            padding: 20px;
            margin-top: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            text-align: center;
        }

        img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #2a5298;
        }

        a {
            color: #2a5298;
            font-weight: bold;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        h1, h2 {
            color: #2a5298;
        }
    </style>
</head>
<body>

<div class="container">

    <!-- Div 1 -->
    <div class="box">
        <h1>Fernando Toledo de Oliveira</h1>

        <!-- SUA FOTO -->
        <img src="minha-foto.jpg" alt="Foto de Fernando">
    </div>

    <!-- Div 2 -->
    <div class="box">
        <h2>Sobre mim</h2>

        <p>
            Olá! Meu nome é <strong>Fernando Toledo de Oliveira</strong> e estou aprendendo 
            <em>desenvolvimento frontend</em>.
        </p>

        <p>
            Estou iniciando na área de tecnologia e tenho muito o que aprender.
        </p>
    </div>

    <!-- Div 3 -->
    <div class="box">
        <h2>Contato</h2>

        <p>
            Acesse meu perfil no 
            <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
            ou 
            <a href="https://github.com" target="_blank">GitHub</a>
        </p>
    </div>

</div>

</body>
</html>
