Este código pertenece a la interfaz de la app Mascotas. La cual fue realizada con Angular 16. 
La app web consiste en un ABM de una Veterinaria, en cuya home se listan automáticamente las mascotas. 

También se puede:
- Agregar una mascota - botón Aceptar
- Visualizar los datos de la mascota seleccionada - icon lupa
- Editar los datos de la mascota seleccionada - icon lápiz
- Borrar una mascota - icon tachito

Cada acción fue separada en un componente para un fácil mantenimiento y futura reutilización. 
La aplicación cuenta con:
- la Interfaz Mascota, donde están los atributos del objeto Mascota.
- Service Mascota, donde se encuentran los métodos para la realización del ABM y que conectan con las APIS del back end.

Para el ruteo entre las diferentes páginas utilicé RouteModule. Aplicando la directiva redirecTo hacia el home.

