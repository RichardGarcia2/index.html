# index.html
HTML- conhecimento

<html lang="pt-br">
    <!DOCTYPE html>
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dark Web</title>
    
    <link rel="shortcut icon" href="Icone/Icone_PSTriangulo.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">

</head>
<body>
   
    <h1>Developer🏴‍☠️ &real;</h1>

    <h2>Bem vindo, toque a musica e boa leitura!</h2>
    
    <audio src="Audios/Some College - National Sweetheart.mp3" controls autoplay loop></audio>

    <hr>
    <h2>Conteúdo</h2>
    <p>
        Você pode escrever um parágrafo de qualquer jeito; Basta colocar tudo no meio do par de tags p e /p;
        se precisar quebrar o texto em algum lugar específico, pode ser usada a tag br; Entendeu?
    </p>

    <p>Vamos adicionar alguns símbolos especiais:
        &real;
        &reg;
        &REG;
        🧑‍💻☠️🏴‍☠️👾 
        <br>
        <button>Now</button>
        <button>Right</button>
    </p>
    <p>Abaixo adicionamos algumas imagens com o comando "img" + enter; clique nas imagens para saber mais!</p>
    <br>
    <a href="video1.html"><img src="imagens/drift200.jpg" alt="html"></a>
    <a href="video2.html"><img src="imagens/Batman200.webp" alt="html"></a>
    
    <br>
    <a href="video3.html"><img src="imagens/ficção-paisagem200.avif"></a>
    <a href="video4.html"><img src="imagens/reinomedieval200.jpg" alt="html"></a>
    
    <br><br>

    <h3>Icone</h3>
    <p>
    Para adicionar um icone ao site você pode baixar do site "icone archive",<br>
    salvar na sua pasta, e adicionar ao programa com o codigo "link" e clicar em "link:favicon" e colocar o nome do arquivo que vc baixou/salvou.
    </p>

    <h1>Principais Formatações</h1>
    <h2>Negrito/Destaque</h2>
    <p>Nesta frase temos um <b>termo em negrito</b>usando a tag B (não semantica). </p>

    <p>Nesta frase, temos um <strong> termo em destaque</strong>usando a tag strong (semântica).</p>

    <h2>Itálico / Ênfase</h2>
    <p>Nesta frase, temos um <i>termo em itálico</i> usando a tag I (não semântica).</p>
    <p>
        Nesta frase, temos um <em>termo em ênfase</em> usando a tag EM (SEMÂNTICA).
    </p>

    <p>
        Podemos criar também <mark>um texto marcado</mark>, usando a tag MARK.
    </p>

    <p style="background-color: rgb(81, 61, 196);">
    Acima fazendo um teste de marcação de texto, e aqui, trocando a cor dessa marcação ou até mesmo do parágrafo como fiz aqui. 
    </p>
    <p>Ou podemos também criar um seletor no cabeçario "mark" para que todos as vezes em que eu precise fazer uma marcação de texto, ela fique somente com aquela cor específica.</p>

    <p>
    Para mostrar que <ins>um texto foi inserido depois</ins>, usamnos a tag 'ins'.
    </p>

    <p>
    Para mostrar que <del>a palavra ou texto foi</del> excluido recentemente usamos a tag del.
    </p>

    <p>
         <u>Texto sublinhado</u>: usamos a tag "u".
    </p>

    <h2>Texto sobrescrito</h2>

    <p>Para escrevermos coisas como 20 <sup>7</sup>, usamos a tag sup, abreviação de superior.</p>
    <p>Para escrevermos coisas como H <sub>2</sub> O, colocamos a tag sub.</p>

    <h1>Outros comandos</h1>
    <h2>Código-Fonte</h2>

    <p>O comando <code><u>document.tigrinhoBet</u></code> é escrito em Linguagem JavaScript, feito com o comando "code".
    </p>
    
    <h2>Citações Simples</h2>
    
    <p>Como diria meu professor: 
        <q>o computador é um burro muito rapido</q>
    </p>
    
    <p>Envelope a frase ou palavra com CTRL+ SHIFT+ P, clique em envelopar/envolver e digite "q" (que serve para fazer citações, pra dar mas sentido a frase).</p>
    <pre>
        <p>com o comando "Pré" você pode mostrar as quebras de linhas na pagina de exibição. </p>
        <p>Util quando for exibir um codigo.</p>
    </pre>

    <p>Estou estudando <abbr title="Linguagem de Marcação de Texto">HTML</abbr> e <abbr title="Cascading Style Sheets">CSS</abbr>;É muito massa!!</p>

    <p><bdo dir="rtl">.Programação em HMLH e CSS para iniciantes</bdo></p>

    <h1>Listas Ordenadas</h1>
    <!--PARA A FORMATAÇÃO DAS LISTAS-->
    <!--ol: 1, A, a, I, i-->
    <!--ul: Square, sircle, disc-->

    <ol type="I">
        <li>Acordar</li>
        <li>Trabalhar</li>
            <ol type="A">
                <li>Agilidade</li>
                    <ul type="disc">
                        <li>Separação/Produção</li>
                    </ul>
            </ol>
        <li>Ir no culto</li>
            <ol type="1">
                <li>Orar</li>
                    <ol type="A">
                        <li>Buscar ao Senhor</li> 
                    </ol>
            </ol>
        <li>Estudar</li>
        <ol type="1">
            <li>Programação</li>
                <ol type="A">
                    <li>HTML</li> 
                    <ul type="sircle">
                        <li>Linguagem de Marcação de Texto.
                        </li>
                    </ul>
                    <li>CSS</li>
                </ol> 
            
        </ol>
    </ol>

    <h1>Listas não Ordenadas</h1>
    <ul type="disc">
        <li>Orar</li>
        <li>Lêr a palavra</li>
            <ul type="sircle">
                <li>Livro de Salmos</li>
                    <ul type="square">
                        <li>Cap: 23</li>
                    </ul>
            </ul>
        <li>Jejuar</li>
        <li>Madrugada</li>
        <ol type="a">
            <li>Periodo de Louvor </li>
            <li>Palavra</li>
        </ol>
    </ul>

    <p>Para fazer listas ordenadas, o comando:"ol type" + "I","i","A","a" e "1".</p>

    <p>Para listas não ordenadas, o comando:"ul, type"+ "square", "disc" ou "sircle"; Podemos misturar a UL com OL também.
    </p>
    <h1>Desafios de HTML</h1>
    <h2>Essas são as tags em html</h2>
    
    <ul type="disc">
        
        <li><abbr title="Use a tag img">Imagem</abbr></li>
        <li><abbr title="Use a tag p">Paragrafos</abbr></li>
        <li><abbr title="Use a tag 'h1', entre o seus niveis">Titulos</abbr></li>
        <li><abbr title="Use a tag abbr">Abreviaçôes</abbr></li>
        <li><abbr title="Use a tag code">Codigo-Fonte</abbr></li>
        <li><abbr title="Use a tag ol/li">Lista Numerada</abbr></li>
        <li><abbr title="Use a tag ul/li">List denumeradas</abbr></li>
    </ul>

    <p>
        Você pode também adicionar um link a palavras e frases, usando o envelopamento "a", colando o link que você deseja; ATENÇÃO, logo em seguida dentro do mesmo comando, você irá colocar: 'target="_blank"' + rel="external", assim quando clicarem no link, irá abrir outra pagina sem sobrepor o seu site; serve para que outras pessoas possam voltar a sua pagina novamente.
    </p>
    
    <p>
        Aqui você pode ver como é a segunda pagina deste site, <a href="PG2.html"> clique aqui!</a> 
    </p>

    <h1>Links para dowload</h1>
    <ul>
        <li>Aqui você consegue acessar o livro.</li>
        <p><a href="10 - Ligações em toda parte.pdf" download="10 - Ligações em toda parte.pdf" type="application/pdf">Ler livro em PDF</a></p>
        <!--Tentei colocar ele para baixar em versão PDF mais não consegui; futuramente tentarei de novo, PESQUISE NA NET-->
        
        <li>Aqui você pode baixa-lo em arquivo zip.</li>
        <p><a href="10 - Ligações em toda parte.zip">Baixar livro zip </a></p>
    </ul>
        
    <p>
        Este é o meu perfil no Instagram, <a href="https://www.instagram.com/richard_g5/" target="_blank" rel="external"> visite</a>!
    </p>

   <h1>Midias Dinâmicas</h1>

    <p>
        Aumente ou diminua o tamanho do seu navegador e veja a magica.
    </p>

    <picture>
        <source media="(max-width: 750px)" srcset="edit/edit.P.png" type="image/png">

        <source media="(max-width: 1050px)" srcset="edit/edit.M.png" type="image/png">
        
        <img src="edit/edit.G.png" alt="html">
    </picture>

    <h1>
        Web Video
    </h1>

    <p>
        Agora, você verá logo abaixo um video muito facil de se colocar na web, antes, é bom ver sobre formatos e tamanhos para o seu video hospedado em um site; Temos um video ao lado com incorporação externa.
    </p>

    <video width="250" controls poster="edit/🖤ཻུꦿ❁ Aesthetic Bruce Wayne.jfif" src="Videos/2Bilion.mp4">
    </video>

    <iframe width="300" height="315" src="https://www.youtube.com/embed/Ekw3Ip61wQE?si=BexzKDF3TXv6QiHA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</body>
</html> 
