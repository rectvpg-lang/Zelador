# Zelador<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#1e40af">
  <title>🏢 App Zelador (Offline)</title>
  <link rel="stylesheet" href="css/estilo.css">
  <link rel="manifest" href="manifest.json">
</head>
<body>
  <div class="container">
    <header>
      <h1>🏢 App Zelador</h1>
      <p class="status">✅ Funciona Offline</p>
    </header>

    <nav class="menu-grid">
      <a href="pages/entregas.html" class="menu-item">
        <span class="icone">📦</span>
        <h3>Entregas</h3>
        <p>Controlar encomendas</p>
      </a>
      <a href="pages/visitantes.html" class="menu-item">
        <span class="icone">👥</span>
        <h3>Visitantes</h3>
        <p>Registro de entrada/saída</p>
      </a>
      <a href="pages/avisos.html" class="menu-item">
        <span class="icone">📢</span>
        <h3>Avisos</h3>
        <p>Comunicados</p>
      </a>
      <a href="pages/manutencao.html" class="menu-item">
        <span class="icone">🔧</span>
        <h3>Manutenção</h3>
        <p>Ordens de serviço</p>
      </a>
      <a href="pages/relatorios.html" class="menu-item">
        <span class="icone">📊</span>
        <h3>Relatórios</h3>
        <p>Exportar dados</p>
      </a>
      <a href="pages/config.html" class="menu-item">
        <span class="icone">⚙️</span>
        <h3>Configurações</h3>
        <p>Backup e mais</p>
      </a>
    </nav>
  </div>
  <script type="module" src="js/app.js"></script>
</body>
</html>
