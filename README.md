<h1>Vitor passou por aqui!, Zak passou por aqui!, Lucas passou por aqui!</h1>

essa uma demostraçao de um dos nossos trabalhos em conjunto espero que goste!

file:///C:/Users/202421811810029/Documents/GET-A-PETv2/Scan%20manga/index.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O Mundo dos Mangás</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f4f6;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px;
            height: 40px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        header h1 {
            font-size: 1.5rem;
            margin: 0;
        }

        nav {
            background-color: #444;
            color: white;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            padding: 10px;
        }

        nav a:hover {
            background-color: #666;
            color: #fff;
            border-radius: 5px;
        }

        .carousel-item img {
            width: 100%;
            height: auto;
            object-fit: cover;
        }
        
        #carouselExample .carousel-item img {
        width: 100%;
        height: 400px;
        object-fit: cover;
        min-height: 200px;
        }
        
        @media (max-width: 768px) {
        #carouselExample .carousel-item img {
            height: 250px;
            object-fit: cover;
        }
    }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }

        .btn-container {
            text-align: center;
            margin-top: 30px;
            padding-bottom: 30px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.2rem;
            }

            nav {
                padding: 8px 0;
            }

            nav a {
                font-size: 1rem;
                padding: 8px 12px;
            }

            .carousel-item iframe {
                height: 300px;
            }

            .btn-container {
                margin-top: 20px;
            }

            .card-body {
                padding: 10px;
            }

            .card-img-top {
                width: 100%;
                height: auto;
            }

            .container {
                padding-left: 15px;
                padding-right: 15px;
            }

            .carousel-control-prev-icon,
            .carousel-control-next-icon {
                background-color: #333;
            }

            .carousel-inner {
                width: 100%;
                overflow: hidden;
            }
        }


        @media (max-width: 500px) {
            .carousel-item img {
                height: 250px;
            }

            .carousel-item {
                height: 250px;
            }

            .row {
                display: block;
                text-align: center;
            }

            .col-md-4 {
                display: inline-block;
                width: 100%;
                margin-bottom: 20px;
            }

            .card-body h5 {
                font-size: 1rem;
            }

            .card-body p {
                font-size: 0.9rem;
            }
        }

        .ranking-section {
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            margin-bottom: 50px;
        }

        .ranking-section h2 {
            margin-bottom: 20px;
        }

        .ranking-section ul {
            list-style-type: none;
            padding-left: 0;
        }

        .ranking-section li {
            font-size: 1.1rem;
            margin-bottom: 10px;
        }

        .ranking-section span {
            font-weight: bold;
            color: #333;
        }

        .video-container {
        position: relative;
        padding-bottom: 56.25%;
        height: 0;
        overflow: hidden;
        max-width: 100%;
    }

    .video-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }

    @media (min-width: 768px) {
        .video-container {
            padding-bottom: 40%;
        }

        .video-container iframe {
            width: 80%;
            height: 80%;
            margin: 0 auto;
            display: block;
        }
    }

    body {
        padding-top: 60px;
    }

    @media (max-width: 768px) {
        body {
            padding-top: 75px;
        }
    }
    </style>
</head>
<body>

<header>
    <h1>O Mundo dos Mangás</h1>
</header>

