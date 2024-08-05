
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AluraBooks</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="reset.css">
</head>

<body>
    <h1>Alurabook</h1>

</body>

</html>
<header class="cabeçalho">
    <div class="container">
        <span class="cabeçalho__menu-hamburguer container__imagem"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem">
    </div>
    <div class="container">
        <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos" class="container__imagem"></a>
        <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras" class="container__imagem"></a>
        <a href="#"><img src="img/Usuario.svg" alt="Meu perfil" class="container__imagem"></a>
    </div>
</header>
<div class="container">
    <input type="checkbox" id="menu" class="container__botao" />
  
    <span class="cabeçalho__menu-hamburguer container__imagem"></span>
    <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem" />
  </div>
  <label for="menu">
    <span class="cabeçalho__menu-hamburguer container__imagem"></span>
  </label>
  <div class="container">
    <input type="checkbox" id="menu" class="container__botao" />
    <label for="menu">
      <span class="cabeçalho__menu-hamburguer container__imagem"></span>
    </label>
    <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem" />
  </div>
  <label for="menu">
    <span class="cabeçalho__menu-hamburguer container__imagem"></span>
  </label>
  
  <ul class="lista-menu">
  </ul>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>AluraBooks</title>
    <link rel="stylesheet" href="reset.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <!-- código omitido -->

<section class="banner">
    <h2 class="banner__titulo">Já sabe por onde começar?</h2>
    <p class="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!<p>
    <input type="search" class="banner_pesquisa" placeholder="Qual será sua próxima leitura?">
</section>

<ul class="lista-menu">
    <li class="lista-menu__titulo">Categorias</li>
    <li class="lista-menu__item">
      <a href="#" class="lista-menu__link">Programação</a>
    </li>
    <li class="lista-menu__item">
      <a href="#" class="lista-menu__link">Front-end</a>
    </li>
    <li class="lista-menu__item">
      <a href="#" class="lista-menu__link">Infraestrutura</a>
    </li>
    <li class="lista-menu__item">
      <a href="#" class="lista-menu__link">Business</a>
    </li>
    <li class="lista-menu__item">
      <a href="#" class="lista-menu__link">Design & UX</a>
    </li>
  </ul>
  //Código omitido

<section class="carrossel"> I
    <h2 class="carrossel titulo">Novos lançamentos</h2>
/section>
//Código omitido

<linf rel="stylesheet" href="https://unpk.com/swiper@8/swiper-bundle.min.css">

//Código omitido

<script src="https://unpkg.com/swiper@8/swiper-bundle.min.js"></script>

//Código omitido
<!-- Slider main container -->
<div class="swiper">
    <!-- Additional required wrapper -->
    <div class="swiper-wrapper">
      <!-- Slides -->
      <div class="swiper-slide">Slide 1</div>
      <div class="swiper-slide">Slide 2</div>
      <div class="swiper-slide">Slide 3</div>
      ...
    </div>
    <!-- If we need pagination -->
    <div class="swiper-pagination"></div>
  
    <!-- If we need navigation buttons -->
    <div class="swiper-button-prev"></div>
    <div class="swiper-button-next"></div>
  
    <!-- If we need scrollbar -->
    <div class="swiper-scrollbar"></div>
  </div>
  //Código omitido

<div class="swiper-wrapper">
    <!-- Slides -->
    <div class="swiper-slide"><img src="img/Apachekafka.svg" alt="Livro sobre apache kafka e spring boot da alura books"></div>
    <div class="swiper-slide"><img src="img/Liderança.svg" alt="Livro sobre liderança em design design da alura books"></div>
    <div class="swiper-slide"><img src="img/Javascript.svg" alt="Livro sobre javascript assertivo da alura books"></div>
    <div class="swiper-slide"><img src="Guia Front-end.svg" alt="Livro Guia front end"></div>
    <div class="swiper-slide"><img src="Portugol.svg" alt="Livro sobre portugol"></div>
    <div class="swiper-slide"><img src="Acessibilidade.svg" alt="livro sobre acessibilidade"></di>
</div>
