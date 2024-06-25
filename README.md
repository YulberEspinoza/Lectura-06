# Lectura-06

1. ¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?
Un objetos son todas las cosas que te puedes imaginar, y como tal tiene ciertas cosas, como las características y tambien sus acciones, estos los podemos representar por medio de código.

2. ¿Cuáles son algunas de las ventajas de crear objetos literales?
Las características principales de un objeto literal, se instancian de una forma global o única y no necesitan de un elemento new para su creación.
Por su estructura son mas rápidos y eficientes. 

4. ¿En qué se diferencian los objetos de los arrays?
La diferencia es que los objetos pueden tener características y acciones, en el caso de las características son enumeraciones y estan en una lista, y los arrays son una lista que pueden o no tener relacion entre ellas, pero si estan ennumeradas.

5. Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.
El ejemplo que se podría dar es cuando la información que necesitamos es de manera dinamica o que no sea válido para acceder por punto:

const miObjeto = {
  'propiedad con espacios': 'Hola, soy una propiedad con espacios',
  '123': 'Soy una propiedad con un número como nombre',
  [variableDinamica]: 'Soy una propiedad calculada'
};

const propiedadEspacios = miObjeto['propiedad con espacios'];
const propiedadNumero = miObjeto['123'];

const nombrePropiedad = 'propiedad con espacios';
const valorPropiedad = miObjeto[nombrePropiedad];

6. Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?

El término this. nos hace refencia a una varible tanto para asiganrle el valor como tambien para poder instanciarlo, decirle aquí. 

1. ¿Qué es el DOM?
El DOM (Modelo de Objetos del Documento) es la estructura que representa un documento HTML en un navegador web. Imagina que una página HTML está formada por múltiples etiquetas HTML anidadas, creando un árbol de nodos relacionados entre sí.  Cada nodo puede ser un elemento, una cadena de texto o incluso un comentario.
  
2. Describe brevemente la relación entre el DOM y JavaScript.
El DOM nos permite acceder y modificar estos elementos desde JavaScript, lo que nos permite crear páginas web dinámicas y automatizar tareas según las acciones del usuario.

