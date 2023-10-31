<script setup>
</script>

<template>
    <nav>
        <div class="container d-flex justify-content-between  align-items-center">
            <img src="../assets/images/logo.png" alt="">
            <div class="nav-right">
                <p>Términos y condiciones </p>
                <ul>
                    <li><a href="">Inicio</a></li>
                    <li><a href="">Nosotros</a></li>
                    <li><a href="">Contacto</a></li>
                    <li><a href="" class="button-tours">Tours a medida</a></li>
                </ul>
            </div>                
        </div>
    </nav>
    <section class="banner-header">
        
        <div class="banner-header--search  all-flex-column">
            <p>Visita los mejores destinos</p>
            <h1>Inicia tu siguiente aventura de inmediato
            </h1>
            <input type="search" placeholder="¿Dónde está tu próxima aventura?">
        </div>
    </section>

    <section class="pt-5  pb-5">
        <form>
            <div>
                <label for="destino">Destino:</label>
                <input type="text" id="destino" autocomplete="off">
            </div>
            <div>
                <label for="checkin">Fecha de Check-In:</label>
                <input type="text" id="checkin">
            </div>
            <div>
                <label for="checkout">Fecha de Check-Out:</label>
                <input type="text" id="checkout">
            </div>
            <input type="submit" value="Buscar">
        </form>
        
        
    </section>

    <section class="container  pt-5  pb-5">
        <div class="titulo  pb-5">
            Ofertas especiales
        </div>
        <div class="box-ofertas  row justify-content-center">
            <div class="col-xs-12  col-lg-4">
                <div class="box-ofertas--item  ofertas-item">
                    <img src="../assets/images/ofertas.png" alt="">
                    <div class="ofertas-detalle">
                        <div class="ofertas-detalle--etiquetas">
                            <span class="tag-morado">Adventure</span> <span>4 Días, 3 Noches</span>
                        </div>
                        <p class="ofertas-detalle--ciudad"><strong>Puno</strong></p>
                        <div class="ofertas-detalle--precio">
                            <p>
                                <strong>100$</strong> <span> /Persona</span>
                            </p>
                            <button class="button-viajes">
                                Reservar
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-xs-12  col-lg-4">
                <div class="box-ofertas--item  ofertas-item">
                    <img src="../assets/images/ofertas.png" alt="">
                    <div class="ofertas-detalle">
                        <div class="ofertas-detalle--etiquetas">
                            <span class="tag-rosado">Relax</span> <span>4 Días, 3 Noches</span>
                        </div>
                        <p class="ofertas-detalle--ciudad"><strong>Puno</strong></p>
                        <div class="ofertas-detalle--precio">
                            <p>
                                <strong>100$</strong> <span> /Persona</span>
                            </p>
                            <button class="button-viajes">
                                Reservar
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-xs-12  col-lg-4">
                <div class="box-ofertas--item  ofertas-item">
                    <img src="../assets/images/ofertas.png" alt="">
                    <div class="ofertas-detalle">
                        <div class="ofertas-detalle--etiquetas">
                            <span>Relax</span> <span>4 Días, 3 Noches</span>
                        </div>
                        <p class="ofertas-detalle--ciudad"><strong>Puno</strong></p>
                        <div class="ofertas-detalle--precio">
                            <p>
                                <strong>100$</strong> <span> /Persona</span>
                            </p>
                            <button class="button-viajes">
                                Reservar
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="pt-5  pb-5">
        <div class="container  rutina">
            <div class="row">
                <div class="col-xs-12 col-lg-4">
                    <img src="../assets/images/rutina.png" alt="">
                </div>
                <div class="col-xs-12 col-lg-8">
                    <div class="titulo">
                        Atrapado en la rutina, es tiempo de tomarte un descanso
                    </div>
                    <div class="rutina-descripcion">
                        ¡Descubre el mundo con nuestros emocionantes paquetes de viaje! En A viajar pe, estamos comprometidos en hacer tus sueños de viajar realidad. Nuestros paquetes de viaje te ofrecen experiencias únicas y memorables en destinos impresionantes de todo el mundo.
                    </div>
                    <button class="button-viajes">
                        Reservar
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section class="container  pt-5  pb-5">
        <div class="titulo  pb-4">
            Destinos recomendados
        </div>
        <div class="destino  row">
            <div class="col-xs-12  col-lg-3">
                <div class="destino--item  destino-item">
                    <span class="box-star"><img class="stars" src="../assets/images/star.png" alt="">4.5</span>
                    <img src="../assets/images/ofertas.png" alt="">
                    <div class="destino-detalle">
                        <div class="destino-detalle--etiquetas">
                            <strong>Cusco</strong>
                        </div>
                        <p class="destino-detalle--ciudad">
                            <span><img src="../assets/images/location.png" alt="">Perú</span>
                        </p>                        
                    </div>
                </div>
            </div>
            <div class="col-xs-12  col-lg-3">
                <div class="destino--item  destino-item">
                    <span class="box-star"><img class="stars" src="../assets/images/star.png" alt="">4.5</span>
                    <img src="../assets/images/ofertas.png" alt="">
                    <div class="destino-detalle">
                        <div class="destino-detalle--etiquetas">
                            <strong>Cusco</strong>
                        </div>
                        <p class="destino-detalle--ciudad">
                            <span><img src="../assets/images/location.png" alt="">Perú</span>
                        </p>                        
                    </div>
                </div>
            </div>
            <div class="col-xs-12  col-lg-3">
                <div class="destino--item  destino-item">
                    <span class="box-star"><img class="stars" src="../assets/images/star.png" alt="">4.5</span>
                    <img src="../assets/images/ofertas.png" alt="">
                    <div class="destino-detalle">
                        <div class="destino-detalle--etiquetas">
                            <strong>Cusco</strong>
                        </div>
                        <p class="destino-detalle--ciudad">
                            <span><img src="../assets/images/location.png" alt="">Perú</span>
                        </p>                        
                    </div>
                </div>
            </div>
            <div class="col-xs-12  col-lg-3">
                <div class="destino--item  destino-item">
                    <span class="box-star"><img class="stars" src="../assets/images/star.png" alt="">4.5</span>
                    <img src="../assets/images/ofertas.png" alt="">
                    <div class="destino-detalle">
                        <div class="destino-detalle--etiquetas">
                            <strong>Cusco</strong>
                        </div>
                        <p class="destino-detalle--ciudad">
                            <span><img src="../assets/images/location.png" alt="">Perú</span>
                        </p>                        
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <div class="row">
                <div class="col-xs-12">
                    
                </div>
            </div>
        </div>
    </section>

    <footer class="pt-5  pb-3">
        <div class="container">
            <div class="row">
                <div class="col-xs-12  col-lg-3">
                    <img src="../assets/images/logo.png" alt="">
                </div>
            </div>
            <div class="row  pt-3  pb-5">
                <div class="col-xs-12  col-lg-4">
                    
                    <div class="box-footer">
                        <p class="box-footer--titulo"><strong>Contacto</strong></p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>+51 +511 3044235</span>
                        </p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>Jirón de la unión 870 Ofc 115 
                                Cercado de Lima</span>
                        </p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>informes@aviajarpe.com</span>
                        </p>
                    </div>
                </div>
                <div class="col-xs-12  col-lg-4">
                    <div class="box-footer">
                        <p class="box-footer--titulo"><strong>Links</strong></p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>Privacy Policy</span>
                        </p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>Términos y condiciones</span>
                        </p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>Medidas Sanitarias</span>
                        </p>
                    </div>
                </div>
                <div class="col-xs-12  col-lg-4">
                    <div class="box-footer">
                        <p class="box-footer--titulo"><strong>Redes sociales</strong></p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>Facebook</span>
                        </p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>Instagram</span>
                        </p>
                        <p class="box-footer--parrafo">
                            <img src="../assets/images/star.png" alt=""><span>Linkedin</span>
                        </p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-12  justify-content-center">
                    <p class="text-center">© 2023 A Viajar PE - Todos los derechos reservados</p>
                </div>
            </div>
        </div>
    </footer>
