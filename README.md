<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="src/style.css">
    <title>Eventos DOM</title>
    <style>
    div#area{
      background: rgb(42, 139, 42);
      color: white;
      width: 200px;
      height: 200px;
      line-height: 200px;
      line-height: center;
      font: normal 20pt Arial;
    }
    </style>
  </head>
  <body>
    <div id = "area" onclick="clicar()" onmouseenter="entrar()onmouseout = "sair">
    Foda-se...
    </div>
    <script>
      var area = document.getElementById('area')

      function clicar(){
        area.innerText = 'Clicou!'
      }
      function entrar(){

      }
    </script>
  </body>
</html>
