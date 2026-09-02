# Capítulo V: Tactical-Level Software Design

## 5.X. Bounded Context: <Bounded Context Name></bounded>

*Qué debe ir: Para cada bounded context, presentar las clases identificadas y documentarlas como diccionario: nombre, propósito, atributos, métodos y relaciones. Repetir toda esta subsección para cada bounded context real del proyecto.*

### 5.X.1. Domain Layer

*Qué debe ir: Explicar las clases que representan el core y las reglas de negocio del bounded context. Considerar categorías como Entities, Value Objects, Aggregates, Factories, Domain Services y abstracciones como interfaces de Repositories.*

### 5.X.2. Interface Layer

*Qué debe ir: Introducir, presentar y explicar las clases de Interface/Presentation Layer, como Controllers o Consumers.*

### 5.X.3. Application Layer

*Qué debe ir: Explicar las clases que manejan los flujos de procesos del negocio y los capabilities del bounded context, incluyendo clases como Command Handlers y Event Handlers.*

### 5.X.4. Infrastructure Layer

*Qué debe ir: Presentar las clases que acceden a servicios externos como bases de datos, sistemas de mensajería o email. Aquí se ubican implementaciones de Repositories y, de forma análoga, implementaciones relacionadas con interfaces de MessageBrokers.*

### 5.X.6. Bounded Context Software Architecture Component Level Diagrams

*Qué debe ir: Presentar y explicar los Component Diagrams de C4 Model para los containers del bounded context. Mostrar los components, sus responsabilidades, interacciones y detalles de implementación/tecnología.*

### 5.X.7. Bounded Context Software Architecture Code Level Diagrams

*Qué debe ir: Presentar y explicar los diagramas con mayor detalle de implementación para el bounded context. Esta sección contiene los diagramas de clases del Domain Layer y el diseño de base de datos.*

#### 5.X.7.1. Bounded Context Domain Layer Class Diagrams

*Qué debe ir: Presentar el Class Diagram UML del Domain Layer con clases, interfaces, enumeraciones, relaciones, atributos, métodos y scope (private/public/protected). Las relaciones deben indicar nombre, dirección cuando aplique y multiplicidad.*

#### 5.X.7.2. Bounded Context Database Design Diagram

*Qué debe ir: Presentar y explicar el Database Diagram con los objetos de persistencia del bounded context. Si se usa base de datos relacional, especificar tablas, columnas, constraints (por ejemplo PK/FK) y relaciones entre tablas.*
