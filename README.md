## Estilos Sass Básicos

Este repositorio contiene estilos Sass básicos que cubren los siguientes aspectos:

### Variables

- En el archivo `partials/variables`, se definen variables para colores, espaciados y otros valores reutilizables en todo el proyecto. Esto facilita el mantenimiento y la coherencia en el diseño.

### Mixins

- En `partials/mixins`, se encuentran mixins Sass que simplifican la escritura de estilos comunes. Estos incluyen mixins para flexbox, estilos de caja y otros patrones de diseño repetitivos.

### Breakpoints

- El archivo `partials/breakpoints` define breakpoints para diseño responsivo. Estos breakpoints se utilizan para adaptar el diseño según el tamaño de la pantalla del dispositivo.

### Funciones

- `partials/functions.scss` contiene funciones Sass que realizan cálculos y conversiones útiles. Estas funciones pueden ser utilizadas para mantener el código más modular y legible.

### Bucles

- Se utilizan bucles `@for` y `@each` para generar estilos de manera dinámica. Por ejemplo, en el código se pueden observar bucles que generan estilos para listas y cajas con colores específicos.

### Flexbox y Responsividad

- Se aplican estilos flexbox para manejar el diseño y la alineación de los elementos.
- Se utilizan breakpoints y mixins para establecer estilos responsivos, asegurando que el diseño se adapte a diferentes tamaños de pantalla.

### Placeholder y Extensión de Estilos

- Se utilizan extensiones de estilos (`@extend`) para heredar estilos a elementos relacionados, manteniendo así un código más limpio y modular.
- Se definen estilos para los placeholders dentro de elementos con clase `.error`, lo que proporciona una experiencia de usuario más coherente.

