<!doctype html>
<html lang="pt-br">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/compiler/bootstrap.css">
    <link rel="stylesheet" href="node_modules/bootstrap/compiler/style.csss">

    <title>Desperte o seu DOM</title>
  </head>
  <body>
      <!-- MENU superior -->
      <nav class="navbar navbar-expand-lg navbar-dark bg-gradient-secondary">

        <div class="container"><!-- Faz o menu ficar no meio, do tamanho do site. -->

          <!-- Nome DOM -->
          <a class="navbar-brand h1 mb-0" href="index.html">DOM</a>

          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSite">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSite">
            
            <!-- Menu à direita com lista horizontal.-->
            <ul class="navbar-nav mr-auto">
            
              <li class="navbar-iten">
                <a class="nav-link" href="">Início</a>
              </li>
            
              <li class="navbar-iten">
                <a class="nav-link" href="">Perfil</a>
              </li>
            
              <li class="navbar-iten">
                <a class="nav-link" href="">Cursos</a>
              </li>
            
              <li class="navbar-iten">
                <a class="nav-link" href="">Depoimentos</a>
              </li>
            
              <li class="navbar-iten">
                <a class="nav-link" href="">Contato</a>
              </li>
            
            </ul>
          
            <!-- Menu dropdown a esquerda (ml-auto)-->
            <ul class="navbar-nav ml-auto">

              <li class="navbar-iten dropdown">
                
                <!-- Nome do link aparente do dropdown-->
                <a class="nav-link dropdown-toggle" data-toggle="dropdown" id="dropDown" href="">
                  Entrar
                </a>

                <!-- Opções do dropdown-->
                <div class="dropdown-menu">
                  
                  <a class="dropdown-item" href="">Login</a>
                  <a class="dropdown-item" href="">Registrar</a>
                 
                </div>
              </li>
   
            </ul>

            <form class="form-inline">
              <input class="form-control ml-2 mr-2" type="search" placeholder="Buscar...">
              <button class="btn btn-danger" type="submit">OK</button> 
            </form>

          </div>

        </div>

      </nav>

      <!-- CAROUSEL -->
      <div id="carouselSite" class="carousel slide" data-ride="carousel">

        <!-- Indicador de qual imagem está mostrando -->
        <ol class="carousel-indicators">
          <li data-target="#carouselSite" data-slide-to="0" class="active"></li>
          <li data-target="#carouselSite" data-slide-to="1"></li>
          <li data-target="#carouselSite" data-slide-to="2"></li>
          <li data-target="#carouselSite" data-slide-to="3"></li>
        </ol>

        <!-- Conjunto de imagens do Carousel -->
        <div class="carousel-inner">

          <!-- Imagens Carousel -->
          <div class="carousel-item active">
            <img class="img-fluid d-block" src="imagens/img1.jpg">
            <div class="carousel-caption d-none d-md-block">
                <h1>Aulas online</h1>
                <p>Aulas online no conforto da sua casa em tempo real com o instrutor.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img class="img-fluid d-block" src="imagens/img2.jpg">
            <div class="carousel-caption d-none d-md-block">
              <h1>Aulas online</h1>
              <p>Aulas online no conforto da sua casa em tempo real com o instrutor.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img class="img-fluid d-block" src="imagens/img3-mine.jpg">
            <div class="carousel-caption d-none d-md-block">
              <h1>Aulas online</h1>
              <p>Aulas online no conforto da sua casa em tempo real com o instrutor.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img class="img-fluid d-block" src="imagens/img4.jpg">
            <div class="carousel-caption d-none d-md-block">
              <h1>Aulas online</h1>
              <p>Aulas online no conforto da sua casa em tempo real com o instrutor.</p>
            </div>
          </div>
         
          <!-- Controle ANTERIOR do Carousel-->
          <a class="carousel-control-prev" href="#carouselSite" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
            <span class="sr-only">Anterior</span>
          </a>

          <!-- Controle AVANÇAR do Carousel-->
          <a class="carousel-control-next" href="#carouselSite" role="button" data-slide="next">
            <span class="carousel-control-next-icon"></span>
            <span class="sr-only">Avançar</span>
          </a>

        </div>

      </div>

      <!-- Texto abaixo do Carousel -->
      <div class="container">

        <div class="row">
        
          <div class="col-12 text-center my-5">
        
            <h1 class="display-3">Seja bem vindo!</h1>
            <p>
              É um fato conhecido de todos que um leitor se distrairá com o conteúdo de texto legível de uma página quando estiver examinando sua diagramação. A vantagem de usar Lorem Ipsum é que ele tem uma distribuição normal de letras, ao contrário de "Conteúdo aqui, conteúdo aqui", fazendo com que ele tenha uma aparência similar a de um texto legível. Muitos softwares de publicação e editores de páginas na internet agora usam Lorem Ipsum como texto-modelo padrão, e uma rápida busca por 'lorem ipsum' mostra vários websites ainda em sua fase de construção. Várias versões novas surgiram ao longo dos anos, eventualmente por acidente, e às vezes de propósito (injetando humor, e coisas do gênero).
            </p>
          
          </div>
        
        </div>

        <div class="row">
          
          <div class="col-3">
          
            <nav id="navbarVertical" class="navbar navbar-light bg-light">
              
              <nav class="nav nav-pills flex-column">
                
                <a class="nav-link" href="#item1">Lorem Ipsum1</a>
                <!--Subtítulo:-->
                <nav class="nav nav-pills flex-column">
                  <a class="nav-link ml-3" href="#item1-1">Lorem Ipsum1-1</a>
                  <a class="nav-link ml-3" href="#item1-2">Lorem Ipsum1-2</a>
                </nav>

                <a class="nav-link my-2" href="#item2">Lorem Ipsum2</a>

                <a class="nav-link my-2" href="#item3">Lorem Ipsum3</a>
                <!--Subtítulo:-->
                <nav class="nav nav-pills flex-column">
                  <a class="nav-link ml-3" href="#item3-1">Lorem Ipsum3-1</a>
                  <a class="nav-link ml-3" href="#item3-2">Lorem Ipsum3-2</a>
                </nav>

              </nav>

            </nav>
          </div>

          <!-- Bloco de conteúdo referente ao menu vertical lateral -->
          <div class="col-9">

            <div data-spy="scroll" data-target="#navbarVertical" data-offset="0">

              <h4 id="item1">Verdades da Profissão de Professor</h4>
              <p>Ninguém nega o valor da educação e que um bom professor é imprescindível. Mas, ainda que desejem bons professores para seus filhos, poucos pais desejam que seus filhos sejam professores. Isso nos mostra o reconhecimento que o trabalho de educar é duro, difícil e necessário, mas que permitimos que esses profissionais continuem sendo desvalorizados. Apesar de mal remunerados, com baixo prestígio social e responsabilizados pelo fracasso da educação, grande parte resiste e continua apaixonada pelo seu trabalho.
              A data é um convite para que todos, pais, alunos, sociedade, repensemos nossos papéis e nossas atitudes, pois com elas demonstramos o compromisso com a educação que queremos. Aos professores, fica o convite para que não descuidem de sua missão de educar, nem desanimem diante dos desafios, nem deixem de educar as pessoas para serem “águias” e não apenas “galinhas”. Pois, se a educação sozinha não transforma a sociedade, sem ela, tampouco, a sociedade muda.</p>
              <h5 id="item1-1">Virtudes</h5>
              <p>Sem certas qualidades ou virtudes como amorosidade, respeito aos outros, tolerância, humildade, gosto pela alegria, gosto pela vida, abertura ao novo, disponibilidade à mudança, persistência na luta, recusa aos fatalismos (...) abertura à justiça, não é possível a prática pedagógico-progressista, que não se faz apenas com ciência e técnica.</p>
              <h5 id="item1-2">Dedicatória aos meus alunos</h5>
              <p>Eis o meu maior compromisso contigo Fazer com que sintas que muito para além de aluno/a, és também um ser humano e que, nestas duas dimensões, tens deveres aos quais deves respeitar, mas também tens direitos que nem eu nem ninguém poderá nunca, ignorar ou desrespeitar!
              Fazer com que aprendas muito mais que a ler, a escrever e a contar…Essas aprendizagens não necessitam de grandes mestres!
              Quero ensinar-te para além disso tudo, que tens dons especiais que fazem toda a diferença entre ti e os outros…por isso, és imprescindível na sociedade: ÚNICO/A e muito importante para todos.
              Fazendo com que te reconheças como parte muito importante da sociedade em que vives, compreenderás que como cidadão da mesma, tens o direito a intervir, participar e escolher com confiança e conhecimento, o tipo de sociedade que te faz verdadeiramente feliz!
              Para além do muito que desejo ajudar-te a SER um ser humano muito feliz, quero acima de tudo que sejas TU PRÓPRIO/A, com os teus sonhos e desejos…com o teu sorriso e as tuas lágrimas…as tuas alegrias e tristezas… os teus medos e esperanças…mas sempre uma criança sem medo de falar, de sentir, de SER exatamente como és!</p>
            
              <h4 id="item3">Lorem Ipsum 3</h4>
              <p>Ninguém nega o valor da educação e que um bom professor é imprescindível. Mas, ainda que desejem bons professores para seus filhos, poucos pais desejam que seus filhos sejam professores. Isso nos mostra o reconhecimento que o trabalho de educar é duro, difícil e necessário, mas que permitimos que esses profissionais continuem sendo desvalorizados. Apesar de mal remunerados, com baixo prestígio social e responsabilizados pelo fracasso da educação, grande parte resiste e continua apaixonada pelo seu trabalho.
              A data é um convite para que todos, pais, alunos, sociedade, repensemos nossos papéis e nossas atitudes, pois com elas demonstramos o compromisso com a educação que queremos. Aos professores, fica o convite para que não descuidem de sua missão de educar, nem desanimem diante dos desafios, nem deixem de educar as pessoas para serem “águias” e não apenas “galinhas”. Pois, se a educação sozinha não transforma a sociedade, sem ela, tampouco, a sociedade muda.</p>
              <h5 id="item3-1">Lorem 3-1</h5>
              <p>Sem certas qualidades ou virtudes como amorosidade, respeito aos outros, tolerância, humildade, gosto pela alegria, gosto pela vida, abertura ao novo, disponibilidade à mudança, persistência na luta, recusa aos fatalismos (...) abertura à justiça, não é possível a prática pedagógico-progressista, que não se faz apenas com ciência e técnica.</p>
              <h5 id="item3-2">Lorem 3-2</h5>
              <p>Eis o meu maior compromisso contigo Fazer com que sintas que muito para além de aluno/a, és também um ser humano e que, nestas duas dimensões, tens deveres aos quais deves respeitar, mas também tens direitos que nem eu nem ninguém poderá nunca, ignorar ou desrespeitar!
              Fazer com que aprendas muito mais que a ler, a escrever e a contar…Essas aprendizagens não necessitam de grandes mestres!
              Quero ensinar-te para além disso tudo, que tens dons especiais que fazem toda a diferença entre ti e os outros…por isso, és imprescindível na sociedade: ÚNICO/A e muito importante para todos.
              Fazendo com que te reconheças como parte muito importante da sociedade em que vives, compreenderás que como cidadão da mesma, tens o direito a intervir, participar e escolher com confiança e conhecimento, o tipo de sociedade que te faz verdadeiramente feliz!
              Para além do muito que desejo ajudar-te a SER um ser humano muito feliz, quero acima de tudo que sejas TU PRÓPRIO/A, com os teus sonhos e desejos…com o teu sorriso e as tuas lágrimas…as tuas alegrias e tristezas… os teus medos e esperanças…mas sempre uma criança sem medo de falar, de sentir, de SER exatamente como és!</p>

            </div>

          </div>

        </div>

      </div>


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="node_modules/jquery/dist/jquery.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.js"></script>
  </body>
</html>
