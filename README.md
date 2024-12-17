¿Por qué elegí esta API?
Elegí trabajar con datos del mundo de Harry Potter porque es un tema atractivo, con mucha información interesante para mostrar (hechizos, personajes, libros, etc.), y que permite explorar una gran variedad de funcionalidades en una aplicación web. Además, al usar una API que contiene múltiples tipos de datos relacionados (personajes, hechizos, libros), pude crear una aplicación más completa y versátil, mostrando la capacidad de manejar datos de diversas fuentes de manera organizada.

Dificultades encontradas y cómo las solucioné:
Uso de múltiples APIs y fuentes de datos:

Al principio, la app estaba diseñada para trabajar con una sola API, pero luego se añadió un archivo db.json con información más completa. Esto complicó la estructura, ya que fue necesario unificar datos de distintas fuentes.
Solución: Decidí usar solo db.json como fuente principal y estructurando los datos para que fueran fáciles de manejar en el código.
Diseño responsivo:

El diseño inicial no estaba bien adaptado para dispositivos móviles, especialmente en el menú de navegación.
Solución: Mejoré el CSS, añadiendo un menú desplegable para móviles y adaptando las tarjetas y modales para que se vean bien en pantallas pequeñas.
Falta de información específica en el modal:

Inicialmente, los hechizos mostrados en los personajes no eran específicos y se repetían.
Solución: Filtré los datos para que cada personaje mostrara hechizos relevantes, o en caso de no tener, los hechizos más generales.

Problemas con el menú en móvil:
El menú no se desplegaba correctamente en dispositivos pequeños.
Solución: Implementé un sistema de clases activas con JavaScript para que el menú funcione correctamente en todas las resoluciones.


Nota del proyecto: 8/10 bajado a un 7.5/10 por tardar tanto
Razón de la nota:

Me pondría un 7.5 porque el proyecto cumple con los requisitos propuestos:
Es responsivo, adaptado para móviles.
Muestra datos de manera clara y organizada, con navegación funcional entre páginas (personajes, hechizos, libros).
Implementa un diseño visual agradable con un menú interactivo, tarjetas bien diseñadas y modales atractivos.
Documenté el proyecto correctamente, incluyendo explicaciones claras.

Puntos a mejorar:

Buscar una api que contenga los mismos datos pero en español, ya que lo he tenido que hacer todo en ingles, y como no he quierido intercambiar idiomas pues esta toda hecha en ingles.

Aunque todo funciona correctamente, podría optimizar la estructura del código para hacerlo más escalable.
Implementar un sistema de manejo de errores más robusto en caso de que los datos de la API no carguen correctamente.
