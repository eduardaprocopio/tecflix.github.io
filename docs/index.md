<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style/main.css">

    <!--Responsividade-->
    <link rel="stylesheet" href="style/responsivo.css">

    <!--Owl CSS-->
    <link rel="stylesheet" href="style/owl/owl.carousel.min.css">
    <link rel="stylesheet" href="style/owl/owl.theme.default.min.css">

    <title>Tecnoflix</title>
</head>
<body>
    <header>
        <div class="container">
            <h2 class="logo">TECFLIX</h2>
            <nav>
                <a href="#">Início</a>
                <a href="#">Filmes</a>
                <a href="#">Séries</a>
                <a href="#">Documentários</a>
            </nav>
        </div>
    </header>
    <main>
        <div class="filme-principal">
            <div class="container">
                <h3 class="titulo">SILICON VALLEY</h3>
                <p class="descricao">Ambientada no Vale do Silício, região da Califórnia fértil em inovações 
                    tecnológicas e científicas, a série mostra um grupo de desenvolvedores que cria novo um 
                    programa com o objetivo de impressionar um bilionário excêntrico do ramo tecnológico.</p>
                <div class="botoes">
                    <button role="button" class="botao">
                        <i class="fas fa-play"></i>
                        ASSISTIR AGORA
                    </button>
                    <button role="button" class="botao">
                        <i class="fas fa-info-circle"></i>
                        MAIS INFORMAÇÕES
                    </button>
                </div>
            </div>
        </div>
    </main>

    <div class="carrosel">
        <div class="owl-carousel owl-theme">
            <div class="item">
                <img class="box-filme" src="img/capa1.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa2.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa3.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa4.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa5.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa6.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa7.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa8.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa9.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa10.jpg">
            </div>
        </div>
    </div>
    <div class="carrosel">
        <div class="owl-carousel owl-theme">
            <div class="item">
                <img class="box-filme" src="img/capa11.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa12.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa13.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa14.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa15.jpg">
            </div>
            <div class="item">
                <img class="box-filme" src="img/capa16.jpg">
            </div>
        </div>
    </div>

    <script src="https://kit.fontawesome.com/aaf8e39ac3.js" crossorigin="anonymous"></script>
    <script src="js/owl/jquery.min.js"></script>
    <script src="js/owl/owl.carousel.min.js"></script>
    <script src="js/setup.js"></script>

</body>
</html>
