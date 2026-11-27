# Sanando-desde-las-ra-ces-pest-n-
Invernadero Digital dedicado al estudio del pestón (Brickellia veronicifolia), planta utilizada tradicionalmente en la comunidad de Santiago Yeche. Incluye información sobre sus características botánicas, propiedades atribuidas, usos tradicionales, formas de preparación y precauciones. 
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sanando desde mis raíces</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Georgia, serif;
    background: #f5f3e8;
    color: #354b35;
    line-height: 1.6;
}

header {
    background: #244b35;
    color: white;
    padding: 25px;
    text-align: center;
}

header h1 {
    font-size: 35px;
    letter-spacing: 2px;
}

nav {
    background: #456b4c;
    padding: 15px;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 10;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 12px;
    font-size: 15px;
}

nav a:hover {
    color: #e8dba7;
}

.hero {
    min-height: 400px;
    background: linear-gradient(#193b2990, #193b2990),
    url("https://images.unsplash.com/photo-1470252649378-9c29740c9fa8");
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    padding: 30px;
}

.hero h2 {
    font-size: 40px;
}

.hero p {
    font-size: 18px;
    margin-top: 15px;
}

section {
    padding: 55px 8%;
}

h2 {
    text-align: center;
    margin-bottom: 25px;
    color: #315b3c;
    font-size: 29px;
}

.intro {
    text-align: center;
    max-width: 850px;
    margin: auto;
}

.catalogo {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
}

.planta {
    background: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 12px #0002;
    transition: 0.3s;
}

.planta:hover {
    transform: translateY(-6px);
}

.planta img {
    width: 100%;
    height: 190px;
    object-fit: cover;
}

.planta div {
    padding: 18px;
}

.planta h3 {
    color: #315b3c;
    margin-bottom: 8px;
}

.especial {
    background: #e5eadb;
}

.destacado {
    background: white;
    padding: 25px;
    border-left: 6px solid #66834d;
    border-radius: 10px;
    max-width: 900px;
    margin: auto;
}

.destacado h3 {
    color: #315b3c;
    margin: 15px 0 8px;
}

.aviso {
    background: #f1e7cb;
    padding: 25px;
    border-radius: 10px;
    max-width: 850px;
    margin: auto;
}

input {
    display: block;
    width: 100%;
    max-width: 450px;
    padding: 12px;
    margin: 0 auto 25px;
    border: 1px solid #8a9c7d;
    border-radius: 8px;
    font-size: 16px;
}

footer {
    background: #244b35;
    color: white;
    text-align: center;
    padding: 25px;
}

footer a {
    color: #e8dba7;
}

@media(max-width:600px) {
    header h1 {
        font-size: 25px;
    }

    nav a {
        display: inline-block;
        margin: 5px;
        font-size: 13px;
    }

    .hero h2 {
        font-size: 28px;
    }
}
</style>
</head>

<body>

<header>
    <h1>Sanando desde mis raíces</h1>
    <p>La sabiduría de las plantas medicinales</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#nosotros">Proyecto</a>
    <a href="#plantas">Plantas</a>
    <a href="#peston">Pestón</a>
    <a href="#cuidados">Cuidados</a>
    <a href="#fuentes">Fuentes</a>
</nav>

<div class="hero" id="inicio">
    <div>
        <h2>La naturaleza guarda grandes conocimientos</h2>
        <p>Conservando nuestras raíces y tradiciones medicinales.</p>
    </div>
</div>

<section id="nosotros">
    <h2>Sobre nuestro proyecto</h2>
    <div class="intro">
        <p>
        La herbolaria es una práctica tradicional que utiliza
        plantas para diferentes propósitos relacionados con
        el bienestar y la salud.
        </p>
        <br>
        <p>
        Este proyecto busca investigar, reconocer y preservar
        los conocimientos sobre las plantas medicinales de
        nuestra comunidad, valorando la relación entre la
        naturaleza, la cultura y nuestras raíces.
        </p>
        <br>
        <p>
        A través de la investigación y los conocimientos
        transmitidos de generación en generación, buscamos
        dar importancia a la biodiversidad y a la medicina
        tradicional de Santiago Yeche.
        </p>
    </div>
</section>

<section id="plantas">
    <h2>Catálogo de plantas medicinales</h2>

    <input type="text" id="buscador"
    placeholder="Buscar una planta..."
    onkeyup="buscarPlanta()">

    <div class="catalogo" id="catalogo">

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1618164436241-4473940d1f5c" alt="Lavanda">
            <div>
                <h3>Lavanda</h3>
                <p><b>Nombre científico:</b> Lavandula angustifolia.</p>
                <p>Tradicionalmente utilizada por su aroma y en preparaciones relajantes.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1470252649378-9c29740c9fa8" alt="Romero">
            <div>
                <h3>Romero</h3>
                <p><b>Nombre científico:</b> Salvia rosmarinus.</p>
                <p>Planta aromática utilizada tradicionalmente en infusiones y preparaciones caseras.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1603905179139-3f44e6d9c6b5" alt="Manzanilla">
            <div>
                <h3>Manzanilla</h3>
                <p><b>Nombre científico:</b> Matricaria chamomilla.</p>
                <p>Tradicionalmente empleada en infusiones relacionadas con el bienestar digestivo.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" alt="Sábila">
            <div>
                <h3>Sábila</h3>
                <p><b>Nombre científico:</b> Aloe vera.</p>
                <p>Conocida por sus usos tradicionales en el cuidado de la piel.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1591955506264-3f5a6834570a" alt="Hierbabuena">
            <div>
                <h3>Hierbabuena</h3>
                <p><b>Nombre científico:</b> Mentha spicata.</p>
                <p>Planta aromática utilizada tradicionalmente en infusiones y preparaciones digestivas.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1504545102780-26774c1bb073" alt="Caléndula">
            <div>
                <h3>Caléndula</h3>
                <p><b>Nombre científico:</b> Calendula officinalis.</p>
                <p>Tradicionalmente utilizada en preparaciones para el cuidado de la piel.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1490750967868-88aa4486c946" alt="Ruda">
            <div>
                <h3>Ruda</h3>
                <p><b>Nombre científico:</b> Ruta graveolens.</p>
                <p>Planta conocida por sus usos en la medicina tradicional. Su consumo puede ser tóxico.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735" alt="Gordolobo">
            <div>
                <h3>Gordolobo</h3>
                <p><b>Nombre científico:</b> Verbascum thapsus.</p>
                <p>Tradicionalmente empleado en preparaciones relacionadas con el bienestar respiratorio.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1508615070457-7baeba4003ab" alt="Diente de león">
            <div>
                <h3>Diente de león</h3>
                <p><b>Nombre científico:</b> Taraxacum officinale.</p>
                <p>Planta utilizada tradicionalmente en diferentes preparaciones herbales.</p>
            </div>
        </article>

        <article class="planta">
            <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef" alt="Llantén">
            <div>
                <h3>Llantén</h3>
                <p><b>Nombre científico:</b> Plantago major.</p>
                <p>Conocido por sus aplicaciones tradicionales en el cuidado de la piel.</p>
            </div>
        </article>

    </div>
</section>

<section class="especial" id="peston">
    <h2>Planta destacada: El pestón</h2>

    <div class="destacado">
        <h3>Brickellia veronicifolia (Kunth) A.Gray</h3>

        <p>
        El pestón es una planta perteneciente a la familia
        Asteraceae, conocida por su presencia en distintas
        regiones de México y por sus usos dentro de la
        medicina tradicional.
        </p>

        <h3>Características</h3>
        <p>
        Es una planta herbácea o arbustiva que crece en
        ambientes naturales. Sus características botánicas
        permiten identificarla y diferenciarla de otras
        especies vegetales.
        </p>

        <h3>Componentes fitoquímicos</h3>
        <p>
        En investigaciones experimentales se han reportado
        flavonoides, terpenos y otros compuestos fenólicos
        en extractos de esta especie.
        </p>

        <h3>Actividades estudiadas</h3>
        <p>
        Algunos estudios experimentales han investigado
        posibles actividades antioxidantes,
        antiinflamatorias y gastroprotectoras.
        Sin embargo, estos resultados no demuestran
        eficacia clínica en seres humanos.
        </p>

        <h3>Usos tradicionales</h3>
        <p>
        Su uso forma parte de los conocimientos
        tradicionales sobre plantas medicinales.
        Las formas de preparación pueden variar
        entre comunidades.
        </p>

        <h3>Conservación</h3>
        <p>
        Es importante identificar correctamente la especie,
        evitar su recolección excesiva y proteger los
        espacios naturales donde crece.
        </p>
    </div>
</section>

<section id="cuidados">
    <h2>Recomendaciones y precauciones</h2>

    <div class="aviso">
        <p>
        Las plantas medicinales contienen sustancias
        naturales que pueden producir efectos no deseados.
        Su origen natural no significa que sean
        completamente seguras.
        </p>
        <br>
        <ul>
            <li>Identificar correctamente cada especie.</li>
            <li>Evitar utilizar plantas contaminadas o en mal estado.</li>
            <li>No sustituir tratamientos médicos por remedios caseros.</li>
            <li>Consultar a un profesional de salud antes de utilizar plantas medicinales.</li>
            <li>Evitar su uso durante el embarazo o lactancia sin orientación profesional.</li>
            <li>No consumir especies tóxicas como la ruda sin supervisión especializada.</li>
        </ul>
    </div>
</section>

<section id="fuentes">
    <h2>Fuentes de información</h2>

    <div class="destacado">
        <p><b>Universidad Nacional Autónoma de México.</b></p>
        <p>Portal de Datos Abiertos, registro de Brickellia veronicifolia.</p>
        <a href="https://datosabiertos.unam.mx/IBUNAM:MEXU:700182" target="_blank">
        Consultar registro de la UNAM
        </a>

        <br><br>

        <p><b>UNAM.</b></p>
        <p>Atlas de las Plantas de la Medicina Tradicional Mexicana.</p>
        <a href="https://www.medicinatradicionalmexicana.unam.mx/" target="_blank">
        Consultar atlas de medicina tradicional
        </a>

        <br><br>

        <p><b>Royal Botanic Gardens, Kew.</b></p>
        <p>Información botánica y taxonómica de plantas.</p>
        <a href="https://powo.science.kew.org/" target="_blank">
        Consultar Plants of the World Online
        </a>
    </div>
</section>

<footer>
    <h3>Sanando desde mis raíces</h3>
    <p>Conservando la sabiduría de nuestra comunidad.</p>
    <p>Proyecto escolar de herbolaria | 2026</p>
    <p>Santiago Yeche, México.</p>
</footer>

<script>
function buscarPlanta() {
    let entrada = document.getElementById("buscador")
        .value.toLowerCase();

    let plantas = document.querySelectorAll(".planta");

    plantas.forEach(function(planta) {
        let nombre = planta.innerText.toLowerCase();

        if (nombre.includes(entrada)) {
            planta.style.display = "block";
        } else {
            planta.style.display = "none";
        }
    });
}
</script>

</body>
</html>
