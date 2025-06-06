<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ícones de Tecnologias</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }

        .icon-container {
            font-size: 5rem; /* Ajuste o tamanho dos ícones aqui */
            color: #333;
            display: flex;
            gap: 30px; /* Espaço entre os ícones */
        }

        .icon-container i {
            transition: transform 0.3s ease-in-out;
        }

        .icon-container i:hover {
            transform: scale(1.1);
        }

        /* Cores específicas para cada ícone (opcional) */
        .fa-html5 {
            color: #e34c26; /* Laranja do HTML */
        }

        .fa-css3-alt {
            color: #264de4; /* Azul do CSS */
        }
        
        /* Font Awesome não possui um ícone oficial para C#, então usamos um genérico de código */
        .fa-code { 
            color: #6a0dad; /* Roxo para C# (exemplo) */
        }

        .fa-php {
            color: #777bb4; /* Roxo do PHP */
        }
    </style>
</head>
<body>
    <div class="icon-container">
        <i class="fab fa-html5" title="HTML5"></i>
        <i class="fab fa-css3-alt" title="CSS3"></i>
        <i class="fa-solid fa-code" title="C#"></i> <i class="fab fa-php" title="PHP"></i>
    </div>
</body>
</html>
