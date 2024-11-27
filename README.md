# FINAL-DO-PROJETO-DO-ALURA-
26.11.2024
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Meu portifólio</title>
</head>
<body>
    <header class="container">
    <img src="img/avatar-perfil.png" class="rounded-circle" width="150"  alt="avatar de Sabrina" srcset="">
<p class="lead">Eu sou Sabrina Kelly da Cruz Camargo</p>
    <h1>Eu estou estudando programação básica</h1>
    <p>Sou aluna do ensino médio.
        E eu estou recebendo conhecimento constante 
        nas aulas de programação. 
        Atualmente, estou aprendendo a fazer web sites
        através da lìngua de programação Html e Css.</p>
<p>Minhas capacidades em programar</p>
<div>
    <p class="badge text-bg-secondary"> HTML</p>
    <p class="badge text-bg-secondary">CSS</p>
    <p class="badge text-bg-secondary">JavaScript</p>
    <p class="badge text-bg-secondary">Scratch</p>
</div>
    </header>
</body>
</html>
<main class="container mt-5">
    <h2>Meus projetos</h2>
    <div class="row">
        <!--projeto 1-->
        <div class="modal" id="modal1" tabinex="-1">
            <div class="modal-dialog">
                <div class="modal-content">
        <div class="modal-header">
        <h5 class="modal-title">Minha biblioteca: uma webpage personalizada</h5>
        <button type="button" class="btn-close" data-bs-dimiss="modal" aria-label="close"></button>
        </div>
        <div class="modal-body">
            <p>O projeto é uma pagina web criada com HTML e CSS destinada a exibir uma coleção 
                pessoal de livros favoritos. O objetivo é criar um ambiente virtual onde seja possivel
                compartilhar seus livros preferidos, fornecendo uma descrição breve de cada um,
                incluindo o autor, ano de publicação e uma opção de compra.</p>
                <p>A estrutura do site é baseada em HTML, que define a semântica e o layout do conteudo,
                    enquanto o CSS é usado para estilizar a página visualmente,incluindo 
                    cores, tipografia e a disposição dos elementos.</p>
                    <p>O HTML organiza o conteúdo em um cabeçalho com o título site, seguido por uma
                        divisão principal(.container) que apresenta o propósito do site e a coleção de 
                        livros em uma seção flexível(.livros). Cada livro é destacado em seu próprio conteiner
                        (.livros), mostrando um imagem de capa, detalhes do livro e um link de compra. O 
                        desing responsivo é garantido pelo uso de uma tag viewport e um flexivel que 
                        se adapta a diferentes tamanhos de tela.</p>
            <p>
                        <p>O CSS personalisa o visual do site, usando variáveis para cores, estilizando o 
                            texto com uma fonte importada do Google Fonts e aplicando um esquema de cores 
                            suaves e botões interatovos. O uso de HTML e CSS é importante pois assim é possivel
                            criar um site acessivel e esteticamente agradável sem a necessidade de scripts
                            completos, com foco na usabilidade e na experiência da pessoa usuària. A escolha 
                            de tipografia e do esquema de cores contribui para a atmosfera acolhedora do site,
                            incentivando a exploração da coleção de livros.</p>
        </div>
        <div class="modal-footer">
            <butoon type="butoon" class="bnt bnt-secondary" data-bs-dimiss="modal">Close</butoon>
            <butoon type="butoon" class="btn btn-primary">Save changes</butoon>
        </div>
        <div class="modal-footer">
            <a href="">Ver projeto ao vivo</a>
            <a href="">Ver código do projeto</a>
        </div>
        <p class="card-text">Este projeto e uma pagina web que apresenta uma lista dos
             meus livros favoritos,incluindo informações sobre os autores, datas de publicação e links 
             para comprar na amazon.  a página é estilizada com CSS para  uma visualização agradável e 
            usa fontes externas no Google Fonts.</p>
        <button type="button" class="bnt bnt-link" data-bs-toogle="modal" data-bs-target="#modal1">Veja o projeto</button>
    </div>
    </div>
