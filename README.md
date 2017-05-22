![En construcción](F:\DungeonWord3.0\images/inicio.jpg)

### Objetivo del juego/aplicación
El objetivo del juego/aplicación es poner en practica los conocimientos aprendidos a  lo largo del curso y poder desarrollar un videojuego que nos permita usar nuestro razonamiento logico y poder crear este juego didactico de manera que pueda servirle a personas de diferentes edades.

### Descripción del juego/aplicación
La descripción del juego/aplicación es un juego de palabras aleatorias en ingles que se muestran en pantalla de manera revuelta, el jugador debe de identificar de que palabra se trata para escribirla correctamente y poder avanzar a la siguiente palabra, debes ser habil pues el personaje solo atacara a los enemigos si aciertas la palabra, de lo contrario el enemigo atacara a dicho personaje.

### Clases principales y sus características
1. Clase 1 Juego
 *caracteristica1: Extiende de la clase World.
 *caracteristica2: Se inicializa el tamaño de la ventana de juego.
 *caracteristica3: En esta clase se inicializa la base de datos.
 *caracteristica4: Se selecciona el personaje para jugar.

2. Clase 2: Ins
 *caracteristica1: Extiende de la clase World.
 *caracteristica2: Se encarga demostrar todo el apartadode instrucciones del juego.

3. Clase 3: MyWorld 
 *caracteristica1: Extiende de la clase World.
 *caracteristica2: Administra las funciones del menu, ya sea jugar, instrucciones o salir.
 *caracteristica3: Muestra la imagen del fondo.

4. Clase 4
* caracteristica1: Extiende de la clase World.
* caracteristica2: Administra el personaje seleccionado por el usuario.

5. Clase 5: BaseDeDatos
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Muestra el boton con las palabras revueltas de manera aleatoria. 
* caracteristica3: Indica cuando se detiene en una palabra para esperar la respuesta del usuario.
* caracteristica4: Valida si la respuesta es correcta o incorrecta para decidir que accion debera ser la siguiente.

6. Clase 6: Personajes
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Contiene los metodos abstractos para el movimiento dependiendo del personaje seleccionado.


7. Clase 7: Ryu
* caracteristica1: Extiende de la clase Personajes.
* caracteristica2: Se encarga del movimiento y ataque del personaje Ryu.

8. Clase 8: Disparo
* caracteristica1: Extiende de la clase Ryu.
* caracteristica2: Se encarga de validar cuando Ryu debe atacar a un enemigo.

9. Clase 9: Iori
* caracteristica1: Extiende de la clase Personajes.
* caracteristica2: Se encarga del movimiento y ataque del personaje Iori.

10. Clase 10: Texto
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Se encarga de los textos mostrados graficamente.

11. Clase 11: botones
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Se encarga de los botones mostrados graficamente.

12. Clase 12: Instrucciones
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton instrucciones.

13. Clase 14: Jugar
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton jugar.

14. Clase 14: BRyu
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Ryu.

15. Clase 15: Salir
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton salir.

16. Clase 16: BIori
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Iori.

17. Clase 17: Volver
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton volver.

18. Clase 18: Enemigos
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Contiene los metodos dependiendo del enemigo.

19. Clase 19: Enemigo1
* caracteristica1: Extiende de la clase Enemigos.
* caracteristica2: Se encarga del movimiento y ataque del Enemigo1.

20. Clase 20: Fuego
* caracteristica1: Extiende de la clase Enemigo1.
* caracteristica2: Se encarga de validar cuando Enemigo1 debe atacar al personaje principal.


21. Clase 21: Enemigo2
* caracteristica1: Extiende de la clase Enemigos.
* caracteristica2: Se encarga del movimiento y ataque del Enemigo2.

### Diagrama de clases
![Diagrama de clases](url-del-diagrama.png)

### Autor(es)
El autor(es) del proyecto son:
- Moreno Torres Ricardo Enrique (REMT11)
- Varela Tristan Gerardo Antonio (SANGUINETIARA)

### Materia(s)
- Programación Orientada a Objetos

### Semestre
- 2016-2017/II

### Universidad Autónoma de San Luis Potosí, 2017

### Markdown
El contenido de esta página está escrito en un lenguaje de marcado sencillo llamado _Markdown_. **Para modificar el contenido de esta página se tiene que editar el archivo README.md del repositorio**. Para más detalles consulta la página de [Markdown para GitHub](https://guides.github.com/features/mastering-markdown/).

### Temas de Jekyll
El estilo y presentación de esta página utiliza el tema de Jekyll seleccionado en la configuración del repositorio. El nombre de este tema está almacenado en el archivo de configuración `_config.yml`. Para más información acerca de los temas de Jekyll soportados por GitHub [haz click en este enlace](https://pages.github.com/themes/).
