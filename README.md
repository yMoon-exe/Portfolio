<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="icon" type="image/png" sizes="35x35" href="imagens/hcbsjdc.png">
    <title>Portfólio</title>
    <style>
        body {
            background-color: #ffffff;
            overflow-x: hidden;
        }

        #boasvindas {
            font-size: 20pt;
            padding: 100px;
            margin-top: 25%;
        }

        .sbm img {
            width: 100%;
            margin-top: 0;
        }

        #sobremim {
            font-size: 18pt;
            margin-left: 40%;
            margin-top: 50%;
        }


        #projetos {
            margin-top: 50%;
            margin-left: 5%;
        }

        .p1,
        .p2,
        .p3,
        .p4,
        .p5,
        .p6,
        .p7,
        .p8 {
            margin-right: 15px;
            width: 290px;
            margin-left: 5%;
            height: 160px;
            background-color: rgb(75, 75, 75);
            border-radius: 20px;
            color: #ffffff;
            display: flex;
            align-items: center;
            justify-content: center;
            text-transform: uppercase;
            opacity: 1;
            transition: opacity 0.5s;
        }

        .p1:hover,
        .p2:hover,
        .p3:hover,
        .p4:hover,
        .p5:hover,
        .p6:hover,
        .p7:hover,
        .p8:hover {
            background-color: rgb(36, 36, 36);
        }

        .p5,
        .p6,
        .p7,
        .p8 {

            margin-top: 30px;
            opacity: 0;
        }

        .btnvermais {
            margin-top: 50px;
            width: 300px;
            height: 40px;
            background-color: #a1ecfc;
            border: none;
            border-radius: 10px;
            text-transform: uppercase;
            font-family: 'Arial';
        }

        .btnvermais:hover {
            background-color: #60d8f3;
        }

        .contatos {
            background-color: #a1ecfc;
            min-width: 100%;
            height: 250px;
            margin-top: 30%;
        }

        #competencias {
            margin-top: 50%;
        }

        #iconsC {
            cursor: pointer;
            display: flex;
            flex-direction: row;
        }

        #iconsC img {
            width: 70px;
        }

        .info {
            font-size: 20pt;
        }

        .navbar-brand,
        .nav-link,
        .dropdown-item {
            font-size: 1.3rem;
        }

        .iconperfil img {
            width: 250px;
            margin-top: 62%;
            margin-left: 10%;
        }

        #ulcontatos {
            list-style-type: none;
            padding: 30px;
        }

        #ctts {
            padding: 30px;
        }

        .html:hover {
            transform: translateY(-2px);
            cursor: pointer;
        }

        .js:hover {
            transform: translateY(-2px);
            cursor: pointer;
        }

        .css:hover {
            transform: translateY(-2px);
            cursor: pointer;
        }

        .git:hover {
            transform: translateY(-2px);
            cursor: pointer;
        }

        .gth:hover {
            transform: translateY(-2px);
            cursor: pointer;
        }

        .php:hover {
            transform: translateY(-2px);
            cursor: pointer;
        }
    </style>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light fixed-top" style="background-color: #a1ecfc;">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"><img src="imagens/ldbçjkbckçjsdc.png" width="175px"></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
                aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Início</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#sobremim">Sobre Mim</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#competencias">Competências</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projetos">Projetos</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="" id="navbarDropdownMenuLink" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            Contatos
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <li><a class="dropdown-item" href="https://github.com/yMoon-exe" target="_blank">GitHub</a>
                            </li>
                            <li><a class="dropdown-item"
                                    href="https://www.linkedin.com/in/let%C3%ADcia-almeida-7941b429b/"
                                    target="_blank">LinkedIn</a></li>
                            <li><a class="dropdown-item" href="#ulcontatos">Ver Mais...</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container">

        <div class="header">

            <div class="row">
                <div class="col" id="boasvindas">Olá! Seja bem-vindo(a) ao meu portfólio!<br>
                    Eu me chamo Letícia Almeida!
                </div>
                <div class="col">
                    <div class="iconperfil">
                        <img src="icones/perfil.svg" alt="">
                    </div>
                </div>
            </div>

            <div class="row">
                <div class="col-9" id="sobremim">
                    <div>
                        <h1>Sobre Mim</h1>
                        <p>Eu sou Letícia Almeida e tenho 18 anos, tenho formações em Técnico em Informática<br>
                            Técnico em Manutenção de Computadores, Técnico em Desenvolvimento de Sistemas<br>
                            e estou cursando Sistemas de Informação na UNIFEB. Entrei no ramo da programação<br>
                            em 2020 mas começei a dar foco em 2022.
                        </p>
                    </div>
                </div>

                <div class="col-3">
                    <div class="sbm">
                        <img src="icones/sobrem.svg" alt="">
                    </div>
                </div>
            </div>



            <div class="row">
                <h1 id="competencias">Competências</h1>
                <div id="iconsC" class="col">
                    <div class="html" data-bs-toggle="modal" data-bs-target="#htmlModal">
                        <img src="imagens/html.png" alt="HTML">
                    </div>
                    <div class="js" data-bs-toggle="modal" data-bs-target="#jsModal">
                        <img src="imagens/js.png" alt="JS">
                    </div>
                    <div class="css" data-bs-toggle="modal" data-bs-target="#cssModal">
                        <img src="imagens/css.png" alt="CSS">
                    </div>
                    <div class="git" data-bs-toggle="modal" data-bs-target="#gitModal">
                        <img src="imagens/git.png" alt="Git">
                    </div>
                    <div class="github" data-bs-toggle="modal" data-bs-target="#githubModal">
                        <img src="imagens/github.png" alt="GitHub">
                    </div>
                    <div class="php" data-bs-toggle="modal" data-bs-target="#phpModal">
                        <img src="imagens/php.png" alt="PHP">
                    </div>
                </div>
                <div class="col">
                    <div class="info">
                        // Clique em cima de cada uma para saber sobre<br>
                        o que cada uma se trata!
                    </div>
                </div>
            </div>

            <!-- Modais -->
            <div class="modal fade" id="htmlModal" tabindex="-1" aria-labelledby="htmlModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="htmlModalLabel">HTML - Linguagem de Marcação</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            Informações detalhadas sobre HTML.
                        </div>
                    </div>
                </div>
            </div>
    
            <div class="modal fade" id="jsModal" tabindex="-1" aria-labelledby="jsModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="jsModalLabel">JavaScript - Linguagem de Programação</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            Informações detalhadas sobre JavaScript.
                        </div>
                    </div>
                </div>
            </div>
    
            <div class="modal fade" id="cssModal" tabindex="-1" aria-labelledby="cssModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="cssModalLabel">CSS - Folhas de Estilo em Cascata</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            Informações detalhadas sobre CSS.
                        </div>
                    </div>
                </div>
            </div>
        </div>
            <div class="modal fade" id="gitModal" tabindex="-1" aria-labelledby="gitModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="gitModalLabel">Git - Sistema de Controle de Versão</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            Informações detalhadas sobre Git.
                        </div>
                    </div>
                </div>
            </div>

            <div class="modal fade" id="githubModal" tabindex="-1" aria-labelledby="githubModalLabel"
                aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="githubModalLabel">GitHub - Plataforma de Hospedagem de Código
                            </h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            Informações detalhadas sobre GitHub.
                        </div>
                    </div>
                </div>
            </div>

            <div class="modal fade" id="phpModal" tabindex="-1" aria-labelledby="phpModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="phpModalLabel">PHP - Linguagem de Programação Server-Side</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            Informações detalhadas sobre PHP.
                        </div>
                    </div>
                </div>
            </div>



            <div class="row">
                <h1 id="projetos">Projetos</h1>
                <div class="col">
                    <div class="p1">
                        Em breve!
                    </div>
                </div>
                <div class="col">
                    <div class="p2">
                        Em breve!
                    </div>
                </div>
                <div class="col">
                    <div class="p3">
                        Em breve!
                    </div>
                </div>
                <div class="col">
                    <div class="p4">
                        Em breve!
                    </div>
                </div>
                <div class="col">
                    <div class="p5">
                        Em breve!
                    </div>
                </div>
                <div class="col">
                    <div class="p6">
                        Em breve!
                    </div>
                </div>
                <div class="col">
                    <div class="p7">
                        Em breve!
                    </div>
                </div>
                <div class="col">
                    <div class="p8">
                        Em breve!
                    </div>
                </div>
            </div>

            <div class="row d-flex justify-content-center align-items-center">
                <button id="btnVerMais" class="btnvermais" onclick="toggleProjetos()">Ver Mais</button>
            </div>

        </div>
    </div>

    <div class="row">
        <div class="contatos">
            <h3 id="ctts">Contatos:</h3>
            <ul id="ulcontatos">
                <li>
                    Email: email@email.com
                </li>
                <li>
                    Telefone: 4002-8922
                </li>
            </ul>
        </div>
    </div>
</body>
<script>
    var projetosVisiveis = false;

    function toggleProjetos() {
        var projetosP5aP8 = document.querySelectorAll('.p5, .p6, .p7, .p8');

        projetosP5aP8.forEach(function (projeto) {
            if (!projetosVisiveis) {
                projeto.style.display = 'flex';
                setTimeout(function () {
                    projeto.style.opacity = 1;
                }, 0);
            } else {
                projeto.style.opacity = 0;
                setTimeout(function () {
                    projeto.style.display = 'none';
                }, 500);
            }
        });

        projetosVisiveis = !projetosVisiveis;

        var btnVerMais = document.getElementById('btnVerMais');
        btnVerMais.textContent = (projetosVisiveis) ? 'Ver Menos' : 'Ver Mais';
    }
</script>
<script>
    var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'));
    var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
        return new bootstrap.Tooltip(tooltipTriggerEl);
    });
</script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>

</html>