</div>
 <!--projeto 2-->
 <div class="modal" id="modal2" tabindex="-1">
    <div class="card">
    <div class="card-body">
    <h5 class="modal-title">Decidindo o Futuro: Uma jornada interativa sobre Inteligencia Artificial</h5>
    <p class="card-text">O projeto consiste em uma aplicação web interativa, desenvolvida com HTML, CSS
         e JavaScript, que simula uma experiência narrativa centrada no tema da Inteligencia
        Artificial. O objetivo é engajar os jogadores em um cenario ficticio que aborda o avanço
    da IA e suas possiveis consequencias para a humanidade, destacando a importancia da 
reflexão ética sobre a tecnologia.</p>
<p>O HTML estrutura o conteúdo da pagina, dividindo-o em seções como a tela inicial,
    caixa de perguntas, alternativas de resposta, e o resultado final baseado nas escolhas
    do jogador. O CSS é utilizado para estilizar a pagina, empregando um esquema de cores
    futurista e layout responsivo para melhorar a experiencia do usuario.
    JavaScript é adicionado para adicionar ao jogo, manipulando o DOM para 
    atualizar o conteudo da pagina conforme as escolhas do jogador, e determinando o fluxo
    da narrativa através de uma série de perguntas e respostas.</p>
    <p>O HTML organiza o conteudo em um cabeçalho com o titulo do site, seguido por 
        uma divisão principal (.container) que apresenta o propósito do site e coleção de 
        livros em uma seção flexível (.livros). Cada livro é destacado em seu próprio conteiner
        (.livros), mostrando uma imagem da capa, detalhes do livro e um link de compra.O desing
        responsivo é garantido pelo uso de uma meta tag viewport e um layout flexível que se 
        adapta a diferentes tamanhos de tela. </p>
        <p>Os scripts JavaScript incluem módulos para gerar nomes aletórios, definir
            as perguntas e aslógicas de jogo, como iniciar o jogo, apresentar perguntas e 
            alternativas, processr as escolhas dos jogadores, e exibir o rsultado final. Este 
            design modular facilita a manutenção e a expansão futura do jogo. A importancia das 
            ferramentas utilizadas (HTML, CSS JavaScript) reside na criação de uma experiência 
            interativa que não apenas entretém, mas também educa os jogadores sobre a complexidade 
            ética e social de IA, incentivando a reflexão crítica sobre o papel de tecnologia em
            nossas vidas.</p>
        <img src="img/projeto-2.png" class="img-fluid w-100" alt="Projeto 2">
        <div class="modal -'footer'">
            <a href="https://github.com/SthefannyS2/Projeto-5--terceiro-trimestre-.git">Ver projeto</a>
            <a href="https://github.com/SthefannyS2/Projeto-5--terceiro-trimestre-.git">Ver codigo do projeto</a>
        </div>
    <button type="button" class="bnt bnt-link"data-bs-toogle="modal" data-bs-target="modal2">Veja o projeto</button>
    </div>
    </div>
 </div>
 <!--projeto 3-->
 <div class="col-md-4">
    <div class="card">
    <img src="img/projeto-1.png" class="card-img-top" alt="imagem do projeto de biblioteca">
    <div class="card-body">
    <h5 class="card-title">Minha biblioteca: uma webpage personalizada</h5>
    <p class="card-text">Este projeto e uma pagina web que apresenta uma lista dos
         meus livros favoritos,incluindo informações sobre os autores, datas de publicação e links 
         para comprar na amazon.  a página é estilizada com CSS para  uma visualização agradável e 
        usa fontes externas no Google Fonts.</p>
    <button type="button" class="bnt bnt-link"data-bs-toogle="modal" data-bs-target="modal3">Veja o projeto</button>
    </div>
    </div>
 </div>
    </div>
</main>
<footer class="container">
    <h2>Entre em contato.</h2>
    <div>
        <a href=""http://github.com/femaschetil"">github</a>
        <p class="my-5 text-center">copyright 2024, produzido por aluna Sabrina Kelly da Cruz Camargo.</p>
</footer>
</body>
</html>
