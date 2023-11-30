TAREA EN CLASE (CHRISTIAN TORRES)
1. EXPLICAR CUANTAS MANERAS EXISTEN PARA VINCULAR HTML CON CSS (README)

Existen 3 maneras para vincular html con css:

- Utilizando la etiqueta style dentro del body
- Utilizando de manera inline como atributo del elemento
- Utilizando un archivo externo .css

2. EXPLICAR CON SUS PALABRAS EL CONJUNTO DE REGLAS DE CSS (SELECTOR, PROPIEDAD, VALOR) (README)

- Selector: Es el elemento HTML que se desea modificar
- Propiedad: Es el atributo que se desea modificar del elemento, por ejemplo, su color, su fondo, etc
- Valor: Es lo que va hacer que se modifique

3. EXPLICAR LOS 4 CONCEPTOS IMPORTANTES CON EJEMPLO (SELECTORES, HERENCIA, CASCADA, ESPECIFICIDAD)

- Selector: Es el elemento HTML que se desea modificar por ejemplo h1, h2, h3, etc.
- Herencia: Es cuando ciertos elementos o etiquetas heredan los estilos principales de sus ancestros por ejemplo:

    <body style="color: blue">
        <h1>Hola mundo</h1>
        <h2>Hola mundo</h2>
    </body>

    Este es un caso de herencia ya que los elementos h1 y h2 heredan el estilo del ancestro body.

- Cascada: Es cuando se le coloca un valor diferente a la misma propiedad y se toma en cuenta la última línea de código por ejemplo:

    h1 {
        color: red;
    }

    h1 {
        color: blue;
    }

    Este es un caso de cascada donde se toma en cuenta el último valor que sería blue

- Especificidad: Es un valor que adquiere el selector para determinar la importancia del estilo por ejemplo:

    h1 {
        color: red !important;
    }

    h1 {
        color: blue;
    }

    Este es un caso de especificidad donde se toma como prioridad al color red gracias al !important

4. SUBIR A GITHUB Y PASAR EL REPOSITORIO POR CHAT INTERNO (PUBLICO)