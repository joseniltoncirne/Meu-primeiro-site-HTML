# Meu-primeiro-site-HTML
Um site feito como trabalho pela faculdade, com exigência á alguns padrões feitos pelo docente.

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site HTML</title>
    <link rel="shortcut icon" href="imagens/html-css-js.ico" type="image/x-icon">
</head>

<body style="font-family: Arial, Helvetica, sans-serif;">
    <div id="inicio"
        style="background-image: linear-gradient(to right, #5541f0f4, #3B48F7, #2FA3ED); padding: 55px; border-radius: 10px;">

        <section>
            <h1 style="text-align: center; ; font-size: 50px">HTML <sup>Linguagem de Marcação de Hipertexto</sup></h1>
        </section>
        <section style="text-align: center; margin-top: 50px; ; font-size: 23px">
            <h2>Tutorial para Iniciantes</h2>
        </section>
    </div>

    <div style="background-image: linear-gradient(to right, #5541F0, #3B48F7, #2FA3ED); 
     display: flex; 
     justify-content: space-between;
     margin-top: 10px;
     color: white;
     padding: 5px;
     border-radius: 7.5px;">

        <a href="#inicio" style="color: white; text-decoration: none;">Início </a>
        <a href="#html" style="color: white; text-decoration: none"> HTML</a>
        <a href="#tabelas0" style="color: white; text-decoration: none"> Tabelas</a>
        <a href="#sobre" style="color: white; text-decoration: none"> Sobre CSS, HTML e JS</a>
        <a href="#links" style="color: white; text-decoration: none"> Links</a>
        <a href="contato.html" style="color: white; text-decoration: none">Contato</a>

    </div>

    <div id="html" style="font-size: 23px; text-align: justify; padding: 10px;">
        <p> <img src="https://tse1.mm.bing.net/th?id=OIP.FN170sbF2Xwk3JZ5OEPxAwHaHs&pid=Api&rs=1&c=1&qlt=95&w=92&h=95"
                align="left" width="70px" /> <strong><ins>HTML</ins></strong> <i>(Linguagem de Marcação de Hipertexto)
            </i> é o bloco de construção mais básico da web.<mark>Define o Significado e a estrutura do conteúdo da
                web.</mark> Outras tecnologias além do HTML geralmente são usadas para descrever a
            aparência/apresentação (CSS) ou a funcionalidade/comportamento (Java Script) de uma página da web.
            Documentos HTML podem ser interpretados por navegarores. A tecnologia é fruto da junção entre os padrões
            HyTime e SGML. HyTime é um padrão para representação estuturada de hipermídia e conteúdo baseado em tempo.
            Os hipertextos são a junção de vários elementos - palavras, vídeos e counteúdos - , que, quando conectados,
            estabelecem uma rede de dados que permite a comunicação, o armazenamento e o compartilhamento de
            informações. Por exemplo, ao visitar um website, você encontra diversas informações com formatações
            diferentes, como parágrafos, bullets e fontes distintas. Pois então, essa estruturação é realizada por meio
            do HTML.</p>

        <p style="font-size: 27px;"><b>Qual a função do HTML?</b></p>
        <p style=" font-size: 23px;">
        <ul type="square">
            <li> Imagine que você precisa construir um site do zero com informações da sua empresa. Nessa caso, você
                precisará conhecer a estrutura do HTML, criando um documento no bloco de notas e acrescentando códigos -
                tags - , que indicarão parágrafos, quebra de texto, espaçamentos, imagens, entre outros. Em geral , em
                um código único site, existem diversos documentos HTML, criando páginas como homepage, página de produto
                e informações sobre a empresa. Em cada aba, existe um código diferente.</p>
            </li>
        </ul>

        <hr style="margin-top: 60px;">

        <section style="display: flex; height: 400px; margin-top: 20px;">

            <section id="tabelas0"
                style="background-color: #0890ffc8; width: 50%; color: #000; padding-bottom: 10px; border-radius: 20px;">
                <table border="1">

                    <thead>

                        <tr>

                            <th colspan=2 style="text-align: center; text-shadow: 3px 3px 3px #1e4ddd9d;">Tabela de Tags
                                Html </th>

                        </tr>

                        <tr>

                            <th>Tags</th>
                            <th>Definições</th>

                        </tr>

                        <body>

                            <tr>

                                <td>&lt;i&gt;</td>
                                <td>Aplica o comando deixando o <i>texto em Itálico</i></td>

                            </tr>

                            <tr>

                                <td> &lt;b&gt; </td>
                                <td>Aplica o comando deixando o texto em <b>texto em Negrito</b></td>

                            </tr>

                            <tr>

                                <td> &lt;img&gt;</td>
                                <td>Adiciona uma Imagem</td>

                            </tr>

                            <tr>

                                <td>&lt;hr&gt;</td>
                                <td>Adiciona uma Linha Horizontal</td>

                            </tr>

                            <tr>

                                <td>&lt;small&gt;</td>
                                <td>Aplica o comando deixando o <small>texto Menor</small></td>

                            <tr>

                                <td>&lt;big&gt;</td>
                                <td> Aplica o comando deixando o <big>texto maior</big></td>

                            </tr>

                            <tr>

                                <td>&lt;href&gt;</td>
                                <td>Ao aplicar o comando, adiciona um Link</td>

                            </tr>

                            <tr>

                                <td>&lt;ins&gt;</td>
                                <td>Aplica o comando e deixa o <ins>texto Sublinhado</ins></td>

                            </tr>

                            <tr>

                                <td>&lt;mark&gt;</td>
                                <td>Aplica o comando, deixando o <mark>texto Grifado</mark></td>

                            </tr>
                            </p>
            </section>
            </table>
            </thead>
        </section>
        <section
            style="background-color: #5f44e7e1; width: 50%; text-align: center; border-radius: 20px; margin-left: 2px;">
            <p style="text-shadow: 2px 2px 2px #1c7996;"><strong>Protocolos da Web</strong></p>

            <ol type="A">

                <li> HTTP - HyperText Transfer Protocol </li>
                <li> POP - Post Office Protocol </li>
                <li> SMTP - Simple Mail Transfer Protocol </li>
                <li> FTP - File Transfer Protocol </li>
                <li> IMAP - Internet Messaging Acess Protocol</li>

            </ol>

            <ul type="disc">

                <li>HTTP - HyperText Transfer Protocol</li>
                <li>POP - Post Office Protocol</li>
                <li>SMTP - Simple Mail Transfer Protocol</li>
                <li>FTP - File Transfer Protocol</li>
                <li>IMAP - Internet Messaging Acess Protocol</li>

            </ul>

        </section>
    </div>
    <section id="sobre" style="display: flex; justify-content: flex-start; padding: 10px;">
        <section style="background-color: #4f2ef893; width: 33.33%; text-align: center;">

            <h2 style="text-shadow: 2px 2px 2px #4326d393;">O que é <abbr title="Cascading Style Sheets"
                    style="text-decoration: none;">CSS</abbr>?</h2>
            <p>
            <ul type="disc">
                <li style="font-size: 22px;">CSS é a sigla para Cascading Style Sheets, ou seja, Folhas de Estilo em
                    Cascatas. É uma maneira de dar estilo ao código criado por linguagens como HTML, XML ou XHTML, por
                    exemplo. O CSS tem a tarefa de separar o conteúdo do site de sua apresentação visual, alterando elementos como cor do texto, fonte e espaçamento entre blocos, assim como todo o aspecto estético de uma página.

                    Portanto, o HTML é uma. De forma prática, ela funciona como uma camada de personalização ao conteúdo visível.</li>
            </ul>
            </p>
        </section>

        <section style="background-color: #05c1f594; width: 33.33%; text-align: center;">

            <h2 style="text-shadow: 2px 2px 2px #096e8ab9;">O que é <abbr title="HiperText Markup Language"
                    style="text-decoration: none;">HTML</abbr>?</h2>
            <p>
            <ul type="square">
                <li style="font-size: 22px;"> Criada pelo britânico Tim Berners-Lee, o acrônimo HTML significa HiperText
                    Markup Language, traduzindo ao português: Linguagem de Marcação de Hipertexto. HTML não é uma linguagem de programação; É usada para definir a estrutura do seu conteúdo. HTML consiste de uma série de elementos, que você usa para delimitar ou agrupar diferentes partes do conteúdo para que ele experimente ou atue de determinada maneira. As tags anexas podem transformar uma palavra ou imagem num hiperlink, pode colocar palavras em itálico, pode aumentar ou diminuir a fonte e assim por diante.</li>
            </ul>
            </p>
        </section>

        <section style="background-color: #0890ff96; width: 33.33%; text-align: center;">

            <h2 style="text-shadow: 2px 2px 2px #075ca196;">O que é <abbr title="JS"
                    style="text-decoration: none;">JavaScript</abbr>?</h2>
            <p>
            <ul type="disc">
                <li style="font-size: 22px;">
                    O JavaScript, ou também conhecido como, JS, é uma linguagem de programação de alto-nível usada para
                    desenvolver aplicações, sistemas e serviços de alta complexidade. Com ela, você pode criar páginas
                    dinâmicas, animações, gráficos, mapas interativos, aplicativos para dispositivos móveis e até games. No desenvolvimento web, o Javascript pode ser usado no Frontend, Backend e até mesmo na comunicação com banco de dados. No frontend é possível manipular os elementos da página, como já exploramos. No backend é possível tratar requisições e executar diversas tarefas através do framework mais popular Node.
                </li>
            </ul>
            </p>
        </section>
    </section>
    <footer>
        <section style="display: flex; padding: 10px;  font-size: 17px; margin-top: 530px; justify-content: space-between; padding: 40px ;">

            <section style="width: 20%; background-color: #7262ec; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Sobre</h3>
                    <li>Voltar ao <a href="#inicio" style="text-decoration: none;">Topo</a>
                    <li>Política de Privacidade
                    <li>Fale conosco

                </ul>
            </section>
            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Referências</h3>
                    <li> <a href="https://www.w3schools.com/" target="_blank"
                            style="text-decoration: none;">W3School</a>
                    <li> <a href="https://www.alura.com.br/planos-cursos-online?gclid=Cj0KCQjwxYOiBhC9ARIsANiEIfYx885Q5_Sn1ojfJUBJrvS7VgOhZk2s3UL9ULNyMJg9Ty0f5bGANR8aAtHrEALw_wcB"
                            target="_blank" style="text-decoration: none;">Alura</a>
                    <li> <a href="https://www.youtube.com/results?search_query=html" target="_blank"
                            style="text-decoration: none;">Youtube</a>
                </ul>
            </section>

            <section style="width: 20%; background-color: #6f5cff; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Tutoriais</h3>
                    <li>Design
                    <li>Marketing
                    <li>Programação
                    <li>Tutoriais
                </ul>
            </section>

            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Outros Links</h3>
                    <li><a href="https://www.youtube.com/@CursoemVideo/search?query=curso%20html" target="_blank"
                            style="text-decoration: none;">Curso em Video HTML</a>
                    <li> <a href="https://www.youtube.com/watch?v=3oSIqIqzN3M" target="_blank"
                            style="text-decoration: none;">Inciando na Programação? </a>
                    <li> <a href="https://www.youtube.com/watch?v=n_Etdr7Dbjs&t=22s" target="_blank"
                            style="text-decoration: none;">Vamos praticar</a>

                </ul>
            </section>
        </section>
    </footer>
