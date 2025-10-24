<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quiz de Conhecimentos Gerais</title>
  <style>
    /* ===== ESTILO GERAL ===== */
    body {
      background: linear-gradient(135deg, #74b9ff, #a29bfe, #81ecec, #55efc4);
      background-size: 400% 400%;
      animation: gradient 10s ease infinite;
      font-family: 'Poppins', Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      padding: 20px;
      color: #333;
      min-height: 100vh;
    }

    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .quiz-container {
      background: rgba(255, 255, 255, 0.95);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      max-width: 700px;
      width: 100%;
      border: 3px solid #6c5ce7;
    }

    h1 {
      text-align: center;
      color: #2d3436;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
      margin-bottom: 25px;
    }

    /* ===== PERGUNTAS ===== */
    .pergunta {
      margin-bottom: 20px;
      padding: 15px;
      border-radius: 10px;
      background: linear-gradient(135deg, #ffeaa7, #fab1a0);
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s ease;
    }

    .pergunta:hover {
      transform: scale(1.02);
      background: linear-gradient(135deg, #fdcb6e, #e17055);
    }

    .pergunta h3 {
      color: #2d3436;
    }

    label {
      display: block;
      background: #dfe6e9;
      margin: 6px 0;
      padding: 8px 10px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.2s, transform 0.1s;
    }

    label:hover {
      background-color: #81ecec;
      transform: scale(1.02);
    }

    input[type="radio"] {
      margin-right: 8px;
    }

    /* ===== BOTÃO E RESPOSTAS ===== */
    .respostas {
      margin-top: 30px;
      text-align: center;
    }

    .botao {
      background: linear-gradient(135deg, #6c5ce7, #0984e3);
      color: white;
      border: none;
      padding: 12px 25px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 18px;
      font-weight: bold;
      transition: background 0.3s, transform 0.2s;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .botao:hover {
      background: linear-gradient(135deg, #00cec9, #00b894);
      transform: scale(1.05);
    }

    .respostas p {
      display: none;
      margin-top: 20px;
      background-color: #dff9fb;
      padding: 12px;
      border-radius: 8px;
      color: #0984e3;
      font-weight: 600;
      border: 2px solid #74b9ff;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .respostas:hover p {
      display: block;
    }
  </style>
</head>
<body>
  <div class="quiz-container">
    <h1>🎯 Quiz de Conhecimentos Gerais</h1>

    <div class="pergunta">
      <h3>1. Qual é o planeta mais próximo do Sol?</h3>
      <label><input type="radio" name="q1">Vênus</label>
      <label><input type="radio" name="q1">Terra</label>
      <label><input type="radio" name="q1">Mercúrio</label>
      <label><input type="radio" name="q1">Marte</label>
    </div>

    <div class="pergunta">
      <h3>2. Quantos continentes existem no mundo?</h3>
      <label><input type="radio" name="q2">5</label>
      <label><input type="radio" name="q2">6</label>
      <label><input type="radio" name="q2">7</label>
      <label><input type="radio" name="q2">8</label>
    </div>

    <div class="pergunta">
      <h3>3. Quem pintou a Mona Lisa?</h3>
      <label><input type="radio" name="q3">Vincent van Gogh</label>
      <label><input type="radio" name="q3">Leonardo da Vinci</label>
      <label><input type="radio" name="q3">Pablo Picasso</label>
      <label><input type="radio" name="q3">Michelangelo</label>
    </div>

    <div class="pergunta">
      <h3>4. Qual é o maior oceano do planeta?</h3>
      <label><input type="radio" name="q4">Atlântico</label>
      <label><input type="radio" name="q4">Pacífico</label>
      <label><input type="radio" name="q4">Índico</label>
      <label><input type="radio" name="q4">Ártico</label>
    </div>

    <div class="pergunta">
      <h3>5. Qual é o animal terrestre mais rápido do mundo?</h3>
      <label><input type="radio" name="q5">Leopardo</label>
      <label><input type="radio" name="q5">Tigre</label>
      <label><input type="radio" name="q5">Guepardo</label>
      <label><input type="radio" name="q5">Leão</label>
    </div>

    <div class="pergunta">
      <h3>6. Em que país fica a Torre Eiffel?</h3>
      <label><input type="radio" name="q6">Itália</label>
      <label><input type="radio" name="q6">Espanha</label>
      <label><input type="radio" name="q6">França</label>
      <label><input type="radio" name="q6">Alemanha</label>
    </div>

    <div class="pergunta">
      <h3>7. Qual é a capital do Japão?</h3>
      <label><input type="radio" name="q7">Pequim</label>
      <label><input type="radio" name="q7">Tóquio</label>
      <label><input type="radio" name="q7">Seul</label>
      <label><input type="radio" name="q7">Xangai</label>
    </div>

    <div class="pergunta">
      <h3>8. Quantos segundos há em um minuto?</h3>
      <label><input type="radio" name="q8">30</label>
      <label><input type="radio" name="q8">45</label>
      <label><input type="radio" name="q8">60</label>
      <label><input type="radio" name="q8">100</label>
    </div>

    <div class="pergunta">
      <h3>9. Quem foi o primeiro homem a pisar na Lua?</h3>
      <label><input type="radio" name="q9">Neil Armstrong</label>
      <label><input type="radio" name="q9">Buzz Aldrin</label>
      <label><input type="radio" name="q9">Yuri Gagarin</label>
      <label><input type="radio" name="q9">John Glenn</label>
    </div>

    <div class="pergunta">
      <h3>10. Qual é a cor resultante da mistura de azul com amarelo?</h3>
      <label><input type="radio" name="q10">Laranja</label>
      <label><input type="radio" name="q10">Verde</label>
      <label><input type="radio" name="q10">Roxo</label>
      <label><input type="radio" name="q10">Marrom</label>
    </div>

    <div class="respostas">
      <button class="botao">Ver respostas</button>
      <p>Respostas corretas:<br>
        1. Mercúrio<br>
        2. 7<br>
        3. Leonardo da Vinci<br>
        4. Pacífico<br>
        5. Guepardo<br>
        6. França<br>
        7. Tóquio<br>
        8. 60<br>
        9. Neil Armstrong<br>
        10. Verde
      </p>
    </div>
  </div>
</body>
</html>
