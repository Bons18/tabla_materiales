# Inventario de Materiales

Proyecto estático listo para desplegar en Vercel.

## Contenido
- `index.html`: inventario con 58 materiales, búsqueda por código o nombre, resaltado de coincidencias, botón para copiar cada código (con notificación) y orden original de la hoja.
- `style.css`: diseño responsive.
- `/terminos/`: términos de uso.
- `/politica/`: política de privacidad y tratamiento de datos.

## Titular
Brayan Restrepo Pabon.

## Importante sobre privacidad
La versión actual no tiene formularios, cuentas, pagos, comentarios ni analítica propia. Por eso la política no afirma que se recojan datos que el sitio no recoge. Si se añade un formulario o cualquier mecanismo de captura de datos, la política debe actualizarse antes de ponerlo en producción.

Para solicitudes de habeas data debe publicarse un canal real de contacto del responsable. No se inventó correo, teléfono o dirección en este proyecto.

## Despliegue
En Vercel, importa este proyecto como sitio estático. No requiere framework ni build command.


## Alcance de los derechos

El sitio concede a los visitantes únicamente el derecho limitado de acceder y utilizar sus servicios y funcionalidades de forma lícita. No se concede propiedad ni una licencia general sobre el código, diseño, interfaz o textos originales. Los derechos de terceros sobre sus marcas, nombres, códigos o contenidos permanecen con sus respectivos titulares.

## Seguridad

Se incorporaron headers de seguridad para el despliegue en Vercel, incluyendo CSP, HSTS, protección contra clickjacking, MIME sniffing, política de referencia y restricciones de permisos del navegador.

La configuración no intenta ocultar el código fuente: en una web estática el navegador necesariamente recibe HTML, CSS y JavaScript. La protección se enfoca en reducir vectores de ataque y evitar configuraciones inseguras.
