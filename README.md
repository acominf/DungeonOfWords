![En construcción](https://lh3.googleusercontent.com/-U0wGPKlLyk0/WSuw0dA2xnI/AAAAAAAAAdU/JezaHOPyCmE_cS3SAjmo35M8fn1A4297QCJoC/w530-h303-p-rw/inicio.png)

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

4. Clase 4 Elige
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

8. Clase 8: Iori
* caracteristica1: Extiende de la clase Personajes.
* caracteristica2: Se encarga del movimiento y ataque del personaje Iori.

9. Clase 9: Marco
* caracteristica1: Extiende de la clase Personajes.
* caracteristica2: Se encarga del movimiento y ataque del personaje Marco.

10. Clase 10: Goku
* caracteristica1: Extiende de la clase Personajes.
* caracteristica2: Se encarga del movimiento y ataque del personaje Goku.

11. Clase 11: Capitanamerica
* caracteristica1: Extiende de la clase Personajes.
* caracteristica2: Se encarga del movimiento y ataque del personaje Capitanamerica.

12. Clase 12: Deadpool
* caracteristica1: Extiende de la clase Personajes.
* caracteristica2: Se encarga del movimiento y ataque del personaje Deadpool.

13. Clase 13: Disparo
* caracteristica1: Extiende de la clases de Ryu, Marco y Goku.
* caracteristica2: Se encarga de validar cuando Ryu debe atacar a un enemigo.

14. Clase 14: Texto
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Se encarga de los textos mostrados graficamente.

15. Clase 15: botones
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Se encarga de los botones mostrados graficamente.

16. Clase 16: Instrucciones
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton instrucciones.

17. Clase 17: Jugar
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton jugar.

18. Clase 18: BRyu
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Ryu.

19. Clase 19: Salir
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton salir.

20. Clase 20: Home
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton home..

21. Clase 21: BIori
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Iori.

22. Clase 22: BMarco
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Marco.

23. Clase 23: BGoku
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Goku.

24. Clase 24: BCapitanamerica
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Capitan america.

25. Clase 25: BDeadpool
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton de seleccion sobre Dead pool.

26. Clase 26: Volver
* caracteristica1: Extiende de la clase botones.
* caracteristica2: Valida cuando se presiona el boton volver.

27. Clase 27: Enemigo1
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Se encarga del movimiento y ataque del Enemigo1.

28. Clase 28: Fuego
* caracteristica1: Extiende de la clase Enemigo1.
* caracteristica2: Se encarga de validar cuando Enemigo1 debe atacar al personaje principal.

29. Clase 29: Enemigo2
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Se encarga del movimiento y ataque del Enemigo2.

30. Clase 30: corazones
* caracteristica1: Extiende de la clase Actor.
* caracteristica2: Se encarga de controlar las vidas del personaje principal.

### Diagrama de clases
![Diagrama de clases](https://lh3.googleusercontent.com/-bb3UWzXWgyc/WSvJFzZJDtI/AAAAAAAAAfY/VZYKiU0RZyUFxmFtSfHMC7kcUdHZdz_dgCL0B/w530-d-h398-p-rw/uml1.png)
![Diagrama de clases](https://lh3.googleusercontent.com/-bIrBUnrlrwQ/WSvJueL0zJI/AAAAAAAAAgc/bzWHD2ol8joQJsFy_jAWkUZ8ZQjO-HmCgCL0B/w530-d-h398-p-rw/uml2.png)

### Autor(es)
El autor(es) del proyecto son:
- Moreno Torres Ricardo Enrique (REMT11)
- Varela Tristan Gerardo Antonio (SANGUINETIARA)

### Materia(s)
- Programación Orientada a Objetos

### Semestre
- 2016-2017/II

### Universidad Autónoma de San Luis Potosí, 2017

### Download
https://www.dropbox.com/pri/get/DungeuonWord5.0.zip?_subject_uid=290201519&w=AAB1xBHNtrE8696tpjVDLa3k3f1qecr4KX8dyzBUlVxl0A

### Markdown
El contenido de esta página está escrito en un lenguaje de marcado sencillo llamado _Markdown_. **Para modificar el contenido de esta página se tiene que editar el archivo README.md del repositorio**. Para más detalles consulta la página de [Markdown para GitHub](https://guides.github.com/features/mastering-markdown/).

### Temas de Jekyll
El estilo y presentación de esta página utiliza el tema de Jekyll seleccionado en la configuración del repositorio. El nombre de este tema está almacenado en el archivo de configuración `_config.yml`. Para más información acerca de los temas de Jekyll soportados por GitHub [haz click en este enlace](https://pages.github.com/themes/).
