<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./css/style.css">
    <link rel="stylesheet" href="./css/tablet.css" media="(min-width:930px)"/>
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Inter:wght@300;500&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <img src="./assets/img/logo.svg" alt="">
        <div class="header-title-container">
            <h1>La proxima revolución en el intercambio de cripto monedas</h1>
            <p>Batatabit te ayuda a navegar entre los diferentes precios y tendencias</p>
            <a href="#plans" class="header-button">Conoce nuestros planes <span></span></a><!-- el span se puede usar dentro de una etiqueta de contenido al costado del mismo -->
        </div>


    </header>
    <main>
        <section class="main-exchange-container">
            <div class="backgroundimg">

            </div>
            <div class="main-exchange-container--tittle"> <!-- contenedor de texto -->
                <h2>Visibilizamos todas las tasas de cambio</h2>
                <p>Información en tiempo real de las tasas de cambio y las monedas del mundo</p>
            </div>
            <div class="main-tables-container">
                <div class="main-currency-table">
                    <p class="currency-table--tittle">Monedas</p>
                    <div class="currency-table-container">
                        <table>
                            <tr>
                                <td class="table__top-left">bitcoin</td>
                                <td class="table__top-right table__right">$1.96 <span class="icon down"></span></td>
                            </tr>
                                <td class="">Etherium</td>
                                <td class="table__right">$0.07 <span class="icon down"></span></td>
                            <tr>
                                <td class="">Ripple</td>
                                <td class="table__right">$2.15 <span class="icon up"></span></td>
                            </tr>
                            <tr>
                                <td class="table__bottom-left">Stellar</td>
                                <td class="table__bottom-right table__right">$4.96 <span class="icon down"></span></td>
                            </tr>
                        </table>
                    </div>
                </div>    
                <div class="currency-table--date">
                    <p><b>Actualizado</b>:19 Julio a las 23:45</p>
                </div>
            </div>
        </section>
        <section class="main-product--detail">
            <span class="product-detail__batataLogo"></span>
            <div class="product-detail--tittle">
                <h2>Creamos un producto sin comparación.</h2>
                <p>Confiable y diseñado para su uso diario.</p>
            </div>
            <section class="product-cards--container">
                    <article class="product-detail--card">
                        <span class="clock"></span>
                        <h3 class="product-card--tittle">Tiempo real</h3>
                        <p class="product-card--body">Nuestra API toma informacion minuto a minuto sobre las tasas que más determinan el comportamiento.</p>
                    </article>
                    <article class="product-detail--card">
                        <span class="eye"></span>
                        <h3 class="product-card--tittle">No hay tasas escondidas</h3>
                        <p class="product-card--body">No más rumores, con Babtabit sabrás el valor real de cada moneda en el mercado actual.</p>
                    </article>               
                    <article class="product-detail--card">
                        <span class="dollar"></span>
                        <h3 class="product-card--tittle">Compara monedas</h3>
                        <p class="product-card--body">No más rumores, con Babtabit sabrás el valor real de cada moneda en el mercado actual.</p>
                    </article>
                    <article class="product-detail--card">
                        <span class="check"></span>
                        <h3 class="product-card--tittle">Información confiable</h3>
                        <p class="product-card--body">Nuestras fuentes están 100% verificadas y continuamos auditando su contenido mientras se actualizan.</p>
                    </article>    
                </section>
        </section>
        <section class="bitcoin-img-container">
            <h2>Conocenos hoy</h2>
        </section>
        <section id="plans" class="main-plans-container">
            <div class="plans-tittle">
                <h2>Escoge el plan que mejor se ajuste a ti.</h2>
                <p>Cualquier plan te da acceso completo a nuestra plataforma.</p>       
            </div>
            <section class="plans-container--slider">
                <article class="plans-container--card">
                <p class="comment">Recomendado</p>
                <div class="plans-info-container">
                    <h3 class="plan-card--tittle">Pago Anual</h3> 
                    <p class="plan-card--price"><span>$</span>99</p>
                    <p class="plan-card--saving">* ahorras $129 comparado al plan mensual.</p>
                </div>
                <button class="plan-card--ca"><p> Escoge este</p><span></span></button>
                </article>
                <article class="plans-container--card">
                <p class="comment">Recomendado</p>
                <div class="plans-info-container">
                    <h3 class="plan-card--tittle">Pago Anual</h3> 
                    <p class="plan-card--price"><span>$</span>99</p>
                    <p class="plan-card--saving">* ahorras $129 comparado al plan mensual.</p>
                </div>
                <button class="plan-card--ca"><p> Escoge este</p><span></span></button>
                </article>
                <article class="plans-container--card">
                <p class="comment">Recomendado</p>
                <div class="plans-info-container">
                    <h3 class="plan-card--tittle">Pago Anual</h3> 
                    <p class="plan-card--price"><span>$</span>99</p>
                    <p class="plan-card--saving">* ahorras $129 comparado al plan mensual.</p>
                </div>
                <button class="plan-card--ca"><p> Escoge este</p><span></span></button>
                </article>
            </section>
        </section>        
    </main>
    <footer>
        <div>
            <ul>
                <li><a href="">LinkedIn</a></li>
                <li><a href="">Crunchbase</a></li>
                <li><a href="">HackerNews</a></li>
            </ul>
        </div>
        <div>
            <img src="./assets/img/logo-footer.svg" alt="Logo de batata bit está aca">
        </div>
    </footer>
</body>
</html>