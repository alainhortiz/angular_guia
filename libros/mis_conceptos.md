# Angular

Angular es un marco de diseño de aplicaciones y una plataforma de desarrollo para crear aplicaciones eficientes y sofisticadas de una sola página.

- Es un framework. 

- Marco de trabajo estandarizado.

- Viene con todo lo que necesitas para trabajar.

-Google es quien le da mantenimiento hoy en día.

# Bloques fundamentales

- Componentes

- Servicios

- Directivas

- Rutas

- Módulos

# Componentes en Angular

Los componentes son los bloques de construcción fundamentales para cualquier aplicación Angular. Es el mas peuqeño y esta conformado por tres partes:

- Clase TypeScript

- Plantilla HTML

- Estilos CSS

En Angular, puedes usar todos los CSS y HTML compatibles con el navegador que están disponibles. Si lo deseas, puedes almacenar la plantilla y los estilos en archivos separados.

# Servicios

Lugares centralizados de información. Podemos tener un componente que tenga un botón html que al darle clic llame a un servicio que traiga información de una BD.

# Directivas

Las directivas son como atributos que pueden cambiar la apariencia o el comportamiento del DOM element.

- Directivas de componentes. 

- Directivas Estructurales. Modifican el DOM o el HTML. Ej: ngIf, ngFor

- Directivas de Atributos. Cambian la apariencia o el comportamiento de un elemento, otro componente o bien una directiva. Ej:  ngClass, ngStyle.

- Directivas Customs. 

# Rutas

- Muestran diferentes componentes basados en el URL del navegador web.

# Módulos

- Permiten agrupar todos estos bloques e inclusive otros módulos. Se puede utilizar módulos de terceros en nuestra aplicación.  Ejemplos de módulos que conforman una aplicación:
  
- Módulo de Autenticación. Módulo de Clientes. Módulo de Productos. Módulo de Proveedores. 

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

 # Enlace de eventos
 El control de eventos habilita características interactivas en las aplicaciones web. Le brinda la capacidad como desarrollador de responder a las acciones del usuario, como presionar botones, enviar formularios y más.

En Angular se enlaza a eventos con la sintaxis de paréntesis. En un elemento determinado, envuelva el evento al que desea enlazar con paréntesis y establezca un controlador de eventos. Considere este ejemplo:()button

# Decorador
Un decorador es un tipo especial de declaración que se puede adjuntar a una clase, método, descriptor de acceso, propiedad o prámetro.

# Comunicación de componentes con @Input
A veces, el desarrollo de aplicaciones requiere que envíe datos a un componente. Estos datos se pueden utilizar para personalizar un componente o quizás enviar información de un componente principal a un componente secundario.

Angular utiliza un concepto llamado Input. Esto es similar a lo que ocurre en otros marcos. Para crear un archivo propsInput , use la propiedad @Input decorador.

El decorador @Input es un componente (o directiva) hijo significa que la propiedad puede recibir su valor de su componente padre.

# Comunicación de componentes con @Output
Al trabajar con componentes, es posible que sea necesario notificar a otros componentes que algo ha sucedido. Tal vez se ha hecho clic en un botón, se ha agregado/eliminado un elemento de una lista o se ha producido alguna otra actualización importante. En este escenario, los componentes deben comunicarse con los componentes primarios.

Angular utiliza el método @Output para habilitar este tipo de comportamiento.

# Ciclo de vida de un componente
Un componente tiene un ciclo de vida que comienza cuando Angular crea una instancia de la clase de componente y representa la vista del componente junto con sus vistas secundarias.












