<!DOCTYPE html>
<html>
    <body>
<style>
@import url('https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&display=swap');

* {
    font-family: 'Rajdhani', sans-serif;
}
body {
    background-color:#202225
}
.nav-barra {
    overflow: hidden;
    padding: 8px;
    background-color: #202225;
}

.nav-barra a {
    color: #f2f2f2;
    padding: 16px;
    text-decoration: none;
    font-size: 20px;
    float: right;
    display: flex;
}

.nav-barra a:hover {
    background-color: #ddd;
    color: black;
}

.nav-barra a.activo {
    background-color: rgb(216, 216, 74);
    color: black;
}

.titulos h1 {
    text-align: center;
    font-size: 70px;
    color: whitesmoke;
    padding: 100px 0px 10px 0px;
    padding-top: 100px;
    text-shadow: 4px 4px 4px #777;
}

.titulos h2 {
    text-align: center;
    font-size: 35px;
    color: whitesmoke;
    padding-top: 10px;
    padding-bottom: 100px;
}

.parrafo {
    color: white;
    font-size: 25px;
    text-align: center;
}

.interesado {
    color: white;
    font-size: 25px;
}

.img-logo {
    width: 100px;
    height: 100px;
    display: block;
}


.footer {
    color: white;
    text-align: center;
}

.footer a {
    color: white;
}

.stats h1 {
    text-align: center;
    color: white;
}

.stats h2 {
    text-align: center;
    color: white;
}
</style>
     <div class="nav-barra">
            <a href="https://github.com/OSSAHUB" target="_BLANK">Github</a>
            <a href="./servicios.html">Servicios</a>
            <a href="./proyectos.html">Proyectos</a>
            <a href="./multipana.html" class="mp">MultiPana</a>
            <a class="activo" href="index.html">Inicio</a>
            <img src="assets/ossa__b-logo.png" class="img-logo">
            </div>
            <div class="titulos">
            <h1>OSSA__B Development</h1><br>
            <h2>Hola :3 Te doy la bienvenida a mi página web! Aquí publicaré proyectos y muchas cosas más!</h2>
            </div>
            <h2 class="parrafo">
                Hola! 👋 Soy OSSA__B!<br><img src="assets/index-img1.png" width="100" style="margin:0 auto;"><br> Mis intereses en la informática son:
            </h2>
            <div class="prrfo">
                <p class="interesado">
                <img src="assets/index-www.png" width="50"> Desarrollo web <br>
                <img src="assets/index-discord.png" width="50"> Bots de discord <br>
                <img src="assets/index-unity.png" width="50"> Desarrollo de videojuegos en Unity 3D (Recién empezando) <br>
                <img src="assets/index-electron.png" width="50"> Aplicaciones de escritorio (Actualmente solo electron.js) <br>
                <img src="assets/index-makeblock.png" width="50"> Robótica en makeblock <br>
                </p>
            </div>
            <h2 class="parrafo">
            <br> Los lenguajes de programación que actualmente uso son:
            </h2>
            <div class="prrfo">
                <p class="interesado">
                <img src="assets/index-js.png" width="50"> JavaScript <br>
                <img src="assets/index-html.png" width="50"> HTML 5 <br>
                <img src="assets/index-css.png" width="50"> CSS 3 <br>
                <img src="assets/index-cs.png" width="50"> C# <br>
                <img src="assets/index-java.png" width="50"> Java <br>
                </p>
            </div>
            <h2 class="parrafo">
                <br> Estadísticas:
                </h2>
                <div class="stats">
                    <h1>Proyectos en desarrollo:</h1>
                    <h2><script>document.write(progreso)</script></h2>
                </div>
                <div class="stats">
                    <h1>Proyectos terminados:</h1>
                    <h2><script>document.write(terminado)</script></h2>
                </div>
            <br>
            <br>
            <footer class="footer">Copyright © OSSA__B Development | Todos los proyectos ya sean públicos o privados están sujetos a derechos de autor bajo la licencia <a href="https://www.apache.org/licenses/LICENSE-2.0" target="_BLANK">Apache 2.0</a> y está prohibida la copia. Son solo para referencias para tus proyectos.</footer>
            
            </body>
            </html>
