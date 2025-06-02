<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
  <link rel="stylesheet" href="style.css" />
  <title>portifólio</title>
</head>

<body>
  <header class="container text-center">
    <img src="./images.jpg" alt="avatar do Isaque" class="rounded-circle" width="150" height="150" srcset="">
    <p class="lead"> Eu sou Isaque Melo Montoski</p>
    <h1>Eu estou estudando Programação</h1>
    <p>Sou um estudante no ensino médio e já trabalhei com desenvolvimento
      web, scratch, CSS, HTML e Java Script. Veja os projetos que já desenvolvi!
    </p>
    <p>Minhas qualidades</p>
    <div>
      <p class="badge bg-secondary">Focado</p>
      <p class="badge bg-secondary">Prestativo</p>
      <p class="badge bg-secondary">persistente</p>
      <p class="badge bg-secondary">sociável</p>
    </div>
  </header>
  <main class="container mt-5">
    <h2>Meus projetos</h2>
    <div class="row">
      <!-- projeto 1 -->
      <div class="col-md-4">
        <div class="card">
          <img src="imagem_post_desenvolvimento_web.jpg" class="card-img-top"
            alt="Imagem do projeto Desenvolvimento Web">
          <div class="card-body">
            <h5 class="card-title">Desenvolvimento Web:Protótipo de baixa e alta fidelidade</h5>
            <p class="card-text">Esse projeto é um protótipo de alta fidelidade que fiz de uma rede social de animais de
              estimação, como gatos, cachorros e coelhos.
            </p>
            <button type="button" class="btn btn-info" data-bs-toggle="modal" data-bs-target="#modal1">Veja
              mais</button>
          </div>
        </div>
        <!-- projeto 2 -->
        <div class="col-md-4">
          <div class="card">
            <img src="images.png" class="card-img-top" alt="Imagem de um modelo de ping pong no scratch">
            <div class="card-body">
              <h5 class="card-title">Jogo Ping Pong no Scratch</h5>
              <p class="card-text">Esse projeto é um jogo de Ping Pong clássico que fiz com ajuda da plataforma Scratch.
                Pode ser jogado com as setas do computador e para não se perder, têm um marcador de pontos para mostrar
                quem está ganhando.
              </p>
            </div>
            <button type="button" class="btn btn-info" data-bs-toggle="modal" data-bs-target="#modal2">Veja
              mais</button>
          </div>
        </div>
      </div>
      <!-- projeto 3 -->
      <div class="col-md-4">
        <div class="card">
          <img src="images (1).png" class="card-img-top" alt="Imagem de sugerir filmes">
          <div class="card-body">
            <h5 class="card-title">Sugestão de filmes INCRÍVEIS e que todo mundo gosta</h5>
            <p class="card-text">Esse é um projeto que fiz para ajudar as pessoas que não conseguem achar filmes bons
              para assistir. Esse projeto vai sugerir os filmes com base no gênero favorito e pela idade.
            </p>
            <button type="button" class="btn btn-info" data-bs-toggle="modal" data-bs-target="#modal3">Veja
              mais</button>
          </div>
        </div>
      </div>
    </div>
  </main>

  <!-- Modal1 -->
  <div class="modal" id="modal1" tabindex="-1">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Desenvolvimento Web:Protótipo de baixa e alta fidelidade</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <p>O projeto é uma página web que mostra uma rede social sobre animais de extimação. Mostra os alimentos
            adequados para os animais, sabor de petiscos que eles mais gostam.</p>
          <p>Nessa rede social, outros usuários postam e compartilham fotos de seus bixinhos para outras pessoas verem,
            as pessoas também dão dicas, como por exemplo: Essa é a melhor ração para o seu cachorro para ele ter uma
            alimantação saudável, balanceada, rica em nutrientes e vitaminas.</p>
          <img src="social-card.png" class="img-fluid w-100"
            alt="Imagem representativa de uma rede social sobre animais de extimação">
        </div>
        <div class="modal-footer">
          <a href="">Ver projeto ao vivo</a>
          <a href="">Ver código do projeto</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Modal2 -->
  <div class="modal" id="modal2" tabindex="-1">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Jogo Ping Pong no Scratch</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <p>Esse projeto é baseado no famoso e popular jogo Ping Pong. O jogo é apenas na vertical, ou seja, é usada
            somente duas teclas, uma para cima e outra para baixo.</p>
          <p>O jogador joga contra o próprio computador e os pontos são computados quando é marcado um ponto. Quem fizer
            a maior quantidade de pontos vence. Mesmo que não dê para jogar 2 jogadores um contra o outro, podem se
            divertirem brincando de quem faz mais pontos em menos tempo por exemplo.</p>
          <img src="jogo do Pong.gif" class="img-fluid w-100" alt="Imagem do projeto Jogo Pong">
        </div>
        <div class="modal-footer">
          <a href="">Ver projeto ao vivo</a>
          <a href="">Ver código do projeto</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Modal3 -->
  <div class="modal" id="modal3" tabindex="-1">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Sugestão de filmes INCRÍVEIS e que todo mundo gosta</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <p>Esse projeto foi feito para pessoas que querem assistir um filme, mas não conseguem escolher nenhum, pois
            não chamam tanta atenção. </p>
          <p>Essa páginas é dividida em 2 partes: Gêneros como romance, ação, aventura, terror, suspence, comédia entre
            outros e Classificação indicativa. Na parte dos gêneros, a pessoa coloca seu favorito e será   sugerido um
            filme com base a opção de gênero que foi escolhido. Na parte da classificação indicativa, a pessoa coloca sua
            idade e é sugerido um filme com base na idade que foi inserida, tendo vários tipos de filme para cada idade,
            de crianças até adultos.</p>
          <img src="images (1).jpg" class="img-fluid w-100" alt="Imagem representativa de pessoa procurando m filme">
        </div>
        <div class="modal-footer">
          <a href="">Ver projeto ao vivo</a>
          <a href="">Ver código do projeto</a>
        </div>
      </div>
    </div>
  </div>

  <footer class="container py-5">
    <h2>Entre em contato</h2>
    <div>
      <i class="bi bi-github"></i>
      <a href="https://github.com/IsaqueMELOSO">GitHub</a>
    </div>
    <p class="my-5 text-center">Copyright 2025. Produzido por Isaque Melo Montoski</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>