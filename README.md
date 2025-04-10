# Nota-certa-site
Aulas de musica
<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nota Certa - Aulas de Música</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Nota Certa</h1>
      <nav>
        <a href="#sobre">Sobre</a>
        <a href="#aulas">Aulas</a>
        <a href="#contato">Contato</a>
      </nav>
    </div>
  </header>  <section class="hero">
    <div class="container">
      <h2>Professor Samuel Schneider</h2>
      <p>Aulas clássicas de violão e teclado, com excelência e tradição musical.</p>
    </div>
  </section>  <section id="sobre" class="container">
    <h2>Sobre</h2>
    <p>Com longa experiência no ensino musical, o Professor Samuel Schneider oferece aulas de violão e teclado em um ambiente acolhedor e personalizado. Método clássico com foco técnico e sensibilidade artística.</p>
  </section>  <section id="aulas" class="container">
    <h2>Aulas</h2>
    <ul>
      <li>Violão erudito e popular</li>
      <li>Teclado com base teórica</li>
      <li>Leitura de partitura e harmonia</li>
      <li>Para iniciantes, intermediários e avançados</li>
    </ul>
  </section>  <section id="contato" class="container">
    <h2>Contato</h2>
    <p>Agende sua aula ou tire dúvidas pelos canais abaixo:</p>
    <ul>
      <li><strong>Instagram:</strong> <a href="https://instagram.com/samuu_schneider" target="_blank">@samuu_schneider</a></li>
      <li><strong>WhatsApp:</strong> <a href="https://wa.me/55991855643" target="_blank">(99) 185-5643</a></li>
    </ul>
    <form>
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required />
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />
      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>  <footer>
    <p>&copy; 2025 Nota Certa - Professor Samuel Schneider</p>
  </footer>
</body>
</html>
Salve esse código como Index.html/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px 0;
}

header {
  background-color: #3d5a80;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  font-size: 2rem;
}

nav {
  margin-top: 10px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin-right: 15px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  background-color: #98c1d9;
  color: #fff;
  padding: 60px 0;
  text-align: center;
}

.hero h2 {
  font-size: 2rem;
  margin-bottom: 10px;
}

section h2 {
  color: #3d5a80;
  margin-bottom: 15px;
  font-size: 1.5rem;
}

ul {
  list-style-type: disc;
  padding-left: 20px;
  margin-top: 10px;
}

form {
  margin-top: 20px;
  display: flex;
  flex-direction: column;
}

form label {
  margin-top: 10px;
  font-weight: bold;
}

form input,
form textarea {
  padding: 10px;
  margin-top: 5px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-family: inherit;
}

form button {
  margin-top: 15px;
  padding: 12px;
  background-color: #3d5a80;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 1rem;
  cursor: pointer;
}

form button:hover {
  background-color: #2e4661;
}

footer {
  text-align: center;
  background-color: #3d5a80;
  color: white;
  padding: 15px 0;
  margin-top: 40px;
  font-size: 0.9rem;
}
