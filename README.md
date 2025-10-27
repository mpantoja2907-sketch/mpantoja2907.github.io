<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>El blog de Sofía</title>
        <style>
            /* ====== Regla 1: cuerpo general ====== */
            body {
                font-family: "Georgia", serif;     /* Propiedad 1: tipo de fuente */
                font-size: 16px;                   /* Propiedad 2: tamaño de fuente */
                font-style: normal;                /* Propiedad 3: estilo de fuente */
                font-weight: normal;               /* Propiedad 4: peso de fuente */
                line-height: 1.6;
                color: #333;
                background-color: #fdfdfd;
                margin: 40px;
            }

            /* ====== Regla 2: encabezado principal ====== */
            h1 {
                font-family: "Trebuchet MS", sans-serif;
                font-weight: bold;
                text-align: center;
                color: #2c3e50;
            }

            /* ====== Regla 3: entradas del blog ====== */
            .post {
                background-color: #fff;
                padding: 20px;
                border-radius: 10px;
                box-shadow: 0 2px 6px rgba(0,0,0,0.1);
                margin-top: 30px;
            }

            /* Estilo para los títulos de las entradas */
            h2 {
                color: #34495e;
                border-bottom: 2px solid #ccc;
                padding-bottom: 5px;
            }

            /* Estilo para la fecha */
            h6 {
                color: #777;
                font-style: italic;
            }

            /* Enlaces de la tabla de contenidos */
            a {
                text-decoration: none;
                color: #2980b9;
            }

            a:hover {
                text-decoration: underline;
            }
        </style>
    </head>

    <body>
        <h1>El blog de Sofía</h1>

        <h3>Tabla de contenidos</h3>
        <ul>
            <li><a href="#primer-post">Mi primer post</a></li>
            <li><a href="#segundo-post">Aprendiendo CSS paso a paso</a></li>
        </ul>

        <div id="primer-post" class="post">
            <h2>Mi primer post</h2>
            <h6>Publicado el 15 de octubre de 2025</h6>
            <p>
                ¡Hola a todos! Este es mi primer paso en el mundo de la programación web.
                Estoy aprendiendo a usar <strong>HTML</strong> y <strong>CSS</strong> para construir mis propias páginas.
                Me encanta cómo el CSS puede cambiar por completo la apariencia del texto y hacerlo más atractivo.
            </p>
            <p>
                Planeo seguir documentando mi aprendizaje y compartiendo lo que descubro cada semana.
                ¡Esto es solo el comienzo!
            </p>
        </div>

        <div id="segundo-post" class="post">
            <h2>Aprendiendo CSS paso a paso</h2>
            <h6>Publicado el 22 de octubre de 2025</h6>
            <p>
                Hoy aprendí a usar propiedades como <code>font-family</code>, <code>font-size</code>,
                <code>font-style</code> y <code>font-weight</code>. Estas propiedades controlan cómo se ve el texto.
            </p>
            <p>
                También comprendí la importancia de usar buenas prácticas en el código:
                mantener el CSS ordenado, usar clases con nombres claros y evitar repetir estilos innecesarios.
            </p>
        </div>
    </body>
</html>
