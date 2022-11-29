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

História do Anime

<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Kentaro Miura - História do anime</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="../css/base.css" />
    <style>
      .card > h2 {
        text-align: center;
      }
      .card p {
        text-indent: 20px;
      }
    </style>
  </head>
  <body>
    <header>
      <section id="menu-principal">
        <header>
          <img src="../img/logo.png" alt="Logo do site" />
          <span>Kentaro Miura</span>
        </header>
        <nav>
          <a href="../index.html">Home</a>
          <a href="#">História do anime</a>
          <a href="biography.html">Biografia do autor</a>
          <a href="characters.html">Personagens</a>
        </nav>
      </section>
      <nav>
        <a href="../index.html">Página inicial</a>
        <span> > </span>
        <span>História do anime</span>
      </nav>
      <img src="../img/historia.png" alt="Kentaro Miura" class="banner" />
    </header>
    <main>
      <div>
        <h1>História do anime</h1>
      </div>
      <article class="card">
        <p>
          Berserk (ベルセルク Beruseruku?) é uma série de mangá escrita e ilustrada por Kentaro Miura. 
          Situado em um mundo de fantasia sombria inspirado na Europa medieval, a história gira em torno de Guts, 
          um solitário mercenário, e 
          Griffith, o líder de um bando de 
          mercenários chamado de "Bando do Falcão". Miura publicou um one-shot de Berserk em 1988.
        </p>
        <p>
          A série começou a ter os seus capítulos publicados no ano seguinte na 
          agora extinta revista Monthly Animal House, que foi substituída em 1992 pela 
          revista bimestral Young Animal, onde Berserk continua a ser serializado 
          intermitentemente. Miura faleceu em maio de 2021, deixando o destino da publicação do mangá indefinido
        </p>
        <p>
          Berserk foi adaptado em uma série de televisão de anime de 25 episódios 
          pelo estúdio Oriental Light and Magic, que adaptou o arco Era de Ouro e foi exibido de 7 de outubro de 1997 a 31 de março de 1998.
          A Era de Ouro foi novamente adaptada em uma trilogia de filmes; os dois primeiros filmes estrearam em 2012 e o terceiro filme estreou em 2013.
        </p>
        <p>
          Uma segunda adaptação de anime para a televisão de 24 episódios 
          foi transmitida por duas temporadas entre 2016 e 2017.

         Em maio de 2021, o mangá de Berserk tinha mais de 50 milhões de cópias em 
         circulação, incluindo versões digitais, tornando-se uma das séries de mangá mais vendidas de todos os tempos.
        </p>
        <p>
          O mangá recebeu o Prêmio de Excelência na sexta edição do Prêmio Cultural Osamu Tezuka em 2002. Berserk
          foi amplamente aclamado pela crítica, que se destacou pelo seu universo sombrio, qualidade nos desenvolvimento da 
          narrativa e de personagens e, especialmente, pela arte detalhada dos desenhos de Miura.
        </p>
      </article>
    </main>
    <footer>
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
  
  
base.css
  @import url("https://fonts.googleapis.com/css2?family=Raleway:wght@400;600;700&display=swap");

@font-face {
  font-family: "Saiyan-Sans";
  src: url("Saiyan-Sans.ttf");
}

* {
  /* Resetando o CSS padrão */
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Raleway", sans-serif;
}

/* Elementos */

main {
  margin: 0 20px;
}

p {
  font-size: 12px;
  text-indent: 10px;
  margin-bottom: 10px;
}

/* Identificação e classes */
section#menu-principal {
  background-color: #e55e2e;
  padding: 7px 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #ffffff;
}
img.banner {
  width: 100%;
  height: 300px;
  object-fit: cover;
}

article.card {
  border-radius: 10px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.25);
  padding: 10px;
}

/* Hierarquia */
section#menu-principal > header {
  display: flex;
  align-items: center;
}

section#menu-principal > header > span {
  margin-left: 15px;
  font-family: "Saiyan-Sans", serif;
  font-size: 20px;
}

nav > a:link,
nav > a:visited {
  color: #ffffff;
  text-decoration: none;
  font-weight: bold;
  font-size: 14px;
}

header > nav {
  background-color: #fda402;
  padding: 10px;
}

header > nav > span {
  color: #ffffff;
  font-weight: bold;
}

header > nav > a,
header > nav > span {
  font-size: 12px !important;
}

header > nav > span + span {
  text-decoration: underline;
}

main > div {
  background-color: #ac0117;
  padding: 10px;
  border-radius: 5px;
  margin: 30px 0;
}

main > div > h1 {
  color: #ffffff;
  font-size: 20px;
  text-align: center;
}

main h2 {
  color: #7fcb07;
  font-size: 16px;
  margin-bottom: 16px;
}

footer {
  background-color: #e55e2e;
  padding: 10px;
  margin-top: 20px;
}

footer > p {
  text-align: center;
  font-size: 10px;
  color: #ffffff;
  font-weight: bold;
}
  
  @import url("base.css");

main {
  display: grid;
  grid-template-columns: repeat(2,auto);
  grid-template-rows: repeat(2,400px);
  column-gap: 180px;
  row-gap: 40px;
  margin: 50px 70px;
}

.box{
    border: 3px solid #AC0117;
    border-radius: 10px;
    background-size: cover;
    background-position: center;
    position: relative;
}

.box>div{
    background-color: rgba(172, 1, 23,.8);
    padding: 10px;
    position: absolute;
    bottom: 0;
    width: 100%;
}

.box>div>a{
    color: #FFFFFF;
    font-size: 40px;
    font-family: 'Saiyan-Sans', serif;
    text-align: center; /* Só funciona em display block */
    display: block;
}

#box_one{
    background-image: url('../img/historia.png');
}
#box_two{
    background-image: url('../img/akira.png');
}
#box_three{
    background-image: url('../img/personagens.png');
}
#box_four{
    background-image: url('../img/galeria.png');
}
  
 
