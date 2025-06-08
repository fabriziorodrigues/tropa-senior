# tropa-senior
#Mini-projeto, agência imobiliaria fake, feito por Natalia Noronha.
#Este é apenas o HTML, o CSS é separado.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="Imagens/agencia-imobiliaria.png" type="image/x-icon">
    <link rel="stylesheet" href="Agência.css">
    <title>Agência Imobiliária</title>
</head>
<body>
    <header>
        <div id="cabecalho-container-principal">
            <div id="cabecalho-container-logo">
                <h5>Agência Imobiliária</h5>
            </div><!--container da logo do cabeçalho-->

            <nav>
                <div id="cabecalho-navegacao-container">
                    <div id="cabecalho-navegacao-items-container">
                        <a class="cabecalho-navegacao-items" href="#" target="_self"><p>Venda</p></a>
                        <a class="cabecalho-navegacao-items" href="#" target="_self"><p>Compra</p></a>
                        <a class="cabecalho-navegacao-items" href="#" target="_self"><p>Alugar</p></a>
                        <a class="cabecalho-navegacao-items" href="#" target="_self"><p>Contato</p></a>
                        <a class="cabecalho-navegacao-items cadastro" href="#" target="_self"><img class="nav-logo" src="Imagens/cadastro.png"><p>Cadastro</p></a>
                        <a class="cabecalho-navegacao-items login" href="#" target="_self"><img class="nav-logo" src="Imagens/contorno-do-botao-de-seta-quadrado-de-login.png"><p>Login</p></a>
                    </div><!--container dos items de navegação-->
                </div><!--container da área de navegação-->
            </nav>
        </div><!--container principal do cabeçalho-->
    </header>

    <section>
            <div id="secao-banner-container">
                <div id="secao-banner-procura">

                    <div id="area-procura">
                        <h3>Agência Imobiliaria Fake: A realisadora de sonhos!</h3>

                        <p>Encontre seu imóvel ideal</p>

                        <div id="area-procura-labels">
                            <label for="procura-negocios">Négocio</label>
                            <label for="procura-imoveis">Tipo de imóvel</label>
                            <label for="procura-cidade">Cidade</label>
                        </div><!--container dos labels-->

                            <div id="area-procura-inputs-button-container">
                                <input type="text" name="procura-negocios" id="procura-negocios">
                                <input type="text" name="procura-imoveis" id="procura-imoveis">
                                <input type="text" name="procura-cidade" id="procura-cidade">

                                <button type="button">Pesquisar</button>
                            </div><!--container dos inputs e do botão-->

                    </div><!--area de procura de imoveis-->
                </div><!--container da area de procura de imoveis-->
            </div><!--container do banner-->
    </section>

    <section>
        <div id="nossa-historia-container">
            
        </div><!--container principal da área "Nossa historia"-->
    </section>
 </div>
</body>
</html>
