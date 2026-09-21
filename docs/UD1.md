# UD 1 — DIGITALIZACIÓN EN LOS SISTEMAS PRODUCTIVOS

> Apuntes extendidos a partir del material de clase (presentación del Bloque 1).
> Asignatura: **Digitalización** — Curso 2026/27.



## Índice

1. [Digitalización en los sistemas productivos](#1-digitalización-en-los-sistemas-productivos)
2. [Digitalización y Transformación Digital](#2-digitalización-y-transformación-digital)
3. [Plan de Digitalización](#3-plan-de-digitalización)
4. [El proceso de Transformación Digital](#4-el-proceso-de-transformación-digital)
5. [Tipos de Transformación Digital](#5-tipos-de-transformación-digital)
6. [Implantación de la tecnología en la empresa](#6-implantación-de-la-tecnología-en-la-empresa)
7. [Entorno IT](#7-entorno-it)
8. [Entorno OT](#8-entorno-ot)
9. [Convergencia IT-OT](#9-convergencia-it-ot)
10. [Digitalización en planta](#10-digitalización-en-planta)
11. [Digitalización en negocio](#11-digitalización-en-negocio)
12. [Transformación Digital Integral](#12-transformación-digital-integral)
13. [Conclusiones](#13-conclusiones)

---

## 1. Digitalización en los sistemas productivos

### 1.1. Contexto actual: la Cuarta Revolución Industrial

Nos encontramos inmersos en lo que se conoce como la **Cuarta Revolución Industrial** o **Industria 4.0**, un cambio de paradigma que va mucho más allá de la mera automatización. Mientras que la **Industria 1.0** introdujo la máquina de vapor, la **2.0** trajo la electricidad y la producción en serie, y la **3.0** incorporó la electrónica y los primeros sistemas informatizados (PLC, robots), la **Industria 4.0** se caracteriza por la **interconexión inteligente** de máquinas, personas y procesos. La información deja de estar aislada en silos y fluye en tiempo real a lo largo de toda la cadena de valor.

| Revolución | Periodo aproximado | Tecnología clave | Aporte principal |
|---|---|---|---|
| 1.ª — Industria 1.0 | Finales del s. XVIII | Máquina de vapor | Mecanización del trabajo físico |
| 2.ª — Industria 2.0 | Finales del s. XIX – principios XX | Electricidad, cadena de montaje | Producción masiva en serie |
| 3.ª — Industria 3.0 | Décadas 1970–2000 | Electrónica, PLC, primeros PCs | Automatización programable |
| 4.ª — Industria 4.0 | Desde ~2011 | IoT, Cloud, Big Data, IA, gemelos digitales | Sistemas ciberfísicos conectados e inteligentes |

### 1.2. ¿Por qué digitalizar los sistemas productivos?

La presión competitiva, las expectativas del cliente y los marcos regulatorios hacen que la digitalización haya dejado de ser opcional. Las razones principales son:

- **Competitividad**: una planta digitalizada produce con menos recursos, menos paradas y menos defectos. Las empresas que no avanzan en este terreno pierden cuota de mercado frente a competidores más ágiles.
- **Trazabilidad completa**: poder seguir un producto desde la materia prima, por todas las fases de producción, hasta la entrega al cliente final —algo cada vez más exigido por clientes y reguladores.
- **Personalización masiva**: el mercado actual demanda lotes cada vez más pequeños e incluso unidades únicas adaptadas a cada cliente, lo que sólo es viable con sistemas flexibles y conectados.
- **Sostenibilidad**: medir y optimizar el consumo de energía, agua y materia prima reduce costes y, al mismo tiempo, el impacto ambiental.
- **Cumplimiento normativo**: regulaciones como las de calidad (ISO 9001),食品安全 (IFS, BRC) o medio ambiente (ISO 14001) exigen registrar digitalmente muchos procesos.
- **Atracción de talento**: las nuevas generaciones de profesionales prefieren entornos tecnológicamente avanzados.

### 1.3. Los diez pilares de la Industria 4.0

Para tener una visión completa del fenómeno, conviene conocer las tecnologías que lo sustentan:

1. **Sistemas ciberfísicos (CPS)** — son la fusión entre el mundo físico (máquinas, sensores, actuadores) y el mundo digital (software, datos, algoritmos). Permiten que un proceso físico "se entienda" con otro digital en tiempo real.
2. **Internet de las Cosas Industrial (IIoT)** — objetos físicos dotados de sensores y conectividad que generan datos sobre su estado, su uso o su entorno.
3. **Big Data y analítica avanzada** — capacidad de almacenar y procesar enormes volúmenes de datos para extraer patrones, tendencias y predicciones.
4. **Computación en la nube (Cloud) y edge computing** — la nube aporta capacidad de cálculo y almacenamiento casi ilimitada; el *edge* acerca el procesamiento al lugar donde se generan los datos para reducir latencia.
5. **Inteligencia Artificial (IA) y Machine Learning** — algoritmos que aprenden de los datos y son capaces de predecir, clasificar o decidir con poca o ninguna programación explícita.
6. **Robótica colaborativa (cobot)** — robots que trabajan junto a personas de forma segura, sin vallas, gracias a sensores de fuerza y visión.
7. **Fabricación aditiva (impresión 3D)** — permite producir piezas complejas, ligeras y personalizadas, reduciendo inventario y plazos.
8. **Realidad aumentada y virtual (AR/VR)** — útiles en formación, asistencia remota, mantenimiento guiado o simulación de procesos.
9. **Ciberseguridad industrial** — disciplina específica para proteger sistemas OT, donde un ciberataque puede tener consecuencias físicas graves.
10. **Gemelos digitales (digital twins)** — réplicas digitales de un proceso, máquina o incluso una fábrica entera, con las que se puede simular qué pasaría antes de tocar la realidad.

---

## 2. Digitalización y Transformación Digital

### 2.1. Diferencia clave entre ambos conceptos

Aunque en el lenguaje cotidiano se confundan, **digitalización** y **transformación digital** no significan lo mismo. Confundirlos es uno de los errores más habituales y, al mismo tiempo, uno de los más importantes de aclarar:

| Concepto | Definición | Alcance | Ejemplo |
|---|---|---|---|
| **Digitalización** | Proceso de convertir información, procesos o comunicaciones que estaban en formato analógico (papel, voz, observación humana) en formato digital. | **Operativo**: afecta a tareas concretas. | Pasar las hojas de pedidos en papel a una base de datos digital; sustituir un parte de averías manuscrito por una app. |
| **Transformación Digital (TD)** | Cambio **estratégico, cultural y organizativo** que una empresa experimenta al incorporar tecnologías digitales, modificando cómo opera, cómo compite y cómo aporta valor. | **Global**: afecta a la estrategia, las personas, los procesos, los productos y el modelo de negocio. | Rediseñar toda la cadena de suministro para tomar decisiones en tiempo real con datos que viajan de planta a cliente. |

> **Idea clave**: la **digitalización es la herramienta**, la **transformación digital es el proceso global** que la integra en la empresa para reinventarla.

Dicho de otra manera: se puede digitalizar sin transformar (por ejemplo, escanear todas las facturas y archivarlas en PDF, sin tocar el proceso), pero **no se puede transformar de verdad sin digitalizar**.

### 2.2. Las cinco dimensiones de la Transformación Digital

Una transformación digital seria afecta a cinco dimensiones simultáneamente:

1. **Tecnología** — adopción de nuevas herramientas: cloud, IA, IoT, plataformas de datos, etc.
2. **Organización** — nuevas estructuras (equipos multidisciplinares, células ágiles), eliminación de silos, nuevas formas de trabajo.
3. **Cultura** — mentalidad basada en datos (*data-driven*), tolerancia al error como parte del aprendizaje, curiosidad, colaboración.
5. **Modelo de negocio** — aparición de nuevos productos, servicios digitales, modelos de ingreso por suscripción, servitización (vender el uso en lugar del producto).
4. **Experiencia de cliente** — interacciones digitales fluidas, omnicanalidad, personalización.

### 2.3. Mitos frecuentes sobre la Transformación Digital

Conviene desmontar algunas creencias muy extendidas:

- ❌ **"Comprar software ya es transformarse digitalmente."** No. La tecnología es un medio, no el fin. Sin estrategia ni cultura adecuada, el software se queda en un proyecto aislado que muere en pocos meses.
- ❌ **"La TD es un proyecto del departamento de IT."** Es responsabilidad de **toda la organización**, empezando por la dirección. IT es un habilitador, no el dueño.
- ❌ **"Solo afecta a las grandes empresas."** Una pyme puede (y debe) digitalizar procesos clave: gestión de pedidos, mantenimiento, relación con clientes. El tamaño no es excusa.
- ❌ **"Es una moda pasajera."** No lo es: es un cambio estructural comparable a la electrificación de las fábricas en el siglo XX.
- ✅ **La TD afecta a personas, procesos y tecnología simultáneamente**, y los tres vectores deben avanzar en paralelo.

---

## 3. Plan de Digitalización

Un **Plan de Digitalización** es la hoja de ruta estratégica que una empresa diseña para incorporar tecnología de forma ordenada, alineada con sus objetivos de negocio. No es un documento de TI, sino un documento **de dirección**. Las fases habituales son las siguientes.

### 3.1. Diagnóstico inicial

Antes de hacer nada, hay que saber **dónde estamos**. Esto implica:

- **Inventario de sistemas actuales** (IT y OT): qué software, qué hardware, qué máquinas, qué sensores hay, qué lenguaje hablan entre sí (si es que hablan).
- **Mapa de procesos** (BPMN u otros): entender cómo se trabaja realmente, no sólo cómo dice el manual que se trabaja.
- **Análisis DAFO** (Debilidades, Amenazas, Fortalezas, Oportunidades) enfocado al uso de tecnología.
- **Evaluación de la madurez digital**: existen modelos de referencia como el **Modelo de Madurez de Siemens** (5 niveles) o el de **Acatech** que permiten ubicar a la empresa en un nivel y compararla con su sector.

### 3.2. Definición de la visión y objetivos

Con el diagnóstico hecho, se establece **hacia dónde se quiere ir**. Aquí es fundamental:

- Fijar la **visión**: qué tipo de empresa digital queremos ser en 3 a 5 años.
- Traducir esa visión en **objetivos concretos y medibles** mediante KPIs (OEE, lead time, costes de calidad, NPS, conversión digital, etc.).
- Alinear la estrategia digital con la **estrategia general** del negocio. Si no aporta a los objetivos de negocio, no debería estar en el plan.

### 3.3. Priorización de iniciativas

Rara vez una empresa puede hacerlo todo a la vez. Por eso se prioriza:

- **Matriz impacto/esfuerzo**: en el eje X, el esfuerzo (coste, complejidad, tiempo); en el eje Y, el impacto en negocio. Las iniciativas de alto impacto y bajo esfuerzo son **quick wins**; las de alto impacto y alto esfuerzo son proyectos **estratégicos**.
- **Análisis de dependencias**: qué proyectos necesitan ir antes que otros (por ejemplo, no se puede hacer analítica avanzada sin antes tener datos limpios y accesibles).

### 3.4. Hoja de ruta (Roadmap)

Es la traducción temporal del plan. Suele estructurarse en:

- **Corto plazo (0–6 meses)**: quick wins, formación básica, pilotajes.
- **Medio plazo (6–18 meses)**: implantaciones principales, integración de sistemas.
- **Largo plazo (1–3 años)**: proyectos estratégicos, transformación cultural profunda, nuevos modelos de negocio.

En cada hito deben definirse **recursos necesarios** (humanos, técnicos, económicos), **responsables** y **entregables verificables**.

### 3.5. Ejecución e implantación

La ejecución suele apoyarse en **metodologías ágiles** (Scrum, Kanban) porque permiten iterar, adaptarse y entregar valor en ciclos cortos. También es clave:

- La **integración con proveedores y partners** tecnológicos.
- La **gestión del cambio**: comunicación interna continua, formación, identificación de "champions" (personas entusiastas que tiren del cambio).
- La **gestión de riesgos**: técnicos, de seguridad, de adopción.

### 3.6. Medición y mejora continua

Un plan de digitalización **nunca termina**: se revisa, se ajusta, se vuelve a medir. Para ello se utilizan:

- **Cuadros de mando** con los KPIs definidos.
- **Revisiones periódicas** siguiendo el ciclo **PDCA** (Plan–Do–Check–Act): planificar, hacer, comprobar los resultados, actuar para corregir y volver a empezar.

### 3.7. Modelos de madurez digital

Una forma estándar de medir el punto de partida y la evolución:

| Nivel | Nombre | Descripción |
|---|---|---|
| 0 | Inicial | Procesos manuales, sin datos digitalizados, decisiones por intuición. |
| 1 | Inicial digitalizado | Algunas tareas informatizadas pero aisladas, sin integración. |
| 2 | Conectado | Sistemas conectados entre sí, ERP implantado, datos estructurados. |
| 3 | Inteligente | Datos integrados, analítica y soporte a la decisión, dashboards. |
| 4 | Transformador | IA, gemelos digitales, innovación continua, nuevos modelos de negocio. |

---

## 4. El proceso de Transformación Digital

### 4.1. Etapas generales del proceso

El proceso puede esquematizarse como una cadena:

```
Sensibilización ➜ Visión ➜ Estrategia ➜ Ejecución ➜ Escala ➜ Cultura digital
```

1. **Sensibilización**: entender por qué es necesario el cambio, qué riesgos tiene no hacerlo y qué oportunidades ofrece. Suele partir de la dirección o de un equipo impulsor interno.
2. **Visión**: definir la empresa digital objetivo. Sin una visión compartida, las iniciativas se dispersan.
3. **Estrategia**: convertir la visión en un plan con objetivos, recursos, plazos y gobernanza.
4. **Ejecución**: lanzar proyectos piloto, aprender rápido, corregir, escalar. Aquí es donde la gestión del cambio y la metodología ágil son críticas.
5. **Escalado**: pasar de pilotos aislados a soluciones transversales a toda la empresa.
6. **Cultura digital**: la meta última. Cuando la organización **ya piensa digitalmente** por defecto, la transformación se ha consolidado.

### 4.2. Factores críticos de éxito

Hay factores sin los cuales la transformación fracasa aunque se invierta mucho dinero:

- **Liderazgo comprometido desde la dirección**: si la dirección no se implica, el resto percibe que "no va en serio".
- **Estrategia clara**, alineada con el negocio, con prioridades explícitas.
- **Gobernanza del dato**: quién es responsable de cada dato, qué calidad tiene, quién puede acceder, cómo se protege.
- **Formación continua**: la tecnología cambia, y las personas con ella.
- **Gestión del cambio**: comunicación transparente, incentivos, atención a la resistencia.
- **Alianzas tecnológicas fiables**: proveedores, partners, centros tecnológicos, startups.

### 4.3. Barreras más habituales

- **Resistencia al cambio** del personal, especialmente cuando se percibe una amenaza al puesto de trabajo.
- **Falta de presupuesto** o, más a menudo, **falta de talento digital**.
- **Sistemas legacy** (antiguos) difíciles de migrar o integrar.
- **Ciberseguridad y compliance**: ampliar la superficie digital aumenta los riesgos.
- **Falta de visión estratégica clara**: se compra tecnología sin saber para qué.
- **Cultura del "aquí siempre se ha hecho así"**.

---

## 5. Tipos de Transformación Digital

### 5.1. Según el alcance

| Tipo | Descripción | Ejemplos |
|---|---|---|
| **De procesos** | Automatización y optimización de procesos internos. | Digitalizar la gestión de pedidos, automatizar la facturación, implantar un MES. |
| **De modelo de negocio** | Cambia lo que la empresa ofrece o cómo gana dinero. | Servitización, suscripciones digitales, plataformas. |
| **De dominio** | Entrar en nuevos mercados o sectores gracias a lo digital. | Una empresa industrial que ofrece servicios de monitorización remota. |
| **Cultural/organizativa** | Cambio en la mentalidad y en las formas de trabajar. | Adoptar metodologías ágiles, trabajo en red, decisiones data-driven. |
| **Global o Integral** | Combinación de todas las anteriores, con estrategia unificada. | La Transformación Digital Integral de la que hablaremos más adelante. |

### 5.2. Según el enfoque de impulso

- **Top-down**: la dirección define y empuja el cambio. Necesario cuando se requiere velocidad y recursos, pero puede generar rechazo si no hay comunicación.
- **Bottom-up**: el cambio surge desde los equipos operativos que detectan oportunidades. Suele ser bien recibido, pero más lento y disperso.
- **Híbrido**: combinación de ambos, generalmente la opción más eficaz. La dirección marca la estrategia y los equipos la ejecutan con autonomía.

### 5.3. Según la velocidad y profundidad

- **Incremental**: pequeños pasos controlados, menor riesgo, resultados acumulativos. Es la más segura para empresas sin experiencia digital.
- **Disruptiva**: saltos grandes que cambian las reglas del juego. Mayor riesgo, pero potencialmente mayor recompensa. Exige madurez organizativa y financiera.

---

## 6. Implantación de la tecnología en la empresa

### 6.1. Decisiones previas a cualquier compra

Antes de adquirir cualquier tecnología, la empresa debería poder responder con claridad a estas preguntas:

1. **¿Qué problema de negocio se quiere resolver?** Si no hay un problema claro, no hay proyecto.
2. **¿Qué alternativas existen?** Proveedores, soluciones, hacer o comprar, construir o subcontratar.
3. **¿Cuál es el coste total de propiedad (TCO)?** No sólo el precio de compra, sino licencias, mantenimiento, formación, integraciones,能耗, etc.
4. **¿Cómo se integra con los sistemas actuales?** Una solución aislada suele acabar sin usarse.
5. **¿Qué formación necesita el personal?** Sin formación, la herramienta se abandona.
6. **¿Qué riesgos implica?** Técnicos, de seguridad, de dependencia de un único proveedor, de cumplimiento normativo.

### 6.2. Ciclo de implantación

El proceso de llevar una tecnología desde la idea hasta su operación habitual sigue, en la mayoría de los casos, este ciclo:

```
Análisis ➜ Selección ➜ Pilotaje ➜ Despliegue ➜ Operación ➜ Mejora continua
```

- **Análisis**: definir el problema, los requisitos, los criterios de éxito.
- **Selección**: elegir la tecnología y el proveedor adecuados.
- **Pilotaje**: probar la solución en un entorno reducido y controlado. Es la fase donde más se aprende y más barato sale equivocarse.
- **Despliegue**: extender la solución al resto de la empresa siguiendo un plan por fases.
- **Operación**: mantenimiento, soporte, gestión de incidencias.
- **Mejora continua**: incorporar feedback, nuevas funcionalidades, optimizar el uso.

### 6.3. Criterios de éxito en la implantación

Para aumentar las probabilidades de éxito:

- **Alineación** con la estrategia de la empresa.
- **Escalabilidad** de la solución (que pueda crecer con la empresa).
- **Interoperabilidad** con sistemas existentes (estándares abiertos siempre que sea posible).
- **Soporte y mantenimiento** garantizados a largo plazo.
- **ROI medible**: poder demostrar que la inversión se recupera, idealmente en plazos definidos.

---

## 7. Entorno IT (Information Technology)

### 7.1. Definición

**IT** agrupa todo lo relacionado con el **tratamiento de la información**: hardware, software, redes, datos y personas que los gestionan. Su misión tradicional es dar soporte a las áreas de negocio: finanzas, recursos humanos, comercial, logística, atención al cliente, etc. En definitiva, IT maneja **datos sobre el negocio**.

### 7.2. Componentes típicos de un entorno IT

- **Infraestructura física**: servidores, almacenamiento, redes LAN/WAN, centros de datos, dispositivos de usuario.
- **Sistemas de gestión empresarial (ERP)**: SAP, Oracle, Microsoft Dynamics, etc. Integran las áreas clave de la empresa en una única base de datos.
- **Sistemas de relación con clientes (CRM)**: Salesforce, HubSpot, Microsoft Dynamics CRM, etc.
- **Bases de datos y data warehouses**: donde se almacena y estructura la información.
- **Aplicaciones ofimáticas y de gestión**: correo, suite ofimática, gestión documental, herramientas de colaboración.
- **Servicios en la nube (SaaS, PaaS, IaaS)**: aplicaciones, plataformas e infraestructura como servicio, contratadas a proveedores como AWS, Azure o Google Cloud.
- **Ciberseguridad corporativa**: firewalls, antivirus, sistemas de detección, gestión de identidades, copias de seguridad.

### 7.3. Características del entorno IT

- **Alta estandarización**: predominan protocolos y plataformas comunes.
- **Ciclos de cambio relativamente largos**: un ERP puede mantenerse 10–15 años.
- **Prioriza la integridad, confidencialidad y disponibilidad** del dato (tríada CIA de la seguridad de la información).
- Habitualmente gestionado por el **departamento de sistemas / CIO** (Chief Information Officer).
- El dato suele ser **transaccional y estructurado** (facturas, pedidos, nóminas, contratos).

---

## 8. Entorno OT (Operational Technology)

### 8.1. Definición

**OT** es la tecnología que **controla y monitoriza los procesos físicos** de la empresa: máquinas, robots, PLC, sistemas SCADA, sensores, actuadores. Es, en cierto sentido, el "cerebro y los nervios" de la planta productiva. Mientras IT trabaja con datos sobre el negocio, OT trabaja con datos sobre **el proceso físico**.

### 8.2. Componentes típicos de un entorno OT

- **PLC (Controladores Lógicos Programables)**: pequeños computadores industriales que ejecutan la lógica de control de una máquina o proceso.
- **SCADA (Supervisory Control and Data Acquisition)**: software que permite supervisar y operar el proceso desde pantallas HMI, registrando alarmas y eventos.
- **HMI (Human-Machine Interface)**: las pantallas y paneles con los que los operarios interactúan con las máquinas.
- **Sensores y actuadores**: ojos (sensores) y manos (actuadores) del sistema. Miden magnitudes físicas (temperatura, presión, vibración) y ejecutan acciones (abrir válvulas, mover motores).
- **Robótica industrial**: brazos, AGV (vehículos de guiado automático), AMR (robots móviles autónomos), cobrones.
- **Variadores de frecuencia y servoaccionamientos**: controlan motores eléctricos con precisión.
- **Redes industriales**: Profibus, Modbus, Profinet, EtherCAT, IO-Link. Diseñadas para ser deterministas y robustas frente a interferencias.
- **Sistemas MES (Manufacturing Execution System)**: capa intermedia entre el ERP y el control de planta. Gestionan las órdenes de fabricación en tiempo real.
- **Gemelos digitales** de proceso/equipo: réplicas digitales usadas para simular, predecir y optimizar.

### 8.3. Características del entorno OT

- Prioriza la **disponibilidad y la seguridad física (Safety)** por encima de cualquier otra cosa: una caída del sistema puede provocar accidentes, paradas y pérdidas enormes.
- **Ciclos de vida muy largos**: máquinas con 15–25 años funcionando con el mismo controlador son habituales.
- **Tolerancia cero a fallos** no controlados que paren la producción.
- Estándares industriales específicos (ISA-95, IEC 62443 para ciberseguridad industrial, IEC 61131 para programación de PLC).
- El dato suele ser **de proceso, en tiempo real y en grandes volúmenes** (series temporales de sensores).

---

## 9. Convergencia IT-OT

### 9.1. ¿Qué es la convergencia IT-OT?

Es la **integración tecnológica y organizativa** de los dos mundos descritos: IT y OT. El objetivo es que la información fluya sin barreras **desde el sensor en planta hasta el sistema de gestión empresarial** y, a la vez, que las decisiones de negocio (pedidos, planificación) lleguen al mismo nivel de la planta para su ejecución.

Visualmente, la convergencia puede representarse así:

```
[Planta / Sensores]  ⇄  [MES / SCADA]  ⇄  [ERP / Cloud]  ⇄  [Cliente / Analítica]
   OT                                              IT
```

Esta cadena coincide con el modelo **ISA-95**, que define los niveles de integración entre empresa y planta:

| Nivel | Función | Ejemplos |
|---|---|---|
| 0 | Proceso físico | Sensores, actuadores, motores |
| 1 | Control básico | PLC, DCS |
| 2 | Supervisión y operación | SCADA, HMI |
| 3 | Operación y control de fabricación | MES |
| 4 | Planificación y gestión empresarial | ERP, CRM |
| 5 | Inteligencia de negocio | BI, IA, gemelos digitales |

### 9.2. Beneficios de la convergencia

- **Visibilidad total** de la operación en tiempo real: se sabe qué se está fabricando, dónde y cómo en cada momento.
- **Toma de decisiones basada en datos reales** de planta, no en estimaciones.
- **Optimización de la cadena de suministro** extremo a extremo.
- **Mantenimiento predictivo**: detectar anomalías antes de que se conviertan en averías.
- **Mayor agilidad** para responder a cambios de la demanda o del mercado.
- **Nuevos modelos de negocio** basados en datos (servitización, pago por uso, etc.).

### 9.3. Retos de la convergencia

- **Cultura organizativa**: dos mundos tradicionalmente separados, con lenguajes, prioridades y métricas diferentes.
- **Diferencias técnicas**: protocolos incompatibles, requisitos de latencia muy distintos, criticidad diferente.
- **Ciberseguridad**: la integración amplía la superficie de ataque. Un fallo de seguridad en IT puede acabar afectando a la planta (y al revés).
- **Gobernanza del dato**: quién es responsable de cada dato, cómo se garantiza su calidad, quién puede acceder.
- **Inversión y plazos**: integrar sistemas viejos (legacy) con plataformas modernas no es barato ni rápido.

### 9.4. Tecnologías habilitadoras de la convergencia

- **OPC UA** — estándar abierto de comunicación industrial, pensado específicamente para ser interoperable entre IT y OT.
- **MQTT** — protocolo ligero de mensajería, muy usado en IoT para enviar telemetría con poco consumo.
- **Edge computing** — procesamiento de datos cerca de la planta, reduciendo latencia y dependencia de la nube.
- **Plataformas IIoT** — software que ingiere, almacena y visualiza datos de planta (PTC ThingWorx, Siemens MindSphere, AWS IoT, Azure IoT, etc.).
- **Modelos de referencia ISA-95 e IEC 62443** — marcos de referencia para integración y ciberseguridad industrial.

---

## 10. Digitalización en planta

### 10.1. Áreas de aplicación

La digitalización en planta (a veces llamada **smart manufacturing** o **smart factory**) afecta a prácticamente todas las funciones:

- **Mantenimiento**: sensores de vibración, temperatura, corriente y ultrasonido permiten detectar anomalías y pasar del mantenimiento correctivo (esperar a que se rompa) al preventivo (revisar cada cierto tiempo) y, finalmente, al **mantenimiento predictivo** (intervenir justo cuando los datos indican que va a fallar).
- **Calidad**: sistemas de **visión artificial** que inspeccionan cada pieza al 100 % sin fatiga, registrando además los datos para trazabilidad.
- **Producción**: cálculo de **OEE** en tiempo real, gestión flexible de órdenes, equilibrio de líneas.
- **Logística interna**: vehículos autónomos (**AGV/AMR**), seguimiento de materiales con RFID o beacons.
- **Seguridad y salud**: wearables que detectan caídas, posturas inadecuadas, exposición a ruido o gases.
- **Energía**: monitorización continua de consumos para detectar ineficiencias y optimizar el uso.

### 10.2. Tecnologías clave en planta

- **Sensórica avanzada (IIoT)**: sensores cada vez más baratos, con más conectividad.
- **Robótica colaborativa y AGV/AMR**: robots que comparten espacio con personas y vehículos que mueven material sin conductor.
- **Visión artificial y reconocimiento de patrones**: inspección, control dimensional, lectura de códigos.
- **MES (Manufacturing Execution System)**: coordina la ejecución de las órdenes en planta, en tiempo real.
- **Realidad aumentada** en operaciones de campo: gafas o tablets que muestran instrucciones sobre la pieza que se está trabajando.
- **Impresión 3D** para prototipos, herramientas y repuestos de baja rotación.
- **Gemelos digitales** de proceso o de planta: permiten simular cambios antes de hacerlos.

### 10.3. Indicadores habituales en planta

| KPI | Qué mide | Por qué es importante |
|---|---|---|
| **OEE** | Eficiencia global del equipo (Disponibilidad × Rendimiento × Calidad) | Resume en un solo número cuánto aprovecha una máquina su tiempo productivo. |
| **MTBF** | Tiempo medio entre fallos | Mide la fiabilidad del equipo. |
| **MTTR** | Tiempo medio de reparación | Mide la mantenibilidad. |
| **Scrap / rechazo** | Porcentaje de piezas defectuosas | Mide la calidad de la producción. |
| **Lead time** | Tiempo desde pedido hasta entrega | Mide la capacidad de respuesta al cliente. |
| **Consumo energético específico** | kWh / unidad producida | Mide la eficiencia energética. |

---

## 11. Digitalización en negocio

### 11.1. Áreas de aplicación

La digitalización en negocio afecta a todas las funciones de gestión y comerciales:

- **Comercial y marketing**: CRM, analítica web, comercio electrónico, marketing digital, redes sociales, embudos de conversión.
- **Finanzas**: automatización de conciliaciones, facturación electrónica, analítica avanzada, planificación financiera.
- **Recursos Humanos**: gestión del talento, formación online (e-learning), People Analytics (analítica de datos de personas).
- **Logística y cadena de suministro**: trazabilidad extremo a extremo, gestión de proveedores, optimización de rutas.
- **Atención al cliente**: chatbots, omnicanalidad, autoservicio, knowledge bases.

### 11.2. Tecnologías clave en negocio

- **ERP y CRM en la nube** — accesibles desde cualquier dispositivo, con actualizaciones continuas y menor inversión inicial.
- **Analítica avanzada y BI (Business Intelligence)** — herramientas como Power BI, Tableau, Looker o Qlik para visualizar y analizar datos.
- **RPA (Robotic Process Automation)** — software que automatiza tareas repetitivas (introducir datos, copiar entre aplicaciones, generar informes).
- **IA generativa** — aplicada a redacción, generación de código, atención al cliente, síntesis de documentos, etc.
- **Plataformas low-code/no-code** — permiten a usuarios no técnicos crear aplicaciones sin programar.
- **Firma electrónica y gestión documental digital** — para sustituir el papel y acelerar procesos administrativos.

### 11.3. Indicadores habituales en negocio

- **Tasa de conversión digital**: porcentaje de visitantes que completan la acción deseada.
- **Coste de adquisición de cliente (CAC)**: cuánto cuesta conseguir un cliente nuevo.
- **Valor de vida del cliente (LTV)**: cuánto aporta un cliente a lo largo de su relación con la empresa.
- **Net Promoter Score (NPS)**: mide la probabilidad de que un cliente recomiende la empresa.
- **Margen operativo**: beneficio sobre ventas, indicador financiero clásico.
- **Plazo medio de cobro**: tiempo que tarda la empresa en cobrar a sus clientes.

---

## 12. Transformación Digital Integral

### 12.1. Concepto

La **Transformación Digital Integral** es el enfoque que aborda la transformación **de manera global**, alineando **planta, negocio, personas y cultura** con una única estrategia digital. No se trata de digitalizar por separado la fábrica y la oficina, sino de concebir la empresa como un **único sistema digital** en el que las decisiones fluyen en ambos sentidos.

### 12.2. Componentes clave

1. **Estrategia digital** clara y medible, alineada con la estrategia general de la empresa.
2. **Gobernanza** del dato y de los proyectos: quién decide, con qué criterios, cómo se mide el progreso.
3. **Plataforma tecnológica integradora** que una IT, OT, cloud y edge en una arquitectura coherente.
4. **Personas**: nuevos perfiles profesionales (científicos de datos, ingenieros IT-OT, especialistas en ciberseguridad), formación continua.
5. **Cultura de innovación y mejora continua**: experimentación controlada, aprendizaje del error, escucha activa del cliente.
6. **Alianzas**: clientes, proveedores, startups, centros tecnológicos, universidades. Ninguna empresa puede hacerlo todo sola.

### 12.3. Beneficios de la integralidad

- **Agilidad organizativa** para responder a la incertidumbre del mercado.
- **Reducción de costes estructurales** por eliminación de tareas sin valor añadido y optimización de recursos.
- **Mayor seguridad y cumplimiento normativo** al tener procesos trazables y auditables.
- **Capacidad de innovar** en producto y servicio, abriendo nuevas fuentes de ingreso.
- **Sostenibilidad** mediante la optimización de recursos y el menor uso de papel y desplazamientos.
- **Atracción y retención de talento**, al ofrecer un entorno de trabajo más moderno y estimulante.

### 12.4. Hoja de ruta típica de una Transformación Digital Integral

Aunque cada empresa es diferente, suele haber un patrón común:

- **Fase 1 — Cimientos**: ERP, conectividad básica, cultura del dato, ciberseguridad básica.
- **Fase 2 — Conexión**: integración IT-OT, MES, BI, automatización de procesos administrativos.
- **Fase 3 — Inteligencia**: analítica avanzada, mantenimiento predictivo, IA en operaciones.
- **Fase 4 — Innovación**: gemelos digitales, nuevos modelos de negocio, IA generativa, ecosistema de innovación abierta.

---

## 13. Conclusiones

- La **transformación digital** es un **proceso integral** que redefine la operación y la gestión empresarial, no un proyecto tecnológico aislado.
- Su verdadero impacto está en la **transformación cultural y estratégica** que se produce gracias a la **convergencia IT-OT**: cuando la información fluye libremente entre planta y negocio.
- La **digitalización en planta** mejora la producción: más eficiencia (OEE), mejor calidad, menos paradas, mantenimiento predictivo.
- La **digitalización en negocio** mejora la gestión empresarial: mejor relación con clientes, decisiones basadas en datos, procesos más ágiles.
- La **transformación digital integral** permite obtener **agilidad, reducción de costes, seguridad y cumplimiento normativo** de forma simultánea.
- Se trata, en definitiva, de un **cambio estructural clave para la competitividad** en un entorno cada vez más impulsado por la tecnología.

> **Idea clave del bloque**: digitalizar no es instalar tecnología, es **repensar la empresa** poniendo el dato, la persona y el cliente en el centro.

---

## Glosario rápido

| Término | Significado |
|---|---|
| **IT** | Information Technology — tecnologías de la información. |
| **OT** | Operational Technology — tecnologías de operación/planta. |
| **ERP** | Enterprise Resource Planning — sistema integral de gestión empresarial. |
| **MES** | Manufacturing Execution System — sistema de ejecución de fabricación. |
| **SCADA** | Supervisory Control and Data Acquisition — supervisión y adquisición de datos. |
| **PLC** | Programmable Logic Controller — controlador lógico programable. |
| **HMI** | Human-Machine Interface — interfaz hombre-máquina. |
| **IIoT** | Industrial Internet of Things — Internet de las Cosas industrial. |
| **OEE** | Overall Equipment Effectiveness — eficiencia global del equipo. |
| **RPA** | Robotic Process Automation — automatización robótica de procesos. |
| **CPS** | Cyber-Physical System — sistema ciberfísico. |
| **MQTT** | Message Queuing Telemetry Transport — protocolo ligero de mensajería IoT. |
| **OPC UA** | Open Platform Communications Unified Architecture — estándar de comunicación industrial. |
| **DAFO** | Debilidades, Amenazas, Fortalezas, Oportunidades (análisis estratégico). |
| **PDCA** | Plan–Do–Check–Act — ciclo de mejora continua. |
| **BI** | Business Intelligence — inteligencia de negocio. |
| **CRM** | Customer Relationship Management — gestión de la relación con clientes. |
| **ISA-95** | Modelo de referencia para la integración entre empresa y sistemas de control. |