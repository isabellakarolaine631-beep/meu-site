<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isabella Karolaine</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #ffe4f0;
            color: #4a1830;
            text-align: center;
        }

        header {
            background-color: #c2185b;
            color: white;
            padding: 50px 20px;
        }

        header h1 {
            font-size: 50px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
        }

        main {
            max-width: 900px;
            margin: 30px auto;
            padding: 20px;
        }

        .sobre {
            background-color: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }

        .sobre h2 {
            color: #c2185b;
            margin-bottom: 15px;
            font-size: 30px;
        }

        .sobre p {
            font-size: 18px;
            line-height: 1.6;
        }

        .hobbies {
            margin-top: 30px;
        }

        .hobbies h2 {
            color: #c2185b;
            margin-bottom: 20px;
            font-size: 30px;
        }

        .cards {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .card {
            background-color: white;
            width: 250px;
            padding: 25px;
            border-radius: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        .card span {
            font-size: 45px;
        }

        .card h3 {
            color: #c2185b;
            margin: 12px 0;
        }

        .card p {
            font-size: 16px;
        }

        footer {
            margin-top: 40px;
            background-color: #c2185b;
            color: white;
            padding: 20px;
        }

        /* Deixa o site bonito no celular */
        @media (max-width: 600px) {
            header h1 {
                font-size: 36px;
            }

            header p {
                font-size: 17px;
            }

            .card {
                width: 100%;
            }

            main {
                padding: 15px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Isabella Karolaine</h1>
        <p>Bem-vindo ao meu site! 🌸</p>
    </header>

    <main>

        <section class="sobre">
            <h2>Sobre mim 💗</h2>
            <p>
                Olá! Meu nome é <strong>Isabella Karolaine</strong>.
                Este é um pouquinho sobre mim e sobre as coisas que eu gosto
                de fazer no meu tempo livre.
            </p>
        </section>

        <section class="hobbies">
            <h2>Meus Hobbies ✨</h2>

            <div class="cards">

                <div class="card">
                    <span>🏐</span>
                    <h3>Vôlei</h3>
                    <p>
                        Gosto de jogar vôlei e me divertir praticando esse esporte.
                    </p>
                </div>

                <div class="card">
                    <span>🎨</span>
                    <h3>Desenho</h3>
                    <p>
                        Adoro desenhar e usar minha criatividade para criar coisas novas.
                    </p>
                </div>

                <div class="card">
                    <span>🎮</span>
                    <h3>Jogos</h3>
                    <p>
                        Gosto de jogar e me divertir com diferentes tipos de jogos.
                    </p>
                </div>

            </div>
        </section>

    </main>

    <footer>
        <p>Feito com 💗 por Isabella Karolaine</p>
    </footer>

</body>
</html>
```
# meu-site
