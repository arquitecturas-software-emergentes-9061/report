# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

El análisis competitivo se orienta a identificar soluciones que ya atienden, total o parcialmente, el problema de orientación dentro de espacios físicos complejos. Para el proyecto se han seleccionado cuatro competidores relevantes: **MazeMap**, **Pointr**, **Mappedin** y **ARway**. Los tres primeros cuentan con ofertas explícitas de indoor mapping y wayfinding para hospitales o instalaciones de salud, mientras que ARway incorpora navegación indoor mediante realidad aumentada, por lo que resulta especialmente relevante para contrastar el componente diferencial de la propuesta.

La comparación permite reconocer prácticas ya validadas en el mercado —como mapas indoor editables, rutas accesibles, integración con sistemas clínicos, analítica y soporte multicanal— y, al mismo tiempo, identificar un espacio de diferenciación en una experiencia centrada en el recorrido completo del paciente dentro de la clínica: **ubicarse, navegar, interactuar con puntos del proceso y completar su objetivo mediante asistencia contextual en AR**.

### 2.1.1. Análisis competitivo

**¿Por qué llevar a cabo este análisis?**  
Determinar qué capacidades de indoor mapping y wayfinding ya ofrecen las principales soluciones del mercado, qué tan cerca se encuentran de una experiencia contextual mediante realidad aumentada para clínicas y qué oportunidades existen para diferenciar la propuesta del equipo en experiencia del paciente, integración con el proceso de atención y simplicidad de adopción.

#### Competitive Analysis Landscape

