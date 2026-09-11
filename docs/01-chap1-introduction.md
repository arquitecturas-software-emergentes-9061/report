# Capítulo I: Introducción

## 1.1. Startup Profile

*Qué debe ir: Presentar la startup y los perfiles de los integrantes del equipo.*

### 1.1.1. Descripción de la Startup

*Qué debe ir: Describir la startup. El enunciado la entiende como una empresa de reciente creación, con potencial innovador y tecnológico y un modelo escalable.*

### 1.1.2. Perfiles de integrantes del equipo

<br>

<table>
  <tr>
    <th>Integrante</th>
    <th>Foto</th>
    <th>Descripcion</th>
  </tr>
  <tr>
    <td>José Jahaziel Guerra Perez (u202319831)</td>
    <td> <img src="https://i.ibb.co/LssNdfh/IMG-8966.jpg" alt="Imagen Jahaziel Guerra" style="width: 750px; margin-right: 20px; border-radius: 10%;"> </td>
    <td>
      Soy estudiante de Ingeniería de Software, actualmente cursando el octavo ciclo de la carrera. Me apasiona el aprendizaje continuo, la planificación detallada y la búsqueda de soluciones eficientes a problemas reales. <br>
      Mi enfoque profesional está orientado al desarrollo de software y al diseño de soluciones con una visión sistémica, con especial interés en backend, arquitecturas distribuidas, automatización, integración de servicios y construcción de productos escalables y mantenibles. <br>
      Asimismo, me interesa la aplicación de inteligencia artificial y modelos de lenguaje dentro de productos de software, especialmente cuando pueden integrarse con sistemas empresariales, procesos de automatización y flujos orientados a eventos para generar valor de negocio. También cuento con experiencia trabajando con APIs, procesamiento de datos, Git, GitHub y prácticas colaborativas como Git Flow y Conventional Commits. <br>
      Dentro del equipo, aporto principalmente en el análisis y diseño de arquitectura, definición de componentes y servicios, evaluación de alternativas tecnológicas, integración técnica y desarrollo de soluciones orientadas a resolver necesidades reales de los usuarios. Mi objetivo profesional es continuar desarrollándome como Full Stack Developer con una visión integral de arquitectura, cloud computing, automatización e inteligencia artificial aplicada al software.
    </td>
  </tr>
  <tr>
    <td>Gabriela Nicole Shapiama Rivera (u202319448)</td>
    <td> <img src="https://i.ibb.co/Y7svVgXm/gaby.jpg" alt="Imagen Gabriela Shapiama" style="width: 750px; margin-right: 20px; border-radius: 10%;"> </td>
    <td>
      Soy estudiante de octavo ciclo de Ingeniería de Software, con un fuerte interés por la lógica, el razonamiento y el desarrollo de soluciones tecnológicas con impacto real.<br>
  Me motiva desarrollar soluciones eficientes, escalables y bien estructuradas, por lo que he adquirido conocimientos en desarrollo full-stack para aplicaciones web y móviles. Cuento con experiencia en visión por computadora aplicada al reconocimiento de señas, así como en herramientas de procesamiento y análisis de datos como Databricks. Manejo herramientas de control de versiones como Git y plataformas colaborativas como GitHub, aplicando buenas prácticas como Gitflow y Conventional Commits. También, tengo conocimientos en Azure, GCP y Docker, lo que complementa mi interés por prácticas relacionadas con DevOps y despliegue de aplicaciones.<br>
  Del mismo modo, vengo fortaleciendo mis conocimientos en diseño y arquitectura de proyectos de software, junto con habilidades de liderazgo asertivo. Estoy comprometida con seguir aprendiendo y aportar valor a cada equipo en el que participo.
    </td>
  </tr>
</table>

## 1.2. Solution Profile

Esta sección presenta el perfil de la solución propuesta y la visión del modelo de negocio digital que será soportado por el producto de software. Se organiza en dos partes complementarias.

### 1.2.1. Antecedentes y problemática

En las últimas décadas, la infraestructura de los establecimientos de salud ha crecido de forma acelerada en el Perú. Las clínicas privadas de gran tamaño han dejado de ser un edificio único con pocos ambientes para convertirse en complejos distribuidos en varias torres, sótanos, pisos y bloques anexos, donde conviven consulta externa, laboratorio, imágenes, farmacia, admisión, caja, emergencia y unidades especializadas. Esta expansión responde a una mayor demanda de atención, pero introduce un efecto secundario poco atendido: la complejidad espacial del establecimiento crece más rápido que la capacidad del visitante para comprenderla.

El problema de orientarse dentro de un edificio complejo se conoce en la literatura como wayfinding, y en el sector salud está ampliamente documentado. Un estudio realizado por Ulrich y colegas en un hospital estadounidense de aproximadamente 604 camas estimó que se pierden cerca de 4,500 horas de personal al año únicamente por atender y reorientar a pacientes desorientados, lo que al año 2004 representaba alrededor de US$202,000, equivalente al costo de casi dos jornadas completas de un médico junior durante todo un año (citado en Revista Médica de Chile, 2014). En el mismo trabajo se reporta que, en un hospital chileno, los problemas de señalización se traducen en que una de cada seis personas camina al menos el doble de la distancia que debería haber recorrido para llegar a su destino.

Desde el lado tecnológico, la orientación en interiores presenta una limitación estructural conocida: el GPS no ofrece precisión suficiente dentro de edificios, por lo que las aplicaciones de navegación de uso masivo dejan de ser útiles justamente en el momento en que el paciente cruza la puerta del establecimiento. Los mecanismos que las clínicas emplean hoy, señalética fija, directorios impresos, tótems y personal de orientación, son estáticos, dependen de la interpretación del visitante y no reflejan cambios temporales como el traslado de un consultorio, el cierre de un ascensor o una campaña de salud que reubica un servicio.

