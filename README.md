# Escena camara e iluminacion

![N|Solid](https://i.gyazo.com/c1ebc76c699252789da35563f5f69753.jpg)

# Indice

  - Introducción
  - La aplicación
  - Decisiones de diseño
  - Tutorial
  - Notas del autor
  - Gif sobre el funcionamiento

# Informe

**Introducción**:

En esta quinta entrega hemos tenido la oportunidad de afrontar un proyecto abierto, centrado en la iluminación de una escena o composición, y al mismo tiempo el poder brindar al usuario unos controles de cámara para visualizar dicha escena.

**La aplicación**:

Nuestra aplicación se fundamenta en una escena compuesta por tres modelos 3d u objetos, los cuales son:

  -Una silla
  
  -Un escritorio
  
  -Una lámpara de escritorio
  
Dichos elementos están colocados de una forma orgánica simulando una habitación. Esta habitación se situa como eje central de nuestra cámara, esto implica que somos capaces de girar y "orbitar" al rededor de esta, pero nunca podemos dejarla de ver. Así mismo tenemos un foco de iluminación en nuestro ratón, es decir, allí donde esté apuntando nuestro puntero generará un foco de luz. Por último, tenemos una iluminación ambiental para darle profundidad a la escena.
![N|Solid](https://i.gyazo.com/8777fcff4da1a44ffba38edf8d415a4e.jpg)

**Decisiones de diseño**:

Se ha decidido mantener nuestra composición de objetos como eje central de la escena para así imposibilitar mareos o "perdidas de cámara", es decir, con esto logramos atraer completamente la atracción del usuario en nuestra escena. Por otra parte, se ha decidido no poner una base inferior o lateral a modo de suelo y parades para dar más libertad al usuario en cuanto a cámara se refiere.

![N|Solid](https://i.gyazo.com/bd5985020a59bdae5119499050f8a65e.jpg)

**Tutorial**

Este apartado de tutorial se divide en dos partes, la cámara y la iluminación.

Iluminación:

  -Se generará un foco de luz en relación a la posición del puntero del ratón en los objetos.
  -Existe una luz ambiental para la escena en general.
  
Cámara:

  -Movimiento en base 
  
Para alternar entre las vistas usamos la tecla "espacio".

**Gif sobre el funcionamiento**

![Alt Text](https://i.gyazo.com/e649d74b9f4904642052ea87205ab64f.mp4)