| Categoría | Propuesta del equipo — **Rumbo** | <img src="https://cdn.prod.website-files.com/5fe0853f9e6927bb4c1a6644/60018c08c5bbb7e94657a8b2_M-06.png" alt="MazeMap" width="72"><br>**MazeMap** | <img src="https://hackerx.org/wp-content/uploads/2023/04/Pointr_logo_from_UK_based_company_Pointr.svg_-1.png" alt="Pointr" width="96"><br>**Pointr** | <img src="https://cdn.prod.website-files.com/685ab3474525f01f6bea0f46/69446598cf15071f7d118ccf_Mappedin-Logo-1-scaled.webp" alt="Mappedin" width="96"><br>**Mappedin** | <img src="https://www.nextechar.com/hubfs/Screen%20Shot%202022-08-03%20at%209.31.51%20AM.png" alt="ARway" width="84"><br>**ARway** |
|---|---|---|---|---|---|
| **Perfil — Overview** | Plataforma B2B para clínicas y establecimientos de salud que acompaña al paciente desde su ubicación inicial hasta un destino o paso del proceso mediante plano digital, navegación indoor y asistencia contextual en realidad aumentada. | Plataforma de mapas indoor y wayfinding para grandes campus, con una oferta específica para hospitales. | Plataforma empresarial de indoor mapping, positioning y navigation con una solución específica para healthcare. | Plataforma de indoor mapping y wayfinding con herramientas específicas para hospitales, visitantes, personal y operaciones. | Plataforma de indoor mapping, wayfinding, indoor positioning y experiencias de realidad aumentada para distintos tipos de espacios físicos. |
| **Ventaja competitiva — valor para el cliente** | Busca unir navegación espacial y contexto del proceso de atención: no solo indicar dónde queda un punto, sino acompañar al paciente durante acciones como llegar a admisión, consultorio, laboratorio u otro servicio. | Reduce fricción de orientación y puede integrarse con recordatorios de citas, kioscos y visualización de activos. | Combina mapas, blue-dot positioning, navegación e integraciones profundas con sistemas clínicos como Epic MyChart. | Facilita mapas actualizables, navegación accesible y conexión con sistemas como EHR, scheduling o directorios. | Su principal diferencial es la navegación AR turn-by-turn y una propuesta de despliegue sin beacons mediante marcadores visuales/QR. |
| **Perfil de Marketing — mercado objetivo** | Clínicas y establecimientos de salud que buscan mejorar la orientación y experiencia de pacientes/visitantes y reducir carga operativa asociada a dar indicaciones. | Hospitales, universidades, oficinas, hoteles, venues y otros campus complejos. | Healthcare, retail, aviation, hospitality, workplace y grandes despliegues empresariales. | Hospitales, malls, oficinas, escuelas, aeropuertos y otros venues complejos. | Malls, retail, aeropuertos, estadios, eventos, universidades, hospitality, museos y otros espacios que buscan navegación o experiencias AR. |
| **Perfil de Marketing — estrategias** | Enfoque vertical inicial en salud; propuesta centrada en la experiencia del paciente, demostraciones piloto dentro de clínicas y validación con usuarios y administradores. | Venta B2B mediante demos, casos de éxito y soluciones escalables por módulos/add-ons. | Venta enterprise basada en demos, integraciones, casos de éxito y paquetes Maps / Maps & Location. | Estrategia self-service + enterprise: permite comenzar con mapas gratuitos/pro y escalar a soluciones personalizadas. | Estrategia SaaS con free trial, planes para developers y ofertas Partner/Corporate para despliegues de mayor escala. |
| **Perfil de Producto — productos y servicios** | App móvil de navegación AR para pacientes; plataforma de configuración de espacios y puntos de interés para la clínica; backend/API; analítica de navegación y fricción. | Mapas 3D, wayfinding, indoor positioning, asset visualization, IoT integrations, map editor, APIs e integraciones. | Indoor maps, AI mapping, CMS, indoor positioning, navigation, analytics, geofencing, SDKs/APIs e integraciones con terceros. | Map editor, indoor navigation, AI mapping, SDK/API, accessible routing, data visualization e integraciones. | Indoor maps, interactive maps, AR navigation & indoor positioning, AR experiences, Creator Portal, analytics y SDK. |
| **Perfil de Producto — precios/costos** | Modelo por definir durante la validación del negocio; se evaluará una oferta B2B por establecimiento/sede y nivel de funcionalidad. | Precio empresarial sujeto a cotización; depende del área a mapear y de las soluciones/add-ons contratados. | Precios personalizados según cliente y alcance; no publica una tarifa única para soluciones enterprise. | Cuenta con nivel Free y plan Pro desde USD 165 por mapa/mes; soluciones enterprise/partner usan cotización personalizada. | Starter gratuito; Developer publicado en USD 299/mes y planes Partner/Corporate con precio personalizado. |
| **Canales de distribución** | Aplicación móvil para paciente y portal web para la clínica; integración vía APIs con sistemas existentes cuando el alcance lo permita. | Web, aplicaciones, kioscos, APIs e integraciones con sistemas del cliente. | iOS, Android, web, kioscos, SDKs y APIs; integración dentro de apps de terceros como Epic MyChart. | Web, mobile, kioscos, SDK/API, links/embeds y soluciones personalizadas. | Mobile, web, kiosk y headset según solución; distribución mediante plataforma, SDK y experiencias publicadas. |
| **SWOT — Fortalezas** | Especialización inicial en clínicas; propuesta AR contextual; posibilidad de diseñar el flujo completo alrededor de necesidades locales y validar desde cero con pacientes reales. | Experiencia comprobada en hospitales, integración con citas/activos y solución madura de wayfinding. | Escala enterprise, posicionamiento indoor, APIs/SDKs e integración con ecosistemas hospitalarios. | Madurez del editor, accesibilidad, facilidad para digitalizar planos e integraciones operativas. | AR nativo como parte central del producto, despliegue visual sin infraestructura de beacons y enfoque no-code. |
| **SWOT — Debilidades** | Producto aún en etapa de diseño/MVP; sin despliegues reales ni precisión indoor validada; ecosistema de integraciones todavía no definido. | La experiencia principal se centra en mapas/wayfinding y no en acompañamiento AR contextual del proceso del paciente. | Puede requerir una implantación enterprise e infraestructura/configuración más compleja que un MVP ligero. | La navegación principal se basa en mapas digitales; la realidad aumentada no constituye su propuesta central. | Oferta transversal y no especializada en procesos clínicos; el valor depende de un correcto anclaje y mantenimiento espacial del venue. |
| **SWOT — Oportunidades** | Clínicas con señalética insuficiente, pacientes que llegan tarde o requieren asistencia, integración futura con citas/turnos y analítica de recorridos para mejorar la experiencia. | Expandir integraciones hospitalarias y servicios de localización/activos. | Profundizar personalización clínica mediante EHR/EMR y despliegues a gran escala. | Integrar datos operativos y clínicos para convertir el mapa en una plataforma de experiencia y operaciones. | Verticalizar su tecnología AR en sectores específicos como healthcare y ampliar integraciones empresariales. |
| **SWOT — Amenazas** | Competidores globales ya consolidados; restricciones de dispositivos; precisión y mantenimiento del mapa; privacidad y seguridad en contextos de salud. | Plataformas con positioning más avanzado o experiencias AR más inmersivas. | Soluciones hardware-free y herramientas self-service de menor costo/menor fricción de despliegue. | Competidores especializados en posicionamiento indoor o navegación AR. | Competidores de mapping enterprise con mayor presencia en healthcare e integraciones clínicas más profundas. |

