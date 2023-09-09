

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            background-color: black;
            color: green;
            font-family: monospace;
            font-size: 1.5rem;
            white-space: nowrap;
            overflow: hidden;
        }

        .matrix-text {
            animation: matrix 5s linear infinite;
        }

        @keyframes matrix {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(-100%);
            }
        }
    </style>

    <div class="matrix-text">
        <!-- Coloque seu texto ou código Matrix aqui -->
        <pre>
            <!-- Exemplo de código Matrix -->
            <code>
                echo "Hello, World!";
            </code>
        </pre>
    </div>
