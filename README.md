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

Código html Autor
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Kentaro Miura - Biografia do autor</title>
    <link rel="stylesheet" href="../css/base.css" />
    <style>
      main {
        width: 70vw; /* Cerca de 70% da tela */
        margin: 0 auto;
      }
      #colunas {
        display: flex;
        justify-content: space-between;
      }
      .card:nth-child(1) {
        width: 30%;
      }
      .card:nth-child(2) {
        width: 60%;
      }
      h2{
        text-align: center;
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
          <a href="#">Biografia do autor</a>
          <a href="characters.html">Personagens</a>
        </nav>
      </section>
      <!-- Segunda seção -->
      <nav>
<a href="../index.html">Página inicial</a>
        <span> > </span>
        <span>Biografia do autor</span>
      </nav>
      <!-- Terceira seção -->
      <img src="../img/kentaro.png" alt="Kentaro Miura" class="banner" />
    </header>
    <main>
      <div>
        <h1>Kentaro Miura</h1>
      </div>
      <section id="colunas">
        <article class="card">
          <h2>Curiosidades</h2>
          <p><b>Nome: </b> Kentaro Miura</p>
          <p><b>Data de nascimento: </b> 11/06/1966</p>
          
          <p><b>Outras obras:</b>
             
           Miuranger (1976)
           Ken e no Michi (1977)
           Futanabi (1985)
           Noa (1985)
           Berserk Prototype (1988)
           The King of Wolves (1989)
           Berserk (1989 - 2021)
           Oh-Roh Den (1990)
           Japan (1992)
           Gigantomachia (2013-2014)
           Duranki (2019-2021)
        </p>
        </article>
        <article class="card">
          <h2>Um pouco da história</h2>
          <p>
            Kentarō Miura (三浦 建太郎, Miura Kentarō?) (Chiba, 11 de julho de 1966 - 6 de maio de 2021)
            foi um mangaká japonês. Ele era mais conhecido por sua aclamada série de fantasia sombria Berserk, que 
            começou a ser publicado em 1989 e se estendeu até a data da morte de Miura, em 2021. Em 2021, Berserk 
            tinha mais de 50 milhões de cópias em circulação, tornando-se uma das séries de mangá mais vendidas de 
            todos os tempos. Em 2002, Miura foi consagrado com o Prêmio Cultural Osamu Tezuka.
          </p>
          <p>
            Kentaro Miura nasceu na cidade de Chiba, província de Chiba, Japão, em 1966.
            Em 1976, com a idade de 10 anos, Miura fez seu primeiro mangá, intitulado Miuranger, que 
            foi publicado para seus colegas em uma publicação escolar; o mangá acabou abrangendo 40 volumes.
          </p>
          <p>
            Em 1977, Miura criou seu segundo mangá chamado Ken e no michi (剣 へ の 道 O Caminho para a Espada), usando tinta nanquim pela primeira vez.
            Quando ele estava no ensino médio em 1979, as técnicas de desenho de Miura melhoraram muito quando ele começou a usar técnicas de desenho profissionais.
           Seu primeiro dōjinshi foi publicado, com a ajuda de amigos, em uma revista em 1982.
          </p>
        </article>
      </section>
    </main>
    <footer>
      <p>
      </p>
    </footer>
  </body>
</html>





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