La información utilizada para construir el Landscape se sustenta en las fuentes oficiales de cada competidor, registradas en la sección **Bibliografía** del informe.

### 2.1.2. Estrategias y tácticas frente a competidores

A partir del Competitive Analysis Landscape se plantean las siguientes estrategias preliminares. Estas deberán refinarse después de las entrevistas y la validación del problema para evitar convertir supuestos de negocio en decisiones definitivas.

| Frente competitivo | Estrategia | Tácticas preliminares | Diferenciador buscado |
|---|---|---|---|
| **MazeMap / Mappedin — wayfinding maduro** | No competir únicamente como “otro mapa indoor”; llevar la propuesta hacia acompañamiento contextual del proceso del paciente. | Diseñar rutas vinculadas a objetivos concretos —admisión, consultorio, laboratorio, farmacia— y mostrar instrucciones AR en el momento de la navegación. Incorporar pruebas de usabilidad enfocadas en estrés, claridad y tiempo para llegar al destino. | Navegación orientada al proceso, no solo al espacio. |
| **Pointr — solución enterprise e integraciones** | Priorizar un MVP de menor fricción que pueda demostrar valor antes de requerir integraciones profundas o infraestructura compleja. | Comenzar con una clínica/piso piloto, configuración simplificada de POIs y rutas, y una arquitectura preparada para integrar citas/directorios posteriormente mediante APIs. | Entrada progresiva y validación rápida con posibilidad de escalar. |
| **ARway — navegación AR generalista** | Verticalizar la experiencia específicamente para salud y para las necesidades del paciente dentro del establecimiento. | Incorporar lenguaje claro, accesibilidad, rutas alternativas, contexto de atención y puntos del recorrido clínico. Validar la experiencia con pacientes y personal administrativo, no solo con usuarios generales de un venue. | Especialización en healthcare y patient journey. |
| **Competidores consolidados en general** | Usar cercanía al problema local como ventaja de descubrimiento y diseño. | Realizar entrevistas con pacientes de clínicas/hospitales y con representantes del lado operativo; priorizar problemas recurrentes encontrados en campo; documentar métricas de navegación y éxito desde el MVP. | Solución construida desde evidencia local y no únicamente desde features existentes en el mercado. |

## 2.2. Entrevistas

Para comprender el problema desde las dos perspectivas que intervienen en la experiencia de orientación dentro de una clínica, se realizarán entrevistas semiestructuradas a representantes de ambos segmentos objetivo. El primer segmento está conformado por **pacientes o visitantes que acuden a clínicas u hospitales**, mientras que el segundo corresponde al **personal administrativo u operativo de clínicas que interactúa con pacientes y participa en procesos de orientación, atención o gestión del espacio**.

Las entrevistas buscan identificar comportamientos actuales, objetivos, frustraciones, recursos utilizados, frecuencia de los problemas de orientación, impacto operativo y apertura frente a herramientas digitales de asistencia indoor. Las preguntas se han formulado de manera abierta para evitar inducir respuestas o presentar la solución antes de comprender el problema. Posteriormente, los hallazgos servirán como insumo para User Personas, User Task Matrix, Empathy Mapping, As-Is Scenario Mapping y la especificación de requisitos.

### 2.2.1. Diseño de entrevistas

#### Segmento 1 — Pacientes y visitantes de clínicas u hospitales

**Objetivo de la entrevista:** comprender cómo las personas se orientan actualmente dentro de establecimientos de salud, qué dificultades encuentran durante su recorrido y qué impacto tienen estas dificultades en su experiencia de atención.

**Preguntas principales**

