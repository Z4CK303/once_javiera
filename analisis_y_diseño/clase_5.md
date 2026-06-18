Resumen: clase 5

Este documento recopila los conceptos esenciales relacionados con el diseño de software, incluyendo sus objetivos, niveles de diseño, principios fundamentales y las bases de la arquitectura de sistemas.

### 1. Concepto del Diseño de Software
Descripción: El diseño de software es una etapa del desarrollo en la que los requerimientos previamente analizados se convierten en modelos técnicos que servirán como guía para la construcción del sistema. Estos modelos describen la organización, estructura y funcionamiento del software antes de iniciar su implementación.
Diferencia entre análisis y diseño:
Análisis de requerimientos: Está orientado a identificar qué necesita el usuario o el negocio y cuáles son los problemas que el sistema debe resolver.
Diseño de software: Se enfoca en determinar cómo se construirá la solución, definiendo su estructura técnica, componentes y mecanismos de funcionamiento.

### 2. Niveles principales del Diseño de Software

El proceso de diseño se divide en diferentes niveles con el propósito de gestionar la complejidad del sistema:

Diseño arquitectónico: Establece la organización general del software, identificando sus módulos principales, subsistemas y las relaciones existentes entre ellos.
Diseño de interfaces: Define la manera en que los usuarios interactúan con el sistema y cómo este se comunica con aplicaciones o servicios externos mediante interfaces como APIs.
Diseño de componentes o diseño detallado: Especifica el comportamiento interno de cada módulo, incluyendo algoritmos, estructuras de datos, clases y procesos necesarios para su funcionamiento.
Diseño de datos: Organiza la información que manejará el sistema, definiendo modelos de almacenamiento, estructuras de bases de datos y relaciones entre los datos.

### 3. Principios esenciales del Diseño de Software

Un buen diseño debe seguir ciertos principios que favorecen la calidad, el mantenimiento y la evolución del software:

Abstracción: Permite representar los elementos más importantes de un sistema sin considerar inicialmente todos los detalles de su implementación.
Modularidad: Consiste en dividir el software en componentes independientes, cada uno encargado de una responsabilidad específica.
Encapsulamiento u ocultamiento de información: Busca proteger los detalles internos de un componente, permitiendo que otros módulos interactúen únicamente a través de sus elementos necesarios.
Alta cohesión: Se refiere a que cada módulo debe estar enfocado en una tarea concreta y bien definida, evitando responsabilidades innecesarias.
Bajo acoplamiento: Indica que los módulos deben tener la menor dependencia posible entre sí para facilitar modificaciones y mantenimiento.

### 4. Aspectos básicos de la Arquitectura de Software

Existen diferentes modelos arquitectónicos que permiten organizar un sistema según sus necesidades:

Arquitectura por capas: Separa el sistema en diferentes niveles, como la interfaz de usuario, la lógica de negocio y la gestión de datos.
Modelo cliente-servidor: Divide las responsabilidades entre los clientes que solicitan servicios y los servidores que proporcionan recursos o procesamiento.
Arquitectura basada en microservicios: Organiza la aplicación como un conjunto de servicios pequeños, independientes y capaces de desarrollarse o desplegarse de forma separada.
Importancia de la arquitectura: Una arquitectura adecuada permite que el software pueda mantenerse, ampliarse y adaptarse a nuevos requerimientos. Una mala decisión arquitectónica puede aumentar la complejidad y los costos de mantenimiento del proyecto.

### 5. Actividades de evaluación del módulo

Las actividades prácticas tienen como propósito comprobar la comprensión de los conceptos estudiados, mediante ejercicios orientados a:

Diferenciar las responsabilidades entre el análisis de requerimientos y el diseño de software.
Aplicar los conceptos de cohesión y acoplamiento para evaluar la calidad de una estructura de software.
Identificar problemas ocasionados por una dependencia excesiva entre módulos y proponer mejoras en el diseño.