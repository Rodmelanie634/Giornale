## Consumir  una API

# Giornale Quotidiano<br>
<p algin="center">
<link rel="shortcut icon" href="../data/logoufps.png" type="image/x-icon">
</p><br>

### Contenido<br>

*CSS
*HTML
*JAVASCRIPT
*API
*API FUNCIONAL

---

### Busqueda de una API<br>

He buscado principalmente en Google, encontrando contenidos varios en Youtube, paginas totalmente aleatorías, seguí recomendaciones de los Formadores y por ultima instancia he recurrido a ChatGPT, quien no fue de mucha ayuda, ya que me hizo un lío pero se le agradece su pequeña colavoración.

### La API

Mi pequeña aportación es una Api de noticias, la cual cuenta con una amplia base de datos que se va actualizando día a día con información cien por ciento real y veridica, la cual podemos encontrar en otros sitios de noticias, lo que distingue esta API y pagina web de absolutamente todos los demás es que es de facil uso y está pensada para todo publico y todos los dispositivos.

Este código es una aplicación web que utiliza la API de noticias de NewsAPI.org para mostrar noticias relacionadas con un tema específico. El usuario puede buscar noticias utilizando una barra de búsqueda o haciendo clic en una de las categorías predefinidas.

La aplicación utiliza JavaScript para realizar llamadas a la API de NewsAPI.org y mostrar las noticias devueltas en el DOM del navegador.

En la parte superior del archivo, se definen tres variables: `cantidadNoticias`, que determina cuántas noticias se cargarán a la vez; `pageInicial` y `pageFinal`, que mantienen un registro de la página actual de noticias que se están mostrando; y `temaActual`, que almacena el tema actual de noticias que se están mostrando.

A continuación, se define un objeto `noticias` que contiene dos métodos: `fetchNoticias` y `displayNoticias`. El método `fetchNoticias` utiliza la API de NewsAPI.org para buscar noticias relacionadas con un tema específico y llama al método `displayNoticias` para mostrar las noticias en el DOM. El método `displayNoticias` toma los datos devueltos por la API y crea elementos HTML para mostrar las noticias en el navegador.

La función `buscar` se utiliza para buscar noticias relacionadas con una categoría específica. La función `buscarTema` se utiliza para buscar noticias relacionadas con un tema especificado por el usuario utilizando la barra de búsqueda.

La función `siguiente` se utiliza para cargar más noticias cuando el usuario hace clic en el botón "Ver más". La función actualiza las variables `pageInicial` y `pageFinal` para indicar la página actual de noticias que se están mostrando y llama al método `fetchNoticias` para cargar más noticias.

El código también incluye un listener de evento para la tecla "Enter" en la barra de búsqueda para que el usuario pueda realizar una búsqueda simplemente pulsando la tecla "Enter".

Finalmente, se llama al método `fetchNoticias` para mostrar noticias relacionadas con el tema predeterminado "Economía" al cargar la página.
