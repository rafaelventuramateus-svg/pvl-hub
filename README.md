# pvl-hub

<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PVL Hub | Portuguese Virtual League</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #071426;
      color: white;
    }
    header {
      background: #0d2340;
      padding: 22px;
      border-bottom: 2px solid #168cff;
    }
    .logo { font-size: 25px; font-weight: bold; }
    .logo span { color: #168cff; }
    nav {
      display: flex;
      gap: 18px;
      overflow-x: auto;
      padding-top: 20px;
    }
    nav a {
      color: white;
      text-decoration: none;
      white-space: nowrap;
      font-size: 14px;
    }
    main { padding: 24px; max-width: 1100px; margin: auto; }
    .welcome {
      background: linear-gradient(120deg, #123d70, #087bd0);
      padding: 35px;
      border-radius: 14px;
      margin-bottom: 25px;
    }
    .welcome h1 { margin-top: 0; }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 15px;
    }
    .card {
      background: #10243d;
      border: 1px solid #203b5c;
      border-radius: 12px;
      padding: 20px;
    }
    .card h3 { color: #42a5ff; }
    footer {
      text-align: center;
      padding: 25px;
      color: #8fa7c2;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">PVL <span>HUB</span></div>
    <nav>
      <a href="#inicio">Início</a>
      <a href="#jogos">Jogos</a>
      <a href="#calendario">Calendário</a>
      <a href="#classificacoes">Classificações</a>
      <a href="#clubes">Clubes</a>
      <a href="#teams">Teams</a>
      <a href="#competicoes">Competições</a>
      <a href="#jogador">Área do Jogador</a>
      <a href="#gestao">Gestão da Liga</a>
    </nav>
  </header>

  <main id="inicio">
    <section class="welcome">
      <h1>Bem-vindo ao PVL Hub</h1>
      <p>Portuguese Virtual League — A casa oficial do futebol virtual.</p>
    </section>

    <div class="cards">
      <section class="card" id="jogos">
        <h3>⚽ Jogos</h3>
        <p>Consulta os jogos da liga.</p>
      </section>
      <section class="card" id="calendario">
        <h3>📅 Calendário</h3>
        <p>Vê os próximos encontros.</p>
      </section>
      <section class="card" id="classificacoes">
        <h3>🏆 Classificações</h3>
        <p>Acompanha as duas divisões.</p>
      </section>
      <section class="card" id="clubes">
        <h3>🛡️ Clubes</h3>
        <p>Descobre os clubes da PVL.</p>
      </section>
      <section class="card" id="teams">
        <h3>👥 Teams</h3>
        <p>Diretório de jogadores registados.</p>
      </section>
      <section class="card" id="competicoes">
        <h3>🏅 Competições</h3>
        <p>Consulta as competições oficiais.</p>
      </section>
      <section class="card" id="jogador">
        <h3>👤 Área do Jogador</h3>
        <p>Consulta a tua informação pessoal.</p>
      </section>
      <section class="card" id="gestao">
        <h3>⚙️ Gestão da Liga</h3>
        <p>Área de administração da PVL.</p>
      </section>
    </div>
  </main>

  <footer>© 2026 Portuguese Virtual League · PVL Hub</footer>
</body>
</html>
