# LaTeX Kaobook Class en ESPAÑOL

Esta es una plantilla traducida parcialmente al español, de la clase kaobook creada por Federico Marotta, que podés encontrar en su repositorio de Github: <https://github.com/fmarotta/kaobook>, junto a documentación y ejemplos. La traducción es parcial en el sentido de que traté de que todos los elementos de la clase aparezcan en español. Esto es: títulos de las secciones del frontmatter y el backmatter, como las referencias y el glosario; ambientes propios de la clase kaobook como teoremas, corolarios, ejemplos, etc.; así como las etiquetas y las referencias de figuras, tablas y ecuaciones como de los ambientes mencionados.

También me tome la libertad de reordenar el contenido de la plantilla, de forma tal que no sea necesario involucrase con los archivos de configuración importantes. Basicamente cuenta con las siguientes carpetas y archivos:

- **frontmatter:** el contenido previo al texto principal como:
  - **cover.tex** La portada del libro, con el título y los autores.
  - **copyright.tex** La página de derechos de autor.
  - **dedication.tex** Una breve dedicación.
  - **preface.tex** Prefacio del libro.
- **mainmatter:** el contenido principal del documento, el cual esta dividido en:
  - **chapters:** capítulos.
    - **comenv.tex** Capitulo donde se muestran los comandos y ambientes traducidos al español
  - **appendices:** apéndices.
    - **appendix.tex** Un apéndice de ejemplo, con listas y familias de fuentes.
  - **estructure.tex** Aquí se construye la estructura de las partes, capítulos y apéndices del libro.
- **backmatter:** el contenido de la parte final del libro, que incluye:
  - **references.bib** Las referencias bibliográficas.
  - **nomenclature.tex** La nomeclatura o notación utilizada en el libro.
  - **glossary.tex** El glosario del libro con las siglas, abreviaciones y términos especiales.
- **images:** aquí van las imagenes del libro.
  - **monalisa.jpg** La Mona Lisa.
  - **seaside.jpeg** Una playa.
- **styles:** los archivos que contienen la información pertinente a los paquetes utilizados, ambientes creados, definiciones, configuraciones, estilos. No deberías modificar los archivos de esta carpeta.
- **kaobook.cls** El archivo que contiene la información pertinente a la clase kaobook, no deberías modificarlo.
- **main.tex** El archivo principal de la plantilla, todo se compila desde aquí. No es necesario modificarlo a menos que quieras editar cosas referidas al backmatter.
- **README.md** Archivo leeme.

Reiterando, la idea es que no es necesario modificar los archivos *kaobook.cls*, *main.tex* y todos aquellos que están en la carpeta *styles* para utilizar esta plantilla. Toda la edición del libro se hace en las carpetas *frontmatter*, *mainmatter* y *backmatter*. Las figuras se guardan en la carpeta *images*.

**ADVERTENCIA:** esta plantilla no debería ser utilizada por alguien novato en LaTeX. Aunque la intención de ordenar los archivos de la manera mostrada es la de simplificar un poco la ediciṕn de esta clase, su uso puede resultar un verdadero dolor de cabeza para quienes tengan poca experiencia. 

Recomiendo fuertemente el uso de Overleaf (<overleaf.com>) para compilar esta plantilla. El PDF generado debería tener ejemplos de como se ve la traducción. No he tenido demasiado exito (ni paciencia) para lidear con los editores de LaTeX de escritorio que andan dando vuelta; overleaf simplemente funciona.

De la misma forma, recomiendo tambien leer la documentación en ingles del Github del autor original. Esta plantilla solo se muestra las cosas que fueron traducidas al español, el potencial de esta clase es mucho mejor explicitado allí.

En lo personal, me gusta mucho todas las herramientas que brinda y aspecto en si. No me gustan los textos que tienen lineas de texto que abarcan toda la hoja, pero tampoco me gusta los enormes margenes que se suelen dejar a ambos costados para evitar esto. Los textos con doble columna, o varias de ellas, pueden resultar muy cansadores de leer. La clase kaobook brinda un ambiente de una única columna, no centrada, de un tamaño razonable y utiliza inteligentemente el margen sobrante para colocar figuras, tablas, ecuaciones, notas al margen, código de programación, cajas, etc. Además brinda herramientas útiles para escribir textos de ciencia e ingenería, que incluyen gran cantidad de imágenes, tablas, ecuaciones, teoremas, definiciones, etc.; donde tener todo correctamente referenciado es la diferencia entre un buen texto y uno tedioso de leer.