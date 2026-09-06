# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

*Qué debe ir: Evidenciar el proceso de Attribute-Driven Design de la solución. Incluir propósito, inputs, drivers arquitectónicos, decisiones de diseño y refinamiento de escenarios de atributos de calidad.*

### 4.1.1. Design Purpose

*Qué debe ir: Explicar el propósito del proceso de diseño, su relación con la problemática identificada y su orientación a las necesidades de los segmentos objetivo y del negocio.*

### 4.1.2. Attribute-Driven Design Inputs

*Qué debe ir: Introducir los tres tipos de input que se utilizarán en el proceso de diseño con ADD.*

#### 4.1.2.1. Primary Functionality (Primary User Stories)

*Qué debe ir: Seleccionar únicamente las Epics/User Stories con mayor relevancia funcional e impacto arquitectónico. Usar el cuadro de ID, título, descripción, criterios de aceptación y Epic relacionado; no duplicar todo el cuadro del capítulo de Requirements.*

#### 4.1.2.2. Quality attribute Scenarios

*Qué debe ir: Especificar la primera versión de los escenarios de atributos de calidad relevantes. Usar una fila por escenario con Atributo, Fuente, Estímulo, Artefacto, Entorno, Respuesta y Medida, asegurando que la medida sea cuantificable.*

#### 4.1.2.3. Constraints

*Qué debe ir: Especificar restricciones no negociables impuestas por el cliente o negocio. Introducirlas y luego representarlas como Technical Stories en un cuadro con ID, título, descripción, criterios de aceptación y Epic relacionado.*

### 4.1.3. Architectural Drivers Backlog

*Qué debe ir: Consolidar Functional Drivers, Quality Attribute Drivers y todos los Constraints acordados tras el Quality Attribute Workshop. Priorizar primero los drivers con alta importancia para stakeholders y alto impacto en Architecture Technical Complexity.*

### 4.1.4. Architectural Design Decisions

*Qué debe ir: Explicar el proceso por iteraciones del Quality Attribute Workshop: drivers considerados, tácticas/patrones evaluados y criterios de decisión. Complementar con Candidate Pattern Evaluation Matrix; si hay más de 3 patrones candidatos, mostrar los 3 más relevantes.*

### 4.1.5. Quality Attribute Scenario Refinements

*Qué debe ir: Presentar la versión final y priorizada de los escenarios refinados. Para cada escenario usar la estructura indicada: Scenario(s), Business Goals, Relevant Quality Attributes, Stimulus, Stimulus Source, Environment, Artifact, Response, Response Measure, Questions e Issues.*

## 4.2. Strategic-Level Domain-Driven Design

*Qué debe ir: Introducir y explicar el proceso de decisiones estratégicas aplicando Domain-Driven Design.*

### 4.2.1. EventStorming

*Qué debe ir: Explicar y evidenciar la sesión de EventStorming utilizada para modelar el dominio a alto nivel e identificar mayor detalle. Incluir capturas de la herramienta indicada y describir las actividades realizadas.*

### 4.2.2. Candidate Context Discovery

*Qué debe ir: A partir del EventStorm, explicar cómo se identificaron los candidate bounded contexts. El enunciado permite técnicas como start-with-value, start-with-simple o look-for-pivotal-events. Incluir capturas de la evolución del EventStorm.*

### 4.2.3. Domain Message Flows Modeling

*Qué debe ir: Explicar y evidenciar cómo colaboran los bounded contexts para resolver casos del negocio mediante Domain Storytelling. Incluir capturas de los diagramas elaborados.*

### 4.2.4. Bounded Context Canvases

*Qué debe ir: Diseñar los candidate bounded contexts por orden de importancia mediante Bounded Context Canvas. Documentar el proceso iterativo: Context Overview Definition, Business Rules Distillation & Ubiquitous Language Capture, Capability Analysis, Capability Layering (si aplica), Dependencies Capture y Design Critique.*

### 4.2.5. Context Mapping

*Qué debe ir: Explicar y evidenciar alternativas de context maps y su discusión hasta llegar a la mejor aproximación. Considerar patrones de relación DDD como Anti-corruption Layer, Conformist, Customer/Supplier o Shared Kernel.*

## 4.3. Software Architecture

