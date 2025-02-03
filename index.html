<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Orçamento Estampas Talentos</title>
  <link href="https://fonts.googleapis.com/css?family=Roboto:400,500&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }
    .container {
      background: #fff;
      max-width: 500px;
      width: 90%;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    h1 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }
    .form-group {
      margin-bottom: 20px;
    }
    label {
      display: block;
      margin-bottom: 5px;
      color: #555;
    }
    select, input[type="button"] {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }
    select:focus, input[type="button"]:focus {
      outline: none;
      border-color: #007BFF;
    }
    input[type="button"] {
      background-color: #007BFF;
      color: #fff;
      border: none;
      cursor: pointer;
      transition: background-color 0.3s ease;
      margin-top: 10px;
    }
    input[type="button"]:hover {
      background-color: #0056b3;
    }
    .result {
      text-align: center;
      font-size: 1.2rem;
      margin-top: 20px;
      color: #007BFF;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Orçamento Estampas Talentos</h1>
    <form id="priceForm">
      <div class="form-group">
        <label for="cores">Quantidade de Cores:</label>
        <select id="cores" name="cores">
          <option value="1">1 (40×50)</option>
          <option value="2">2 (40×50)</option>
          <option value="3">3 (40×50)</option>
          <option value="4">4 (40×50)</option>
        </select>
      </div>
      
      <div class="form-group">
        <label for="quantidade">Quantidade de Peças:</label>
        <select id="quantidade" name="quantidade">
          <option value="10-50">10 a 50</option>
          <option value="50-100">50 a 100</option>
          <option value="100-200">100 a 200</option>
          <option value="200-500">200 a 500</option>
          <option value="500-1000">500 a 1000</option>
        </select>
      </div>
      
      <div class="form-group">
        <label for="material">Material:</label>
        <select id="material" name="material">
          <option value="tintaLeve">Tinta Leve (Tecido Claro)</option>
          <option value="tintaCobertura">Tinta Cobertura (Tecido Escuro)</option>
          <option value="tintaRelevo">Tinta Relevo, Gel, Puff Nivelado</option>
        </select>
      </div>
      
      <div class="form-group">
        <label for="tamanho">Tamanho da Tela:</label>
        <select id="tamanho" name="tamanho">
          <option value="40x50">40×50 (Sem acréscimo)</option>
          <option value="50x60">50×60 (+10%)</option>
          <option value="60x70">60×70 (+20%)</option>
          <option value="80x90">80×90 (+30%)</option>
          <option value="90x100">90×100 (+40%)</option>
        </select>
      </div>
      
      <input type="button" value="Calcular Preço" onclick="calcularPreco()">
    </form>
    
    <div class="result">
      <h2>Preço Final: <span id="resultado">R$ 0,00</span></h2>
    </div>
  </div>

  <script>
    // Tabela de preços baseada na dimensão 40×50
    const tableData = {
      "1": {
        "10-50": { "tintaLeve": 7.50, "tintaCobertura": 9.00, "tintaRelevo": 12.00 },
        "50-100": { "tintaLeve": 3.10, "tintaCobertura": 3.60, "tintaRelevo": 4.00 },
        "100-200": { "tintaLeve": 2.90, "tintaCobertura": 3.50, "tintaRelevo": 4.00 },
        "200-500": { "tintaLeve": 2.40, "tintaCobertura": 3.00, "tintaRelevo": 3.80 },
        "500-1000": { "tintaLeve": 1.60, "tintaCobertura": 1.90, "tintaRelevo": 2.20 }
      },
      "2": {
        "10-50": { "tintaLeve": 14.00, "tintaCobertura": 17.00, "tintaRelevo": 22.00 },
        "50-100": { "tintaLeve": 6.00, "tintaCobertura": 7.00, "tintaRelevo": 9.00 },
        "100-200": { "tintaLeve": 4.80, "tintaCobertura": 5.60, "tintaRelevo": 7.00 },
        "200-500": { "tintaLeve": 3.80, "tintaCobertura": 4.80, "tintaRelevo": 6.00 },
        "500-1000": { "tintaLeve": 2.20, "tintaCobertura": 2.80, "tintaRelevo": 3.40 }
      },
      "3": {
        "10-50": { "tintaLeve": 20.00, "tintaCobertura": 25.00, "tintaRelevo": 33.00 },
        "50-100": { "tintaLeve": 9.00, "tintaCobertura": 10.00, "tintaRelevo": 13.00 },
        "100-200": { "tintaLeve": 7.00, "tintaCobertura": 8.00, "tintaRelevo": 9.00 },
        "200-500": { "tintaLeve": 5.70, "tintaCobertura": 6.50, "tintaRelevo": 7.50 },
        "500-1000": { "tintaLeve": 2.80, "tintaCobertura": 3.30, "tintaRelevo": 4.00 }
      },
      "4": {
        "10-50": { "tintaLeve": 25.00, "tintaCobertura": 32.00, "tintaRelevo": 44.00 },
        "50-100": { "tintaLeve": 12.00, "tintaCobertura": 13.00, "tintaRelevo": 17.00 },
        "100-200": { "tintaLeve": 9.00, "tintaCobertura": 10.00, "tintaRelevo": 12.00 },
        "200-500": { "tintaLeve": 7.50, "tintaCobertura": 9.00, "tintaRelevo": 10.50 },
        "500-1000": { "tintaLeve": 4.40, "tintaCobertura": 5.20, "tintaRelevo": 6.80 }
      }
    };

    // Percentuais de acréscimo conforme o tamanho selecionado
    const sizePercentage = {
      "40x50": 0,
      "50x60": 10,
      "60x70": 20,
      "80x90": 30,
      "90x100": 40
    };

    function calcularPreco() {
      // Obtém os valores selecionados
      const cores = document.getElementById("cores").value;
      const quantidade = document.getElementById("quantidade").value;
      const material = document.getElementById("material").value;
      const tamanho = document.getElementById("tamanho").value;
      
      // Busca o preço base na tabela para os parâmetros escolhidos
      let basePrice = tableData[cores][quantidade][material];
      
      // Aplica o acréscimo conforme o tamanho da tela
      const percent = sizePercentage[tamanho];
      let finalPrice = basePrice * (1 + percent / 100);
      
      // Formata para duas casas decimais
      finalPrice = finalPrice.toFixed(2);
      
      // Exibe o resultado
      document.getElementById("resultado").textContent = "R$ " + finalPrice;
    }
  </script>
</body>
</html>
