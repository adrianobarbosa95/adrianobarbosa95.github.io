<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Professor Adriano Barbosa</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f4f6f8; }
    header { background: #1f2937; color: #fff; padding: 30px; text-align: center; }
    header img { width: 140px; height: 140px; border-radius: 50%; object-fit: cover; margin-bottom: 15px; }
    main { max-width: 1000px; margin: auto; padding: 20px; }
    h2 { color: #1f2937; }
    .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; }
    .card { background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,.08); }
    a { text-decoration: none; color: #2563eb; font-weight: bold; }
    footer { text-align: center; padding: 20px; color: #555; }
    select { padding: 8px; margin: 10px 0; }
  </style>
</head>
<body>

<header>
  <img src="foto.jpg" alt="Foto do Professor">
  <h1>Professor Adriano Barbosa</h1>
  <p>Professor de Informática | Ciência da Computação</p>
</header>

<main>
  <section>
    <h2>📌 Meu Perfil</h2>
    <p>Bem-vindo à minha página profissional. Aqui você encontrará minhas disciplinas, materiais de aula, currículo e links importantes.</p>
  </section>

  <section>
    <h2>🔗 Links Importantes</h2>
    <div class="cards">
      <div class="card"><a href="curriculo.pdf" target="_blank">📄 Currículo (PDF)</a></div>
      <div class="card"><a href="disciplinas.html">📚 Disciplinas</a></div>
      <div class="card"><a href="notas.html">📝 Notas</a></div>
      <div class="card"><a href="https://github.com/adrianobarbosa95" target="_blank">💻 GitHub</a></div>
    </div>
  </section>
</main>

<footer>
  © 2026 – Professor Adriano Barbosa
</footer>

</body>
</html>
