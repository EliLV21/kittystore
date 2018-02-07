# Pet Store

[Work in progress]

## Tareas
### Procedimientos
Evaluar si el código actual cumple con los estándares básicos de programación por procedimientos: ¿Es claro, legible y tiene funciones que se dedican a procesos específicos?
#### Aproximación 1: 
- [ ] Con cada click sobre un gatito, se deben obtener sus datos 
- [ ] Primero del html, después de la BD kitties. 
- [ ] Cuando se tengan estos datos, se debe calcular el precio gatito *  cantidad 
- [ ]Crear un elemento de la lista carrito de compras con el numero de elementos seleccionados, con su precio. 
- [ ] Mostrar el total $$$
    ````javascript
        agregarAtributos();
        //se hace click
        obtenerData();
        contarElementos();
        calcularPrecio();
        // se abre el carrito
        crearElementosCarrito();
        //calcular total 
        calcularPrecioTotal();
        renderCarrito();
    ````

### OOP
* Añadir un objeto _Cart_ que te permita agregar, quitar o modificar los objetos seleccionados por el usuario.
* Al dar click el botón comprar, el modal que aparece debe contener los datos de la compra(listado de items y precio total + iva) estos datos deben provenir del nuevo objeto _Cart_.
* Evaluar si los listeners y las modificaciones al DOM merecen ser parte de un objeto. De ser así implementarlo con sus respectivos métodos y propiedades.
* Evaluar si cada uno de los productos merece ser convertido en un objeto, si es así deberíamos usar un factory? Herencia prototipal o quizás hacer una composicion?

### Programación Funcional
* De los métodos antes desarrollados, ¿cuál de ellos podría tener una aproximación funcional? Recuerda que esta aproximación debe tomar en cuenta inmutabilidad, funciones puras y predecibles.
* ¿Podríamos y/o deberíamos modificar todos nuestros objetos para implementar solamente FP?