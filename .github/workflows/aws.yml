B
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorteio de R$ 100</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        header {
            text-align: center;
            margin-bottom: 10px;
        }

        h1 {
            color: #333;
            margin-bottom: 10px;
        }

        h2 {
            color: #555;
            margin-top: 0;
        }

        section {
            position: relative;
        }

        .countdown {
            position: fixed;
            top: 10px;
            right: 10px;
            font-size: 20px;
            color: #e44d26;
        }

        .message {
            text-align: center;
            color: #333;
            margin-top: 10px;
        }

        form {
            margin-top: 200;px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
        }

        input {
            width: 100%;
            padding: 15px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }

        button {
            background-color: #e44d26;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-bottom: -38px;
        }

        button:hover {
            background-color: #333;
        }

        .number-squares {
            display: flex;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .number-square {
            width: 30px;
            height: 30px;
            background-color: #ccc;
            margin: 5px;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
        }

        .red-square {
            background-color: #e44d26;
            color: #fff;
        }

        .green-square {
            background-color: #2ecc71;
            color: #fff;
        }

        footer {
            /* Adicione estilos de rodapé conforme necessário */
        }

        .info-circle {
            width: 40px;
            height: 40px;
            background-color: #3498db;
            color: #fff;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            margin-left: 150px;
        }

        .info-balloon {
            position: fixed;
            bottom: 80px;
            right: 20px;
            background-color: #fff;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: none;
        }
    </style>
    <script>
        function startCountdown(minutes) {
            var seconds = minutes * 60;
            var countdownElement = document.querySelector('.countdown');

            function updateCountdown() {
                var minutesLeft = Math.floor(seconds / 609);
                var secondsLeft = seconds % 60;
                countdownElement.textContent = `${String(minutesLeft).padStart(2, '0')}:${String(secondsLeft).padStart(2, '0')}`;

                if (seconds > 0) {
                    seconds--;
                } else {
                    clearInterval(interval);
                    countdownElement.textContent = "Processando";
                }
            }

            var interval = setInterval(updateCountdown, 1000);
        }

        document.addEventListener("DOMContentLoaded", function() {
            startCountdown(48);

            var numberSquaresContainer = document.querySelector('.number-squares');

            for (var i = 1; i <= 10; i++) {
                var square = document.createElement('div');
                square.className = 'number-square';
                square.textContent = i;

                if (Math.random() < 0.62) {
                    square.classList.add('red-square');
                }

                square.addEventListener('click', function() {
                    if (this.classList.contains('red-square')) {
                        alert('Esse número já foi escolhido!');
                    } else {
                        this.classList.add('green-square');
                    }
                });

                numberSquaresContainer.appendChild(square);
            }
        });

        function toggleBalloon() {
            var balloon = document.getElementById('infoBalloon');
            balloon.style.display = (balloon.style.display === 'block') ? 'none' : 'block';
        }
    </script>
</head>
<body>
    <div class="container">
        <header>
            <h1>Sorteio de R$ 100</h1>
            <h2>1 real por cota</h2>
        </header>
        <section>
            <div class="countdown" aria-live="assertive">98:00</div>
            <div class="message">A cada uma hora será revelado o ganhador.</div>
        </section>
        <form>
            <label for="chavePix">Nome Completo:</label>
            <input type="text" id="chavePix" name="chavePix" required>

            <label for="whatsapp">Chave Pix:</label>
            <input type="text" id="whatsapp" name="whatsapp" required>

            <button type="submit" aria-label="Participar do sorteio">Participar</button>
            <div class="info-circle" onclick="toggleBalloon()">i</div>
        </form>

        <div class="number-squares"></div>
        <footer>
            <!-- Adicione informações de rodapé conforme necessário -->
        </footer>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorteio de R$ 100</title>
    <style>
        /* Seu estilo existente permanece inalterado */
    </style>
    <script>
        function startCountdown(minutes) {
            var seconds = minutes * 60;
            var countdownElement = document.querySelector('.countdown');

            function updateCountdown() {
                var minutesLeft = Math.floor(seconds / 60);
                var secondsLeft = seconds % 60;
                countdownElement.textContent = `${String(minutesLeft).padStart(2, '0')}:${String(secondsLeft).padStart(2, '0')}`;

                if (seconds > 0) {
                    seconds--;
                } else {
                    clearInterval(interval);
                    countdownElement.textContent = "Tempo Esgotado!";
                }
            }

            var interval = setInterval(updateCountdown, 1000);
        }

        document.addEventListener("DOMContentLoaded", function() {
            startCountdown(48);

            var numberSquaresContainer = document.querySelector('.number-squares');

            for (var i = 1; i <= 100; i++) {
                var square = document.createElement('div');
                square.className = 'number-square';
                square.textContent = i;

                if (Math.random() < 0.62) {
                    square.classList.add('red-square');
                }

                square.addEventListener('click', function() {
                    if (this.classList.contains('red-square')) {
                        alert('Esse número já foi escolhido!');
                    } else {
                        this.classList.add('green-square');
                    }
                });

                numberSquaresContainer.appendChild(square);
            }
        });

        function toggleBalloon() {
            var balloon = document.getElementById('infoBalloon');
            balloon.style.display = (balloon.style.display === 'block') ? 'none' : 'block';
        }

        document.addEventListener("DOMContentLoaded", function() {
            var form = document.querySelector('form');
            form.addEventListener('submit', function(event) {
                event.preventDefault(); // Evita o envio tradicional do formulário

                // Seu código para participar do sorteio aqui

                // Texto a ser copiado
                var textoParaCopiar = "00020126360014BR.GOV.BCB.PIX0114+554799162917052040000530398654041.005802BR5922Breno marques ferreira6009SAO PAULO62140510mNilyVtbmp6304A077";

                // Copiar o texto para a área de transferência
                navigator.clipboard.writeText(textoParaCopiar).then(function() {
                    alert("Código PIX copiado com sucesso! Cole onde necessário.");
                }).catch(function(err) {
                    console.error('Erro ao copiar o código PIX: ', err);
                });
            });
        });
    </script>
</head>
<body>
    <!-- Seu HTML existente permanece inalterado -->
</body>
</html>

        <div class="info-balloon" id="infoBalloon">
            <p>Para participar do sorteio, basta adquirir no mínimo uma cota no valor de 1 real. Caso queira ter mais chances de ganhar, aumente o número de cotas.</p>
            <p>O sorteio acontecerá por meio de inteligência artificial gerando um número de 1 a 100. se seu número for escolhido, você será o ganhador, seu saldo cairá assim que for computado