La arquitectura de la solución se documenta mediante **C4 Model**, comenzando por las vistas estratégicas que permiten comprender el ecosistema y los límites del sistema antes de definir containers, componentes y decisiones de despliegue. En esta etapa se evita fijar prematuramente una tecnología concreta de posicionamiento indoor o un proveedor externo: dichas decisiones deben desprenderse de los architectural drivers, quality attributes, restricciones y bounded contexts que el equipo continuará refinando.

Las vistas presentadas a continuación describen el alcance conceptual actual del producto: una plataforma B2B para clínicas y establecimientos de salud que permite configurar un espacio indoor y asistir a pacientes/visitantes durante su recorrido mediante navegación contextual y realidad aumentada. La arquitectura deberá evolucionar sin perder consistencia con el análisis de usuarios, las historias de usuario y las decisiones de Domain-Driven Design.

### 4.3.1. Software Architecture System Landscape Diagram

El **System Landscape Diagram** presenta el ecosistema de alto nivel en el que opera la solución. El sistema principal es la *AR Indoor Navigation Platform*. Sus usuarios principales son el paciente o visitante que necesita orientación y el personal del establecimiento responsable de mantener información del espacio y revisar insights operativos.

También se muestran dos dependencias del entorno que todavía se mantienen de forma tecnológicamente neutral. Por un lado, los sistemas de información de la clínica pueden convertirse en fuente de datos de citas, servicios o destinos cuando se definan integraciones posteriores. Por otro lado, la navegación necesita una capacidad de referencia espacial o posicionamiento indoor; la tecnología concreta todavía debe seleccionarse mediante el proceso de diseño arquitectónico.

![Software Architecture System Landscape Diagram](../assets/chapter-04/c4/system-landscape/system-landscape.svg)

**Elementos principales del landscape:**

- **Patient / Visitor:** utiliza la solución para seleccionar un destino y recibir asistencia durante el recorrido.
- **Clinic Operations Staff:** configura destinos, rutas e información del establecimiento y consulta datos útiles para operación.
- **AR Indoor Navigation Platform:** sistema desarrollado por el equipo que concentra configuración del venue, navegación indoor, asistencia AR y generación de eventos/insights.
- **Clinic Information Systems:** sistemas externos potenciales que pueden aportar información de citas, servicios o directorios cuando exista una integración definida.
- **Spatial / Positioning Capability:** capacidad técnica necesaria para conocer o inferir la referencia espacial del usuario. Se representa sin proveedor específico porque la decisión todavía está abierta.

La representación evita convertir alternativas tecnológicas aún no evaluadas en compromisos arquitectónicos. De esta manera el landscape puede mantenerse estable mientras el equipo compara estrategias de positioning, actualización de planos e integración con sistemas clínicos.

### 4.3.2. Software Architecture Context Level Diagrams

El **Context Diagram** delimita la *AR Indoor Navigation Platform* como un único sistema de software y muestra las relaciones que mantiene con personas y sistemas externos. Este nivel no expone todavía aplicaciones, bases de datos, APIs ni componentes internos; dichas responsabilidades se detallarán en el Container Diagram y en las vistas tácticas posteriores.

![Software Architecture Context Level Diagram](../assets/chapter-04/c4/context/context-diagram.svg)

Desde la perspectiva del paciente, el sistema recibe la selección del destino y la interacción de navegación, y devuelve la ruta e indicaciones contextuales/AR. Desde la perspectiva operativa, el personal de la clínica mantiene la información del venue y consulta insights derivados del uso. La relación con sistemas clínicos se presenta como una integración opcional futura, mientras que la capacidad espacial/posicionamiento representa una dependencia necesaria cuyo mecanismo concreto aún debe definirse.

Esta vista establece un límite claro para el sistema y permite que las siguientes decisiones arquitectónicas respondan preguntas más específicas: qué containers asumirán la experiencia móvil y administrativa, dónde se ubicará la lógica de navegación, cómo se persistirá la configuración del establecimiento y de qué forma se desacoplará el mecanismo de posicionamiento para poder evolucionarlo sin afectar al resto de la solución.

### 4.3.3. Software Architecture Container Level Diagrams

*Qué debe ir: Presentar y explicar el Container Diagram, mostrando elementos de alto nivel, distribución de responsabilidades, principales decisiones tecnológicas y comunicación entre containers.*

### 4.3.4. Software Architecture Deployment Diagrams

*Qué debe ir: Incluir los diagramas de despliegue indicados en la estructura. El enunciado también exige el Deployment Diagram de C4 Model dentro de Software Deployment Configuration (7.1.4).*
