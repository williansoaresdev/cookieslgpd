# cookieslgpd
Gerador de aviso de cookies da LGPD.

## Objetivo ##
Demonstrar como incluir o aviso de cookies da LGPD em seu site, sem cookies, sem plugins de terceiro.
De forma simples e fácil de aplicar.

## Requisitos ##
Saber o básico de HTML.

## Arquivos do projeto ##
### avcookies.css ###
CSS para estilizar o aviso.

### avcookies.js ###
Javascript que controla a exibição do aviso de acordo com o aceite do usuário.

### index.html ###
Exemplo de como utilizar a ferramenta.

## Como utilizar ##

Em sua página HTML, na seção head insira a chamada para a folha de estilos (preferencialmente logo antes de fechar a **head**):

        <link href="./avcookies.css" rel="stylesheet">
    </head>

Agora, no final de seu corpo HTML (preferencialmente logo antes de fechar o **body**>) insira a chamada para o script:

        <script src="./avcookies.js"></script>
    </body>

Pronto!