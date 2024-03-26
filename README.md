# 7894561 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lƒmpada</title>
</head>
<body>
    <img id="lampada" src="lampada_apagada.png" alt="Lƒmpada">
    <button id="botao">Ligar/Desligar</button>

    <script>
        // Fun‡Æo para ligar/desligar a lƒmpada
        function ligarDesligarLampada() {
            var lampada = document.getElementById("lampada");
            if (lampada.src.match("lampada_apagada.png")) {
                lampada.src = "lampada_acesa.png";
            } else {
                lampada.src = "lampada_apagada.png";
            }
        }

        // Associar a fun‡Æo ao evento de clique do botÆo
        document.getElementById("botao").addEventListener("click", ligarDesligarLampada);
    </script>
</body>
</html>
