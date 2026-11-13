# Proyecto_Inmobiliaria
Proyecto de maquetacion web para separa el contenido de el header/footer.

## Descripción del proyecto
Villa Buitre es una web inmobiliaria basada en la plantilla Villa Agency de TemplateMo. El sitio consta de cuatro páginas —Inicio, Propiedades, Detalle de propiedad y Contacto— con un catálogo de viviendas (villas, apartamentos y áticos), imágenes, precios, datos técnicos y un formulario de contacto, todo maquetado en HTML estático con Bootstrap 5, jQuery y algunos plugins (Owl Carousel, Isotope, contadores animados).
El trabajo realizado en el proyecto ha sido únicamente la separación del contenido común del sitio: en lugar de repetir la cabecera, la navegación y el pie de página en cada archivo HTML, se han extraído a una plantilla compartida (plantilla.html.php) y cada página se ha convertido en una vista parcial que se carga dentro de ella mediante PHP. Para ello, cada URL pública es ahora un pequeño archivo en public/ que solo define el título de la página y qué vista debe incluirse, y la plantilla se encarga del <head>, el menú, el footer y la carga de estilos y scripts.
En resumen: no se ha añadido funcionalidad nueva ni backend; el objetivo ha sido eliminar la duplicación de código y centralizar la estructura común del sitio, de forma que un cambio en la cabecera o el footer se aplique automáticamente a todas las páginas.

## ¡IMPORTANTE! Es un trabajo escolar y esta es la entrega no o tengais en cuenta como uno de mis proyectos.
