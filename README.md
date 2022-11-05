<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <!--top demaiss-->
        <meta charset="utf-8">
        <title>Pagina exemplo estrutura base</title>
        <meta name="author" content="Rafael">
        <meta name="description" content="Lista de Documentos">
        <meta name="keywords" content="html5, tecnologia">

        <link rel="stylesheet" href="css/estilo.css">
        <style>
            body{
                font-family: arial, sans-serif;
                background:#ccc;
            }

            .hero{
                background-image: url(../imagens/bg-3.jpg);
                height: 500px;
                margin: 0;
                background-position: right center;
                background-size: cover;
                margin-top: -15px;
                margin-inline: -1%;
            }
            .hero-content{
                text-align: center;
                color: white;
                margin-top: 150px;
            }
            .hero-content h1{
                text-transform: uppercase;
                font-size: 46px;
                text-shadow: 3px 3px 2px #333;
            }
            main{
                width: 80%;
                margin: auto;
            }
            .content-section{
                background-color: white;
                padding-top: 15px;
                padding-bottom: 1px;
                margin-top: 15px;
            }
            .content-section h2{
                background-color: #DCDCDC;
                padding: 10px;
                margin-top: 0px;
                margin-left: 25px;
                margin-right: 25px;
            }
            .content-footer{
                background-color: #808080;
                padding: 10px;
                margin-top: 15px;
            }
            .content-footer p{
                text-shadow: 2px 1px 1px #333;
                text-align: center;
                color: white;
            }
            .card{
                display: inline-block;
                margin-right: 27px;
                padding-left: 25px;
                
                
            }
            .card p{
                background-color: #333;
                text-align: left;
                font-family: Verdana, sans-serif;
                padding: 25px;
                color: white;
                text-transform: uppercase;
                margin-top: -3%;
            }
            .content_paragraph_article{
                margin-left: 25px;
            }
            .hero ul li{
                list-style: none;
                margin-right: 25px;
                text-decoration: none;
                border-color: white;
                border-width: thin;
                border-style: solid;
                font-size: 12px;
                padding: 8px;
                color: white;
                display: inline-block;
                padding-inline: 2px;
            }
            .hero ul{
                text-align: right;
            }
            .inicio, .contato, .quem_sou{
                text-transform: uppercase;
                color: white;
                text-decoration: none;
                transition: all 0.5s;
                cursor: pointer;
                background-color: black;
                opacity: 0.3;
                padding: 7px;
                
                
            }
            .inicio:hover, .contato:hover, .quem_sou:hover{
                background-color:black;
                opacity: 0.7;
            }
            .hero-content p{
                background-color: black;
                opacity: 0.7;
                margin-inline: 40%;
                padding: 11px;
                border-bottom-width: 3px;
                border-bottom-style: solid;
                border-bottom-color: white;

            }

        </style>
    </head>

    <body>
        <div id="principal"></div>
            <header class="hero">
                <nav>
                    <ul>
                        <br>
                        <li><a class="inicio" href="index.html">Início</a></li>
                        <li><a class="quem_sou" href="#">Quem Sou</a></li>
                        <li><a class="contato" href="#">Contato</a></li>
                    </ul>
                </nav>
                <div class="hero-content">
                    <h1>Curso Web Fundamentos</h1>
                    <p>Aprenda HTML, CSS e JavaScript</p>
                </div>
            </header>
            <main>
                <section class="content-section">
                    <div class="card">
                        <img class="img" src="../imagens/card_01.png" alt="">
                        <p>Seletores</p>
                    </div>
                    <div class="card">
                        <img class="img" src="../imagens/card_03.jpg" alt="">
                        <p>Posicionamento</p>
                    </div>
                    <div class="card">
                        <img class="img" src="../imagens/card_04.jpg" alt="">
                        <p>Fontes e ícones</p>
                    </div>
                </section>
                    
                <section class="content-section">
                    <article>
                        <header><h2>título</h2></header>
                        <p class="content_paragraph_article">Primeiro parágrafo de exemplo</p>
                        <p class="content_paragraph_article">Segundo parágrafo de exemplo</p>
                    </article>
                </section>
            </main>
            <footer class="content-footer">
                <p>Copyright &copy; 2018</p>
            </footer>

    </body>

</html>