What (¿Qué ocurre?)

Los pacientes y acompañantes no logran ubicar de forma autónoma los ambientes y puntos de atención que necesitan dentro del establecimiento, ni identificar con claridad cuál es el siguiente paso de su proceso de atención. El resultado es desorientación, recorridos innecesarios, consultas repetidas al personal y llegadas tarde al punto de atención.

El mecanismo de orientación efectivamente utilizado no es el que la clínica ha dispuesto para ello. Guillen-Calle et al. (2025) reportan que el 88,4% de los usuarios prefiere preguntar al personal, frente a un 11,6% que utiliza señalización o mapas. Es decir, la infraestructura de orientación existe, pero es sustituida en la práctica por la intervención humana.

When (¿Cuándo y con qué frecuencia ocurre?)

El problema aparece desde que la persona ingresa al establecimiento hasta que completa su objetivo de atención, con mayor incidencia en las transiciones del proceso: del ingreso a admisión, de admisión al consultorio, y del consultorio a laboratorio, imágenes, caja o farmacia. No se trata de un evento aislado sino de una condición recurrente en cada visita, que se agrava en horas de mayor afluencia y cuando existen cambios temporales en la ubicación de los servicios.

Where (¿Dónde sucede?)

El problema se manifiesta dentro de las instalaciones de clínicas privadas de gran tamaño de Lima Metropolitana: establecimientos distribuidos en varios pisos, torres o bloques, con múltiples servicios y transiciones verticales mediante ascensores, escaleras y rampas. La escala del entorno es determinante: el establecimiento estudiado por Quijano Muñoz (2024) abarca aproximadamente 23,431.24 m² y su digitalización requirió el registro de 301 puntos de interés, lo que ilustra el volumen de información espacial que un visitante debe procesar sin asistencia.

Who (¿Quiénes se ven afectados?)

Los afectados directos son los pacientes y acompañantes que acuden a clínicas privadas de gran tamaño, en particular quienes visitan la sede por primera vez, quienes acuden a un servicio distinto al que utilizan habitualmente y quienes llegan con restricciones de tiempo por una cita programada. La evidencia local sugiere que la dificultad no se limita a un perfil específico: no encontraron diferencias significativas en la capacidad de orientación según la frecuencia de visitas ni según el nivel educativo, lo que indica que el problema no se resuelve por familiaridad con el establecimiento ni por escolaridad del visitante.

Los afectados indirectos son el personal administrativo y operativo de la clínica, que debe interrumpir sus funciones para dar indicaciones, y los responsables de operaciones y de experiencia del paciente, quienes asumen el costo organizacional del problema sin contar hoy con información que lo haga visible.

Why (¿Por qué es un problema?)

Porque la información espacial del establecimiento es estática y está desacoplada del proceso de atención de la persona. La señalética no se actualiza al ritmo de los cambios operativos, no indica cuál es el siguiente paso del proceso y no puede personalizarse según el destino de cada visitante. A esto se suma la limitación técnica del posicionamiento satelital, que carece de precisión en interiores, razón por la cual las herramientas de navegación convencionales no cubren este escenario.

How (¿Cómo se manifiesta y cómo se enfrenta actualmente?)

El visitante recurre a la señalética y a los directorios impresos, pregunta al personal de recepción, seguridad o admisión, sigue a un acompañante que ya conoce el lugar, o explora el establecimiento por ensayo y error. Todos estos mecanismos dependen de la disponibilidad de un tercero o de la capacidad de interpretación del propio visitante.

Las limitaciones de la alternativa tradicional están documentadas. Quijano Muñoz (2024) señala que los mapas colocados en puntos estratégicos requieren actualizaciones frecuentes ante cambios de infraestructura, no ofrecen información sobre la atención brindada en cada área y representan un costo adicional para la organización

How much (¿Cuál es el impacto cuantitativo?)

La evidencia internacional permite dimensionar el costo operativo del problema: alrededor de 4,500 horas de personal perdidas al año en un hospital de aproximadamente 604 camas por reorientar pacientes, valorizadas en cerca de US$202,000 al año 2004, y una de cada seis personas recorriendo al menos el doble de la distancia necesaria dentro de un hospital.

### 1.2.2. Lean UX Process

*Qué debe ir: Aplicar Lean UX Process sobre el dominio del problema y la visión del modelo de negocio que será soportado por el producto de software.*

#### 1.2.2.1. Lean UX Problem Statements

*Qué debe ir: Redactar Problem Statements considerando, según el enunciado, aspectos como domain, customer segments, pain points, gap, visión/strategy e initial segment.*

#### 1.2.2.2. Lean UX Assumptions

*Qué debe ir: Registrar las assumptions del Lean UX Process que sustentan la propuesta. Deben formar parte del proceso documentado, sin presentarlas como hechos ya validados.*

#### 1.2.2.3. Lean UX Hypothesis Statements

*Qué debe ir: Formular los Hypothesis Statements del Lean UX Process, de modo que puedan contrastarse posteriormente con los resultados obtenidos durante el proyecto.*

#### 1.2.2.4. Lean UX Canvas

*Qué debe ir: Cerrar la sección Lean UX Process incluyendo el Lean UX Canvas elaborado para el modelo de negocio.*

## 1.3. Segmentos objetivo

*Qué debe ir: Describir los segmentos asociados al dominio del problema, incluyendo características demográficas e información estadística que sustente su definición.*
