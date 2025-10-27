<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exercício de CSS</title>
  <style>
    body {
      background-color: #f2f2f2;
      font-family: Arial, sans-serif;
    }

   h1 {
      color: purple;
      text-align: center;
    }

   .destaque {
      color: purple;
      font-weight: bold;
    }

   #rodape {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
    h2 {
      color: green;
    }
  </style>
</head>
<body>

  <h1>Library Isas</h1>
  <p>Confira alguns produtos da nossa loja:</p>

  <h2>O Pequeno Príncipe</h2>
  <p>
    Uma história alegórica sobre um piloto que encontra um jovem príncipe de outro planeta em sua jornada.<br>
    Escrito por Antoine de Saint-Exupéry, o livro aborda temas como amizade, amor, perda e o olhar puro da infância sobre o mundo adulto.
  </p>

  <h2 class="destaque">Dom Quixote</h2>
  <p>
    Um fidalgo que, após ler muitos romances de cavalaria, decide viver aventuras imaginárias.<br>
    Escrito por Miguel de Cervantes, é considerado um dos maiores clássicos da literatura mundial.<br>
    A obra explora a linha tênue entre realidade e fantasia com humor e crítica social.
  </p>

  <h2>Dom Casmurro</h2>
  <p>
    Obra de Machado de Assis que narra a história de Bentinho, um homem que vive remoendo a possibilidade de traição de sua esposa, Capitu.<br>
    A narrativa em primeira pessoa levanta dúvidas sobre a confiabilidade do narrador.<br>
    Discute temas como ciúme, memória e identidade.
  </p>
  
  <h2 class="destaque">O Cortiço</h2>
  <p>
    Obra de Aluísio Azevedo que expõe a vida em um cortiço carioca e a ascensão de João Romão, explorando a ganância.<br>
    O romance naturalista retrata as condições sociais e raciais do Brasil do século XIX.<br>
    Destaca o determinismo e a influência do meio sobre o comportamento humano.
  </p>

  <div id="rodape">
    &copy; 2025 Library Isas
  </div>

</body>
</html>
