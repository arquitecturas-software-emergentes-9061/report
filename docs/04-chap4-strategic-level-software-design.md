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

*Qué debe ir: Presentar y explicar la arquitectura de software usando C4 Model y la herramienta indicada. El enunciado desarrolla especialmente los niveles Context y Container, además de incluir System Landscape y Deployment en la estructura oficial.*

### 4.3.1. Software Architecture System Landscape Diagram

*Qué debe ir: Incluir el Software Architecture System Landscape Diagram porque aparece explícitamente en la estructura oficial. El apartado descriptivo del enunciado no añade instrucciones específicas adicionales para este artefacto.*

### 4.3.2. Software Architecture Context Level Diagrams

*Qué debe ir: Presentar el Context Diagram, mostrando el sistema como un recuadro central rodeado por usuarios y otros sistemas con los que interactúa. Añadir una explicación del diagrama.*

### 4.3.3. Software Architecture Container Level Diagrams

*Qué debe ir: Presentar y explicar el Container Diagram, mostrando elementos de alto nivel, distribución de responsabilidades, principales decisiones tecnológicas y comunicación entre containers.*

### 4.3.4. Software Architecture Deployment Diagrams

*Qué debe ir: Incluir los diagramas de despliegue indicados en la estructura. El enunciado también exige el Deployment Diagram de C4 Model dentro de Software Deployment Configuration (7.1.4).*
