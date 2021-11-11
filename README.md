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

Ainda na página HTML, adicione o corpo do aviso de cookies, no final do conteúdo (antes do fim do **body**)

    <!-- Box para o aviso LGPD -->
    <div class="box-cookies hide">
        <p class="msg-cookies">Este site usa cookies para garantir que você obtenha uma melhor experiência.</p>
        <button class="btn-cookies">Aceitar!</button>
    </div>
    <!-- Fim Box para o aviso LGPD -->

Agora, ainda no final de seu corpo HTML (preferencialmente logo antes de fechar o **body**) insira a chamada para o script:

        <script src="./avcookies.js"></script>
    </body>

Pronto!