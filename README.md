<!DOCTYPE html>
<html lang="pt-br">
 <head>
  <meta charset="UTF-8">
  <title>Exercício de CSS</title>

  <style>
    /* Seletor por TAG */
    body {
      background-color: #f2f2f2;
      font-family: Arial, sans-serif;
    }

    h1 {
      color:purple;
      text-align: center;
    }

    /* Seletor por CLASSE */
    .destaque {
      color: purple;
      font-weight: bold;
    }

    /* Seletor por ID */
    #rodape {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }

    /* Seletor por TAG */
    h2 {
      color: green;
    }
  </style>
</head>
<body>

  <h1>Library Isas </h1>
  <p>Confira alguns produtos da nossa loja:</p>

  <h2>O pequeno príncipe! </h2>
  <p>Uma história alegórica sobre um piloto que encontra um jovem príncipe de outro planeta em sua jornada.</p>

  <h2 class="destaque">Dom Quixote</h2>
  <p> Um fidalgo que, após ler muitos romances de cavalaria, decide viver aventuras imaginárias.</p>

  <h2>Dom Casmurro</h2>
  <p> Obra de Machado de Assis que narra a história de Bentinho, um homem que vive remoendo a possibilidade de traição de sua esposa, Capitu.</p>
  
  <h2 class="destaque">O Cortiço</h2>
  <p>Obra de Aluísio Azevedo que expõe a vida em um cortiço carioca e a ascensão de João Romão, explorando a ganância. </p>


  <div id="rodape">
    ©️ 2025 Library Isas 
  </div>

</body>
</html>
