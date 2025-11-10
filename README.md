HOTELES WEB:

A partir de un listado de 80 hoteles con sus respectivos links con la dirección de google Maps, se tiene que generar un QR que muestre la lista de hoteles con su enlace a google Maps. Además, se quiere que al clicar en los enlaces de los hoteles se muestre la ruta más efectiva saliendo desde el aeropuerto.

Implementación de una Web-App, que para lo que se pide será más que suficiente y se puede realizar en un tiempo limitado y bastante rápido con buenos resultados.

Descripción de los archivos necesarios:

Index.html: Archivo muy simple que sirve de estructura básica para que la web funcione correctamente y es prácticamente un esqueleto que se podría usar para múltiples webs, solo he añadido dos links, uno para poder usar las APIs de google y la otra para generar QR(esta segunda no debería ser del todo necesaria debido que el QR será impreso y puramente para acceder a la web.)

script.js: Este es el archivo clave del programa ya que aquí se gestiona toda la navegación de la web así como la comunicación con las APIs de google.

style.css: Archivo también muy básico para darle algo de forma y estilo a la web y que luzca mínimamente presentable.

hotels.json: Listado de hoteles con su enlace a google maps.


Formato Excel a JSON: Para que sea más fácil trabajar con el archivo de Excel y no tener que pasar manualmente todos los hoteles, transformaremos el Excel a Google sheet para asegurar que tiene X columnas, posteriormente guardaremos una copia en formato CSV(nos guarda los valores separados por ",") y con una web online convertiremos el fichero CSV a formato JSON. Todo este proceso nos ahorrará mucho tiempo.
