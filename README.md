<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mundini Coutinho Suplementos</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to right, #0f0f0f, #1a1a1a);
      color: #fff;
      margin: 0;
      padding: 2rem;
    }
    h1, h2 {
      color: #ffd700;
      text-align: center;
    }
    .categoria {
      margin-top: 3rem;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1.5rem;
      padding: 1rem 0;
    }
    .produto {
      background-color: #222;
      border-radius: 16px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.4);
      transition: transform 0.3s ease;
    }
    .produto:hover {
      transform: translateY(-5px);
    }
    .produto img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .produto-content {
      padding: 1rem;
    }
    .produto-content strong {
      display: block;
      font-size: 1rem;
      margin-bottom: 0.3rem;
    }
    .produto-content span {
      display: block;
      margin-bottom: 0.5rem;
    }
    input[type="number"] {
      width: 48px;
      padding: 0.2rem;
      border-radius: 5px;
      border: none;
      background-color: #444;
      color: #fff;
    }
    label {
      font-size: 0.9rem;
    }
    textarea, select {
      width: 100%;
      margin-top: 1rem;
      padding: 0.7rem;
      border-radius: 8px;
      border: none;
      resize: none;
      background-color: #333;
      color: #fff;
    }
    button {
      margin-top: 2rem;
      padding: 1rem 2rem;
      background-color: #ffd700;
      border: none;
      color: #000;
      font-weight: bold;
      border-radius: 10px;
      cursor: pointer;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }
    button:hover {
      background-color: #e6c200;
    }
  </style>
</head>
<body>
  <h1>Mundini Coutinho Suplementos</h1>

  <div class="categoria">
    <h2>🥤 PROTEÍNAS</h2>
    <div class="container">
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Whey+Protein" alt="Whey Protein">
        <div class="produto-content">
          <strong>Whey Protein Concentrado</strong>
          <span>R$ 129,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Whey Protein Concentrado" data-valor="129.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Whey+Isolado" alt="Whey Isolado">
        <div class="produto-content">
          <strong>Whey Isolado Premium</strong>
          <span>R$ 179,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Whey Isolado Premium" data-valor="179.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Protein+Vegano" alt="Vegano Protein">
        <div class="produto-content">
          <strong>Vegano Plant Protein</strong>
          <span>R$ 89,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Vegano Plant Protein" data-valor="89.90"></label>
        </div>
      </div>
    </div>
  </div>

  <div class="categoria">
    <h2>🔥 Termogênicos</h2>
    <div class="container">
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Black+Fire+Burner" alt="Black Fire Burner">
        <div class="produto-content">
          <strong>Black Fire Burner</strong>
          <span>R$ 79,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Black Fire Burner" data-valor="79.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Cafeína+Hardcore" alt="Cafeína Hardcore">
        <div class="produto-content">
          <strong>Cafeína Hardcore</strong>
          <span>R$ 64,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Cafeína Hardcore" data-valor="64.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Chá+Detox+Power" alt="Chá Detox Power">
        <div class="produto-content">
          <strong>Chá Detox Power</strong>
          <span>R$ 49,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Chá Detox Power" data-valor="49.90"></label>
        </div>
      </div>
    </div>
  </div>

  <div class="categoria">
    <h2>🧃 Pré-Treino / Pós-Treino</h2>
    <div class="container">
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Pré-Treino+NitroX" alt="Pré-Treino NitroX">
        <div class="produto-content">
          <strong>Pré-Treino NitroX</strong>
          <span>R$ 99,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Pré-Treino NitroX" data-valor="99.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Creatina" alt="Creatina">
        <div class="produto-content">
          <strong>Creatina 100% Pura</strong>
          <span>R$ 89,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Creatina 100% Pura" data-valor="89.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=BCAA+4:1:1" alt="BCAA">
        <div class="produto-content">
          <strong>BCAA 4:1:1</strong>
          <span>R$ 79,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="BCAA 4:1:1" data-valor="79.90"></label>
        </div>
      </div>
    </div>
  </div>

  <div class="categoria">
    <h2>🛍️ Combos Promocionais</h2>
    <div class="container">
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Combo+Ganho+de+Massa" alt="Combo Ganho de Massa">
        <div class="produto-content">
          <strong>Combo Ganho de Massa</strong>
          <span>R$ 219,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Combo Ganho de Massa" data-valor="219.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Combo+Definição+Total" alt="Combo Definição Total">
        <div class="produto-content">
          <strong>Combo Definição Total</strong>
          <span>R$ 189,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Combo Definição Total" data-valor="189.90"></label>
        </div>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/300x200?text=Combo+Vegano+Power" alt="Combo Vegano Power">
        <div class="produto-content">
          <strong>Combo Vegano Power</strong>
          <span>R$ 199,90</span>
          <label>Qtd: <input type="number" min="0" value="0" data-nome="Combo Vegano Power" data-valor="199.90"></label>
        </div>
      </div>
    </div>
  </div>
   
   <label for="endereco"><strong>📌 - Endereço de Entrega:</strong></label>
   <textarea id="endereco" rows="3" placeholder="Digite seu endereço completo"></textarea>

  <label for="pagamento"><strong>💳 - Forma de Pagamento:</strong></label>
<select id="pagamento">
  <option value="Dinheiro">Dinheiro</option>
  <option value="Cartão">Cartão de Crédito/Débito</option>
  <option value="PIX">PIX</option>
  <option value="Link de Pagamento">Link de Pagamento</option>
</select>

<!-- Ícones de formas de pagamento -->
<div style="margin-top: 2rem; display: flex; justify-content: center; gap: 1.5rem; flex-wrap: wrap;">
  <div style="text-align: center;">
    <img src="https://via.placeholder.com/60?text=💵" alt="Dinheiro" style="background: #333; border-radius: 10px; padding: 10px;">
    <p>Dinheiro</p>
  </div>
  <div style="text-align: center;">
    <img src="https://via.placeholder.com/60?text=💳" alt="Cartão" style="background: #333; border-radius: 10px; padding: 10px;">
    <p>Cartão</p>
  </div>
  <div style="text-align: center;">
    <img src="https://via.placeholder.com/60?text=🔁" alt="PIX" style="background: #333; border-radius: 10px; padding: 10px;">
    <p>PIX</p>
  </div>
  <div style="text-align: center;">
    <img src="https://via.placeholder.com/60?text=🔗" alt="Link de Pagamento" style="background: #333; border-radius: 10px; padding: 10px;">
    <p>Link</p>
  </div>
</div>

<button onclick="enviarPedido()">Finalizar Pedido via WhatsApp</button>

  <script>
    function enviarPedido() {
      const inputs = document.querySelectorAll('input[type="number"]');
      const endereco = document.getElementById('endereco').value;
      const pagamento = document.getElementById('pagamento').value;
      let mensagem = 'Olá! Gostaria de fazer um pedido:%0A';
      let total = 0;
      inputs.forEach(input => {
        const qtd = parseInt(input.value);
        if (qtd > 0) {
          const nome = input.getAttribute('data-nome');
          const valor = parseFloat(input.getAttribute('data-valor'));
          total += valor * qtd;
          mensagem += `- ${qtd}x ${nome} - R$ ${(valor * qtd).toFixed(2)}%0A`;
        }
      });
      mensagem += `%0ATotal: R$ ${total.toFixed(2)}%0A`;
      mensagem += `%0AEndereço: ${encodeURIComponent(endereco)}%0A`;
      mensagem += `%0AForma de Pagamento: ${pagamento}`;
      window.open(`https://wa.me/5521966227981?text=${mensagem}`);
    }
  </script>
</body>
</html>