1. Cuéntame sobre la última vez que acudiste a una clínica u hospital. ¿A qué fuiste y cómo fue tu recorrido desde que ingresaste hasta que llegaste al lugar que necesitabas?
2. Cuando llegas a un establecimiento que no conoces bien, ¿cómo haces normalmente para ubicar admisión, consultorios, laboratorios, farmacia u otros servicios?
3. ¿En qué momentos del recorrido te ha resultado más difícil saber hacia dónde ir o qué hacer después?
4. ¿Alguna vez te has perdido, has llegado tarde o has tenido que retroceder porque no encontrabas un ambiente? Cuéntame qué ocurrió.
5. ¿Qué recursos utilizaste para orientarte en esa situación: señalética, personal de la clínica, mapas, mensajes, aplicaciones u otros?
6. ¿Qué tan fácil o difícil te resulta interpretar la señalización dentro de clínicas u hospitales? ¿Por qué?
7. Cuando tienes una cita o procedimiento, ¿qué información recibes antes de llegar y qué información te gustaría tener para moverte con mayor seguridad dentro del establecimiento?
8. ¿Qué parte de la experiencia de orientación te genera mayor frustración, estrés o pérdida de tiempo?
9. ¿Sueles utilizar tu celular durante una visita a una clínica? ¿Para qué actividades lo utilizas normalmente?
10. Si una herramienta digital pudiera ayudarte durante el recorrido dentro de una clínica, ¿en qué momentos consideras que tendría más valor para ti?
11. ¿Hay alguna condición que haría que no utilizaras una herramienta de orientación desde tu celular? Por ejemplo, batería, datos móviles, privacidad, dificultad de uso o preferencia por preguntar a una persona.
12. Si pudieras cambiar una sola cosa de la forma en que las clínicas orientan actualmente a sus pacientes y visitantes, ¿qué cambiarías?

**Preguntas complementarias / de profundización**

- ¿Con qué frecuencia acudes a clínicas u hospitales?
- ¿Normalmente visitas el mismo establecimiento o diferentes sedes?
- ¿Sueles acudir solo o acompañado?
- ¿Tuviste que preguntar a más de una persona para encontrar el destino?
- ¿Cuánto tiempo consideras que perdiste buscando el lugar?
- ¿Qué hiciste después de llegar al primer punto, por ejemplo admisión o recepción?
- ¿Te resultó claro cuál era el siguiente paso del proceso?
- ¿Qué tipo de indicación te resulta más fácil de seguir: texto, flechas, mapa, referencias visuales, instrucciones por voz u otra?
- ¿Has utilizado alguna vez mapas o navegación indoor en centros comerciales, aeropuertos u otros espacios? ¿Cómo fue la experiencia?
- ¿Qué dispositivos y aplicaciones utilizas con mayor frecuencia en tu día a día?
- ¿Qué canales digitales prefieres para recibir información de una cita: aplicación, correo, WhatsApp, SMS u otro?

#### Segmento 2 — Personal administrativo u operativo de clínicas

**Objetivo de la entrevista:** comprender cómo la desorientación de pacientes y visitantes afecta la operación del establecimiento, cómo se gestiona actualmente la información de espacios y qué necesidades existirían para implementar una solución digital de orientación indoor.

**Preguntas principales**

1. ¿Cuál es tu rol dentro de la clínica y qué tipo de interacción tienes normalmente con pacientes o visitantes?
2. Cuéntame cómo se orienta actualmente a una persona que necesita llegar a un consultorio, laboratorio, admisión, farmacia u otro servicio.
3. ¿Con qué frecuencia los pacientes o visitantes solicitan indicaciones porque no encuentran un ambiente o no saben cuál es el siguiente paso?
4. ¿Cuáles son los puntos, pisos, servicios o momentos del proceso donde observas más confusión?
5. Cuando una persona se pierde o llega tarde por problemas de orientación, ¿qué consecuencias genera para la atención o para el trabajo del personal?
6. ¿Qué recursos utiliza actualmente la clínica para reducir estos problemas: señalética, mapas, módulos de información, personal de apoyo, mensajes previos u otros?
7. ¿Qué dificultades existen para mantener actualizada la información sobre ambientes, rutas, cambios temporales o puntos de atención?
8. ¿Quién suele ser responsable de actualizar o comunicar este tipo de información dentro de la organización?
9. ¿La clínica cuenta con sistemas digitales que manejen información útil para orientar al paciente, como citas, sedes, consultorios, directorios o servicios? ¿Cómo se utilizan actualmente?
10. ¿Qué información consideras que debería conocer una herramienta de orientación para que realmente sea útil dentro de una clínica?
11. ¿Qué métricas o resultados permitirían saber si una solución de orientación está generando valor? Por ejemplo, menos consultas al personal, menos tardanzas o menor tiempo para encontrar un destino.
12. ¿Qué preocupaciones tendrías al implementar una solución de este tipo dentro del establecimiento?
13. ¿Qué tan importante sería poder modificar rutas, puntos de interés o información del establecimiento sin depender constantemente de un proveedor técnico?
14. Si pudieras resolver un solo problema relacionado con la orientación y el recorrido de pacientes dentro de la clínica, ¿cuál priorizarías y por qué?

