<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>DINO</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: purple light;
        }
    </style>
    <script>
        function accionParaCuandoElDigaQueRECONTRACHI(){
            alert('ERES LO MÁXIMO, Mi paleontólogo favorito <3');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";
            

        }
    </script>
</head>
<body>
    <h3>TE IRA SUPER BIEN EN LÓGICA AMOUR</h3>
    <input type="button" onclick="accionParaCuandoElDigaQueRECONTRACHI()" id="btnSi" value="RECONTRACHI" />
    <input type="button" id="btnCHI" onmouseover="mueveElBoton()" value="CHI" />
    <img src="DINOU.png" width="200">
</body>
</html>
