<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>João Victor</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: white;
      text-align: center;
    }

    .container {
      padding: 40px 20px;
    }

    h1 {
      font-size: 2.5rem;
      animation: fadeIn 2s ease-in-out;
    }

    h2 {
      color: #38bdf8;
      margin-top: 40px;
    }

    p {
      max-width: 600px;
      margin: 10px auto;
      opacity: 0.9;
    }

    .card {
      background: rgba(255,255,255,0.05);
      padding: 20px;
      margin: 15px auto;
      border-radius: 15px;
      width: 300px;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
      background: rgba(255,255,255,0.1);
    }

    .skills span {
      display: inline-block;
      background: #38bdf8;
      color: black;
      padding: 8px 12px;
      margin: 5px;
      border-radius: 10px;
      font-weight: bold;
      transition: 0.3s;
    }

    .skills span:hover {
      background: #0ea5e9;
      transform: translateY(-3px);
    }

    a {
      color: #38bdf8;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(-20px);}
      to {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>

<body>
  <div class="container">

    <h1>👋 Olá, eu sou João Victor</h1>

    <p>🎓 Estudante de Análise e Desenvolvimento de Sistemas – FIAP</p>
    <p>📅 Previsão de conclusão: 2026</p>
    <p>💻 Apaixonado por tecnologia, desenvolvimento e projetos com Arduino</p>
    <p>🚀 Em busca de estágio na área de tecnologia</p>

    <h2>🚀 Tecnologias</h2>
    <div class="skills">
      <span>C++</span>
      <span>HTML</span>
      <span>CSS</span>
      <span>Arduino</span>
      <span>Lógica</span>
    </div>

    <h2>📌 Projetos</h2>

    <div class="card">
      <h3>💻 Sistema de Cadastro</h3>
      <p>Aplicação em C++ para cadastro de usuários no terminal.</p>
    </div>

    <div class="card">
      <h3>🌐 Site Responsivo</h3>
      <p>Projeto web com HTML e CSS com layout moderno.</p>
    </div>

    <div class="card">
      <h3>🔌 Arduino</h3>
      <p>Automação com sensores de temperatura, presença e luz.</p>
    </div>

    <h2>📫 Contato</h2>
    <p>Email: <a href="mailto:seuemail@email.com">seuemail@email.com</a></p>
    <p>Telefone: (11) 97551-3884 </p>

    <p style="margin-top:40px; opacity:0.7;">
      ⭐ Sempre evoluindo na área de tecnologia
    </p>

  </div>
</body>
</html>
