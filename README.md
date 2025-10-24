# Trabalho-Feira-T-cnica
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Calculadora Simples</title>

  <style>
    body {
      background-color: #f3f4f6;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    .calculadora {
      background-color: #222;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }

    .tela {
      width: 100%;
      height: 50px;
      text-align: right;
      font-size: 1.5em;
      margin-bottom: 15px;
      border: none;
      border-radius: 5px;
      padding: 10px;
      box-sizing: border-box;
      background-color: #fff;
    }

    .botoes {
      display: grid;
      grid-template-columns: repeat(4, 60px);
      gap: 10px;
    }

    button {
      height: 60px;
      font-size: 1.2em;
      border: none;
      border-radius: 5px;
      background-color: #444;
      color: white;
      cursor: pointer;
      transition: background 0.2s;
    }

    button:hover {
      background-color: #555;
    }

    .operador {
      background-color: #ff9500;
    }

    .operador:hover {
      background-color: #e08900;
    }

    .igual {
      grid-column: span 2;
      background-color: #28a745;
    }

    .igual:hover {
      background-color: #218838;
    }

    .limpar {
      background-color: #dc3545;
    }

    .limpar:hover {
      background-color: #c82333;
    }
  </style>
</head>
<body>
  <div class="calculadora">
    <input type="text" class="tela" id="tela" disabled />

    <div class="botoes">
      <button onclick="adicionar('7')">7</button>
      <button onclick="adicionar('8')">8</button>
      <button onclick="adicionar('9')">9</button>
      <button class="operador" onclick="adicionar('/')">÷</button>

      <button onclick="adicionar('4')">4</button>
      <button onclick="adicionar('5')">5</button>
      <button onclick="adicionar('6')">6</button>
      <button class="operador" onclick="adicionar('*')">×</button>

      <button onclick="adicionar('1')">1</button>
      <button onclick="adicionar('2')">2</button>
      <button onclick="adicionar('3')">3</button>
      <button class="operador" onclick="adicionar('-')">−</button>

      <button onclick="adicionar('0')">0</button>
      <button onclick="adicionar('.')">.</button>
      <button class="limpar" onclick="limpar()">C</button>
      <button class="operador" onclick="adicionar('+')">+</button>

      <button class="igual" onclick="calcular()">=</button>
    </div>
  </div>

  <script>
    const tela = document.getElementById("tela");

    function adicionar(valor) {
      tela.value += valor;
    }

    function limpar() {
      tela.value = "";
    }

    function calcular() {
      try {
        tela.value = eval(tela.value);
      } catch {
        tela.value = "Erro";
      }
    }
  </script>
</body>
</html>
