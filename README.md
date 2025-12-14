<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MasterX – O Rei dos Lanches</title>
  <meta name="theme-color" content="#5a2d0c" />
  <style>
    body{margin:0;font-family:Arial,Helvetica,sans-serif;background:#fff;color:#222}
    header{background:#5a2d0c;color:#f5c16c;padding:16px;text-align:center}
    header img{max-width:120px}
    .btn{display:inline-block;margin:8px;padding:12px 18px;border-radius:8px;text-decoration:none;font-weight:bold}
    .primary{background:#f5c16c;color:#5a2d0c}
    .secondary{background:#222;color:#fff}
    section{padding:20px}
    h2{color:#5a2d0c}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
    .card{border:1px solid #eee;border-radius:12px;padding:16px}
    .price{font-weight:bold;color:#5a2d0c}
    footer{background:#222;color:#fff;padding:16px;text-align:center}
    .wa{position:fixed;right:16px;bottom:16px;background:#25d366;color:#fff;padding:14px 18px;border-radius:50px;text-decoration:none;font-weight:bold}
  </style>
</head>
<body>
<header>
  <h1>MasterX – O Rei dos Lanches 👑🍔</h1>
  <p>Embaúba – SP • Praça da Matriz • 18h às 00h</p>
  <a class="btn primary" href="#cardapio">Ver Cardápio</a>
  <a class="btn secondary" href="#club">Entrar no MasterX Club</a>
</header>

<section id="club">
  <h2>👑 MasterX Club</h2>
  <p>A cada <strong>R$100 em compras</strong>, você ganha <strong>10 pontos</strong>. Troque por lanches, porções e descontos exclusivos.</p>
  <p>Níveis: Bronze • Prata • Ouro</p>
</section>

<section id="cardapio">
  <h2>🍔 Cardápio</h2>
  <div class="grid">
    <div class="card"><h3>Rei Clássico</h3><p>Pão, hambúrguer, queijo, alface, tomate e molho.</p><p class="price">R$ 15,00</p></div>
    <div class="card"><h3>Rei Verde</h3><p>Hambúrguer, queijo, alface, tomate, milho e molho.</p><p class="price">R$ 17,00</p></div>
    <div class="card"><h3>Rei Bacon</h3><p>Hambúrguer, queijo, bacon crocante e molho.</p><p class="price">R$ 19,00</p></div>
    <div class="card"><h3>Rei Supremo 👑</h3><p>Hambúrguer, queijo, presunto, bacon, ovo, alface, tomate, milho e molho.</p><p class="price">R$ 24,00</p></div>
  </div>
</section>

<section>
  <h2>🔥 Combos</h2>
  <div class="grid">
    <div class="card"><h3>Combo do Rei</h3><p>Rei Supremo + Batata Média + Refri</p><p class="price">R$ 32,00</p></div>
    <div class="card"><h3>Combo Clássico</h3><p>Rei Clássico + Batata Pequena + Refri</p><p class="price">R$ 26,00</p></div>
    <div class="card"><h3>Combo Bacon Real</h3><p>Rei Bacon + Batata Média + Refri</p><p class="price">R$ 30,00</p></div>
  </div>
</section>

<footer>
  <p>📲 Pedidos pelo WhatsApp: (17) 99742-4680</p>
  <p>© MasterX – O Rei dos Lanches</p>
</footer>

<a class="wa" href="https://wa.me/5517997424680?text=Quero%20fazer%20um%20pedido%20na%20MasterX">WhatsApp</a>
</body>
</html>
