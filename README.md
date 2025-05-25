<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Formulário para Virar Staff</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #f9f9f9;
      color: #333;
    }
    h2 {
      text-align: center;
      color: #444;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      max-width: 480px;
      margin: 0 auto;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, textarea, select {
      width: 100%;
      padding: 8px;
      margin-top: 6px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1em;
    }
    button {
      margin-top: 20px;
      width: 100%;
      padding: 12px;
      font-size: 1.1em;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h2>Formulário para Virar Staff</h2>
  <form id="staffForm">
    <label for="nome">Nome ou Nickname:</label>
    <input type="text" id="nome" name="nome" required />

    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="idade" required min="10" max="120" />

    <label for="contato">Contato (Discord, WhatsApp, Email):</label>
    <input type="text" id="contato" name="contato" required />

    <label for="experiencia">Você já foi staff antes? Onde?</label>
    <textarea id="experiencia" name="experiencia" rows="3" required></textarea>

    <label for="tempo">Quanto tempo pode dedicar por semana? (ex: 10 horas)</label>
    <input type="text" id="tempo" name="tempo" required />

    <label for="funcoes">Quais funções gostaria de exercer?</label>
    <select id="funcoes" name="funcoes" required>
      <option value="">Selecione</option>
      <option value="moderacao">Moderação</option>
      <option value="suporte">Suporte</option>
      <option value="eventos">Eventos</option>
      <option value="outros">Outros</option>
    </select>

    <label for="motivacao">Por que quer ser staff?</label>
    <textarea id="motivacao" name="motivacao" rows="4" required></textarea>

    <button type="submit">Enviar</button>
  </form>

  <script>
    document.getElementById('staffForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Formulário enviado! Agora você precisa enviar as respostas para a equipe.'); 
      // Aqui você pode colocar um código para enviar as respostas por email, salvar num servidor etc.
      // Por enquanto só mostra a mensagem mesmo.
      this.reset();
    });
  </script>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Formulário para Virar Staff</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #f9f9f9;
      color: #333;
    }
    h2 {
      text-align: center;
      color: #444;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      max-width: 480px;
      margin: 0 auto;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, textarea, select {
      width: 100%;
      padding: 8px;
      margin-top: 6px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1em;
    }
    button {
      margin-top: 20px;
      width: 100%;
      padding: 12px;
      font-size: 1.1em;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h2>Formulário para Virar Staff</h2>
  <form id="staffForm">
    <label for="nome">Nome ou Nickname:</label>
    <input type="text" id="nome" name="nome" required />

    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="idade" required min="10" max="120" />

    <label for="contato">Contato (Discord, WhatsApp, Email):</label>
    <input type="text" id="contato" name="contato" required />

    <label for="experiencia">Você já foi staff antes? Onde?</label>
    <textarea id="experiencia" name="experiencia" rows="3" required></textarea>

    <label for="tempo">Quanto tempo pode dedicar por semana? (ex: 10 horas)</label>
    <input type="text" id="tempo" name="tempo" required />

    <label for="funcoes">Quais funções gostaria de exercer?</label>
    <select id="funcoes" name="funcoes" required>
      <option value="">Selecione</option>
      <option value="moderacao">Moderação</option>
      <option value="suporte">Suporte</option>
      <option value="eventos">Eventos</option>
      <option value="outros">Outros</option>
    </select>

    <label for="motivacao">Por que quer ser staff?</label>
    <textarea id="motivacao" name="motivacao" rows="4" required></textarea>

    <button type="submit">Enviar</button>
  </form>

  <script>
    document.getElementById('staffForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Formulário enviado! Agora você precisa enviar as respostas para a equipe.'); 
      // Aqui você pode colocar um código para enviar as respostas por email, salvar num servidor etc.
      // Por enquanto só mostra a mensagem mesmo.
      this.reset();
    });
  </script>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Formulário para Virar Staff</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #f9f9f9;
      color: #333;
    }
    h2 {
      text-align: center;
      color: #444;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      max-width: 480px;
      margin: 0 auto;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, textarea, select {
      width: 100%;
      padding: 8px;
      margin-top: 6px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1em;
    }
    button {
      margin-top: 20px;
      width: 100%;
      padding: 12px;
      font-size: 1.1em;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h2>Formulário para Virar Staff</h2>
  <form id="staffForm">
    <label for="nome">Nome ou Nickname:</label>
    <input type="text" id="nome" name="nome" required />

    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="idade" required min="10" max="120" />

    <label for="contato">Contato (Discord, WhatsApp, Email):</label>
    <input type="text" id="contato" name="contato" required />

    <label for="experiencia">Você já foi staff antes? Onde?</label>
    <textarea id="experiencia" name="experiencia" rows="3" required></textarea>

    <label for="tempo">Quanto tempo pode dedicar por semana? (ex: 10 horas)</label>
    <input type="text" id="tempo" name="tempo" required />

    <label for="funcoes">Quais funções gostaria de exercer?</label>
    <select id="funcoes" name="funcoes" required>
      <option value="">Selecione</option>
      <option value="moderacao">Moderação</option>
      <option value="suporte">Suporte</option>
      <option value="eventos">Eventos</option>
      <option value="outros">Outros</option>
    </select>

    <label for="motivacao">Por que quer ser staff?</label>
    <textarea id="motivacao" name="motivacao" rows="4" required></textarea>

    <button type="submit">Enviar</button>
  </form>

  <script>
    document.getElementById('staffForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Formulário enviado! Agora você precisa enviar as respostas para a equipe.'); 
      // Aqui você pode colocar um código para enviar as respostas por email, salvar num servidor etc.
      // Por enquanto só mostra a mensagem mesmo.
      this.reset();
    });
  </script>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Formulário para Virar Staff</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #f9f9f9;
      color: #333;
    }
    h2 {
      text-align: center;
      color: #444;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      max-width: 480px;
      margin: 0 auto;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, textarea, select {
      width: 100%;
      padding: 8px;
      margin-top: 6px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1em;
    }
    button {
      margin-top: 20px;
      width: 100%;
      padding: 12px;
      font-size: 1.1em;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h2>Formulário para Virar Staff</h2>
  <form id="staffForm">
    <label for="nome">Nome ou Nickname:</label>
    <input type="text" id="nome" name="nome" required />

    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="idade" required min="10" max="120" />

    <label for="contato">Contato (Discord, WhatsApp, Email):</label>
    <input type="text" id="contato" name="contato" required />

    <label for="experiencia">Você já foi staff antes? Onde?</label>
    <textarea id="experiencia" name="experiencia" rows="3" required></textarea>

    <label for="tempo">Quanto tempo pode dedicar por semana? (ex: 10 horas)</label>
    <input type="text" id="tempo" name="tempo" required />

    <label for="funcoes">Quais funções gostaria de exercer?</label>
    <select id="funcoes" name="funcoes" required>
      <option value="">Selecione</option>
      <option value="moderacao">Moderação</option>
      <option value="suporte">Suporte</option>
      <option value="eventos">Eventos</option>
      <option value="outros">Outros</option>
    </select>

    <label for="motivacao">Por que quer ser staff?</label>
    <textarea id="motivacao" name="motivacao" rows="4" required></textarea>

    <button type="submit">Enviar</button>
  </form>

  <script>
    document.getElementById('staffForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Formulário enviado! Agora você precisa enviar as respostas para a equipe.'); 
      // Aqui você pode colocar um código para enviar as respostas por email, salvar num servidor etc.
      // Por enquanto só mostra a mensagem mesmo.
      this.reset();
    });
  </script>
</body>
</html>
