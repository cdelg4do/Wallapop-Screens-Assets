# Práctica Diseño de Apps para Desarrolladores de Carlos Delgado Andrés

Diseño de pantallas y assets para iOS de la app *Wallapop*, realizados con **Sketch v41**.

Adicionalmente, se han genereado también los assets para Android y se ha construido un pequeño prototipo con **Marvel** que se puede ejecutar en la url siguiente:

##### **https://marvelapp.com/3013974**

.
#### Contenido del repositorio:

- **readme.md**: Este fichero conteniendo la descripción del repositorio.

- **wallapop.sketch**: Fichero de Sketch que contiene el diseño de las pantallas y los recursos necesarios para generar los assets para los dispositivos móviles.

- **/iOS_assets**: Carpeta que contiene los assets generados desde Sketch para iOS, en tamaños 1x, 2x y 3x.

- **/Android_assets**: Carpeta que contiene los assets para Android, en tamaños mdpi, hdpi, xhdpi, xxhdpi y xxxhdpi. Estos assets se han generado a partir del diseño en Sketch utilizando el plugin **Zeplin** (https://app.zeplin.io/welcome.html).

.
#### Consideraciones sobre el prototipo de Marvel:

- La versión del fichero **wallapop.sketch** del repositorio no se corresponde 100% con la utilizada para construir el prototipo en Marvel, ya que para simular el scroll de productos en la primera pantalla (*Product search*) se ha alargado el tamaño del artwork original. Este es el único cambio que se realizó en el fichero respecto al que se encuentra en el respositorio.

- Dado que el scroll de Marvel no funciona muy bien con los elementos flotantes de la interfaz, se ha optado por dejar el selector de proximidad y el botón de subir producto anclados al comienzo y al final del listado de productos, respectivamente.

- En la realidad, ambos elementos deberían permanecer en una posición fija mientras por debajo de ellos se hace scroll de los productos, pero no he encontrado el modo de simular este comportamiento en Marvel.

- Del mismo modo, para simular en Marvel el scroll en la pantalla de un producto (*Product detail*), se ha delimitado la parte superior fija de la ventana con la barra de navegación y la status bar. Ambos elementos son semi-transparentes y deberían mostrar el resto de la pentalla desplazándose bajo ellos durante el scroll. Sin embargo, en el prototipo de Marvel el fondo de ambos elementos aparece fijo como si fuesen opacos.

- El efecto de mostrar/ocultar el menú desplegable (*Drawer menu*) se ha simulado en Marvel utilizando transiciones "push right" y "push left" entre esta pantalla y la de productos (*Product search*). Aunque este comportamiento no se corresponde 100% con el funcionamiento real de la app, sí permite al usuario experimentar con el menú desplegable.

.
#### Assets generados para cada pantalla:

- **Product search**:
    *  btn_common_filter
    *  btn_drawer_menu
    *  btn_floating_new
    *  chevron_down_black
    *  icon_search

.
- **Drawer menu**:
    *  chevron_down_gray
    *  icon_menu_categories
    *  icon_menu_collections
    *  icon_menu_help
    *  icon_menu_invite
    *  icon_menu_magazine
    *  icon_menu_messages
    *  icon_menu_new
    *  icon_menu_notifications

.
- **Product detail**:
    *  btn_facebook
    *  btn_gmail
    *  btn_messenger
    *  btn_nav_back
    *  btn_nav_favorite
    *  btn_nav_options
    *  btn_nav_share
    *  btn_twitter
    *  btn_whatsapp
    *  icon_default_avatar
    *  icon_emphasized_product
    *  icon_favorite_counter
    *  icon_location
    *  icon_star_0
    *  icon_star_50
    *  icon_star_100
    *  icon_view_counter

.
- **New product**:
    *  btn_close
    *  chevron_right_gray (*)
    *  icon_camera (*)

    (*) Los assets *chevron_right_gray* e *icon_camera* no aparecen como elementos independientes en esta pantalla, y se han exportado desde la página *Symbols*, ya que forman parte de otros símbolos que sí se utilizan en esta pantalla.


