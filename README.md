<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>João Victor | Portfólio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f172a;
      color: #e2e8f0;
    }

    header {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #1e293b, #0f172a);
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      margin-top: 10px;
      opacity: 0.8;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      margin-bottom: 20px;
      color: #38bdf8;
    }

    .skills span {
      display: inline-block;
      background: #1e293b;
      padding: 10px 15px;
      margin: 5px;
      border-radius: 8px;
      border: 1px solid #38bdf8;
      transition: 0.3s;
    }

    .skills span:hover {
      background: #38bdf8;
      color: #0f172a;
    }

    .card {
      background: #1e293b;
      padding: 20px;
      margin: 15px 0;
      border-radius: 10px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 20px rgba(0,0,0,0.5);
    }

    footer {
      text-align: center;
      padding: 20px;
      opacity: 0.6;
    }

    a {
      color: #38bdf8;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <header>
    <h1>👋 João Victor</h1>
    <p>Estudante de ADS – FIAP | Desenvolvedor em evolução 🚀</p>
    <p>Previsão de conclusão: 2026</p>
  </header>

  <section>
    <h2>💻 Sobre mim</h2>
    <p>
      Tenho interesse em desenvolvimento de software e projetos com Arduino.
      Atualmente busco uma oportunidade de estágio para evoluir minhas habilidades na prática.
    </p>
  </section>

  <section>
    <h2>🚀 Tecnologias</h2>
    <div class="skills">
      <span>C++</span>
      <span>HTML</span>
      <span>CSS</span>
      <span>Arduino</span>
      <span>Lógica de Programação</span>
    </div>
  </section>

  <section>
    <h2>📌 Projetos</h2>

    <div class="card">
      <h3>Sistema de Cadastro em C++</h3>
      <p>Aplicação para cadastro de usuários no terminal.</p>
    </div>

    <div class="card">
      <h3>Site Responsivo</h3>
      <p>Projeto web utilizando HTML e CSS com layout responsivo.</p>
    </div>

    <div class="card">
      <h3>Projeto com Arduino</h3>
      <p>Automação com sensores de temperatura, presença e luminosidade.</p>
    </div>

  </section>

  <section>
    <h2>📫 Contato</h2>
    <p>Email: <a href="mailto:seuemail@email.com">seuemail@email.com</a></p>
    <p>Telefone: (11) 99999-9999</p>
  </section>

  <footer>
    <p>⭐ João Victor - Sempre evoluindo na tecnologia</p>
  </footer>

</body>
</html>
