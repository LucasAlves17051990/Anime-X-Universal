# Anime-X-Universal
Nosso projeto conta um pouco sobre a história do autor Kentaro Miura,entre varios de seus projetos destacamos o anime Berserk,que conta história  de Guts, um solitário mercenário, e Griffith, o líder de um bando de mercenários chamado de "Bando do Falcão".

Requisitos Funcionais
• Navegação entre as páginas disponibilizadas pelo menu.
• Botão de Ligar/Desligar a musica de fundo.
Requisitos Não Funcionais
• Conexão com a internet.
• Compatibilidade com Windows.
• Compatibilidade com Smartphones.
• Recursos de acessibilidade para deficientes








Personagens 
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Kentaro Miura- Personagens</title>
    <link rel="stylesheet" href="../css/base.css" />
    <style>
        #colunas{
            display: flex;
            flex-wrap: wrap; /* Permite a quebra de linha */
            justify-content: space-between;
            row-gap: 20px;
        }
        .card{
            display: flex;
            justify-content: space-around;
            width: 340px;
        }
    </style>
  </head>
  <body>
    <header>
      <!-- Primeira seção -->
      <section id="menu-principal">
 <header>
          <img src="../img/logo.png" alt="Logo do site" />
          <span>Kentaro Miura</span>
        </header>
        <nav>
          <a href="../index.html">Home</a>
          <a href="history.html">História do anime</a>
          <a href="biography.html">Biografia do autor</a>
          <a href="#">Personagens</a>
        </nav>
      </section>
      <!-- Segunda seção -->
      <nav>
        <a href="../index.html">Página inicial</a>
        <span> > </span>
        <span>Personagens</span>
      </nav>
      <!-- Terceira seção -->
      <img src="../img/personagens.png" alt="Kentaro Miura" class="banner" />
    </header>
    <main>
      <div>
        <h1>Personagens</h1>
      </div>
<section id="colunas">
        <article class="card">
          <img src="../img/guts.png" alt="Guts" />
          <div>
            <h2>Guts</h2>
            <p><b>Nome: </b> Guts</p>
            <p><b>Gênero: </b> Masculino</p>
          </div>
        </article>
