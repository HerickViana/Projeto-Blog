Projeto de Blog sobre HTML 5, com ajuda da DIO.
Projeto bem básico utilizando algumas "tags" básicas de HTML.
Não tinha nenhuma noção de como usar o GitHub nem como versionar em Git, e espero me desenvolver ainda mais.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Pojeto Blog</title>
</head>
<body>
    <!-- Nota, o id não pode ter # e o href tem # -->
    <h1 id="inicio"> Blog sobre aprendizado <img width="40" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/800px-HTML5_logo_and_wordmark.svg.png"> </h1> 
   
    <hr />

    <h2> Índice</h2>
        <ul>
            <li> <a href="#Surgimento"> Surgimento da internet </a></li>
            <li> <a href="#Como-funciona"> Como funciona o HTML </a></li>
            <li> <a href="#Tags"> O que são Tags </a> </li>
            <ul>
                <li> <a href="#Atributos"> Atributos </a> </li>
            </ul>
            <li> <a href="#Aprendizado"> O que foi aprendido nas aulas </a></li>
                <ul>
                    <li> <a href="#H1, H2 e parágrafos"> Usando H1, H2 e Parágrafos </a> </li>
                </ul>
            <li> <a href="#Referências"> Referências </a></li>
        </ul>
    
        <h2 id="Surgimento"> Surgimento da internet </h2>
        <small><a href="#inicio"> (Início) </a></small>
    <p> A internet surgiu, na década de 1960, como uma rede (chamada Arpanet) para envio de informações entre centro de pesquisas e instalações militares e o Pentágono. </p>
    <p> A primeira mensagem enviada se deu entre computadores da Universidade da Califórnia em Los Angeles (UCLA) e do Instituto de Pesquisa de Stanford (SRI), instituições universitárias dos Estados Unidos. </p>
    <p> Na década de 1980, a internet expandiu seu uso para fins comerciais e privados.
        A rede chegou ao Brasil em 1988, sendo liberada para uso privado e comercial em 1994. 
        A internet é, atualmente, o principal meio de comunicação do planeta, com mais de 5 bilhões de usuários.
        O físico britânico Tim Berners-Lee é o responsável pela criação da World Wide Web (WWW) em 1989. A WWW foi um sistema que permitiu a criação da internet comercial e a popularização da rede. </p>
    <p> <blockquote> <strong>Curiosidade:</strong> O Dia Mundial da Internet é comemorado em 17 de maio. </p> </blockquote>

    <h2 id="Como-funciona"> Como funciona o HTML </h2>
    <small><a href="#inicio"> (Início) </a></small>
    <p> Com o surgimento da web, era necessário criar uma linguagem que fosse entendida por meios de acesso diferentes. Para tanto, <a href="https://pt.wikipedia.org/wiki/Tim_Berners-Lee" target="_blank"> Tim Berners-Lee </a> desenvolveu o HTML, com a proposta de suprir essa necessidade. Somente na década de 1990, quando o Mosaic – browser desenvolvido por <a href="https://pt.wikipedia.org/wiki/Marc_Andreessen" target="_blank"> Marc Andreessen </a> – se popularizou, o HTML ganhou força e foi adotado por outros desenvolvedores e fabricante de browsers, compartilhando as mesmas convenções. </p>
    <p> HTML é uma abreviação de Hypertext Markup Language, ou seja, Linguagem de Marcação de Hipertexto. Resumindo, o HTML é uma linguagem usada para a publicação de conteúdo (texto, imagens, vídeos, áudio etc.) na web. </p>

    <h2 id="Tags"> O que são Tags </h2>
    <small><a href="#inicio"> (Início) </a></small>
    <p> As tags são usadas para informar ao navegador a estrutura do site. Ou seja: quando se escreve um código em HTML, as tags serão interpretadas pelo navegador, produzindo assim a estrutura e o conteúdo visual da página. </p>
    <p> A principal característica das tags é estarem sempre dentro dos sinais de chevron (sinal de “maior que” e “menor que”), ou seja: < >.
        As tags HTML são divididas em dois tipos: as que precisam de fechamento e as que não precisam de fechamento. As tags que precisam de fechamento possuem a sintaxe <tag> </tag>, já as que não precisam de fechamento possuem como estrutura <tag/>.
        Além disso, uma mesma tag pode receber um ou mais atributos, que possuirá um valor que modifica sua estrutura ou funcionalidade. </p>
        <h3 id="Atributos"> <ul> 
            <li> <u> Atributos  </li> </u> </h3>
        <p> Os atributos são usados para personalizar as tags, modificando sua estrutura ou funcionalidade. Igualmente, os atributos são utilizados para atribuir uma classe ou id a um elemento.
            A maioria das tags tem seus próprios atributos. Contudo, existem alguns atributos genéricos que podem ser utilizados na maioria das tags HTML, vamos estudá-los: </p>
        <ol>
            <li> class=”…“ – Atribui uma classe ao elemento (uma classe pode ser utilizada para um ou mais elementos); </li>
        <li> id=”…“ – Atribui um id ao elemento (um id deve ser único, ou seja atribuído a um único elemento); </li>
        <li> style=”…” – Permite incluir elementos CSS (estilos) dentro da tag; </li>
        <li> lang=”…” – Define o idioma principal do elemento; </li>
        <li> title=”…” – Define o título do elemento; </li>
        <li> alt=”…” – Define um texto alternativo e, por isso, é muito utilizado em imagens, auxilia nas práticas de SEO; </li>
        <li> hidden – Oculta o elemento; </li>
        <li> align=”…” – Permite definir o padrão de alinhamento desse elemento, como por exemplo: right, center, left e justify; </li>
        <li> width=”…” – Define uma largura para o elemento; </li>
        <li> height=”…” – Define uma altura para o elemento. </li>
        </ol>

    <h2 id="Aprendizado"> O que foi aprendido nas aulas </h2>
    <small><a href="#inicio"> (Início) </a></small>
    <h3 id="H1, H2 e parágrafos">Como usar Títulos e Parágrafos</h3>
    <p> <strong><u> Títulos</u> </strong>
    <p> Títulos são definidos com as tags < H1 > até a < H6>. 
    <p> A < H1> define o título maior. A < H6> define o título menor.
        <h1>Este é um título</h1>
        <h2>Este é um título</h2>
        <h3>Este é um título</h3>
        <h4>Este é um título</h4>
        <h5>Este é um título</h5>
        <h6>Este é um título</h6> </p>
    <p> <strong><u> Parágrafos</u></strong> </p>
    <p> Os parágrafos são definidos com a tag < p>. </p>

    <h2 id="Referências"> Referências </h2>
    <small><a href="#inicio"> (Início) </a></small>
        <ul> 
             <li> <i> Pesquisa sobre o surgimento da internet: </i> <a href="https://brasilescola.uol.com.br/informatica/internet.htm#:~:text=A%20internet%20surgiu%2C%20na%20d%C3%A9cada,institui%C3%A7%C3%B5es%20universit%C3%A1rias%20dos%20Estados%20Unidos." title="História da internet" target="_blank"> História da internet </a> </li> 
            
             <li> <i> Pesquisa sobre HTML: </i> <a href="https://www.devmedia.com.br/o-que-e-o-html5/25820" title="O que é HTML5" target="_blank"> O que é HTML5 </a> </li>
            
             <li> <i> Pesquisa sobre o que são Tags: </i> <a href="https://www.homehost.com.br/blog/tutoriais/tags-html/" title="Tags HTML" target="_blank"> Tags HTML </a> </li>
            
             <li> <i> Pesquisa sobre títulos e Parágrafos: </i> <a href="http://www.clem.ufba.br/tuts/html/c04.htm#:~:text=ap%C3%B3s%20um%20titulo..-,Par%C3%A1grafos,com%20a%20tag.&text=A%20HTML%20adiciona%20automaticamente%20uma,antes%20e%20ap%C3%B3s%20um%20par%C3%A1grafo." title="Tutorial de HTML" target="_blank"> Títulos e Parágrafos </a> </li>
        </ul>

</body>
</html>
