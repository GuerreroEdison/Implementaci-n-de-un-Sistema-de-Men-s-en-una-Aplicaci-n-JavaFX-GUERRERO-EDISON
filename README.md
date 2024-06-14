# Implementaci-n-de-un-Sistema-de-Men-s-en-una-Aplicaci-n-JavaFX-GUERRERO-EDISON

![WhatsApp Image 2024-06-14 at 14 27 25](https://github.com/GuerreroEdison/Implementaci-n-de-un-Sistema-de-Men-s-en-una-Aplicaci-n-JavaFX-GUERRERO-EDISON/assets/172848826/465838ba-288f-413b-8681-678498422949)

Explicacion del codigo:

MenuBar y Menús: Se crea una MenuBar (menuBar) y se añaden tres menús principales: "Archivo", "Editar" y "Ayuda".

MenuItems: Dentro de cada menú se añaden varios MenuItem. Además, se utiliza SeparatorMenuItem para agregar separadores entre algunos elementos.

Acciones: Se definen acciones para cada MenuItem utilizando expresiones lambda. Por ejemplo, al seleccionar "Nuevo" se imprime un mensaje en la consola.

Layout: Se utiliza un BorderPane (borderPane) como layout principal. La MenuBar se coloca en la parte superior (setTop) del BorderPane.

Ventana "Acerca de...": Se define un método mostrarAcercaDe() que muestra un Alert cuando se selecciona la opción "Acerca de" del menú Ayuda.

Main y lanzamiento: En el método main, se lanza la aplicación llamando a launch(args).