**Preguntas complementarias / de profundización**

- ¿Cuántas personas aproximadamente solicitan indicaciones durante un turno o día habitual?
- ¿Existen horarios, especialidades o campañas donde este problema aumente?
- ¿Qué áreas reciben con mayor frecuencia consultas de orientación?
- ¿Los cambios de consultorio o cierres temporales generan problemas adicionales?
- ¿Hay pacientes para quienes la orientación sea especialmente difícil, por ejemplo adultos mayores, personas con discapacidad o visitantes nuevos?
- ¿Qué canales usa la clínica actualmente para comunicarse con el paciente antes de su cita?
- ¿Qué información del establecimiento cambia con mayor frecuencia?
- ¿Sería necesario diferenciar rutas según accesibilidad, ascensores, restricciones o tipo de paciente?
- ¿Qué integraciones con sistemas actuales serían útiles y cuáles serían difíciles de implementar?
- ¿Qué requisitos de seguridad, privacidad o control de acceso serían importantes desde la perspectiva de la organización?
- ¿Quién debería administrar la plataforma y quién debería tener únicamente permisos de consulta?

### 2.2.2. Registro de entrevistas

*Qué debe ir: Realizar de 3 a 5 entrevistas por segmento. Para cada una registrar nombres, apellidos, edad, distrito, screenshot del video, URL en Microsoft Stream, timing de inicio y duración. Añadir un resumen descriptivo de las respuestas y características objetivas/subjetivas que luego sustentarán los arquetipos.*

### 2.2.3. Análisis de entrevistas

*Qué debe ir: Analizar cada segmento con sustento estadístico (porcentajes), identificando las características objetivas y subjetivas más comunes. La evidencia debe provenir de las entrevistas registradas y sus resúmenes.*

## 2.3. Needfinding

*Qué debe ir: Introducir y explicar los artefactos obtenidos a partir del análisis de la información recolectada.*

### 2.3.1. User Personas

*Qué debe ir: Incluir una introducción que conecte los artefactos con el análisis de entrevistas y competencia. Elaborar una ficha de User Persona por cada segmento objetivo utilizando la herramienta indicada (UXPressia).*

### 2.3.2. User Task Matrix

*Qué debe ir: Presentar las tareas que realizan los User Persona para alcanzar sus objetivos, sin confundir tareas con funcionalidades de software. Incluir por persona Frecuencia e Importancia y, después del cuadro, explicar tareas de mayor frecuencia/importancia, diferencias y coincidencias.*

### 2.3.3. Empathy Mapping

*Qué debe ir: Presentar y explicar un Empathy Map por cada User Persona. Documentar el proceso y las observaciones sobre qué necesita hacer, qué dice, ve, hace, escucha, siente y piensa, además de Pains y Gains.*

### 2.3.4. As-is Scenario Mapping

*Qué debe ir: Presentar un As-Is Scenario Map por cada User Persona con las filas Phases, Doing, Thinking y Feeling. Resumir el proceso seguido e identificar áreas positivas, negativas y blank areas que requieran mayor aprendizaje.*

## 2.4. Ubiquitous Language

*Qué debe ir: Redactar un glosario de términos del business domain sin ambigüedad. Incluir solo términos del dominio, no términos técnicos de ingeniería de software. Los términos deben estar en inglés; puede añadirse el equivalente en español entre paréntesis y la definición puede estar en español.*