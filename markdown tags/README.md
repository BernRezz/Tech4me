<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Markdown</title>
    <style type="text/css">
        * {
            margin: 0;
        }

        html {
            overflow-x: hidden;
    
        }

        body {
            background-color: rgb(57, 56, 58);
            color: rgb(191, 197, 197);
            font-family: Arial, Helvetica, sans-serif;
        }

        #header {
            background-color: rgb(102, 102, 102);
            color: rgb(114, 246, 38);
            -webkit-text-stroke: 2px rgba(0, 0, 0, 0.716);
            text-align: center;
            margin-bottom: 3em;
            padding: 1em;
            font-size: 20px;
            border-bottom: rgb(46, 46, 46) 3px solid;
            border-radius: 0px 0px 0.8em 0.8em;
        }

        .caixa {
            padding: 25px;
            background-color: rgb(48, 47, 47);
            border-radius: 0.5em;
            border-bottom: rgb(102, 102, 102) solid 2px;
            width: 74.9em;
        }

        .separacao {
            position: relative;
            left: 2em;
            margin-bottom: 3em;
        }

        hr {
            margin-bottom: 3em;
            border: rgb(74, 74, 74) solid 1px;
            width: 90.5em;
            position: relative;
            left: 2em;
        }

        .markdown {
            text-align: center;
            position: relative;
            right: 1.5em;
            color: rgb(114, 246, 38);
        }

        a{
            color: rgb(114, 246, 38);
        }

        img{
            width: 20em;
            border-radius: 1em;
            border: rgb(46, 46, 46) 3px solid;
        }

        img:hover{
            border-radius: 0px;
            border: rgb(114, 246, 38) solid;
        }
    </style>
</head>

<body>
    <div id="header">
        <h1>Comandos <span>Markdown</span></h1>
    </div>
    <div class="separacao">

        <div>
            <h1 class="markdown">Titulação</h1> <br>
            <h3 class="caixa">
                Sintaxes: <br><br>
                &lt;h1&gt;Conteúdo&lt;/h1&gt;<br><br>
                &lt;h2&gt;Conteúdo&lt;/h2&gt;<br><br>
                &lt;h3&gt;Conteúdo&lt;/h3&gt;<br><br>
                h3
                h4
                h5
                h6
                ...
            </h3>

            <br><br>
            <h1>Exemplos:</h1>
            <br><br>
            <h1>Texto h1</h1><br>
            <h2>Texto h2</h2><br>
            <h3>Texto h3</h3><br>
            <h4>Texto h4</h4><br>
            <h5>Texto h5</h5><br>
            <h6>Texto h6</h6><br><br><br><br>

        </div>

        <hr>

        <div>
            <h1 class="markdown">Listas de Itens</h1> <br>
            <h3 class="caixa">
                Sintaxes: <br><br>
                <u>Lista ordenada:</u>&lt;ol&gt;Lista de conte&uacute;dos&lt;/ol&gt; <br><br>
                <u>Não ordenada:</u> &lt;ul&gt;Lista de conte&uacute;dos&lt;/ul&gt; <br><br>
                <u>Item Listado:</u> &lt;li&gt;Item&lt;/li&gt; (<u>obs:</u> listar dentro de uma ol ou ul)
            </h3>

            <br><br>
            <h1>Exemplos:</h1>
            <br><br>

            <u>Lista ordenada:</u>
            <br><br>
            <ol>
                <li>Conteúdo 1</li>
                <li>Conteúdo 2</li>
                <li>Conteúdo 3</li>
                <li>Conteúdo 4</li>
                <li>Conteúdo 5</li>
            </ol>
            <br><br>
            <u>Lista Não ordenada:</u>
            <br><br>
            <ul>
                <li>Conteúdo 1</li>
                <li>Conteúdo 2</li>
                <li>Conteúdo 3</li>
                <li>Conteúdo 4</li>
                <li>Conteúdo 5</li>
                <br><br><br><br>
            </ul>



        </div>

        <hr>

        <div>
            <h1 class="markdown">Links</h1> <br>
            <h3 class="caixa">
                Sintaxe: <br><br>
                &lt;a href="Local de destino"&gt;Conte&uacute;do&lt;/a&gt;
              
            </h3>

            <br><br>
            <h1>Exemplo:</h1>
            <br><br>
            <a href="index.html">Link Para esta aba</a>
            <br><br><br><br>
            

        </div>
        
        <hr>

        <div>
            <h1 class="markdown">Ênfase</h1> <br>
            <h3 class="caixa">
                Sintaxes: <br><br>    
                <u>Negrito:</u>  &lt;b&gt;Conte&uacute;do&lt;/b&gt; <br><br>
                <u>Itálico:</u>  &lt;i&gt;Conte&uacute;do&lt;/i&gt;
            </h3>
            

            <br><br>
            <h1>Exemplos:</h1>
            <br><br>
            Conteúdo sem Ênfase
            <br>
            <b>Conteúdo em Negrito</b>
            <br>
            <i>Conteúdo em Itálico</i>
            <br><br><br><br>
       </div>
        
        <hr>

        <div>
            <h1 class="markdown">Imagem</h1> <br>
            <h3 class="caixa">
                Sintaxe: <br><br>
                &lt;img src="Url ou local da imagem" alt="Texto alternativo (caso a imagem não carregue)"&gt;
              
            </h3>

            <br><br>
            <h1>Exemplo:</h1>
            <br><br>
            <img src="https://scontent-gig2-1.xx.fbcdn.net/v/t39.30808-6/299360659_496028975835708_8806920021851579205_n.png?_nc_cat=101&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=F-qLv6DiCiAAX_3VjeE&_nc_ht=scontent-gig2-1.xx&oh=00_AfBpu2MwKartv4mMoqTlxAsQxVUzwn2QrKXJpTEpbzBiAw&oe=63DFC744" alt="Logo da Tech4me">
            <br><br><br><br>
            

        </div>
        
        <hr>
    </div>



    <h2 class="sintaxe"></h2>
</body>

</html>