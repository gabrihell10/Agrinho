<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Conscientização sobre Poluição</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Estilo do corpo para usar Flexbox e manter o footer no final */
        body {
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            line-height: 1.6;
        }

        /* Conteúdo principal */
        main {
            flex: 1;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }

        h1 {
            text-align: center;
            color: #2e8b57;
            margin-bottom: 20px;
        }

        p {
            margin-bottom: 15px;
            font-size: 1.1em;
        }

        /* Estilo da imagem */
        .conscientizacao-img {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 20px auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        /* Estilo do footer */
        footer {
            background-color: #2e8b57;
            color: white;
            text-align: center;
            padding: 15px 10px;
        }
    </style>
</head>
<body>
    <main>
        <h1>Conscientização sobre Poluição</h1>
        <p>A poluição afeta a saúde do planeta e de todos os seres vivos. Ela causa problemas ambientais, como o aquecimento global, a destruição de ecossistemas e doenças humanas. Conscientizar-se é o primeiro passo para fazer a diferença!</p>
        <!-- Imagem relacionada ao tema -->
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Poluição e meio ambiente" class="conscientizacao-img" />
        <p>Como podemos ajudar?</p>
        <ul>
            <li>Reduza o uso de plástico descartável.</li>
            <li>Recicle materiais sempre que possível.</li>
            <li>Economize água e energia.</li>
            <li>Utilize transporte público ou bicicleta.</li>
            <li>Plante árvores e cuide do meio ambiente.</li>
        </ul>
        <p>Juntos podemos fazer a diferença! Conscientize-se e ajude a proteger o planeta.</p>
    </main>
    <footer>
        &copy; 2024 Conscientização Ambiental. Todos os direitos reservados.
    </footer>
</body>
</html>
