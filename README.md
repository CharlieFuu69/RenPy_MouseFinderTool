# Herramienta "MouseFinderTool" para juegos Ren'Py

¡Hola! Este script es una pequeña herramienta de asistencia para el desarrollo de juegos en el motor Ren'Py.
Hay momentos en que necesitamos posicionar un displayable en el juego y concurrimos a probar coordenadas al azar para ver en donde colocar finalmente ese displayable. Bueno, te diré que eso es una completa pérdida de tiempo, y este script tiene la misión de ayudarte en eso.
La labor de este script es mostrarte las coordenadas actuales del cursor del mouse en la pantalla del juego, lo que puede ayudar a economizar tiempo al momento de posicionar objetos en la UI.

* [Descarga la herramienta desde aquí](https://github.com/CharlieFuu69/Codigos_RenPy/blob/master/MouseFinderTool/MouseFinderTool.rpyc)
* [Código fuente de la herramienta](https://github.com/CharlieFuu69/Codigos_RenPy/blob/master/MouseFinderTool/MouseFinderTool.rpy)

---

### ¿Cómo funciona? :

Es simple. Debes colocar el archivo `MouseFinderTool.rpyc` en el interior de la carpeta `game` de tu proyecto. Una vez que lo coloques en esa ruta, funcionará automáticamente cuando arranques tu juego.
Cuando presiones "Nueva partida" o en el momento de cargar una partida existente, se mostrará un recuadro con las coordenadas actuales del cursor. Este recuadro se ve algo así:

![EQ_Screenshot_0002](https://user-images.githubusercontent.com/77955772/155878496-bcdfc0b8-6b7f-450e-bcd2-4b4cfefc6d33.png)

Por supuesto, para tu comodidad, el recuadro se puede arrastrar y ocultar de la interfaz sin mucho lío de por medio. También hay una opción para ocultarla si así lo deseas =)
El estilo de la ventana depende del tema de UI de tu juego, asi que puede variar al usarse en un proyecto u otro.

![ic_warning](https://user-images.githubusercontent.com/77955772/143798585-2a612721-a193-4ec0-af5f-811c6bef6c4c.png) Para apuntar coordenadas, se recomienda confiar más en las coordenadas de píxeles que en las coordenadas relativas, pues este último es levemente menos preciso.

---

### Algunos keybindings para usar MouseFinderTool :

Los Keybindings son atajos que se ejecutan con una o más combinaciones de teclas, pero en este caso solo basta presionar una tecla para ejecutar una acción. En este caso, la herramienta tiene los siguientes Keybindings:

* __C :__ Muestra nuevamente el recuadro en caso de que lo hayas ocultado.
* __R :__ Registra las coordenadas actuales en un archivo TXT. Este archivo TXT se guarda en la carpeta base de tu proyecto, con el nombre `mouse_log.txt`


---

### Tareas pendientes por hacer :

- [x] Mostrar coordenadas relativas (0.0 a 1.0).
- [ ] Superposición de la herramienta en los menús de juego.
- [ ] Mostrar coordenadas relativas de 3 decimales para incrementar precisión.

---

Espero que esta pequeña herramienta te sirva :3

