# Diseño de Patrones

## Tabla de contenido

- [Principios de diseño de Software](#principios-de-diseno-de-software)
- [Patrones Creacionales](#patrones-creacionales)
- [Patrones Estructurales](#patrones-estructurales)
- [Patrones de Comportamiento](#patrones-de-comportamiento)
- [Referencia](#referencia)

--- 

### Por qué aprender Patrones de Diseño?
> Los patrones de diseño son *soluciones comprobadas* a problemas habituales en el Diseño de Software. 
>
> Al utilizar los patrones de diseño nos permite la reutilización de código, que es la mejor forma de reducir costo de desarrollo.

### Principios de diseño de Software

**Encapsula lo que varia**

> Identifica los aspectos de tu aplicación que varían y sepáralos de los que se mantienen inalterables.

**Programa a una interfaz, no a una implementación**

> Depende de abstracciones, no de clases concretas.

**Favorece la composición sobre la herencia**

> Existe una alternativa a la herencia llamada composición. Mientras la herencia es la relación "es un/a" entre clases, la composición se basa en la relación "tiene un/a". Ejemplo: un auto tiene conductor pero este puede utilizar otro auto o caminar _sin el auto_.
---

### Patrones Creacionales

> Los patrones creacionales proporcionan varios mecanismos de creación de objetos que incrementan la flexibilidad y la **reutilización del código existente**.


1. FACTORY METHOD / **Método Fábrica**

Proporciona una interfaz para la creación de objetos en una superclase, mientras permite a las subclases alterar el tipo de objeto que se crearán.

2. ABSTRACT FACTORY / **Fábrica Abstracta**

Permite producir familias de objetos relacionados sin especificar sus clases concretas.

3. BUILDER / **Constructor**

Permite construir objetos complejos paso a paso. Este patrón nos permite producir distintos tipos de representaciones de un objeto empleando el mismo código de construcción.

4. PROTOTYPE / **Prototipo**

Permite copiar objetos existentes sin que el código dependa de sus clases.

5. SINGLETON / **Instancia Única**

Permite asegurarnos de que una clase tenga una única instancia, a la vez que proporciona un punto de acceso global a dicha instancia.

--- 

### Patrones Estructurales

> Los patrones estructurales explican como **ensamblar objetos y clases en estructuras más grandes**, a la vez que se mantiene la flexibilidad y eficiencia de estas estructuras.

1. ADAPTER / **Adaptador**

Permite colaboración entre objetos con interfaces incomplatibles

2. BRIDGE / **Puente**

Permite dividir una clase grande o un grupo de clases estrechamente relacionadas, en dos jerarquías separadas (abstracción e implentación) que pueden desarrollarse independientemente la una de la otra.

3. COMPOSITE / **Objeto Compuesto**

Permite componer objetos en estructuras de árbol y trabajar con esas estructuras como si fueran objetos individuales.

4. DECORATOR / **Decorador**

Permite añadir funcionalidades a objetos colocando estos objetos dentro de objetos encapsuladores especiales que contienen estas funcionalidades. 

5. FACADE / **Fachada**

Proporciona una interfaz simplificada a una biblioteca, un framework o cualquier otro grupo complejo de clases.

6. FLYWEIGHT / **Peso Mosca**

Permite mantener más objetos dentro de la cantidad disponible de memoria RAM compartiendo las partes comunes del estado entre varios objetos en lugar de mantener toda la información en cada objeto.

7. PROXY / **Proxy**

Permite proporcionar un sustituto o marcador de posición para otro objeto. Un proxy controla el acceso al objeto original, permitiéndotehacer algo antes o después de que la solicitud llegue al objeto original.

--- 

### Patrones de Comportamiento

> Los patrones de comportamiento tratan con **algoritmos y la asignación de responsabilidades entre objetos.**

1. CHAIN OF RESPONSIBILITY / **Cadena de Responsabilidad**

Permite pasar solicitudes a lo largo de una cadena de manejadores. Al recibir una solicitud, cada manejador decide si la procesa o si la pasa al siguiente manejador de la cadena.

2. COMMAND / **Comando**

Convierte una solicitud de un objeto independiente que contiene toda la información sobre la solicitud. Esta transformación te permite parametrizar los métodos con diferentes solicitudes, retrasar o poner en cola la ejecución de una solicitud y soporta operaciones que no se pueden realizar.

3. ITERATOR / Iterador

Permite recorrer elementos de una colección sin exponer su representación subyacente (lista, pila, árbol, etc)

4. MEDIATOR / **Mediador**

Permite reducir las dependencias caóticas entre objetos. El patrón restringe las comunicaciones directas entre los objetos, forzándolos a colaborar únicamente a través de un objeto mediador.

5. MEMENTO / **Recuerdo**

Permite guardar y restaurar el estado previo de un objeto sin revelar los detalles de su implementación.

6. OBSERVER / **Observador**

Permite definir un mecanismo de suscripción para notificar a varios objetos sobre cualquier evento que le suceda al objeto que están observando.

7. STATE / **Estado**

Permite a un objeto alterar su comportamiento cuando su estado interno cambia. Parece como si el objeto cambiara su clase.

8. STRATEGY / **Estrategia**

Permite definir una familia de algoritmos, colocar cada uno de ellos en una clase separada y hacer sus objetos intercambiables.


9. TEMPLATE METHOD / **Método de Plantilla**
Define el esqueleto de un algoritmo en la superclase pero permite que las subclases sobrescriban pasos del algoritmo sin cambiar su estructura.

10. VISITOR / **Visitante**

Permite separar algoritmos de los objetos sobre los que operan.


### Referencia

![Alexander Shvets](https://avatars.githubusercontent.com/u/121889?v=4)

Esto fue un resumen del libro:
> **_Sumérgete en los patrones de diseño_** de **Alexander Shvets**. 
> 
> Puedes visitar la página del autor en: [www.refactoring.guru](https://refactoring.guru/es/design-patterns/book)


