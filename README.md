## María Teresa Rivera López
## 24000579

Country Explorer es una aplicación web que permite a los usuarios buscar y explorar información sobre países del mundo.
La aplicación obtiene los datos desde la REST Countries API y muestra información como la bandera del país, su capital, 
población, región y subregión.

Lab0 Parte1-Parte2
## Parte 1 – Sistema de búsqueda y filtros
- Búsqueda de países
  Los usuarios pueden escribir el nombre de un país en el buscador.
  La aplicación realiza una petición a la API y muestra los resultados.
- Filtro por región
  Se agregó un menú desplegable que permite filtrar los países por región.
  Las regiones se cargan dinámicamente a partir de los resultados obtenidos de la API.
- Filtros combinados
  La aplicación permite combinar filtros: búsqueda por nombre y por región

- Archivos modificados
  main.ts: Implementación de la búsqueda y del filtro por región
  Creación de la función applyFilters() para combinar filtros
  Creación de la función populateRegions() para llenar el dropdown

  index.html: Se agregó el selector de regiones (regionFilter)

## Parte 2 – Sistema de favoritos
- Icono de favorito
  Cada tarjeta de país tiene un icono que permite marcar o desmarcar un país como favorito.
  Los países favoritos se guardan en el almacenamiento del navegador usando localStorage,
  por lo que permanecen guardados incluso después de recargar la página.
- Filtro de favoritos
  Se agregó un checkbox que permite mostrar únicamente los países marcados como favoritos.
- Limpiar favoritos
  Se agregó un botón que permite eliminar todos los países guardados como favoritos.

- Archivos modificados
  utils/storage.ts: Archivo creado para manejar el almacenamiento de favoritos.
  main.ts: Se agregó el filtro de favoritos y el botón para limpiar favoritos.
  index.html: Checkbox Favorites Only y botón Clear Favorites

Link del video: https://youtu.be/Cm5t5fOx54E


Con ayuda de IA pude agilizar parte del proyecto y la documentacion, asi como comprender mejor el funcionamiento de Android, 
al igual que su estructura al hacer una app y en que carpetas colocarlas.
