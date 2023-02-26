---
layout: post
title: "Ackerman - Raio da Curva descrita"
date: 2023-02-26 10:00:00 -0300
categories: matematica ferramentas
author: paulo
---
<html>

<head>
    <meta content="text/html; charset=UTF-8" http-equiv="content-type">
    <style type="text/css">
        .lst-kix_list_1-3>li:before {
            content: "\0025cf  "
        }

        .lst-kix_list_1-4>li:before {
            content: "\0025cb  "
        }

        ul.lst-kix_list_1-0 {
            list-style-type: none
        }

        .lst-kix_list_1-7>li:before {
            content: "\0025cb  "
        }

        .lst-kix_list_1-5>li:before {
            content: "\0025a0  "
        }

        .lst-kix_list_1-6>li:before {
            content: "\0025cf  "
        }

        li.li-bullet-0:before {
            margin-left: -18pt;
            white-space: nowrap;
            display: inline-block;
            min-width: 18pt
        }

        ul.lst-kix_list_1-3 {
            list-style-type: none
        }

        .lst-kix_list_1-0>li:before {
            content: "\0025cf  "
        }

        ul.lst-kix_list_1-4 {
            list-style-type: none
        }

        .lst-kix_list_1-8>li:before {
            content: "\0025a0  "
        }

        ul.lst-kix_list_1-1 {
            list-style-type: none
        }

        ul.lst-kix_list_1-2 {
            list-style-type: none
        }

        ul.lst-kix_list_1-7 {
            list-style-type: none
        }

        .lst-kix_list_1-1>li:before {
            content: "\0025cb  "
        }

        .lst-kix_list_1-2>li:before {
            content: "\0025a0  "
        }

        ul.lst-kix_list_1-8 {
            list-style-type: none
        }

        ul.lst-kix_list_1-5 {
            list-style-type: none
        }

        ul.lst-kix_list_1-6 {
            list-style-type: none
        }

        ol {
            margin: 0;
            padding: 0
        }

        table td,
        table th {
            padding: 0
        }

        .c9 {
            -webkit-text-decoration-skip: none;
            color: #000000;
            font-weight: 400;
            text-decoration: line-through;
            vertical-align: baseline;
            text-decoration-skip-ink: none;
            font-size: 11pt;
            font-family: "Arial";
            font-style: normal
        }

        .c15 {
            color: #000000;
            font-weight: 400;
            text-decoration: none;
            vertical-align: baseline;
            font-size: 3pt;
            font-family: "Arial";
            font-style: normal
        }

        .c16 {
            padding-top: 0pt;
            padding-bottom: 3pt;
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        .c8 {
            color: #000000;
            font-weight: 400;
            text-decoration: none;
            vertical-align: baseline;
            font-size: 26pt;
            font-family: "Arial";
            font-style: normal
        }

        .c0 {
            color: #000000;
            font-weight: 400;
            text-decoration: none;
            vertical-align: baseline;
            font-size: 11pt;
            font-family: "Arial";
            font-style: normal
        }

        .c13 {
            color: #000000;
            font-weight: 400;
            text-decoration: none;
            vertical-align: baseline;
            font-size: 11pt;
            font-family: "Arial";
            font-style: italic
        }

        .c10 {
            padding-top: 20pt;
            padding-bottom: 6pt;
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        .c11 {
            color: #000000;
            font-weight: 400;
            text-decoration: none;
            vertical-align: baseline;
            font-size: 22pt;
            font-family: "Arial";
            font-style: normal
        }

        .c6 {
            color: #000000;
            font-weight: 400;
            text-decoration: none;
            vertical-align: baseline;
            font-size: 20pt;
            font-family: "Arial";
            font-style: normal
        }

        .c1 {
            padding-top: 0pt;
            padding-bottom: 0pt;
            line-height: 1.1500000000000001;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        .c4 {
            text-decoration-skip-ink: none;
            -webkit-text-decoration-skip: none;
            color: #1155cc;
            text-decoration: underline
        }

        .c14 {
            background-color: #ffffff;
            max-width: 451.5pt;
            padding: 72pt 72pt 72pt 72pt
        }

        .c12 {
            text-decoration-skip-ink: none;
            -webkit-text-decoration-skip: none;
            text-decoration: line-through
        }

        .c3 {
            margin-left: 36pt;
            padding-left: 0pt
        }

        .c5 {
            color: inherit;
            text-decoration: inherit
        }

        .c18 {
            padding: 0;
            margin: 0
        }

        .c17 {
            font-style: italic
        }

        .c2 {
            height: 11pt
        }

        .c7 {
            font-size: 14pt
        }

        .title {
            padding-top: 0pt;
            color: #000000;
            font-size: 26pt;
            padding-bottom: 3pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        .subtitle {
            padding-top: 0pt;
            color: #666666;
            font-size: 15pt;
            padding-bottom: 16pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        li {
            color: #000000;
            font-size: 11pt;
            font-family: "Arial"
        }

        p {
            margin: 0;
            color: #000000;
            font-size: 11pt;
            font-family: "Arial"
        }

        h1 {
            padding-top: 20pt;
            color: #000000;
            font-size: 20pt;
            padding-bottom: 6pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        h2 {
            padding-top: 18pt;
            color: #000000;
            font-size: 16pt;
            padding-bottom: 6pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        h3 {
            padding-top: 16pt;
            color: #434343;
            font-size: 14pt;
            padding-bottom: 4pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        h4 {
            padding-top: 14pt;
            color: #666666;
            font-size: 12pt;
            padding-bottom: 4pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        h5 {
            padding-top: 12pt;
            color: #666666;
            font-size: 11pt;
            padding-bottom: 4pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            orphans: 2;
            widows: 2;
            text-align: left
        }

        h6 {
            padding-top: 12pt;
            color: #666666;
            font-size: 11pt;
            padding-bottom: 4pt;
            font-family: "Arial";
            line-height: 1.1500000000000001;
            page-break-after: avoid;
            font-style: italic;
            orphans: 2;
            widows: 2;
            text-align: left
        }
    </style>
</head>

<body class="c14 doc-content">
    <p class="c16 title" id="h.gjdgxs"><span class="c8">Defini&ccedil;&atilde;o do raio de curva e do &acirc;ngulo de
            ataque atrav&eacute;s de tr&ecirc;s pontos</span></p>
    <p class="c1 c2"><span class="c0"></span></p>
    <p class="c1"><span>A empilhadeira do projeto </span><span>Indorama</span><span class="c0">&nbsp;utiliza um sistema
            de dire&ccedil;&atilde;o pivotado exc&ecirc;ntrico de forma a compensar a diferen&ccedil;a angular nas duas
            rodas traseiras quando operando em curvas. Assim, o &acirc;ngulo observado &eacute; diferente, de acordo com
            qual roda est&aacute; no lado interno da curva. Corresponde efetivamente ao conceito da geometria de
            Ackerman.</span></p>
    <p class="c1"><span
            style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 553.28px; height: 309.84px;"><img
                alt="" src="/docs/images/image6.png"
                style="width: 553.28px; height: 309.84px; margin-left: -0.00px; margin-top: -0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);"
                title=""></span></p>
    <p class="c1"><span>Isso torna-se um problema na empilhadeira pois o sensor que monitora a posi&ccedil;&atilde;o do
            eixo n&atilde;o est&aacute; montado no centro de um conjunto pinh&atilde;o e cremalheira, e sim na ponta de
            um dos eixos. Curvas para um lado </span><span>ester&ccedil;am</span><span class="c0">&nbsp;a roda quase
            totalmente na horizontal enquanto a outra roda oferece um &acirc;ngulo ligeiramente inclinado. O inverso se
            observa quando a curva for feita para o lado oposto.</span></p>
    <p class="c1"><span
            style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 692.50px; height: 260.27px;"><img
                alt="" src="/docs/images/image8.png"
                style="width: 692.50px; height: 260.27px; margin-left: -0.00px; margin-top: -0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);"
                title=""></span></p>
    <p class="c1"><span
            style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 667.50px; height: 278.46px;"><img
                alt="" src="/docs/images/image7.png"
                style="width: 667.50px; height: 278.46px; margin-left: -0.00px; margin-top: -0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);"
                title=""></span></p>
    <p class="c1 c2"><span class="c0"></span></p>
    <p class="c1"><span class="c0">Atrav&eacute;s dos conceitos b&aacute;sicos de trigonometria e de semelhan&ccedil;a
            de tri&acirc;ngulos &eacute; poss&iacute;vel determinar o raio da curva de um objeto em movimento circular
            (MC).</span></p>
    <p class="c1"><span class="c0">Para isso devemos utilizar as leituras dos scanners para definir o plano, ponto
            inicial, ponto intermedi&aacute;rio e ponto final. Com tr&ecirc;s pontos n&atilde;o colineares &eacute;
            poss&iacute;vel determinar uma circunfer&ecirc;ncia &uacute;nica, relativa a um raio &uacute;nico.</span>
    </p>
    <p class="c1"><span class="c0">O volante de dire&ccedil;&atilde;o deve ser acionado e registrado o valor lido de
            inclina&ccedil;&atilde;o indicado pelo sensor.</span></p>
    <p class="c1"><span class="c0">Esse valor lido refere-se a inclina&ccedil;&atilde;o na roda, que define o raio da
            curvatura.</span></p>
    <p class="c1 c2"><span class="c0"></span></p>
    <p class="c1 c2"><span class="c0"></span></p>
    <p class="c1"><span
            style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 588.50px; height: 312.21px;"><img
                alt="" src="/docs/images/image10.png"
                style="width: 588.50px; height: 312.21px; margin-left: -0.00px; margin-top: -0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);"
                title=""></span></p>
    <p class="c1"><span
            style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 624.50px; height: 98.61px;"><img
                alt="" src="/docs/images/image9.png"
                style="width: 624.50px; height: 98.61px; margin-left: -0.00px; margin-top: -0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);"
                title=""></span></p>
    <p class="c1"><span class="c4"><a class="c5"
                href="https://www.google.com/url?q=https://docs.google.com/spreadsheets/u/0/d/1c5jDQXhziRNmU11Qgrh6cyj4rT9BrWs90MtyBox3-pM/edit&amp;sa=D&amp;source=editors&amp;ust=1677420684224869&amp;usg=AOvVaw3gkXaFRmGnd8TevK1yIw5m">Link
                da planilha</a></span></p>
    <p class="c1"><span>O objeto descrevendo a trajet&oacute;ria circular &eacute; sempre tangente ao ponto da
            circunfer&ecirc;ncia </span><span>e perpendicular</span><span class="c0">&nbsp;ao raio. A dist&acirc;ncia
            entre eixos da empilhadeira forma o cateto oposto ao &acirc;ngulo &#x1d7a1;, enquanto que o raio forma o
            cateto adjacente ao &acirc;ngulo &#x1d7a1;. Por semelhan&ccedil;a de tri&acirc;ngulos ele &eacute; o
            &acirc;ngulo de ataque da roda, ou de inclina&ccedil;&atilde;o que acompanhar&aacute; a
            circunfer&ecirc;ncia.</span></p>
    <p class="c1"><span class="c0">Esse &acirc;ngulo &#x1d7a1; &eacute; o &acirc;ngulo de inclina&ccedil;&atilde;o da
            roda central ou equivalente &agrave; geometria Ackermann, como se fosse um triciclo. Ele &eacute; calculado
            pela fun&ccedil;&atilde;o:</span></p>
    <p class="c1"><img src="/docs/images/image1.png"></p>
    <p class="c1"><img src="/docs/images/image2.png"><span class="c7">: Theta Ackerman equivalente</span></p>
    <p class="c1"><span class="c0">L: Dist&acirc;ncia entre eixos</span></p>
    <p class="c1"><span class="c0">R: Raio do giro </span></p>
    <p class="c1 c2"><span class="c0"></span></p>
    <p class="c1"><span class="c0">O &acirc;ngulo da roda interna &agrave; curva, que faz uma circunfer&ecirc;ncia de
            raio menor, &eacute; calculado pela fun&ccedil;&atilde;o:</span></p>
    <p class="c1"><img src="/docs/images/image3.png"></p>
    <p class="c1"><img src="/docs/images/image4.png"><span class="c7">: Theta interno</span></p>
    <p class="c1"><span class="c0">L: Dist&acirc;ncia entre eixos</span></p>
    <p class="c1"><span class="c0">R: Raio do giro</span></p>
    <p class="c1"><span class="c0">T: Dist&acirc;ncia entre rodas</span></p>
    <p class="c1 c2"><span class="c0"></span></p>
    <p class="c1"><span>O &acirc;ngulo da roda externa a curva, que faz uma circunfer&ecirc;ncia de raio maior, &eacute;
            calculado pela fun&ccedil;&atilde;o </span><img src="/docs/images/image5.png"></p>
    <p class="c1"><img src="/docs/images/image2.png"><span class="c7">: Theta externo</span></p>
    <p class="c1"><span class="c0">L: Dist&acirc;ncia entre eixos</span></p>
    <p class="c1"><span class="c0">R: Raio do giro</span></p>
    <p class="c1"><span class="c0">T: Dist&acirc;ncia entre rodas</span></p>
    <p class="c1"><span class="c0">&nbsp;</span></p>
    <h1 class="c10" id="h.30j0zll"><span class="c6">Resultados esperados:</span></h1>
    <ul class="c18 lst-kix_list_1-0 start">
        <li class="c1 c3 li-bullet-0"><span class="c12">Criar tabela relacionando posi&ccedil;&atilde;o do sensor,
                &acirc;ngulo Ackermann e raio obtido na curva</span></li>
        <li class="c1 c3 li-bullet-0"><span class="c9">Passar ao MCU o valor final esperado do sensor de
                posi&ccedil;&atilde;o do steering para as posi&ccedil;&otilde;es relativas ao raio esperado.</span></li>
        <li class="c1 c3 li-bullet-0"><span class="c17">Criar uma malha fechada que monitore e corrija a
                posi&ccedil;&atilde;o de steering em fun&ccedil;&atilde;o do raio descrito pelos valores lidos nos
                scanners, corrigindo o deslocamento em tempo real.</span></li>
    </ul>
    <p class="c1 c2"><span class="c0"></span></p>
    <p class="c1 c2"><span class="c0"></span></p>
</body>

</html>