</template>



<style scoped>
.titulo {
  font-weight: bold;
  font-size: 32px;
  text-align: center;
}

nav {
  display: none;
  position: fixed;
  width: 100%;
  height: 120px;
  border-bottom: 1px solid #000;
}
nav ul {
  display: flex;
  padding-top: 12px;
}
nav ul li {
  list-style: none;
}
nav ul li a {
  text-decoration: none;
  color: #fff;
  padding: 12px 18px;
}
nav ul .button-tours {
  background-color: #FFC34C;
  width: 256px;
  height: 65px;
  border-radius: 50px;
}
nav .nav-right p {
  color: #fff;
  padding-top: 24px;
  text-align: right;
}

.button-viajes {
  background-color: #FFC34C;
  border: none;
  border-radius: 25px;
  height: 47px;
  width: 107px;
  color: white;
}

.tag-rosado {
  color: #F178B6;
  background-color: #FCDDEC;
  padding: 2px 24px;
  border-radius: 24px;
  display: inline-block;
}

.tag-morado {
  color: #7879F1;
  background-color: #F1F1FD;
  padding: 4px 12px;
  display: inline-block;
}

.all-flex-column {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.box-ofertas--item {
  background-color: #fff;
  border-radius: 5%;
  padding: 12px 48px 12px 12px;
  margin: auto;
  margin-bottom: 12px;
  max-width: 380px;
}

.banner-header {
  width: 100%;
  height: 600px;
  background: url(../assets/images/banner.png);
  display: flex;
  align-items: center;
  justify-content: center;
}
.banner-header--search p {
  color: #fff;
  text-align: center;
}
.banner-header--search h1 {
  color: #fff;
  text-align: center;
}
.banner-header--search input {
  height: 45px;
  min-width: 300px;
  border-radius: 45px;
  border: 1px solid #fff;
  margin-top: 32px;
}

.ofertas-item {
  background-color: #fff;
  width: 100%;
  padding: 12px;
}

.ofertas-detalle {
  padding-left: 16px;
  margin-top: 24px;
}
.ofertas-detalle--etiquetas {
  margin-bottom: 12px;
}
.ofertas-detalle--precio {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.destino--item {
  background-color: #fff;
  border-radius: 25px;
  padding: 12px 10px;
  margin: auto;
  margin-bottom: 12px;
  width: 280px;
}
.destino--item img {
  width: 260px;
}
.destino .destino-item {
  position: relative;
}
.destino .destino-item .box-star {
  background-color: #fff;
  border-radius: 12px;
  width: 60px;
  display: inline-block;
  position: absolute;
  right: 32px;
  top: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: 500;
  font-size: 12px;
}
.destino .destino-item img.stars {
  width: 17px;
  padding-right: 4px;
}
.destino .destino-detalle {
  padding-left: 24px;
  padding-top: 12px;
}
.destino .destino-detalle--ciudad img {
  width: 17px;
}

footer {
  background-color: #1B3356;
}
footer p {
  color: #fff;
}

@media (min-width: 768px) {
  .titulo {
    font-weight: bold;
    font-size: 48px;
  }
  .carousel-inner .carousel-item:nth-child(odd) {
    display: none;
  }
}
@media (max-width: 767px) {
  .carousel-inner .carousel-item:nth-child(odd) {
    display: none;
  }
  .carousel-inner .carousel-item:nth-child(even) {
    display: block;
  }
}
@media (min-width: 1024px) {
  nav {
    display: block;
  }
}
/* Estilos modernos para el calendario */
.flatpickr-calendar {
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
  font-family: Arial, sans-serif;
  font-size: 14px;
}

/* Estilos para el campo de destino */
.awesomplete {
  width: 100%;
  max-width: 300px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 16px;
}

/* Estilo para el campo de mes */
.flatpickr-monthDropdown-months {
  text-transform: uppercase;
}

/* Estilo para los botones de navegación del calendario */
.flatpickr-prev-month, .flatpickr-next-month {
  background-color: #007BFF;
  color: #fff;
  padding: 5px 10px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.flatpickr-prev-month:hover, .flatpickr-next-month:hover {
  background-color: #0056b3;
}/*# sourceMappingURL=index.css.map */
</style>