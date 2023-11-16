Componentes en Angular

Los componentes son los bloques de construcción fundamentales para cualquier aplicación Angular. Cada componente tiene tres partes:

- Clase TypeScript

- Plantilla HTML

- Estilos CSS

En Angular, puedes usar todos los CSS y HTML compatibles con el navegador que están disponibles. Si lo deseas, puedes almacenar la plantilla y los estilos en archivos separados.

Actualización de la clase de componente

En Angular, la lógica y el comportamiento del componente se definen en la clase TypeScript del componente.

La interpolación se refiere a la incrustación de expresiones en texto marcado. De forma predeterminada, la interpolación utiliza las llaves dobles y como delimitadores.{{}}

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