</body>

</html>

=======================================================================================================================================================================

<!DOCTYPE html>
<html lang="pt-br">

<head>

    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registro</title>
    <link rel="shortcut icon" href="imagens/usuario.ico" type="image/x-icon">
    <link rel="import" href="index.html">
</head>
<style>
    body {
        background-image: linear-gradient(to right, #85b2df, #89acce, #88a2bc, #98b3ce);
        font-family: Arial, Helvetica, sans-serif;
    }

    div {
        background-image: linear-gradient(to right, royalblue, royalblue);
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 450px;
        max-width: 500px;
        height: 600px;
        border-radius: 10px;
        display: flex;
        outline: none;
        margin-top: 300px;
    }

    form {
        text-align: center;
    }

    section {
        margin-bottom: 20px;
        margin-left: 20px;
    }

    form h3 {
        text-align: center;
        margin-top: -50px;
        color: #0052a4;
    }
</style>

<body>
    <section
        style="background-image: linear-gradient(to right, #5541f0, #3B48F7, #2FA3ED); padding: 55px; border-radius: 10px;">

        <section>
            <h1 style="text-align: center; ; font-size: 40px;">HTML <sup>Linguagem de Marcação de Hipertexto</sup></h1>
        </section>

        <section style="text-align: center; margin-top: 50px; ; font-size: 20px">
            <h2>Tutorial para Iniciantes</h2>
        </section>
    </section>

    <section style="background-image: linear-gradient(to right, #5541F0, #3B48F7, #2FA3ED); 
     display: flex; 
     justify-content: space-between;
     margin-top: 10px;
     color: white;
     padding: 5px;
     border-radius: 7.5px;">

        <a href="index.html#inicio" target="_self" rel="prev" style="color: white; text-decoration: none;">Início </a>
        <a href="index.html#html" style="color: white; text-decoration: none"> HTML</a>
        <a href="index.html#tabelas0" style="color: white; text-decoration: none"> Tabelas</a>
        <a href="index.html#sobre" style="color: white; text-decoration: none"> Sobre CSS, HTML e JS</a>
        <a href="index.html#links" style="color: white; text-decoration: none"> Links</a>
        <a href="contato.html" style="color: white; text-decoration: none">Contato</a>

    </section>

    <div>
        <section>
            <section><img src="imagens/usuario-imagem.png" alt="foto de usuário"
                    style="width: 100px; margin-bottom: 60px; margin-left: 142px; margin-top: 50px;"></section>
            <section>
                <form action="obrigado.html" method="get">
                    <h3 style="color: black;">Faça seu comentário</h3>

                    <input type="text" name="nome" placeholder="nome" required
                        style="margin: 10px 0; width: 100%; font-size: 15px; outline: none;"><br>
                    <input type="text" name="email" placeholder="email" required
                        style="margin: 10px 0; width: 100%; font-size: 15px; outline: none;"><br>

                    <label>Assunto: </label>

                    <select style="margin-top: 10px;" name="assunto">

                        <option value="sugestao">Sugestão</option>
                        <option value="elogio">Elogio</option>
                        <option value="critica" selected>Crítica</option>

                    </select><br>

                    <label>Mensagem: </label>

                    <textarea style="margin-top: 20px;" name="mensagem" required></textarea><br>

                    <input style="margin-top: 20px;" type="checkbox" name="termo" value="Concordo com os termos"
                        required>

                    <label>

                        Concordo com os Termos de Privacidade do Site

                    </label><br>

                    <input type="submit" value="Enviar Mensagem" style="width: 100%; 
                    height: 35px; 
                    cursor: pointer; 
                    background-color: rgb(186, 215, 225);
                    margin: 30px 0;
                    transition: 1s;
                    border: none;
                    border-radius: 5px;">

                </form>

                <section>
                    <a href="index.html" target="_self" rel="prev"> <img src="imagens/botao-voltar-preto.png"
                            alt="botao-voltar" style="width: 40px; margin-bottom: 20px; margin-left: 140px;"></a>
                </section>
            </section>
        </section>
    </div>
    <footer>
        <section style="display: flex; padding: 10px;  font-size: 17px; margin-top: 1300px; justify-content: space-between; padding: 40px ;">

            <section style="width: 20%; background-color: #7262ec; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Sobre</h3>
                    <li>Voltar ao <a href="#inicio" style="text-decoration: none;">Topo</a>
                    <li>Política de Privacidade
                    <li>Fale conosco

                </ul>
            </section>
            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Referências</h3>
                    <li> <a href="https://www.w3schools.com/" target="_blank"
                            style="text-decoration: none;">W3School</a>
                    <li> <a href="https://www.alura.com.br/planos-cursos-online?gclid=Cj0KCQjwxYOiBhC9ARIsANiEIfYx885Q5_Sn1ojfJUBJrvS7VgOhZk2s3UL9ULNyMJg9Ty0f5bGANR8aAtHrEALw_wcB"
                            target="_blank" style="text-decoration: none;">Alura</a>
                    <li> <a href="https://www.youtube.com/results?search_query=html" target="_blank"
                            style="text-decoration: none;">Youtube</a>
                </ul>
            </section>

            <section style="width: 20%; background-color: #6f5cff; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Tutoriais</h3>
                    <li>Design
                    <li>Marketing
                    <li>Programação
                    <li>Tutoriais
                </ul>
            </section>

            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Outros Links</h3>
                    <li><a href="https://www.youtube.com/@CursoemVideo/search?query=curso%20html" target="_blank"
                            style="text-decoration: none;">Curso em Video HTML</a>
                    <li> <a href="https://www.youtube.com/watch?v=3oSIqIqzN3M" target="_blank"
                            style="text-decoration: none;">Inciando na Programação? </a>
                    <li> <a href="https://www.youtube.com/watch?v=n_Etdr7Dbjs&t=22s" target="_blank"
                            style="text-decoration: none;">Vamos praticar</a>

                </ul>
            </section>
        </section>
    </footer>
</body>

</html>

=====================================================================================================================================================================


<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body style="background-image: linear-gradient(to right, #85b2df, #89acce, #88a2bc, #98b3ce)">
    <div
        style="background-image: linear-gradient(to right, #5541f0f4, #3B48F7, #2FA3ED); padding: 55px; border-radius: 10px;">

        <section>
            <h1 style="text-align: center; ; font-size: 50px">HTML <sup>Linguagem de Marcação de Hipertexto</sup></h1>
        </section>
        <section style="text-align: center; margin-top: 50px; ; font-size: 23px">
            <h2>Tutorial para Iniciantes</h2>
        </section>
    </div>

    <div style="background-image: linear-gradient(to right, #5541F0, #3B48F7, #2FA3ED); 
     display: flex; 
     justify-content: space-between;
     margin-top: 10px;
     color: white;
     padding: 5px;
     border-radius: 7.5px;">

        <a href="index.html#inicio" style="color: white; text-decoration: none;">Início </a>
        <a href="index.html#html" style="color: white; text-decoration: none"> HTML</a>
        <a href="index.html#tabelas0" style="color: white; text-decoration: none"> Tabelas</a>
        <a href="index.html#sobre" style="color: white; text-decoration: none"> Sobre CSS, HTML e JS</a>
        <a href="index.html#links" style="color: white; text-decoration: none"> Links</a>
        <a href="contato.html" style="color: white; text-decoration: none">Contato</a>

    </div>
    <section>
        <center>
            <img src="imagens/computador.png" alt="imagem computador" style="width: 700px; margin-top: 80px;">
        </center>
    </section>
    <p style="text-align: center; margin-bottom: 20px; font-size: 40px; margin-top: 40px;">Obrigado por entrar em contato conosco,
        retornaremos em breve!</p>
    <footer>
        <section style="display: flex; padding: 10px;  font-size: 17px; margin-top: 660px; justify-content: space-between; padding: 40px ;">

            <section style="width: 20%; background-color: #7262ec; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Sobre</h3>
                    <li>Voltar ao <a href="#inicio" style="text-decoration: none;">Topo</a>
                    <li>Política de Privacidade
                    <li>Fale conosco

                </ul>
            </section>
            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Referências</h3>
                    <li> <a href="https://www.w3schools.com/" target="_blank"
                            style="text-decoration: none;">W3School</a>
                    <li> <a href="https://www.alura.com.br/planos-cursos-online?gclid=Cj0KCQjwxYOiBhC9ARIsANiEIfYx885Q5_Sn1ojfJUBJrvS7VgOhZk2s3UL9ULNyMJg9Ty0f5bGANR8aAtHrEALw_wcB"
                            target="_blank" style="text-decoration: none;">Alura</a>
                    <li> <a href="https://www.youtube.com/results?search_query=html" target="_blank"
                            style="text-decoration: none;">Youtube</a>
                </ul>
            </section>

            <section style="width: 20%; background-color: #6f5cff; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Tutoriais</h3>
                    <li>Design
                    <li>Marketing
                    <li>Programação
                    <li>Tutoriais
                </ul>
            </section>

            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Outros Links</h3>
                    <li><a href="https://www.youtube.com/@CursoemVideo/search?query=curso%20html" target="_blank"
                            style="text-decoration: none;">Curso em Video HTML</a>
                    <li> <a href="https://www.youtube.com/watch?v=3oSIqIqzN3M" target="_blank"
                            style="text-decoration: none;">Inciando na Programação? </a>
                    <li> <a href="https://www.youtube.com/watch?v=n_Etdr7Dbjs&t=22s" target="_blank"
                            style="text-decoration: none;">Vamos praticar</a>

                </ul>
            </section>
        </section>
    </footer>


</body>

</html>

==============================================================================================================================================================================

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body style="background-image: linear-gradient(to right, #85b2df, #89acce, #88a2bc, #98b3ce)">
    <div
        style="background-image: linear-gradient(to right, #5541f0f4, #3B48F7, #2FA3ED); padding: 55px; border-radius: 10px;">

        <section>
            <h1 style="text-align: center; ; font-size: 50px">HTML <sup>Linguagem de Marcação de Hipertexto</sup></h1>
        </section>
        <section style="text-align: center; margin-top: 50px; ; font-size: 23px">
            <h2>Tutorial para Iniciantes</h2>
        </section>
    </div>

    <div style="background-image: linear-gradient(to right, #5541F0, #3B48F7, #2FA3ED); 
     display: flex; 
     justify-content: space-between;
     margin-top: 10px;
     color: white;
     padding: 5px;
     border-radius: 7.5px;">

        <a href="index.html#inicio" style="color: white; text-decoration: none;">Início </a>
        <a href="index.html#html" style="color: white; text-decoration: none"> HTML</a>
        <a href="index.html#tabelas0" style="color: white; text-decoration: none"> Tabelas</a>
        <a href="index.html#sobre" style="color: white; text-decoration: none"> Sobre CSS, HTML e JS</a>
        <a href="index.html#links" style="color: white; text-decoration: none"> Links</a>
        <a href="contato.html" style="color: white; text-decoration: none">Contato</a>

    </div>
    <section>
        <center>
            <img src="imagens/computador.png" alt="imagem computador" style="width: 700px; margin-top: 80px;">
        </center>
    </section>
    <p style="text-align: center; margin-bottom: 20px; font-size: 40px; margin-top: 40px;">Obrigado por entrar em contato conosco,
        retornaremos em breve!</p>
    <footer>
        <section style="display: flex; padding: 10px;  font-size: 17px; margin-top: 660px; justify-content: space-between; padding: 40px ;">

            <section style="width: 20%; background-color: #7262ec; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Sobre</h3>
                    <li>Voltar ao <a href="#inicio" style="text-decoration: none;">Topo</a>
                    <li>Política de Privacidade
                    <li>Fale conosco

                </ul>
            </section>
            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Referências</h3>
                    <li> <a href="https://www.w3schools.com/" target="_blank"
                            style="text-decoration: none;">W3School</a>
                    <li> <a href="https://www.alura.com.br/planos-cursos-online?gclid=Cj0KCQjwxYOiBhC9ARIsANiEIfYx885Q5_Sn1ojfJUBJrvS7VgOhZk2s3UL9ULNyMJg9Ty0f5bGANR8aAtHrEALw_wcB"
                            target="_blank" style="text-decoration: none;">Alura</a>
                    <li> <a href="https://www.youtube.com/results?search_query=html" target="_blank"
                            style="text-decoration: none;">Youtube</a>
                </ul>
            </section>

            <section style="width: 20%; background-color: #6f5cff; border-radius: 15px;  margin-top: -500px; height: 150px; box-shadow: 20px 20px 20px #433a8d; padding: 10px;">
                <ul>
                    <h3>Tutoriais</h3>
                    <li>Design
                    <li>Marketing
                    <li>Programação
                    <li>Tutoriais
                </ul>
            </section>

            <section style="width: 20%; background-color: #5c66f8; border-radius: 15px;  margin-top: -550px; height: 150px; box-shadow: 20px 20px 20px #3c43a3; padding: 10px;">
                <ul>
                    <h3>Outros Links</h3>
                    <li><a href="https://www.youtube.com/@CursoemVideo/search?query=curso%20html" target="_blank"
                            style="text-decoration: none;">Curso em Video HTML</a>
                    <li> <a href="https://www.youtube.com/watch?v=3oSIqIqzN3M" target="_blank"
                            style="text-decoration: none;">Inciando na Programação? </a>
                    <li> <a href="https://www.youtube.com/watch?v=n_Etdr7Dbjs&t=22s" target="_blank"
                            style="text-decoration: none;">Vamos praticar</a>

                </ul>
            </section>
        </section>
    </footer>


</body>

</html>

=================================================================================================================================================================================

*Style.css* (externo)

@charset "UTF-8";

* {
    font-family: Arial, Helvetica, sans-serif;
}
body {
    background-color: rgb(74, 114, 233);
}
form {
    background-color: rgb(0, 0, 255);
    display: flex;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    position: absolute;
    max-width: 500px;
    width: 70%;
    padding: 20px;
    
}
