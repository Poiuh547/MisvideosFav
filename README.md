# misvideosfav

Este proyecto consiste en la pagina web de captura de videos a través del llenado de un formulario que se guarda en una base de
datos y hace display del video en un frame dado. 
La captura debe realizarse en el apartado "Agregar", proporcionando un link Embebed, el cual se encuentra en los videos de Youtube em la 
seccion "Compartir". Una vez hecho eso se procederá a guardar el registro y, de vuelta en la pagina principal se mostrarán los datos.

Los vídeos vinculados mantienen el tamaño del archivo de presentación más pequeño, pero los vínculos se pueden romper. Es recomendable almacenar las presentaciones y los vídeos vinculados en la misma carpeta.

Se pueden especificar múltiples fuentes de archivos usando el elemento <source> con el fin de proporcionar vídeo o audio codificados en formatos diferentes para diferentes navegadores.

Si el atributo type no está especificado, el tipo de contenido multimedia se obtiene del servidor y se comprueba para ver si el navegador lo puede manejar; si no puede ser mostrado, se comprueba el siguiente source , si ninguno de los elementos source especificados pueden ser usados, un evento de error es enviado al elemento video. Si el atributo type está especificado, es comparado con los tipos que el navegador puede reproducir, y si no es reconocido, no se hace la consulta al servidor; en su lugar, el siguiente source se comprueba una vez.

