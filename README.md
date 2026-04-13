<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TechStore</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background-color: #121212; color: #fff; }
    header { background-color: #8B0000; padding: 15px; text-align: center; font-size: 24px; font-weight: bold; }
    nav { display: flex; justify-content: center; background-color: #1f1f1f; padding: 10px; gap: 20px; flex-wrap: wrap; }
    nav a { color: #fff; text-decoration: none; font-weight: bold; }
    nav a:hover { color: #ff4d4d; }
    .container { padding: 20px; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
    .card { background-color: #1f1f1f; padding: 15px; border-radius: 10px; text-align: center; }
    .card img { width: 100%; border-radius: 10px; }
    .btn { background-color: #8B0000; border: none; padding: 10px; color: #fff; cursor: pointer; margin-top: 10px; border-radius: 5px; }
    .ads { background-color: #333; margin: 20px 0; padding: 20px; text-align: center; border-radius: 10px; }
    footer { background-color: #8B0000; text-align: center; padding: 10px; margin-top: 20px; }/* WhatsApp Button */
.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #25D366;
  color: white;
  padding: 15px;
  border-radius: 50%;
  font-size: 20px;
  text-decoration: none;
  box-shadow: 0 0 10px rgba(0,0,0,0.5);
}
.whatsapp:hover { background-color: #1ebe5d; }

  </style>
</head>
<body><header>TechStore - Sua Loja Gamer</header><nav>
  <a href="#">Peças PC</a>
  <a href="#">PC Gamer</a>
  <a href="#">Celulares</a>
  <a href="#">Conserto</a>
  <a href="#">Vídeo Games</a>
</nav><div class="container">  <div class="ads">
    <h2>Espaço para Anúncio</h2>
    <p>Google AdSense ou banners aqui</p>
  </div>  <h2>Produtos</h2>
  <div class="grid"><div class="card">
  <img src="https://via.placeholder.com/200" alt="Produto">
  <h3>Placa de Vídeo</h3>
  <p>R$ 1.500</p>
  <button class="btn" onclick="contato('Placa de Vídeo')">Comprar</button>
</div>

<div class="card">
  <img src="https://via.placeholder.com/200" alt="Produto">
  <h3>PC Gamer</h3>
  <p>R$ 4.000</p>
  <button class="btn" onclick="contato('PC Gamer')">Comprar</button>
</div>

<div class="card">
  <img src="https://via.placeholder.com/200" alt="Produto">
  <h3>Celular</h3>
  <p>R$ 1.200</p>
  <button class="btn" onclick="contato('Celular')">Comprar</button>
</div>

<div class="card">
  <img src="https://via.placeholder.com/200" alt="Produto">
  <h3>Console</h3>
  <p>R$ 2.500</p>
  <button class="btn" onclick="contato('Console')">Comprar</button>
</div>

  </div>  <div class="ads">
    <h2>Mais anúncios aqui</h2>
  </div></div><footer>
  © 2026 TechStore - Todos os direitos reservados
</footer><!-- Botão WhatsApp --><a class="whatsapp" href="https://wa.me/5599999999999" target="_blank">💬</a>

<script>
  function contato(produto) {
    const numero = "5599999999999"; // TROQUE PELO SEU NÚMERO
    const mensagem = `Olá, tenho interesse em ${produto}`;
    const url = `https://wa.me/${numero}?text=${encodeURIComponent(mensagem)}`;
    window.open(url, '_blank');
  }
</script></body>
</html>
