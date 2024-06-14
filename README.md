# Implementaci-n-de-un-Sistema-de-Men-s-en-una-Aplicaci-n-JavaFX-GUERRERO-EDISON

![WhatsApp Image 2024-06-14 at 14 27 25](https://github.com/GuerreroEdison/Implementaci-n-de-un-Sistema-de-Men-s-en-una-Aplicaci-n-JavaFX-GUERRERO-EDISON/assets/172848826/465838ba-288f-413b-8681-678498422949)

Explicacion del codigo:

Se crea una interfaz de usuario con una barra de menú (menuBar) que incluye tres menús principales: "Archivo", "Editar", y "Ayuda". Cada menú contiene varios elementos de menú (MenuItem), con separadores (SeparatorMenuItem) entre algunos de ellos para mejorar la organización visual.

Cada MenuItem tiene asociada una acción específica utilizando expresiones lambda. Por ejemplo, al seleccionar "Nuevo" en el menú "Archivo", se imprime un mensaje en la consola.

El diseño de la interfaz utiliza un BorderPane (borderPane) como contenedor principal. La MenuBar se sitúa en la parte superior del BorderPane (setTop).

Para la opción "Acerca de" del menú "Ayuda", se define un método mostrarAcercaDe() que muestra un cuadro de diálogo (Alert) cuando se selecciona esta opción.

En el método main, se inicia la aplicación invocando launch(args) para lanzar la interfaz y manejar las interacciones del usuario.
