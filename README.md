<!DOCTYPE html>
<html lang="pt-br">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Alura Plus</title>
   <link rel="stylesheet" href="aluraplus.css">
   <link rel="preconnect" href="https://fonts.googleapis.com">
   <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
   <link href="https://fonts.googleapis.com/css2?familyy=inter:wght@100..900&display=swap" rel="stylesheet">


</head>
<body>
   <section class="container principal">
    <div class="container__caixa ">
        <h1>Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço único.</h1>
        <img src="Combo.png" alt="o combo+ é a junçao do alura+ e o alura lingua" class=" container__imagem">
        <a href="www.alura.com.br" class="container_botao">Assine por 12x de R$120,00</a>
        <p class="container_aviso">"O preço pode variar caso a assinatura seja feita em outros planos.</p>
   </div>
</section>
<section class="container secundario">
   <img src="Plataformas.png" alt="um monitor e um celular com alura aberto" class=" secundario_imagem"><div
   class="conatiner_descriçao">
<h2 class="descriçao_titulo">Assista do seu jeito</h2> 
<p class="descriçao_texto">Aproveite a tela grande da Tv ou assista no tablet, laptop, celular e outros aparelhos. Nessa seleçao de </p>
</section>
  
</body>
</html>
<section class="container secundario">
   <div class="container__descrição">
     <p class="descrição__texto">Só o Combo+ oferece Alura+ e Alura Língua juntos para você ter acesso a cursos de diversas áreas da tecnologia e aprender inglês ou espanhol, onde e como quiser.</p>
     <a href="www.alura.com.br" class="container__botao secundario__botao">Assinar o Combo+</a>
   </div>
   <img src="Telas.png" alt="Tela da Alura Plus e da Alura Lingua" class="secundario__imagem">
 </section>
  <section class="container secundario">
   <img src="Notebook.png" alt="Tela Alura curso HTML5 e CSS3" class="secundario__imagem">
   <div class="container__descrição">
     <h2 class="descrição__titulo">Baixe seus cursos</h2>
     <p class="descrição__texto">Baixe e assista quando e onde quiser. Assim, seus favoritos estão sempre com você, até mesmo sem internet.</p>
   </div>
 </section>
  <section class="dispositivos">
   <h2 class="dispositivos__titulo">Disponível nos seus dispositivos favoritos</h2>
   <ul class="dispositivos__lista">
     <li>
       <img src="tv.png" alt="ícone da televisão">
       <h3 class="lista__item">TV</h3>
     </li>
     <li>
       <img src="computador.png" alt="ícone de computador">
       <h3 class="lista__item">Computadores</h3>
     </li>
     <li>
       <img src="celular.png" alt="ícone de celular">
       <h3 class="lista__item">Celulares e Tablets</h3>
     </li>
   </ul>
 </section>
 <footer class="rodape">
   <img src="Logo.png" alt="alura+" class="rodape__logo">
   <ul class="rodape__lista">
     <li class="lista__link"><a href="#">Idioma</a></li>
     <li class="lista__link"><a href="#">Dispositivo compatíveis</a></li>
     <li class="lista__link"><a href="#">Contrato de assinatura</a></li>
     <li class="lista__link"><a href="#">Política de privacidade</a></li>
     <li class="lista__link"><a href="#">Proteção de dados no Brasil</a></li>
     <li class="lista__link"><a href="#">Anúncios personalizados</a></li>
     <li class="lista__link"><a href="#">Ajuda</a></li>
   </ul>
   <p class="rodape__texto">© 2021 Alura, Alura+ e Alura Língua. Todos os direitos reservados. Serviço de assinatura paga. Conteúdo sujeito a disponibilidade.</p>
   <p class="rodape__texto">Alura+ é um serviço pago, baseado em assinatura e sujeito a termos e condições. O serviço Alura+ é comercializado por Aovs Sistemas de Informática S.A., Rua Vergueiro, 3185 - Liberdade, São Paulo - SP, 04101-300, Brasil e CNPJ 05.555.382/0001-33</p>
 </footer>


:root {--branco-principal: #FFFFFF;--cinza-principal: #cececo; --botao-azul: #167BF7; --cor-de-fundo:#00030C;
    --font-principal: 'inter';--botao-azul-efeito: #6387b3;
    }
    body { background-color: var(--cor-de-fundo); color: var(--branco-principal);--font-family: var(--font-principal); font-size: 16px;
    font-weight: 400;}
    *{margin: 0; padding: 0;}
    .principal { background-image: url(Background.png); background-repeat: no-repeat; background-size: contain; align-items: center; text-align: center;}
    .container{height: 100vh; display:grid;grid-template-columns: 33% 33% 33%; }
    
    .container_botao {background-color: var(--botao-azul); border-radius: 5px;padding: 1em;color: var(--branco-principal);display:
    block; text-decoration: none; margin-bottom: 1em;}
    .botao_secundario {background-color: transparent; border: 2px solid var(--branco-principal);}
    .container_aviso { font-size: 12px; color:var(--cinza-secundario);}
    .container_imagem{margin:1em 0 2em 0;}
    .container_caixa {margin:0 6em; }
    .secundario_imagem{width:80%;}
    .secundario{ align-items:center; margin:0 10em}
    .descricao_titulo {font-weight:700;font-size: 40px; color: var(--branco-principal); margin-bottom:0.3em;}
    .descricao_texto {color:var(--cinza-secundario);} 
    .secundario_botao {display:inline-block; margin-top: 1em;}
    .container_descriçao{padding: 2em;}
    .dispositivos_lista{ display: flex; justify-content: center; list-style-type: none; margin: 5em 0;}
    .dispositivos { text-align: center;}
    .dispositivos_titulo{font-size: 48px; color: var(--branco-principal);} 
    .lista_item {font-size: 32px; color: var(--branco-principal);}
    .rodape {text-align: center; margin: 5em 3;}
    .rodape_texto {margin: 1em 0; color: var(--cinza-secundario); font-size: 14px;}
    .rodape_lista {display: flex; justify-content: center; list-style-type: none; margin: 1em;}
    .lista link a{text-decoration: none; color:var(--branco-principal); margin-left: 1em;}
    .lista link a:hover{color: var(--botao-azul); }
    .lista_link a:active{ color: chocolate;}
    .container_botao:hover{background-color: var(--botao-azul-efeito); color:var(--cor-de-fundo)}
