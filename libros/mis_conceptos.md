# Componentes en Angular

Los componentes son los bloques de construcción fundamentales para cualquier aplicación Angular. Cada componente tiene tres partes:

- Clase TypeScript

- Plantilla HTML

- Estilos CSS

En Angular, puedes usar todos los CSS y HTML compatibles con el navegador que están disponibles. Si lo deseas, puedes almacenar la plantilla y los estilos en archivos separados.

# Actualización de la clase de componente

En Angular, la lógica y el comportamiento del componente se definen en la clase TypeScript del componente.

# La interpolación 

Se refiere a la incrustación de expresiones en texto marcado. De forma predeterminada, la interpolación utiliza las llaves dobles y como delimitadores.{{}}

en el fichero ts

export class AppComponent {
  customers = CUSTOMERS;
  currentCustomer = 'Maria';
  title = 'Featured product:';
  itemImageUrl = '../assets/potted-plant.svg';
  recommended = 'You might also like:';
  itemImageUrl2 = '../assets/lamp.svg';
  getVal(): number {
    return 2;
  }

 en el html

 <h3>Current customer: {{ currentCustomer }}</h3>
 <p>{{ title }}</p>
 <div><img alt="item" src="{{ itemImageUrl }}"></div>

 # Composición de componentes.

 Puedes usar todo el marcado HTML y todos los componentes que necesites para hacer realidad la idea de tu aplicación. Incluso puede tener varias copias de su componente en la misma página.

 # Flujo de control en componentes - @if - @else -@for

 Para expresar visualizaciones condicionales en plantillas, Angular utiliza la sintaxis de plantilla.@if

 # Enlace de propiedades en Angular
 El enlace de propiedades en Angular le permite establecer valores para las propiedades de los elementos HTML, los componentes de Angular y más.

 Use el enlace de propiedades para establecer dinámicamente los valores de las propiedades y los atributos. Puede hacer cosas como alternar las funciones de los botones, establecer rutas de imagen mediante programación y compartir valores entre componentes.

 Utilice el enlace de propiedades para hacer cosas como alternar características de botón, establecer rutas de acceso mediante programación y compartir valores entre componentes.

 El enlace de propiedades es una de las muchas características poderosas de Angular.

 # Control de eventos
 El control de eventos habilita características interactivas en las aplicaciones web. Le brinda la capacidad como desarrollador de responder a las acciones del usuario, como presionar botones, enviar formularios y más.

En Angular se enlaza a eventos con la sintaxis de paréntesis. En un elemento determinado, envuelva el evento al que desea enlazar con paréntesis y establezca un controlador de eventos. Considere este ejemplo:()button

# Comunicación de componentes con @Input
A veces, el desarrollo de aplicaciones requiere que envíe datos a un componente. Estos datos se pueden utilizar para personalizar un componente o quizás enviar información de un componente principal a un componente secundario.

Angular utiliza un concepto llamado Input. Esto es similar a lo que ocurre en otros marcos. Para crear un archivo propsInput , use la propiedad @Input decorador.

# Comunicación de componentes con @Output
Al trabajar con componentes, es posible que sea necesario notificar a otros componentes que algo ha sucedido. Tal vez se ha hecho clic en un botón, se ha agregado/eliminado un elemento de una lista o se ha producido alguna otra actualización importante. En este escenario, los componentes deben comunicarse con los componentes primarios.

Angular utiliza el método @Output para habilitar este tipo de comportamiento.