<!-- menu de navegação no topo -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">Mangá Infinity</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav mx-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#o-que-e">O que é Mangá</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#historia">História</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#tipos">Tipos de Mangá</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#ranking">Ranking de Mangás</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#video">Vídeo</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#galeria">Galeria</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<main class="container mt-5">
    <!-- carrossel de imagens sobre os mangás -->
    <section id="carrossel" class="mb-5">
        <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://i.pinimg.com/736x/a7/df/0d/a7df0da16fe7feae5ef386546e839463.jpg" class="d-block w-100" alt="Banner de Jujutsu Kaisen">
                </div>
                <div class="carousel-item">
                    <img src="https://i.pinimg.com/736x/8f/9d/13/8f9d134f0fd5b2398a63c9c4c16acf29.jpg" class="d-block w-100" alt="Banner de One Piece">
                </div>
                <div class="carousel-item">
                    <img src="https://www.animeunited.com.br/oomtumtu/2021/03/sousou-frieren-nuovo-successo-shonen-sunday-popolarita-vendite-rete-v3-491395.jpg" class="d-block w-100" alt="Banner de Sousou no Frieren">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Próximo</span>
            </button>
        </div>
    </section>

    <section id="o-que-e" class="mb-5">
        <h2>O que é Mangá?</h2>
        <p>O mangá é uma forma de quadrinhos originária do Japão. A palavra "mangá" pode ser traduzida como "desenho divertido", e é amplamente reconhecida como uma forma de entretenimento que combina narrativa visual com textos.</p>
    </section>

    <section id="historia" class="mb-5">
        <h2>História do Mangá</h2>
        <p>Os mangás têm raízes profundas na cultura japonesa, com origens que remontam ao século 12, mas o formato moderno começou a se popularizar na década de 1950.</p>
    </section>

    <section id="tipos" class="mb-5">
        <h2>Tipos de Mangá</h2>
        <ul>
            <li><strong>Shonen:</strong> Mangás voltados para jovens meninos, com muita ação e aventura.</li>
            <li><strong>Shojo:</strong> Mangás voltados para meninas, geralmente com histórias de romance e drama.</li>
            <li><strong>Seinen:</strong> Mangás voltados para adultos, com temas mais complexos e profundos.</li>
            <li><strong>Josei:</strong> Mangás voltados para mulheres adultas, com temas de relacionamento e vida cotidiana.</li>
        </ul>
    </section>

    <!-- ranking de mangás mais vendidos de 2024 -->
    <section id="ranking" class="ranking-section">
        <h2>Ranking de Mangás Mais Vendidos no Japão (2024)</h2>
        <p>A Oricon divulgou a lista dos mangás mais vendidos no Japão durante o ano de 2024 por série, com Jujutsu Kaisen liderando o ranking.</p>
        <p>A obra que ficou em segundo lugar no ano passado voltou a assumir a liderança, enquanto Blue Lock caiu da primeira para a quinta posição.</p>
        <p>Confira o top 10 abaixo:</p>
        <ul>
            <li><span>1º - Jujutsu Kaisen</span> - 7.610.995 cópias</li>
            <li><span>2º - One Piece</span> - 5.250.210 cópias</li>
            <li><span>3º - Frieren e a Jornada Para o Além</span> - 4.988.170 cópias</li>
            <li><span>4º - Diários de uma Apotecária</span> - 4.723.562 cópias</li>
            <li><span>5º - Blue Lock</span> - 3.881.269 cópias</li>
            <li><span>6º - Kaiju No. 8</span> - 3.398.326 cópias</li>
            <li><span>7º - Kingdom</span> - 3.234.204 cópias</li>
            <li><span>8º - Haikyuu!!</span> - 3.077.085 cópias</li>
            <li><span>9º - My Hero Academia</span> - 2.943.985 cópias</li>
            <li><span>10º - SPY x FAMILY</span> - 2.662.408 cópias</li>
        </ul>
        <p>Vale lembrar que também foi divulgado o ranking anual dos mangás mais vendidos por volumes individuais.</p>
        <p>O mangá de Gege Akutami foi serializado na revista semanal Shonen Jump entre 2018 e 2024. Os volumes finais, #29 e #30, serão lançados em 25 de dezembro.</p>
    </section>
    <section>
        <!-- vídeo do youtube falando sobre mangá -->
        <section id="video" class="mb-5">
            <h2>Assista a um Vídeo Sobre Mangás</h2>
            <div class="video-container">
                <iframe 
                    src="https://www.youtube.com/embed/OgPDS2AJyhU?si=i8h0LCGR_PVTRM-_" 
                    frameborder="0" 
                    allowfullscreen>
                </iframe>
            </div>
        </section>

    <!-- galeria de imagens sobre mangá -->
    <section id="galeria" class="mb-5">
        <h2>Galeria de Imagens</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card mb-4">
                    <img src="https://i.pinimg.com/736x/e5/ac/53/e5ac53e098273cdda00d94f3d0ed662d.jpg" class="card-img-top" alt="Imagem de Mangá 1">
                    <div class="card-body">
                        <h5 class="card-title">One Punch Man</h5>
                        <p class="card-text">Uma imagem representando um dos muitos estilos de mangá.</p>
                        <span class="badge bg-primary">Novo</span>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4">
                    <img src="https://i.pinimg.com/736x/2b/61/ea/2b61eaf1e4ec450f596bae787234e42a.jpg" class="card-img-top" alt="Imagem de Mangá 2">
                    <div class="card-body">
                        <h5 class="card-title">Blue Lock</h5>
                        <p class="card-text">Outra cena de um mangá popular.</p>
                        <span class="badge bg-success">Destaque</span>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4">
                    <img src="https://i.pinimg.com/736x/15/fd/3f/15fd3f54bb3b7b1460bb0d36d12e8e99.jpg" class="card-img-top" alt="Imagem de Mangá 3">
                    <div class="card-body">
                        <h5 class="card-title">Hajime no Ippo</h5>
                        <p class="card-text">Descubra mais sobre este mangá incrível!</p>
                        <span class="badge bg-danger">Popular</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="btn-container">
        <a href="https://brasilescola.uol.com.br/artes/o-que-e-manga.htm" target="_blank" class="btn btn-primary">Saiba mais</a>
    </section>
</main>

<footer>
    <p>© 2024 - O Mundo dos Mangás</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
