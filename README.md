<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8" />
    <title>projeto picpro</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@1,300&display=swap" rel="stylesheet" />
    <link rel="stylesheet" type="text/css" href="./ASSETS/css/reset.css" />
    <link rel="stylesheet" type="text/css" href="./ASSETS/css/style.css" />
</head>

<body>

    <!--cabeçalho-->
    <header class="cabecaralho">
        <div class="container">
            <figure class="cabeçalhologo_picpro">
                <img src="./ASSETS/img/logo-picpro.png" alt="logo pic pro">
            </figure>
            <figure class="cabeçaralho_logo_kenzie">
                <img src="./ASSETS/img/logo-kenzie.png" alt="logo da kenzie">
            </figure>
        </div>
    </header>

    <!--conteudo principal-->
    <main>
        <section class="secaodetalhesconta">
            <div class="container">
                <div class="secaodetalhesconta_usuario">
                    <div class="secaodetalhesconta_usuario_nome">
                        <img src="./ASSETS/img/usuario.png" alt="icone do usuario">
                        <p>Bem Vindo, <strong>@gansgans</strong></p>
                    </div>
                    <div class="secaodetalhesconta_usuario_icones">
                        <img src="./ASSETS/img/presente.png" alt="icone_presente">
                        <img src="./ASSETS/img/chat.png" alt="icone_chat">
                    </div>
                </div>
                <div class="secaodetalhesconta_saldo">
                    <div>
                        <p>Saldo pic pay</p>
                        <div class="secaodetalhesconta_saldo_valor">
                            <p>R$ 100mil</p>
                            <img src="./ASSETS/img/visualizar.png" alt="olhinho">
                        </div>
                    </div>
                    <button>Extrato</button>
                </div>
                <ul class="secaodetalhesconta_opcoestransacao">
                    <li class="secaodetalhesconta_itemtransacao secaodetalhesconta_itemtransacao_qrcode" id="1">
                        <figure>
                            <img src="./ASSETS/img/qrcode.png" alt="icone qr code">
                        </figure>
                        <p>qr code</p>
                    </li>
                    <li class="secaodetalhesconta_itemtransacao secaodetalhesconta_itemtransacao_pix" id="2">
                        <figure>
                            <img src="./ASSETS/img/pix.png" alt="icone pix">
                        </figure>
                        <p>pix</p>
                    </li>
                    <li class="secaodetalhesconta_itemtransacao secaodetalhesconta_itemtransacao_codigo" id="3">
                        <figure>
                            <img src="./ASSETS/img/codigo.png" alt="icone codigo">
                        </figure>
                        <p>Pagar Boleto</p>
                    </li>
                    <li class="secaodetalhesconta_itemtransacao secaodetalhesconta_itemtransacao_cobrar" id="4">
                        <figure>
                            <img src="./ASSETS/img/cobrar-icon.png" alt="icone cobrar">
                        </figure>
                        <p>cobrar</p>
                    </li>
                </ul>
            </div>
        </section>

        <section class="secaotransacao">

            <!--div geral-->
            <div class="container">

                <!--selecionar forma de pagamento-->
                <div class="secaotransacao_aviso mostrar">
                    <p>Selecione a forma de pagmentos</p>
                    <img src="./ASSETS/img/banner.png" alt="banner pic pay">
                </div>

                <!--qr code-->
                <div data-id="1" class="secaotransacao_qrcode">
                    <img src="./ASSETS/img/qrcode-imagem.png" alt="img do qrcode">
                    <p>@gansgiofrino</p>
                    <button>cobre um inimigo</button>
                    <a href="">compartilhar meu codigo</a>
                </div>

                <!--pix-->
                <div data-id="2" class="secaotransacao_pix">
                    <img src="./ASSETS/img/pix-logo.png" alt="pix logo">
                    <div class="secaotransacao_box">
                        <img src="./ASSETS/img/pix1.png" alt="opção pix">
                        <p>envie por cpf/cnpj ou chave eletronica</p>
                    </div>
                    <div class="secaotransacao_box">
                        <img src="./ASSETS/img/pix2.png" alt="opção pix">
                        <p>inisra um codigo pix copia e cola</p>
                    </div>
                </div>

                <!--boleto-->
                <div data-id="3" class="secaotransacao_boleto">
                    <img src="./ASSETS/img/boleto.png" alt="imagem boleto">
                    <h2>pagar com codigo de barras</h2>
                    <p>voce parcelar suas comprar em ate 12x</p>
                    <input type="text" placeholder="insira o codigo de barras">
                </div>

                <!--cobrar-->
                <div data-id="4" class="secaotransacao_cobrar">
                    <img src="./ASSETS/img/cobrar.png" alt="icone cobrar">
                    <h2>cobrar</h2>
                    <p>divida a conta com os amigos</p>
                    <div class="secaotransacao_box">
                        <img src="./ASSETS/img/picpay-icon.png" alt="picpay icon">
                        <p>
                            <strong>Amigos do picpay</strong> <br> Descubra e acompanhe os gastos com os seus amigos
                            </br>
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!--rodape-->
        <footer class="rodape">
            <div class="container">
                <ul class="rodape_principal">
                    <li class="rodape_menuitem">
                        <a href="#">
                            <img src="./ASSETS/img/inicio.png" alt="icone inicio">
                            <p>inicio</p>
                        </a>
                    </li>
                    <li class="rodape_menuitem">
                        <a href="#">
                            <img src="./ASSETS/img/carteira-icon.png" alt="icone carteira">
                            <p>carteira</p>
                        </a>
                    </li>
                    <li class="rodape_menuitem rodape_menuitem-pagar">
                        <a href="#">
                            <img src="./ASSETS/img/pagar.png" alt="icone pagar">
                            <p>pagar</p>
                        </a>
                    </li>
                    <li class="rodape_menuitem">
                        <a href="#">
                            <img src="./ASSETS/img/notificacao.png" alt="icone notificacao">
                            <p>notificação</p>
                        </a>
                    </li>
                    <li class="rodape_menuitem">
                        <a href="#">
                            <img src="./ASSETS/img/bolsa.png" alt="icone bolsa">
                            <p>store</p>
                        </a>
                    </li>
                </ul>
            </div>
        </footer>
    </main>

    <script src="./ASSETS/js/script.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>
</body>

</html>
