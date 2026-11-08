# UNIDAD DIDÁCTICA 6: CIBERSEGURIDAD

## ÍNDICE
1. La información como un activo
2. La privacidad de la información
3. Clasificación de la información
4. Cifrado de la información
5. Copia de seguridad
6. Borrado seguro de la información
7. Principales amenazas: Phishing
8. Prevención del phishing
9. Principales amenazas: Malware
10. Contraseñas seguras
11. Autenticación multifactor
12. Protección del puesto de trabajo
13. Conclusiones

---

## 1. LA INFORMACIÓN COMO UN ACTIVO

### 1.1. Introducción

En la era digital, la información se ha convertido en uno de los activos más valiosos para cualquier organización. Al igual que el dinero, los edificios o los equipos, la información debe ser gestionada, protegida y valorada como lo que es: un recurso estratégico fundamental.

### 1.2. Concepto de activo de información

Un **activo de información** es cualquier recurso que tenga valor para una organización y que contenga, procese o transmita información. Los activos de información son esenciales para el funcionamiento de las operaciones del negocio y para mantener la ventaja competitiva.

**Características de un activo de información:**
- Tiene valor para la organización
- Puede ser tangible o intangible
- Requiere protección y gestión
- Su pérdida o compromiso puede tener consecuencias significativas
- Debe ser inventariado y clasificado

### 1.3. Tipos de activos

#### **ACTIVOS TANGIBLES**

Los activos tangibles son aquellos que tienen una existencia física y se pueden tocar, ver y medir. En el contexto de la información, son los dispositivos y tecnologías que almacenan y procesan datos.

**Ejemplos de activos tangibles:**

**Hardware:**
- **Servidores**: Equipos que almacenan y procesan grandes cantidades de datos
- **Ordenadores personales**: PCs de escritorio y portátiles de empleados
- **Dispositivos móviles**: Smartphones, tablets, laptops
- **Dispositivos de red**: Routers, switches, firewalls
- **Dispositivos de almacenamiento**: Discos duros externos, NAS, SANs
- **Medios de almacenamiento**: USBs, CDs, DVDs, cintas magnéticas
- **Dispositivos IoT**: Cámaras de seguridad, sensores, termostatos inteligentes

**Documentación física:**
- Contratos impresos
- Expedientes de empleados
- Documentos financieros en papel
- Planos y diseños físicos
- Notas y borradores manuscritos

**Infraestructura:**
- Centros de datos (data centers)
- Salas de servidores
- Cableado de red
- Sistemas de alimentación ininterrumpida (UPS)

**Riesgos asociados a activos tangibles:**
- Robo físico
- Daño por desastres naturales (incendios, inundaciones)
- Fallos de hardware
- Obsolescencia tecnológica
- Acceso no autorizado físico

#### **ACTIVOS INTANGIBLES**

Los activos intangibles son aquellos que no tienen una existencia física pero que tienen un valor significativo para la organización. Son elementos no físicos como el conocimiento, la reputación y la propiedad intelectual.

**Ejemplos de activos intangibles:**

**Conocimiento:**
- Know-how técnico y empresarial
- Experiencia acumulada de empleados
- Metodologías y procesos propietarios
- Patentes y propiedad intelectual
- Fórmulas y recetas secretas
- Algoritmos y código fuente

**Reputación y marca:**
- Imagen de marca
- Reputación corporativa
- Relaciones con clientes
- Confianza del mercado
- Valor de marca

**Información digital:**
- Bases de datos de clientes
- Información financiera
- Planes estratégicos
- Estrategias de marketing
- Listas de precios y costos
- Contratos digitales
- Correos electrónicos corporativos
- Credenciales de acceso
- Certificados digitales

**Relaciones:**
- Redes de contactos
- Relaciones con proveedores
- Acuerdos de confidencialidad
- Alianzas estratégicas

**Riesgos asociados a activos intangibles:**
- Fuga de información
- Pérdida de empleados clave
- Daño reputacional
- Robo de propiedad intelectual
- Espionaje corporativo
- Violación de datos

### 1.4. La Tríada CID (CIA en inglés)

La seguridad de la información se basa en tres principios fundamentales conocidos como la Tríada CID (Confidencialidad, Integridad y Disponibilidad):

#### **CONFIDENCIALIDAD**
- Garantizar que la información solo es accesible para quienes están autorizados
- Prevenir la divulgación no autorizada de información
- Implementar controles de acceso
- Cifrar información sensible
- Ejemplo: Solo el departamento de RRHH puede acceder a los expedientes de empleados

#### **INTEGRIDAD**
- Mantener la exactitud y completitud de la información
- Prevenir modificaciones no autorizadas
- Detectar alteraciones accidentales o maliciosas
- Implementar controles de versión y auditoría
- Ejemplo: Un registro financiero no debe ser modificado sin autorización y seguimiento

#### **DISPONIBILIDAD**
- Garantizar que la información y los sistemas están accesibles cuando se necesitan
- Prevenir interrupciones del servicio
- Implementar redundancia y backups
- Planes de recuperación ante desastres
- Ejemplo: Un sistema de ventas debe estar operativo 24/7

**Relación entre los tres principios:**
- Los tres son igualmente importantes
- Deben equilibrarse según las necesidades del negocio
- Un fallo en cualquiera de ellos compromete la seguridad
- La protección de activos tangibles e intangibles depende de estos principios

### 1.5. Valoración de activos de información

**¿Por qué es importante valorar los activos?**
- Permite priorizar la protección
- Ayuda a asignar recursos de seguridad
- Facilita la toma de decisiones
- Es requisito para cumplir con normativas
- Permite calcular el impacto de una brecha

**Métodos de valoración:**
- **Costo de reemplazo**: ¿Cuánto costaría recrear el activo?
- **Valor de mercado**: ¿Cuánto vale en el mercado?
- **Impacto en el negocio**: ¿Qué pasa si se pierde o compromete?
- **Costo de oportunidad**: ¿Qué ingresos genera?
- **Valor estratégico**: ¿Qué ventaja competitiva proporciona?

### 1.6. Gestión de activos de información

**Inventario de activos:**
- Mantener un registro actualizado de todos los activos
- Clasificar por tipo, valor y criticidad
- Asignar responsables para cada activo
- Actualizar regularmente el inventario

**Ciclo de vida del activo:**
1. **Adquisición**: Compra o creación del activo
2. **Registro**: Inclusión en el inventario
3. **Clasificación**: Determinar nivel de seguridad
4. **Protección**: Implementar controles apropiados
5. **Monitoreo**: Seguimiento continuo
6. **Actualización**: Mantener al día
7. **Disposición**: Eliminar o retirar de forma segura

---

## 2. LA PRIVACIDAD DE LA INFORMACIÓN

### 2.1. Introducción a la privacidad

La privacidad de la información se refiere al derecho de las personas a controlar cómo se recopilan, usan, comparten y almacenan sus datos personales. En un mundo cada vez más digitalizado, la protección de la privacidad se ha convertido en una preocupación fundamental tanto para individuos como para organizaciones.

### 2.2. Marco regulatorio europeo y español

#### **RGPD (Reglamento General de Protección de Datos)**

El **Reglamento (UE) 2016/679**, conocido como RGPD o GDPR (por sus siglas en inglés), es el reglamento europeo que establece las normas relativas a la protección de datos personales. Entró en vigor el 25 de mayo de 2018 y es de aplicación directa en todos los Estados miembros de la Unión Europea.

**Objetivos del RGPD:**
- Proteger los derechos fundamentales de las personas en relación con sus datos personales
- Armonizar las legislaciones de protección de datos en la UE
- Adaptar la protección de datos a la era digital
- Fortalecer los derechos de los ciudadanos

**Ámbito de aplicación:**
- Se aplica a todas las organizaciones que procesan datos personales de ciudadanos de la UE
- No importa dónde esté ubicada la organización (dentro o fuera de la UE)
- Incluye tanto responsables del tratamiento como encargados del tratamiento
- Aplica a empresas de todos los tamaños

**Principios fundamentales del RGPD:**

1. **Licitud, lealtad y transparencia**
   - Los datos deben ser tratados de forma lícita, leal y transparente
   - Informar claramente a las personas sobre el tratamiento de sus datos

2. **Limitación de la finalidad**
   - Los datos deben ser recogidos con fines determinados, explícitos y legítimos
   - No pueden ser tratados posteriormente de manera incompatible con esos fines

3. **Minimización de datos**
   - Solo se deben recoger los datos que sean adecuados, pertinentes y limitados a lo necesario
   - No recoger datos "por si acaso"

4. **Exactitud**
   - Los datos deben ser exactos y, si es necesario, actualizados
   - Rectificar o suprimir datos inexactos sin dilación

5. **Limitación del plazo de conservación**
   - Los datos deben mantenerse durante no más tiempo del necesario
   - Establecer plazos de conservación claros

6. **Integridad y confidencialidad**
   - Garantizar la seguridad de los datos mediante medidas técnicas y organizativas
   - Protección contra tratamiento no autorizado o ilícito, pérdida, destrucción o daño

7. **Responsabilidad proactiva**
   - El responsable del tratamiento debe ser capaz de demostrar el cumplimiento
   - Implementar medidas para garantizar y demostrar el cumplimiento

**Bases legales para el tratamiento de datos:**

Para tratar datos personales, debe existir una base legal válida:

1. **Consentimiento del interesado**
   - Consentimiento libre, específico, informado e inequívoco
   - Debe ser una declaración o una clara acción afirmativa
   - El consentimiento debe poder retirarse fácilmente

2. **Ejecución de un contrato**
   - Cuando el tratamiento es necesario para la ejecución de un contrato
   - Ejemplo: Datos necesarios para entregar un producto comprado

3. **Cumplimiento de una obligación legal**
   - Cuando el tratamiento es necesario para cumplir con una obligación legal
   - Ejemplo: Conservación de facturas para Hacienda

4. **Protección de intereses vitales**
   - Cuando es necesario para proteger la vida de una persona
   - Ejemplo: Datos médicos en una emergencia

5. **Interés público o ejercicio de poderes públicos**
   - Para tareas de interés público o ejercicio de poderes públicos
   - Ejemplo: Actividades de las administraciones públicas

6. **Interés legítimo del responsable**
   - Cuando existe un interés legítimo que justifique el tratamiento
   - Debe equilibrarse con los derechos del interesado
   - No aplica a administraciones públicas en ejercicio de sus funciones

**Derechos de los interesados (Derechos ARCO+):**

El RGPD reconoce una serie de derechos a las personas cuyos datos son tratados:

1. **Derecho de acceso**
   - Obtener confirmación de si se están tratando sus datos
   - Acceder a sus datos personales
   - Conocer la finalidad del tratamiento

2. **Derecho de rectificación**
   - Obtener la corrección de datos inexactos
   - Completar datos incompletos

3. **Derecho de supresión ("derecho al olvido")**
   - Obtener la eliminación de sus datos cuando:
     - Ya no sean necesarios para la finalidad recogida
     - Retire el consentimiento
     - Se opongan al tratamiento
     - Se hayan tratado ilícitamente

4. **Derecho a la limitación del tratamiento**
   - Solicitar que se restrinja el tratamiento de sus datos en ciertos casos
   - Los datos se conservan pero no se tratan

5. **Derecho a la portabilidad**
   - Recibir sus datos en un formato estructurado, de uso común y lectura mecánica
   - Transmitir esos datos a otro responsable

6. **Derecho de oposición**
   - Oponerse al tratamiento de sus datos
   - Oponerse específicamente a la toma de decisiones automatizada
   - Oponerse al tratamiento para marketing directo

7. **Derecho a no ser objeto de decisiones automatizadas**
   - No ser objeto de decisiones basadas únicamente en el tratamiento automatizado
   - Incluida la elaboración de perfiles que produzca efectos jurídicos

**Obligaciones de las organizaciones:**

1. **Registro de actividades de tratamiento**
   - Documentar todas las actividades de tratamiento de datos
   - Mantener un registro actualizado

2. **Evaluación de Impacto (EIPD/DPIA)**
   - Realizar evaluaciones de impacto cuando el tratamiento pueda entrañar un alto riesgo
   - Especialmente para nuevas tecnologías o tratamientos de alto riesgo

3. **Notificación de brechas de seguridad**
   - Notificar a la autoridad de control en 72 horas
   - Notificar a los afectados si la brecha entraña un alto riesgo

4. **Designación de DPD/DPO**
   - Designar un Delegado de Protección de Datos en ciertos casos
   - El DPD supervisa el cumplimiento del RGPD

5. **Responsabilidad proactiva**
   - Implementar medidas técnicas y organizativas apropiadas
   - Ser capaz de demostrar el cumplimiento

6. **Privacidad desde el diseño y por defecto**
   - Integrar la protección de datos desde el diseño de sistemas y procesos
   - Configuraciones por defecto que respeten la privacidad

**Sanciones:**

El RGPD establece un régimen de sanciones severo:

- **Infracciones leves**: Multas de hasta 10 millones de euros o 2% del volumen de negocio anual global
- **Infracciones graves**: Multas de hasta 20 millones de euros o 4% del volumen de negocio anual global (la cantidad que sea mayor)

#### **LOPDGDD (Ley Orgánica de Protección de Datos y Garantía de Derechos Digitales)**

La **Ley Orgánica 3/2018**, conocida como LOPDGDD, es la ley española que adapta el ordenamiento jurídico español al RGPD y añade disposiciones específicas para España.

**Características de la LOPDGDD:**
- Complementa el RGPD en el ámbito español
- Establece normas específicas para ciertos sectores
- Añade garantías adicionales para los derechos digitales
- Regula aspectos que el RGPD deja a discreción de los Estados miembros

**Aspectos destacados de la LOPDGDD:**

1. **Edad para el consentimiento**
   - En España, la edad mínima para dar consentimiento es 14 años
   - Para menores de 14 años, se requiere el consentimiento de los padres o tutores

2. **Tratamiento de datos por razones laborales**
   - Regula el uso de datos personales en el ámbito laboral
   - Establece límites al control empresarial
   - Protege la privacidad de los empleados

3. **Derechos digitales**
   - Reconoce nuevos derechos en el entorno digital
   - Derecho a la seguridad digital
   - Derecho a la educación digital
   - Derecho al olvido en internet

4. **Sector específico**
   - Normas específicas para tratamientos sanitarios
   - Regulación de datos financieros
   - Tratamiento de datos por administraciones públicas
   - Normas para partidos políticos y elecciones

5. **Autoridad de control**
   - La AEPD (Agencia Española de Protección de Datos) es la autoridad competente
   - Tiene potestad sancionadora
   - Supervisa el cumplimiento del RGPD y LOPDGDD

### 2.3. Principios clave de la privacidad

#### **Consentimiento Explícito**
- Debe ser una manifestación de voluntad libre, específica, informada e inequívoca
- No se acepta el consentimiento por silencio o inacción
- Debe ser tan fácil retirar el consentimiento como darlo
- Debe documentarse el consentimiento obtenido
- El consentimiento debe ser específico para cada finalidad

#### **Derechos del Interesado**
- Las organizaciones deben facilitar el ejercicio de estos derechos
- Respuesta en un plazo máximo de un mes (ampliable a tres en casos complejos)
- La respuesta debe ser gratuita (salvo solicitudes manifiestamente infundadas o excesivas)
- Los derechos deben ejercerse de forma clara y accesible

#### **Notificación de Brechas**
- Obligación de notificar brechas de seguridad a la autoridad de control
- Plazo de 72 horas desde que se tuvo conocimiento de la brecha
- Si la brecha supone un alto riesgo, también deben notificarse a los afectados
- Documentar todas las brechas, incluso las que no requieren notificación

#### **Protección desde el Diseño (Privacy by Design)**
- Integrar la protección de datos desde la concepción de sistemas y procesos
- Considerar la privacidad en cada etapa del desarrollo
- Minimizar la recopilación de datos
- Implementar medidas de privacidad por defecto

#### **Delegado de Protección de Datos (DPO/DPD)**
- Figura responsable de supervisar el cumplimiento del RGPD
- Obligatorio en ciertos casos:
  - Administraciones públicas
  - Tratamientos a gran escala de datos sensibles
  - Monitoreo sistemático de personas
- Funciones:
  - Informar y asesorar
  - Supervisar el cumplimiento
  - Actuar como punto de contacto con la autoridad de control

### 2.4. Adaptaciones nacionales

Cada país de la UE puede establecer normas específicas en ciertos ámbitos:

**España:**
- LOPDGDD como ley de adaptación
- AEPD como autoridad de control
- Edad de consentimiento: 14 años
- Regulación específica para ámbitos como:
  - Laboral
  - Sanitario
  - Educativo
  - Administraciones públicas

**Otros ejemplos:**
- Alemania: BDSG (Bundesdatenschutzgesetz)
- Francia: Loi Informatique et Libertés
- Italia: Codice Privacy
- Reino Unido: Data Protection Act 2018 (post-Brexit)

### 2.5. Cumplimiento normativo

**Pasos para el cumplimiento:**

1. **Análisis inicial**
   - Identificar qué datos personales se tratan
   - Determinar las bases legales
   - Mapear flujos de datos

2. **Registro de actividades**
   - Documentar todas las actividades de tratamiento
   - Incluir finalidades, plazos, medidas de seguridad

3. **Evaluación de riesgos**
   - Identificar riesgos para los derechos y libertades
   - Realizar EIPD cuando sea necesario

4. **Implementación de medidas**
   - Medidas técnicas (cifrado, control de acceso)
   - Medidas organizativas (políticas, procedimientos)

5. **Gestión de derechos**
   - Establecer procedimientos para ejercer derechos
   - Formar al personal

6. **Gestión de proveedores**
   - Revisar contratos con encargados del tratamiento
   - Garantizar que cumplen con el RGPD

7. **Formación y concienciación**
   - Formar a empleados en protección de datos
   - Cultura de privacidad en la organización

8. **Monitoreo y mejora continua**
   - Auditorías periódicas
   - Revisión y actualización de medidas

---

## 3. CLASIFICACIÓN DE LA INFORMACIÓN

### 3.1. Importancia de la clasificación

La clasificación de la información es un proceso fundamental para:
- Proteger adecuadamente los datos según su sensibilidad
- Optimizar los recursos de seguridad
- Cumplir con obligaciones legales y contractuales
- Facilitar la gestión de la información
- Prevenir accesos no autorizados

### 3.2. Proceso de clasificación de la información

La clasificación de la información sigue un proceso estructurado de seis pasos:

#### **PASO 1: Identificar Información**
**Objetivo**: Reconocer todos los activos de información dentro de la organización

**Actividades:**
- Realizar un inventario completo de activos de información
- Identificar dónde se almacenan los datos
- Determinar quién es el propietario de cada activo
- Documentar flujos de información
- Considerar tanto información digital como física

**Preguntas clave:**
- ¿Qué información tenemos?
- ¿Dónde está almacenada?
- ¿Quién la usa?
- ¿Cómo fluye dentro y fuera de la organización?

#### **PASO 2: Definir Criterios**
**Objetivo**: Establecer criterios para evaluar la información basada en sensibilidad y valor

**Criterios comunes:**
- **Sensibilidad**: ¿Qué daño causaría si se divulga?
- **Valor**: ¿Qué valor tiene para la organización?
- **Importancia crítica**: ¿Qué tan esencial es para las operaciones?
- **Requisitos legales**: ¿Existen obligaciones regulatorias?
- **Confidencialidad contractual**: ¿Hay acuerdos de confidencialidad?

**Factores a considerar:**
- Impacto en la reputación
- Impacto financiero
- Impacto operativo
- Impacto legal y regulatorio
- Impacto en la privacidad de las personas

#### **PASO 3: Categorizar Información**
**Objetivo**: Clasificar la información en niveles según su sensibilidad

**Niveles típicos de clasificación:**

1. **Pública**
   - Información que puede ser divulgada libremente
   - No requiere protección especial
   - Ejemplos: Material de marketing, información pública del sitio web, comunicados de prensa

2. **Interna**
   - Información para uso interno de la organización
   - Su divulgación causaría daño menor
   - Ejemplos: Políticas internas, procedimientos operativos, directorios de empleados

3. **Confidencial**
   - Información sensible que requiere protección
   - Su divulgación causaría daño significativo
   - Ejemplos: Datos financieros, planes estratégicos, información de clientes, contratos

4. **Secreta/Restringida**
   - Información altamente sensible
   - Su divulgación causaría daño grave
   - Ejemplos: Secretos comerciales, datos de tarjetas de crédito, información médica, credenciales de acceso

**Ejemplo de matriz de clasificación:**

| Nivel | Ejemplos | Acceso | Protección |
|-------|----------|--------|------------|
| Pública | Marketing, web | Cualquiera | Mínima |
| Interna | Políticas, procedimientos | Empleados | Básica |
| Confidencial | Finanzas, clientes | Autorizados | Media |
| Secreta | Secretos comerciales, credenciales | Muy restringido | Alta |

#### **PASO 4: Implementar Protección**
**Objetivo**: Aplicar medidas de seguridad apropiadas para cada categoría de información

**Medidas según nivel:**

**Pública:**
- Sin restricciones de acceso
- Protección básica contra modificación no autorizada

**Interna:**
- Acceso para empleados autorizados
- No compartir externamente sin autorización
- Etiquetado como "Uso Interno"

**Confidencial:**
- Acceso basado en necesidad de conocer
- Cifrado en tránsito y en reposo
- Registro de accesos
- Acuerdos de confidencialidad
- Etiquetado como "Confidencial"

**Secreta:**
- Acceso estrictamente limitado y controlado
- Cifrado fuerte
- Autenticación multifactor
- Monitoreo continuo
- Etiquetado como "Secreto" o "Restringido"

#### **PASO 5: Capacitar al Personal**
**Objetivo**: Educar a los empleados sobre la importancia de la clasificación de la información

**Actividades:**
- Formación inicial sobre clasificación
- Guías y procedimientos claros
- Ejemplos prácticos
- Actualizaciones periódicas
- Concienciación sobre riesgos

**Contenido de la formación:**
- Qué es la clasificación de la información
- Niveles de clasificación y sus significados
- Cómo manejar cada nivel
- Consecuencias del mal manejo
- Responsabilidades individuales
- A quién consultar ante dudas

#### **PASO 6: Revisar y Actualizar**
**Objetivo**: Revisar y actualizar regularmente los procesos de clasificación

**Actividades:**
- Auditorías periódicas de clasificación
- Revisión de cambios en requisitos legales
- Actualización de políticas
- Reclasificación cuando sea necesario
- Mejora continua del proceso

**Frecuencia recomendada:**
- Revisión anual de políticas de clasificación
- Revisión semestral de activos críticos
- Revisión continua de accesos
- Actualización inmediata ante cambios regulatorios

### 3.3. Etiquetado de la información

**Importancia del etiquetado:**
- Identifica visualmente el nivel de clasificación
- Recuerda a los usuarios cómo manejar la información
- Facilita la identificación de información sensible
- Ayuda a prevenir divulgaciones accidentales

**Tipos de etiquetas:**
- **Etiquetas visuales**: Marcas en documentos (encabezados, pies de página)
- **Metadatos**: Información de clasificación en archivos digitales
- **Marcas de agua**: Para documentos confidenciales
- **Etiquetas físicas**: En documentos impresos y medios de almacenamiento

**Ejemplos de etiquetas:**
- "PÚBLICO"
- "USO INTERNO"
- "CONFIDENCIAL"
- "SECRETO"
- "NO DISTRIBUIR"
- "BORRAR DESPUÉS DE USAR"

### 3.4. Herramientas y tecnologías

**Soluciones de clasificación:**
- Microsoft Information Protection (MIP)
- Symantec Data Loss Prevention (DLP)
- McAfee Total Protection for Data Loss Prevention
- Forcepoint Data Loss Prevention
- Digital Guardian

**Funcionalidades comunes:**
- Clasificación automática basada en contenido
- Etiquetado visual
- Aplicación de políticas de protección
- Monitoreo y reporting
- Integración con otras herramientas de seguridad

### 3.5. Mejores prácticas

1. **Comenzar con lo simple**: No sobrecomplicar la clasificación inicialmente
2. **Involucrar a los stakeholders**: Incluir a todas las áreas de la organización
3. **Comunicar claramente**: Asegurar que todos entienden la clasificación
4. **Automatizar cuando sea posible**: Usar herramientas para clasificación automática
5. **Revisar regularmente**: La clasificación no es un ejercicio de una sola vez
6. **Adaptar a la organización**: No hay un modelo único para todas
7. **Considerar el ciclo de vida**: La clasificación puede cambiar con el tiempo

---

## 4. CIFRADO DE LA INFORMACIÓN

### 4.1. Introducción al cifrado

El cifrado (o encriptación) es el proceso de convertir información legible (texto plano) en una forma no legible (texto cifrado) para protegerla de accesos no autorizados. Solo quienes poseen la clave de descifrado pueden convertir el texto cifrado de vuelta a su forma original.

### 4.2. Conceptos fundamentales

**Terminología básica:**
- **Texto plano (plaintext)**: Información original legible
- **Texto cifrado (ciphertext)**: Información cifrada no legible
- **Algoritmo de cifrado**: Conjunto de reglas matemáticas para cifrar y descifrar
- **Clave (key)**: Información secreta utilizada por el algoritmo
- **Cifrado (encryption)**: Proceso de convertir texto plano en texto cifrado
- **Descifrado (decryption)**: Proceso de convertir texto cifrado en texto plano

**Principios del cifrado:**
- **Confidencialidad**: Solo los autorizados pueden leer la información
- **Integridad**: Detectar si la información ha sido modificada
- **Autenticación**: Verificar la identidad de las partes
- **No repudio**: Imposibilidad de negar la autoría de un mensaje

### 4.3. Tipos de cifrado

#### **CIFRADO SIMÉTRICO**

**Características:**
- Utiliza la misma clave para cifrar y descifrar
- Más rápido que el cifrado asimétrico
- Ideal para grandes volúmenes de datos
- Desafío: distribución segura de la clave

**Algoritmos simétricos comunes:**

1. **AES (Advanced Encryption Standard)**
   - Estándar actual más utilizado
   - Claves de 128, 192 o 256 bits
   - Considerado muy seguro
   - Usado por gobiernos y empresas

2. **DES (Data Encryption Standard)**
   - Antiguo estándar, ya no recomendado
   - Clave de 56 bits (demasiado corta)
   - Reemplazado por AES

3. **3DES (Triple DES)**
   - Variante más segura de DES
   - Aplica DES tres veces
   - En proceso de desuso

4. **Blowfish/Twofish**
   - Algoritmos de código abierto
   - Rápidos y eficientes
   - Claves variables

**Ventajas:**
- Alta velocidad de procesamiento
- Eficiente para grandes volúmenes
- Ampliamente soportado

**Desventajas:**
- Distribución segura de claves
- Necesidad de una clave por cada par de comunicantes
- Escalabilidad limitada

#### **CIFRADO ASIMÉTRICO**

**Características:**
- Utiliza un par de claves: pública y privada
- La clave pública cifra, la privada descifra
- Más seguro para intercambio de claves
- Más lento que el simétrico

**Algoritmos asimétricos comunes:**

1. **RSA (Rivest-Shamir-Adleman)**
   - El más utilizado
   - Basado en la factorización de números primos
   - Claves típicas: 2048, 4096 bits
   - Usado en SSL/TLS, firmas digitales

2. **DSA (Digital Signature Algorithm)**
   - Especializado en firmas digitales
   - No para cifrado de datos
   - Estándar gubernamental

3. **ECC (Elliptic Curve Cryptography)**
   - Basado en curvas elípticas
   - Claves más cortas para misma seguridad
   - Eficiente para dispositivos móviles
   - Cada vez más utilizado

4. **ElGamal**
   - Basado en el problema del logaritmo discreto
   - Usado en sistemas de archivo cifrado

**Ventajas:**
- No requiere distribución segura de claves
- Permite firmas digitales
- Mejor escalabilidad
- Ideal para comunicaciones iniciales

**Desventajas:**
- Mucho más lento que el simétrico
- Requiere más recursos computacionales
- No eficiente para grandes volúmenes

#### **CIFRADO HÍBRIDO**

**Características:**
- Combina cifrado simétrico y asimétrico
- Usa asimétrico para intercambiar la clave simétrica
- Usa simétrico para cifrar los datos
- Aprovecha las ventajas de ambos

**Funcionamiento:**
1. Se genera una clave simétrica temporal (clave de sesión)
2. Se cifra la clave simétrica con la clave pública del destinatario
3. Se cifran los datos con la clave simétrica
4. Se envían ambos (datos cifrados y clave simétrica cifrada)
5. El destinatario descifra la clave simétrica con su clave privada
6. Se descifran los datos con la clave simétrica

**Ejemplos de uso:**
- SSL/TLS (HTTPS)
- PGP (Pretty Good Privacy)
- GPG (GNU Privacy Guard)
- S/MIME (correo electrónico seguro)

### 4.4. Aplicaciones del cifrado

**Cifrado en reposo:**
- Protección de datos almacenados
- Discos duros cifrados (BitLocker, FileVault)
- Bases de datos cifradas
- Archivos y carpetas cifradas
- Dispositivos móviles

**Cifrado en tránsito:**
- Protección de datos en comunicación
- HTTPS para navegación web
- VPN para redes privadas virtuales
- Email cifrado (PGP, S/MIME)
- Mensajería segura (Signal, WhatsApp)

**Firmas digitales:**
- Verificación de autenticidad
- Garantía de integridad
- No repudio
- Certificados digitales

**Certificados digitales:**
- Documentos electrónicos que acreditan la identidad
- Emitidos por autoridades de certificación (CA)
- Contienen clave pública e identidad
- Base de la infraestructura de clave pública (PKI)

### 4.5. Gestión de claves

**Importancia de la gestión de claves:**
- Las claves son el punto más crítico del cifrado
- Una clave comprometida = cifrado comprometido
- Necesidad de políticas y procedimientos claros

**Ciclo de vida de las claves:**

1. **Generación**
   - Usar generadores de números aleatorios seguros
   - Longitud adecuada según algoritmo
   - Documentar metadatos

2. **Distribución**
   - Canales seguros para compartir claves
   - Uso de cifrado asimétrico para intercambio inicial
   - Evitar transmisión por canales inseguros

3. **Almacenamiento**
   - Módulos de seguridad de hardware (HSM)
   - Almacenes de claves seguros
   - Cifrado de las propias claves
   - Control de acceso estricto

4. **Rotación**
   - Cambiar claves periódicamente
   - Limitar el daño en caso de compromiso
   - Políticas de rotación claras

5. **Revocación**
   - Procedimientos para claves comprometidas
   - Listas de revocación de certificados (CRL)
   - Protocolo OCSP para verificación en tiempo real

6. **Destrucción**
   - Eliminación segura de claves
   - Garantizar que no se pueden recuperar
   - Documentar la destrucción

**Mejores prácticas:**
- No hardcoded keys en código
- Usar gestión centralizada de claves
- Rotación automática cuando sea posible
- Backup seguro de claves
- Auditoría de uso de claves

### 4.6. Consideraciones legales y éticas

**Regulaciones:**
- Algunos países restringen el uso de cifrado fuerte
- Obligaciones de entrega de claves en investigaciones
- Excepciones para fuerzas de seguridad
- Cumplimiento con normativas sectoriales

**Consideraciones éticas:**
- Balance entre privacidad y seguridad
- Responsabilidad en el diseño de sistemas
- Transparencia en algoritmos
- Protección de derechos fundamentales

### 4.7. Tendencias futuras

**Criptografía post-cuántica:**
- Computadoras cuánticas podrían romper cifrado actual
- Desarrollo de algoritmos resistentes a ataques cuánticos
- NIST trabajando en estándares post-cuánticos
- Preparación para la transición

**Cifrado homomórfico:**
- Permitir computación sobre datos cifrados
- Sin necesidad de descifrar para procesar
- Gran potencial para privacidad en la nube
- Aún en desarrollo, computacionalmente costoso

**Zero-knowledge proofs:**
- Demostrar conocimiento sin revelar la información
- Aplicaciones en autenticación y privacidad
- Criptomonedas y blockchain

---

## 5. COPIA DE SEGURIDAD

### 5.1. Importancia de las copias de seguridad

Las copias de seguridad (backups) son una medida fundamental para:
- Proteger contra pérdida de datos
- Recuperarse ante fallos de hardware
- Restaurar después de ataques (ransomware)
- Cumplir con requisitos legales de conservación
- Garantizar la continuidad del negocio

**Consecuencias de no tener backups:**
- Pérdida permanente de datos críticos
- Interrupción del negocio
- Pérdidas económicas
- Daño reputacional
- Incumplimiento legal

### 5.2. Selección de datos

**¿Qué datos respaldar?**

No todos los datos tienen la misma importancia. La selección debe basarse en:

1. **Criticidad del negocio**
   - Datos esenciales para operaciones
   - Datos financieros y contables
   - Información de clientes
   - Propiedad intelectual

2. **Requisitos legales**
   - Datos que deben conservarse por ley
   - Plazos de conservación regulatorios
   - Requisitos de auditoría

3. **Frecuencia de cambio**
   - Datos que cambian frecuentemente
   - Información transaccional
   - Contenido dinámico

4. **Costo de recuperación**
   - ¿Cuánto costaría recrear los datos?
   - Tiempo necesario para recuperar
   - Impacto en el negocio

**Datos que NO necesitan backup:**
- Sistemas operativos (se pueden reinstalar)
- Aplicaciones (se pueden reinstalar)
- Archivos temporales
- Caché
- Datos que se pueden recrear fácilmente

### 5.3. Tipos de copia de seguridad

#### **COPIA COMPLETA (Full Backup)**
**Características:**
- Copia todos los datos seleccionados
- Independiente de backups anteriores
- Restauración más simple y rápida

**Ventajas:**
- Restauración sencilla (solo necesita el último backup completo)
- Todos los datos en un solo conjunto
- Menos dependiente de backups anteriores

**Desventajas:**
- Consume más espacio
- Tarda más en realizar
- Mayor uso de recursos

**Cuándo usar:**
- Backup inicial
- Periódicamente (semanal o mensual)
- Cuando el espacio no es limitante

#### **COPIA INCREMENTAL**
**Características:**
- Solo copia datos cambiados desde el último backup (completo o incremental)
- Más rápida y usa menos espacio
- Marca los datos como respaldados

**Ventajas:**
- Más rápida que la copia completa
- Menor uso de espacio
- Ideal para backups frecuentes

**Desventajas:**
- Restauración más compleja (necesita todos los incrementales)
- Si un incremental falla, se pierde la cadena
- Más puntos de fallo potenciales

**Cuándo usar:**
- Backups diarios o más frecuentes
- Cuando el tiempo de backup es crítico
- Cuando el espacio es limitado

#### **COPIA DIFERENCIAL**
**Características:**
- Copia datos cambiados desde el último backup COMPLETO
- No marca los datos como respaldados
- Balance entre completa e incremental

**Ventajas:**
- Restauración más simple que incremental (solo necesita último completo + último diferencial)
- Menos espacio que la completa
- Restauración más rápida que incremental

**Desventajas:**
- Más espacio que incremental
- El tamaño crece con el tiempo
- Más lento que incremental

**Cuándo usar:**
- Cuando se quiere balance entre espacio y tiempo de restauración
- Backups diarios con restauración semanal

#### **COPIA CONTINUA (Continuous Data Protection)**
**Características:**
- Copia datos en tiempo real o casi real
- Monitoreo constante de cambios
- Restauración a punto específico en el tiempo
- También conocido como "backup en tiempo real"

**Ventajas:**
- Pérdida mínima de datos (RPO cercano a cero)
- Restauración granular
- Protección continua

**Desventajas:**
- Requiere más recursos
- Más complejo de implementar
- Mayor costo

**Cuándo usar:**
- Sistemas críticos con alta disponibilidad
- Bases de datos transaccionales
- Entornos donde la pérdida de datos es inaceptable

### 5.4. Medios de almacenamiento

#### **DISCO**
**Características:**
- Discos duros internos o externos
- SSDs para mayor velocidad
- NAS (Network Attached Storage)
- SAN (Storage Area Network)

**Ventajas:**
- Acceso rápido
- Restauración rápida
- Reutilizable
- Buen equilibrio costo/rendimiento

**Desventajas:**
- Vida útil limitada
- Susceptible a fallos mecánicos (HDD)
- Costo por GB más alto que cinta

**Casos de uso:**
- Backups frecuentes
- Restauraciones rápidas
- Datos de acceso regular

#### **CINTA**
**Características:**
- Cintas magnéticas (LTO - Linear Tape-Open)
- Tecnología madura y probada
- Almacenamiento de largo plazo

**Ventajas:**
- Muy bajo costo por GB
- Larga vida útil (30+ años)
- Gran capacidad
- Consumo energético cero cuando no está en uso
- Portable

**Desventajas:**
- Acceso lento (secuencial)
- Restauración lenta
- Requiere hardware específico
- No ideal para acceso frecuente

**Casos de uso:**
- Archivado de largo plazo
- Backups históricos
- Cumplimiento regulatorio
- Grandes volúmenes a bajo costo

#### **NUBE**
**Características:**
- Servicios de backup en la nube
- Proveedores como AWS, Azure, Google Cloud
- Soluciones SaaS especializadas
- Almacenamiento remoto gestionado

**Ventajas:**
- Escalabilidad ilimitada
- No requiere infraestructura local
- Accesible desde cualquier lugar
- Gestión simplificada
- Redundancia geográfica

**Desventajas:**
- Costo recurrente
- Dependencia del proveedor
- Velocidad limitada por ancho de banda
- Consideraciones de seguridad y privacidad

**Casos de uso:**
- Backups remotos
- Disaster recovery
- Complemento a backups locales
- PYMEs sin infraestructura

#### **HÍBRIDO**
**Características:**
- Combinación de múltiples medios
- Local + nube
- Disco + cinta
- Múltiples ubicaciones

**Ventajas:**
- Balance óptimo de costos y rendimiento
- Redundancia adicional
- Flexibilidad
- Protección contra múltiples escenarios

**Desventajas:**
- Mayor complejidad
- Requiere gestión de múltiples sistemas
- Costo potencialmente mayor

**Casos de uso:**
- Organizaciones medianas y grandes
- Datos críticos con requisitos estrictos
- Cumplimiento de múltiples normativas

### 5.5. La Regla 3-2-1

**Definición:**
La regla 3-2-1 es una estrategia recomendada para copias de seguridad:

- **3**: Mantener al menos 3 copias de los datos (1 original + 2 backups)
- **2**: Almacenar las copias en al menos 2 medios diferentes
- **1**: Al menos 1 copia en ubicación diferente (offsite)

**Ejemplo de implementación:**
- Original: Servidor de producción
- Backup 1: Disco duro local (NAS)
- Backup 2: Servicio en la nube (diferente ubicación geográfica)

**Variantes modernas:**
- **3-2-1-1-0**: 3 copias, 2 medios, 1 offsite, 1 copia inmutable/air-gapped, 0 errores
- **3-2-1-1**: Incluye una copia offline o inmutable para protección contra ransomware

**Importancia:**
- Protección contra múltiples escenarios de fallo
- Redundancia geográfica
- Diversidad de medios
- Recuperación garantizada

### 5.6. Frecuencia de copia

**Factores para determinar frecuencia:**

1. **RTO (Recovery Time Objective)**
   - Tiempo máximo aceptable de interrupción
   - ¿Cuánto tiempo puede estar el sistema caído?

2. **RPO (Recovery Point Objective)**
   - Cantidad máxima aceptable de pérdida de datos
   - ¿Cuántos datos podemos permitirnos perder?

3. **Tasa de cambio**
   - Frecuencia con la que cambian los datos
   - Datos transaccionales: cambios constantes
   - Datos de archivo: cambios esporádicos

4. **Importancia del negocio**
   - Sistemas críticos: backups más frecuentes
   - Sistemas secundarios: backups menos frecuentes

**Estrategias comunes:**

**Para datos críticos:**
- Backup continuo o cada pocas horas
- Replicación en tiempo real
- RPO cercano a cero

**Para datos importantes:**
- Backup diario incremental
- Backup completo semanal
- RPO de 24 horas

**Para datos normales:**
- Backup semanal
- Backup completo mensual
- RPO de 7 días

**Para datos de archivo:**
- Backup mensual o trimestral
- Archivado a largo plazo
- RPO flexible

### 5.7. Pruebas de restauración

**Importancia:**
- Un backup no probado no es un backup
- Verificar que los datos son recuperables
- Identificar problemas antes de una emergencia
- Cumplir con requisitos de auditoría

**Tipos de pruebas:**

1. **Prueba de restauración completa**
   - Restaurar todo el sistema
   - Verificar funcionalidad completa
   - Medir tiempo de restauración

2. **Prueba de restauración granular**
   - Restaurar archivos individuales
   - Verificar integridad de datos
   - Probar recuperación selectiva

3. **Prueba de restauración en entorno aislado**
   - Restaurar en entorno de pruebas
   - Sin afectar producción
   - Validar procesos

**Frecuencia recomendada:**
- Pruebas trimestrales como mínimo
- Después de cambios significativos
- Antes de migraciones importantes
- Anualmente: simulacro completo de disaster recovery

### 5.8. Automatización y monitorización

**Automatización:**
- Programar backups automáticos
- Eliminar dependencia de intervención manual
- Garantizar consistencia
- Reducir errores humanos

**Monitorización:**
- Verificar éxito de cada backup
- Alertas ante fallos
- Logs detallados
- Reporting periódico
- Validación de integridad

**Herramientas comunes:**
- Veeam Backup & Replication
- Veritas Backup Exec
- Acronis Cyber Protect
- Commvault
- Soluciones nativas de cloud (AWS Backup, Azure Backup)

---

## 6. BORRADO SEGURO DE LA INFORMACIÓN

### 6.1. Introducción

El borrado seguro de la información es el proceso de eliminar datos de forma que no puedan ser recuperados. No basta con eliminar archivos o formatear discos; se necesitan métodos específicos para garantizar que la información no pueda ser accesible por personas no autorizadas.

**¿Por qué es importante?**
- Protección de información sensible
- Cumplimiento de normativas (RGPD - derecho al olvido)
- Prevención de fugas de datos
- Protección de la reputación
- Fin del ciclo de vida de los datos

### 6.2. Diferencia entre eliminar y borrar de forma segura

**Eliminación convencional:**
- Borrado de archivos: Solo elimina la referencia, no los datos
- Formateo rápido: No sobrescribe datos
- Los datos siguen siendo recuperables con software especializado
- Riesgo alto de recuperación no autorizada

**Borrado seguro:**
- Sobrescritura de datos múltiples veces
- Destrucción física del medio
- Cifrado y destrucción de claves
- Garantía de que los datos no son recuperables
- Cumplimiento de estándares internacionales

### 6.3. Métodos de borrado seguro

#### **PROCEDIMIENTOS INTERNOS**

**Políticas y procedimientos:**
- Establecer políticas claras de borrado seguro
- Definir responsabilidades
- Documentar procesos
- Establecer criterios de clasificación
- Crear flujos de trabajo aprobados

**Componentes clave:**
1. **Clasificación de datos**: Determinar qué requiere borrado seguro
2. **Autorización**: Aprobar el borrado antes de ejecutar
3. **Ejecución**: Realizar el borrado según procedimientos
4. **Verificación**: Confirmar que el borrado fue exitoso
5. **Documentación**: Registrar el proceso realizado

**Roles y responsabilidades:**
- Propietario del dato: Autoriza el borrado
- Responsable de TI: Ejecuta el borrado
- Responsable de seguridad: Verifica y audita
- Responsable legal: Asegura cumplimiento normativo

#### **CONCIENCIACIÓN DE EMPLEADOS**

**Formación necesaria:**
- Importancia del borrado seguro
- Riesgos de no hacerlo correctamente
- Procedimientos a seguir
- Herramientas disponibles
- Consecuencias del incumplimiento

**Temas a cubrir:**
- Qué datos requieren borrado seguro
- Cuándo se debe borrar de forma segura
- Cómo usar las herramientas de borrado
- Dónde solicitar autorización
- Cómo documentar el proceso

**Cultura organizacional:**
- Fomentar la responsabilidad individual
- Incluir en programas de onboarding
- Actualizaciones periódicas
- Ejemplos y casos prácticos
- Consecuencias reales de fallos

#### **CIFRADO DE DATOS**

**Enfoque:**
- Cifrar datos desde el inicio
- Cuando se necesite borrar, destruir las claves
- Sin clave, los datos son inaccesibles
- Método eficiente para grandes volúmenes

**Ventajas:**
- Rápido (solo destruir claves)
- Efectivo para grandes volúmenes
- No requiere sobrescritura
- Útil cuando el medio se reutiliza

**Consideraciones:**
- Debe implementarse desde el inicio
- Las claves deben gestionarse adecuadamente
- Usar algoritmos robustos (AES-256)
- Documentar el proceso

**Crypto-shredding:**
- Destrucción de claves criptográficas
- Hace los datos inaccesibles permanentemente
- Especialmente útil en la nube
- Complemento a otros métodos

#### **SOFTWARE ESPECIALIZADO**

**Herramientas de borrado seguro:**

1. **DBAN (Darik's Boot and Nuke)**
   - Gratuito y de código abierto
   - Arranca desde CD/USB
   - Múltiples métodos de sobrescritura
   - Ideal para discos completos

2. **Blancco**
   - Solución comercial profesional
   - Certificados de borrado
   - Cumple estándares internacionales
   - Ampliamente utilizado en empresas

3. **KillDisk**
   - Versión gratuita y comercial
   - Soporta múltiples métodos
   - Interfaz gráfica
   - Compatible con múltiples sistemas

4. **Eraser**
   - Gratuito para Windows
   - Integración con Explorer
   - Múltiples algoritmos
   - Fácil de usar

5. **Shred (Linux/Mac)**
   - Comando nativo en Unix-like
   - Borrado seguro de archivos individuales
   - Múltiples pasadas de sobrescritura
   - Integrado en el sistema

**Métodos de sobrescritura:**

1. **DoD 5220.22-M (3 pasadas)**
   - Estándar del Departamento de Defensa de EE.UU.
   - 3 pasadas con patrones específicos
   - Ampliamente utilizado

2. **Gutmann (35 pasadas)**
   - 35 pasadas con patrones complejos
   - Extremadamente seguro
   - Muy lento
   - Para datos altamente sensibles

3. **DoD 5220.22-M (7 pasadas)**
   - 7 pasadas de sobrescritura
   - Muy seguro
   - Estándar militar

4. **Schneier (7 pasadas)**
   - Algoritmo de Bruce Schneier
   - 7 pasadas con patrones específicos
   - Buen balance seguridad/velocidad

5. **Random (1 pasada)**
   - Una pasada con datos aleatorios
   - Suficiente para discos modernos
   - Rápido
   - Recomendado por muchos expertos

### 6.4. Auditorías periódicas

**Objetivo:**
- Verificar cumplimiento de políticas
- Identificar áreas de mejora
- Detectar posibles fallos
- Documentar para auditorías externas

**Actividades:**
- Revisión de procedimientos
- Verificación de ejecuciones
- Comprobación de certificados
- Análisis de muestras
- Reporting a dirección

**Frecuencia:**
- Auditorías internas: trimestrales o semestrales
- Auditorías externas: anuales
- Revisiones ad-hoc: tras incidentes

### 6.5. Inventario actualizado

**Importancia:**
- Saber qué activos existen
- Facilitar la gestión del borrado
- Cumplimiento normativo
- Trazabilidad completa

**Información a mantener:**
- Descripción del activo
- Propietario/responsable
- Clasificación de datos
- Ubicación física/lógica
- Fecha de adquisición
- Estado del ciclo de vida
- Fecha de borrado previsto
- Historial de borrados

**Herramientas:**
- Sistemas de gestión de activos (ITAM)
- Bases de datos de inventario
- Hojas de cálculo (para organizaciones pequeñas)
- Soluciones integradas con gestión de seguridad

### 6.6. Procedimientos en la nube

**Consideraciones especiales:**
- No se tiene control físico del medio
- Depende del proveedor de servicios
- Necesidad de seguir procedimientos del proveedor
- Verificar certificaciones del proveedor

**Pasos a seguir:**
1. Revisar contrato y políticas del proveedor
2. Identificar todos los datos a borrar
3. Seguir procedimientos del proveedor
4. Verificar el borrado
5. Obtener confirmación/certificado
6. Documentar el proceso

**Proveedores comunes:**
- AWS: EC2 Secure Erase, S3 Delete
- Azure: Disk wipe, Storage delete
- Google Cloud: Disk encryption + deletion

### 6.7. Servicios de destrucción física

**Cuándo usar:**
- Fin de vida del hardware
- Medios dañados
- Máxima seguridad requerida
- Cumplimiento de normativas estrictas

**Tipos de destrucción:**

1. **Desmagnetización (Degaussing)**
   - Campos magnéticos potentes
   - Borra datos magnéticamente
   - Inutiliza el medio
   - Para cintas y discos duros

2. **Trituración**
   - Destrucción física en fragmentos
   - Tamaños específicos según norma
   - Irrecuperable
   - Para cualquier medio

3. **Incineración**
   - Alta temperatura
   - Destrucción total
   - Para medios específicos
   - Requiere instalaciones especiales

4. **Perforación**
   - Agujeros en el medio
   - Daña platos de disco
   - Rápido y efectivo
   - Para discos duros

**Empresas especializadas:**
- Deben estar certificadas
- Proporcionar certificados de destrucción
- Cumplir con normativas
- Ofrecer trazabilidad completa

**Certificaciones a buscar:**
- NAID (National Association for Information Destruction)
- ISO 27001
- DIN 66399
- Certificaciones locales

### 6.8. Normativas y estándares

**Estándares internacionales:**

1. **NIST SP 800-88**
   - Guidelines for Media Sanitization
   - Estándar de referencia
   - Define métodos claros
   - Ampliamente adoptado

2. **ISO 27040**
   - Storage security
   - Incluye gestión de borrado
   - Marco general
   - Complementa ISO 27001

3. **DIN 66399**
   - Estándar alemán
   - Niveles de seguridad
   - Clasificación de medios
   - Métodos de destrucción

4. **DoD 5220.22-M**
   - Estándar militar de EE.UU.
   - Muy estricto
   - Ampliamente referenciado
   - Múltiples métodos

**RGPD y borrado:**
- Derecho al olvido (Artículo 17)
- Obligación de borrar datos personales
- Plazos razonables
- Excepciones limitadas
- Sanciones por incumplimiento

### 6.9. Mejores prácticas

1. **Clasificar datos**: No todos requieren el mismo nivel de borrado
2. **Documentar todo**: Políticas, procedimientos, ejecuciones
3. **Formar al personal**: Concienciación continua
4. **Usar herramientas adecuadas**: Software certificado
5. **Verificar el borrado**: No confiar ciegamente
6. **Obtener certificados**: Para auditorías y cumplimiento
7. **Revisar periódicamente**: Actualizar políticas y procedimientos
8. **Considerar el ciclo completo**: Desde la creación hasta la destrucción

---

## 7. PRINCIPALES AMENAZAS: PHISHING

### 7.1. Introducción al phishing

**Definición:**
El phishing es una técnica de ingeniería social que utiliza la manipulación psicológica para engañar a las víctimas y obtener información sensible (credenciales, datos financieros, etc.) o hacer que realicen acciones que comprometen su seguridad.

**Características:**
- No explota vulnerabilidades técnicas
- Explota la psicología humana (confianza, miedo, urgencia)
- Se adapta constantemente
- Altamente efectivo
- Cada vez más sofisticado

**Estadísticas:**
- Más del 80% de los incidentes de seguridad involucran phishing
- Costo promedio por incidente: miles de euros
- Aumento exponencial en los últimos años
- Principal vector de ataque para ransomware

### 7.2. Tipos de phishing

#### **PHISHING POR CORREO ELECTRÓNICO**
**Características:**
- Método más común y tradicional
- Correos electrónicos que imitan entidades legítimas
- Solicitan información sensible o redirigen a sitios falsos
- Gran volumen de envíos

**Tácticas comunes:**
- Suplantar bancos, servicios online, redes sociales
- Crear sentido de urgencia ("su cuenta será bloqueada")
- Incluir enlaces a sitios falsos
- Solicitar verificación de datos
- Adjuntar archivos maliciosos

**Ejemplos:**
- "Su cuenta ha sido comprometida, verifique sus datos"
- "Ha recibido un pago, confirme sus datos bancarios"
- "Actualice su información de seguridad"
- "Factura pendiente de pago"

**Indicadores de alerta:**
- Remitente sospechoso (dirección similar pero no idéntica)
- Errores ortográficos o gramaticales
- Enlaces que no coinciden con el texto mostrado
- Solicitan información personal o financiera
- Sentido de urgencia o amenaza

#### **SPEAR PHISHING**
**Características:**
- Phishing dirigido a individuos específicos
- Personalizado con información de la víctima
- Investigación previa del objetivo
- Mayor tasa de éxito que el phishing masivo
- Más difícil de detectar

**Tácticas:**
- Investigación en redes sociales
- Uso de información real (nombre, empresa, colegas)
- Personalización del mensaje
- Suplantación de personas conocidas
- Contexto relevante para la víctima

**Objetivos típicos:**
- Ejecutivos y personal con acceso a información sensible
- Empleados de departamentos financieros
- Personal de TI con privilegios administrativos
- Personas con acceso a propiedad intelectual

**Ejemplo:**
"Juan, he visto que asististe a la conferencia de ciberseguridad la semana pasada. Adjunto están las diapositivas que mencionamos. ¿Podrías revisarlas y darme tu feedback? - María (Directora de TI)"

**Diferencias con phishing tradicional:**
| Aspecto | Phishing | Spear Phishing |
|---------|----------|----------------|
| Alcance | Masivo | Dirigido |
| Personalización | Baja | Alta |
| Investigación | Mínima | Extensa |
| Tasa de éxito | Menor | Mayor |
| Detección | Más fácil | Más difícil |

#### **WHALING**
**Características:**
- Dirigido a "ballenas" (ejecutivos de alto nivel)
- CEOs, CFOs, CIOs, otros altos directivos
- Extremadamente sofisticado
- Investigación exhaustiva
- Potencial de grandes pérdidas

**Tácticas:**
- Suplantación de otros ejecutivos o socios
- Solicitudes de transferencias urgentes
- Información confidencial falsa
- Uso de lenguaje ejecutivo
- Contexto empresarial real

**Ejemplo:**
"Soy el CEO. Necesito que realices una transferencia urgente y confidencial para una adquisición. No se lo comentes a nadie. Aquí están los detalles..."

**Consecuencias:**
- Pérdidas financieras significativas
- Compromiso de información estratégica
- Daño reputacional
- Impacto en la confianza de inversores

#### **SMISHING**
**Características:**
- Phishing a través de mensajes SMS
- "SMS phishing" o "smishing"
- Enlaces maliciosos en mensajes de texto
- Aprovecha la confianza en SMS
- Muy efectivo en móviles

**Tácticas:**
- Mensajes de entrega de paquetes
- Alertas bancarias
- Ofertas demasiado buenas para ser verdad
- Solicitan llamar a números premium
- Enlaces a sitios de phishing

**Ejemplos:**
- "Tu paquete ha sido retenido. Confirma la dirección: [enlace]"
- "Alerta: actividad sospechosa en tu cuenta. Verifica: [enlace]"
- "Has ganado un premio. Reclama aquí: [enlace]"

**Por qué es efectivo:**
- Confianza en SMS vs correos
- Dificultad para verificar enlaces en móviles
- Urgencia percibida
- Menos protección técnica

#### **VISHING**
**Características:**
- Phishing por voz (voice phishing)
- Llamadas telefónicas fraudulentas
- Suplantación de entidades legítimas
- Ingenio social por teléfono
- Aumento con IA y deepfakes de voz

**Tácticas:**
- Suplantar bancos, soporte técnico, gobierno
- Solicitar códigos de verificación
- Pedir acceso remoto al ordenador
- Crear pánico o urgencia
- Usar información real para ganar confianza

**Ejemplo:**
"Soy del soporte técnico de su banco. Hemos detectado actividad sospechosa. Necesito que me proporcione el código que le hemos enviado por SMS para verificar su identidad."

**Tecnologías emergentes:**
- VoIP para enmascarar origen
- IA para generar voces realistas
- Spoofing de números de teléfono
- Grabaciones automatizadas

#### **PHISHING EN MOTORES DE BÚSQUEDA**
**Características:**
- Manipulación de resultados de búsqueda
- Sitios falsos aparecen en primeros resultados
- SEO malicioso
- Víctimas buscan servicios legítimos
- Encuentran sitios fraudulentos

**Tácticas:**
- Crear sitios con nombres similares a marcas legítimas
- Optimizar para palabras clave populares
- Comprar anuncios en buscadores
- Crear contenido que parece legítimo
- Redirigir a sitios de phishing

**Ejemplo:**
Buscar "banco XYZ login" y encontrar un sitio falso en primera posición que parece el sitio oficial.

**Prevención:**
- Verificar la URL cuidadosamente
- Usar marcadores para sitios frecuentes
- Buscar el candado HTTPS
- Desconfiar de ofertas demasiado buenas

#### **PHISHING EN REDES SOCIALES**
**Características:**
- Explotación de plataformas sociales
- Perfiles falsos que imitan personas o marcas
- Mensajes directos maliciosos
- Publicaciones con enlaces fraudulentos
- Aprovecha la confianza en contactos

**Tácticas:**
- Perfiles falsos de amigos o colegas
- Mensajes con enlaces maliciosos
- Ofertas de trabajo falsas
- Sorteos y promociones falsas
- Solicitudes de información personal

**Plataformas comunes:**
- LinkedIn (ofertas de trabajo falsas)
- Facebook (perfiles falsos, mensajes)
- Instagram (cuentas falsas, sorteos)
- Twitter/X (cuentas verificadas falsas)
- WhatsApp (mensajes de contactos comprometidos)

**Ejemplos:**
- "Hola, soy tu amigo Juan. Necesito ayuda urgente. ¿Puedes hacerme una transferencia?"
- "¡Felicidades! Has ganado un iPhone. Haz clic aquí para reclamar"
- "Oferta de trabajo exclusiva. Envíame tus datos personales"

#### **ANGLER PHISHING**
**Características:**
- Phishing en servicio al cliente
- Suplantación de soporte técnico
- Respuesta a quejas o consultas públicas
- Ofrecen ayuda pero roban información
- Explotan la búsqueda de soluciones

**Tácticas:**
- Monitorear quejas en redes sociales
- Responder ofreciendo ayuda
- Solicitar información personal para "verificar"
- Redirigir a sitios falsos de soporte
- Solicitar acceso remoto

**Ejemplo:**
Usuario publica queja sobre un servicio. Atacante responde: "Lamentamos el problema. Por favor, envíanos un DM con tus datos de cuenta para verificar y solucionar."

**Prevención:**
- Solo contactar soporte por canales oficiales
- Verificar la identidad del representante
- No compartir información por DM
- Usar números de teléfono oficiales

### 7.3. Ingeniería social en el phishing

**Principios psicológicos explotados:**

1. **Autoridad**
   - Suplantar figuras de autoridad
   - Jefes, policía, bancos, gobierno
   - Las personas tienden a obedecer

2. **Urgencia**
   - Crear sensación de emergencia
   - "Su cuenta será bloqueada en 24 horas"
   - Reduce el pensamiento crítico

3. **Miedo**
   - Amenazar con consecuencias negativas
   - "Actividad sospechosa detectada"
   - La víctima actúa por pánico

4. **Curiosidad**
   - Ofrecer información interesante
   - "Mira estas fotos tuyas"
   - Atrae a hacer clic

5. **Codicia**
   - Promesas de recompensas
   - "Has ganado un premio"
   - Explota el deseo de ganancia

6. **Confianza**
   - Suplantar conocidos o marcas
   - "Es tu amigo, necesita ayuda"
   - Aprovecha relaciones existentes

7. **Reciprocidad**
   - Ofrecer algo primero
   - "Te ayudamos, ahora ayúdanos"
   - Sentimiento de obligación

### 7.4. Identificación de phishing

**Señales de alerta generales:**

**En correos electrónicos:**
- Remitente con dirección sospechosa
- Errores ortográficos o gramaticales
- Saludos genéricos ("Estimado cliente")
- Urgencia o amenazas
- Enlaces que no coinciden con el texto
- Solicitan información sensible
- Adjuntos inesperados

**En sitios web:**
- URL con errores tipográficos
- HTTP en lugar de HTTPS
- Certificados SSL sospechosos
- Diseño de baja calidad
- Formularios que solicitan información excesiva

**En mensajes de texto:**
- Números desconocidos
- Enlaces acortados o sospechosos
- Solicitan información personal
- Ofertas demasiado buenas

**En llamadas telefónicas:**
- Solicitan información sensible
- Piden códigos de verificación
- Presionan para actuar rápidamente
- No pueden verificar su identidad

---

## 8. PREVENCIÓN DEL PHISHING

### 8.1. Estrategias de prevención

La prevención del phishing requiere un enfoque multifacético que combine tecnología, procesos y concienciación humana.

### 8.2. Formación del usuario

**Importancia:**
- El eslabón más débil en la seguridad
- La tecnología no puede detectar todo
- Los atacantes evolucionan constantemente
- La concienciación es la mejor defensa

**Contenido de la formación:**

1. **Conocer las amenazas**
   - Tipos de phishing
   - Tácticas comunes
   - Ejemplos reales
   - Tendencias actuales

2. **Identificar señales de alerta**
   - Remitentes sospechosos
   - Enlaces peligrosos
   - Solicitudes inusuales
   - Tácticas de ingeniería social

3. **Buenas prácticas**
   - Verificar antes de actuar
   - No hacer clic en enlaces sospechosos
   - No compartir información sensible
   - Reportar incidentes

4. **Procedimientos de respuesta**
   - Qué hacer si se es víctima
   - A quién reportar
   - Pasos de mitigación
   - Documentación del incidente

**Frecuencia:**
- Formación inicial obligatoria
- Actualizaciones trimestrales
- Simulacros regulares
- Comunicaciones de alerta

### 8.3. Verificación de la identidad

**Principios:**
- Nunca confiar ciegamente en el remitente
- Verificar por canales alternativos
- Confirmar solicitudes inusuales
- Desconfiar de solicitudes urgentes

**Procedimientos:**

**Para correos electrónicos:**
1. Verificar el remitente completo (no solo el nombre)
2. Contactar al remitente por otro canal (teléfono, presencial)
3. Confirmar la solicitud directamente
4. No responder al correo sospechoso

**Para llamadas telefónicas:**
1. Colgar y llamar al número oficial
2. No proporcionar información durante la llamada inicial
3. Verificar la identidad del llamante
4. No actuar bajo presión

**Para solicitudes de transferencia:**
1. Verificar por múltiples canales
2. Confirmar con el solicitante directamente
3. Seguir procedimientos de aprobación
4. Documentar la verificación

### 8.4. Uso de filtros anti-phishing

**Tecnologías de protección:**

1. **Filtros de correo**
   - Detección de spam y phishing
   - Análisis de URLs y adjuntos
   - Cuarentena de mensajes sospechosos
   - Soluciones: Proofpoint, Mimecast, Barracuda

2. **Protección web**
   - Bloqueo de sitios maliciosos
   - Filtrado de contenido
   - Análisis en tiempo real
   - Soluciones: Cisco Umbrella, Zscaler

3. **Protección de endpoints**
   - Antivirus/antimalware
   - Detección de comportamiento sospechoso
   - Aislamiento de amenazas
   - Soluciones: CrowdStrike, SentinelOne

**Características clave:**
- Actualización constante de signatures
- Análisis heurístico y de comportamiento
- Sandbox para análisis de archivos
- Integración con threat intelligence

### 8.5. Verificación de sitios web

**Cómo verificar la legitimidad:**

1. **URL**
   - Verificar el dominio completo
   - Buscar errores tipográficos (g00gle vs google)
   - Comprobar el protocolo (https://)
   - Verificar que coincida con la entidad esperada

2. **Certificado SSL/TLS**
   - Buscar el candado en la barra de direcciones
   - Hacer clic para ver detalles del certificado
   - Verificar que el nombre coincida con el dominio
   - Comprobar la validez del certificado

3. **Contenido**
   - Calidad del diseño
   - Errores ortográficos
   - Enlaces rotos o sospechosos
   - Formularios que solicitan información excesiva

4. **Reputación**
   - Buscar el sitio en buscadores
   - Verificar reseñas y opiniones
   - Comprobar en listas de sitios seguros
   - Usar herramientas de verificación

**Herramientas útiles:**
- Google Safe Browsing
- VirusTotal
- PhishTank
- Verificación de certificados en línea

### 8.6. Autenticación de Dos Factores (2FA)

**Importancia:**
- Añade una capa adicional de seguridad
- Protege incluso si las credenciales son robadas
- Dificulta enormemente el acceso no autorizado
- Implementación relativamente simple

**Métodos de 2FA:**

1. **SMS**
   - Código enviado por mensaje de texto
   - Fácil de usar
   - Vulnerable a SIM swapping
   - Menos seguro que otras opciones

2. **Aplicaciones de autenticación**
   - Google Authenticator
   - Authy
   - Microsoft Authenticator
   - Generan códigos TOTP (Time-based One-Time Password)
   - Más seguros que SMS

3. **Tokens físicos**
   - YubiKey
   - Google Titan
   - Dispositivos hardware
   - Más seguros
   - Requieren posesión física

4. **Biometría**
   - Huella dactilar
   - Reconocimiento facial
   - Escaneo de iris
   - Cómodo para el usuario
   - Preocupaciones de privacidad

5. **Push notifications**
   - Aprobación mediante notificación push
   - Fácil de usar
   - Requiere dispositivo móvil
   - Bueno balance seguridad/usabilidad

**Implementación:**
- Habilitar 2FA en todas las cuentas importantes
- Preferir aplicaciones sobre SMS
- Usar tokens físicos para cuentas críticas
- Guardar códigos de respaldo de forma segura
- No compartir códigos de verificación

### 8.7. Cultura de seguridad

**Elementos clave:**

1. **Liderazgo**
   - Compromiso de la dirección
   - Asignación de recursos
   - Ejemplo desde arriba
   - Comunicación clara

2. **Comunicación**
   - Canales abiertos
   - Reporte sin miedo a represalias
   - Compartir experiencias
   - Actualizaciones regulares

3. **Responsabilidad compartida**
   - Todos son responsables
   - No solo "problema de TI"
   - Reconocimiento de buenas prácticas
   - Consecuencias por negligencia

4. **Mejora continua**
   - Aprendizaje de incidentes
   - Adaptación a nuevas amenazas
   - Retroalimentación constante
   - Actualización de políticas

### 8.8. Simulacros de phishing

**Objetivos:**
- Evaluar la efectividad de la formación
- Identificar áreas de mejora
- Crear conciencia práctica
- Medir el progreso

**Diseño de simulacros:**

1. **Variedad de escenarios**
   - Diferentes tipos de phishing
   - Diferentes niveles de sofisticación
   - Contextos relevantes para la organización
   - Actualización con tendencias actuales

2. **Frecuencia**
   - Mensual o trimestral
   - Anuncios previos o sorpresa
   - Combinación de ambos
   - Progresión en dificultad

3. **Métricas**
   - Tasa de clics
   - Tasa de reporte
   - Tiempo de respuesta
   - Diferencias por departamento
   - Tendencias a lo largo del tiempo

4. **Seguimiento**
   - Formación adicional para quienes fallen
   - Reconocimiento para quienes reporten
   - Análisis de resultados
   - Ajuste de estrategia

**Consideraciones éticas:**
- No castigar, sino educar
- Comunicar que son simulacros
- Respetar la privacidad
- Mantener transparencia

---

## 9. PRINCIPALES AMENAZAS: MALWARE

### 9.1. Introducción al malware

**Definición:**
Malware (software malicioso) es cualquier programa o código creado con la intención de causar daño, explotar vulnerabilidades o realizar acciones no autorizadas en un sistema informático.

**Tipos principales:**
- Virus
- Gusanos
- Troyanos
- Spyware
- Adware
- Ransomware

**Vectores de infección comunes:**
- Correos electrónicos con adjuntos maliciosos
- Descargas de internet
- Dispositivos USB infectados
- Vulnerabilidades de software
- Ingeniería social

### 9.2. Tipos de malware

#### **VIRUS**

**Características:**
- Se adhiere a archivos ejecutables
- Requiere acción del usuario para propagarse
- Se replica al ejecutar el archivo huésped
- Puede dañar o modificar archivos
- Necesita un programa anfitrión

**Funcionamiento:**
1. Infecta un archivo ejecutable
2. Cuando se ejecuta el archivo, el virus se activa
3. Se replica a otros archivos
4. Puede realizar acciones maliciosas
5. Se propaga cuando se comparten archivos infectados

**Tipos de virus:**
- **Virus de archivo**: Infectan ejecutables
- **Virus de boot**: Infectan el sector de arranque
- **Virus de macro**: Infectan documentos de Office
- **Virus polimórficos**: Cambian su código para evadir detección
- **Virus residentes**: Permanecen en memoria

**Síntomas de infección:**
- Rendimiento lento del sistema
- Archivos corruptos o desaparecidos
- Comportamiento inesperado
- Mensajes de error frecuentes
- Actividad de red inusual

**Prevención:**
- Antivirus actualizado
- No ejecutar archivos sospechosos
- Actualizar software
- Backups regulares
- Escanear dispositivos externos

#### **GUSANO (WORM)**

**Características:**
- Se propaga automáticamente por redes
- No necesita archivo huésped
- Explota vulnerabilidades de software
- Muy rápido y eficiente
- Puede causar congestión de red

**Funcionamiento:**
1. Explota una vulnerabilidad en un sistema
2. Se instala y ejecuta
3. Escanea la red en busca de otros sistemas vulnerables
4. Se replica automáticamente
5. Puede realizar acciones maliciosas

**Diferencias con virus:**
| Aspecto | Virus | Gusano |
|---------|-------|--------|
| Propagación | Requiere acción humana | Automática |
| Huésped | Necesita archivo | Independiente |
| Velocidad | Más lento | Muy rápido |
| Red | No se propaga por red | Se propaga por red |

**Ejemplos históricos:**
- Morris Worm (1988): Primer gusano de internet
- SQL Slammer (2003): Infectó 75,000 sistemas en 10 minutos
- Conficker (2008): Infectó millones de sistemas

**Prevención:**
- Mantener software actualizado
- Firewalls configurados correctamente
- Segmentación de red
- Monitoreo de tráfico
- Parches de seguridad

#### **TROYANO**

**Características:**
- Se disfraza de software legítimo
- No se replica por sí mismo
- Crea puertas traseras (backdoors)
- Permite acceso remoto no autorizado
- Engaña al usuario para su instalación

**Funcionamiento:**
1. Se presenta como programa legítimo o útil
2. El usuario lo descarga e instala voluntariamente
3. Una vez ejecutado, realiza acciones maliciosas
4. Puede crear backdoors para acceso remoto
5. Roba información o instala otro malware

**Tipos de troyanos:**
- **Backdoor**: Permite acceso remoto
- **Downloader**: Descarga e instala otro malware
- **Spyware**: Roba información
- **FakeAV**: Falso antivirus que pide pago
- **Rootkit**: Oculta su presencia en el sistema

**Ejemplos comunes:**
- "Cracks" y keygens para software pirata
- Herramientas "gratuitas" con funcionalidad oculta
- Actualizaciones falsas
- Juegos o aplicaciones con malware oculto

**Prevención:**
- Descargar solo de fuentes oficiales
- Leer reseñas y verificar desarrolladores
- Escaner con antivirus antes de ejecutar
- Desconfiar de ofertas demasiado buenas
- No usar software pirata

#### **SPYWARE**

**Características:**
- Rastreadores de datos no autorizados
- Monitorean actividades del usuario
- Recopilan información personal
- Se ejecutan en segundo plano
- Difíciles de detectar

**Tipos de spyware:**

1. **Keyloggers**
   - Registran todas las pulsaciones de teclado
   - Roban contraseñas y datos sensibles
   - Hardware o software
   - Muy peligrosos

2. **Adware**
   - Muestra anuncios intrusivos
   - Rastrea hábitos de navegación
   - Menos malicioso pero molesto
   - A veces incluido en software gratuito

3. **Tracking cookies**
   - Cookies de seguimiento
   - Monitorean actividad web
   - Comparten datos con terceros
   - Preocupación de privacidad

4. **Browser hijackers**
   - Modifican configuración del navegador
   - Redirigen a sitios maliciosos
   - Cambian página de inicio
   - Instalan extensiones no deseadas

**Información que recopilan:**
- Credenciales de acceso
- Datos bancarios
- Historial de navegación
- Correos electrónicos
- Mensajes instantáneos
- Información personal

**Detección:**
- Rendimiento lento del sistema
- Páginas de inicio cambiadas
- Anuncios excesivos
- Comportamiento extraño del navegador
- Herramientas de seguridad que detectan spyware

**Prevención:**
- Antivirus/antimalware actualizado
- Extensiones de navegador de confianza
- Leer acuerdos de licencia
- No instalar software sospechoso
- Escanear regularmente

#### **ADWARE**

**Características:**
- Muestra anuncios intrusivos
- Generalmente no malicioso
- Genera ingresos para el desarrollador
- Puede ralentizar el sistema
- A veces incluido en software legítimo

**Tipos:**
- **Pop-ups**: Ventanas emergentes
- **Banners**: Anuncios en páginas web
- **Ad-supported software**: Software gratuito con anuncios
- **Browser extensions**: Extensiones que muestran anuncios

**Problemas:**
- Experiencia de usuario degradada
- Consumo de recursos
- Posibles redirecciones a sitios maliciosos
- Preocupaciones de privacidad

**Prevención:**
- Leer términos de instalación
- Desmarcar software adicional
- Usar bloqueadores de anuncios
- Eliminar extensiones no necesarias
- Escanear con antimalware

#### **RANSOMWARE**

**Características:**
- Cifra datos para pedir rescate
- Extorsión financiera
- Muy dañino y disruptivo
- Aumento exponencial en ataques
- Objetivo principal: dinero

**Funcionamiento:**
1. Infecta el sistema (phishing, exploits, RDP)
2. Cifra archivos del usuario
3. Muestra mensaje de rescate
4. Solicita pago (generalmente criptomonedas)
5. Promete descifrar tras el pago (no siempre cumplen)

**Tipos:**
- **Crypto ransomware**: Cifra archivos
- **Locker ransomware**: Bloquea el sistema
- **Scareware**: Falso software que pide pago
- **Doxware/Leakware**: Amenaza con publicar datos
- **RaaS (Ransomware as a Service)**: Modelo de negocio criminal

**Ejemplos famosos:**
- WannaCry (2017): Afectó a 200,000+ sistemas en 150 países
- NotPetya (2017): Daños por $10 mil millones
- Ryuk: Dirigido a organizaciones grandes
- Colonial Pipeline (2021): Paralizó oleoducto en EE.UU.

**¿Pagar o no pagar?**
- **No pagar** (recomendado por autoridades):
  - No garantiza recuperación de datos
  - Financia actividades criminales
  - Fomenta más ataques
  - Puede haber alternativas de recuperación

- **Pagar** (último recurso):
  - Solo si los datos son críticos
  - Si no hay backups
  - Si el costo de no tener datos es mayor
  - Consultar con autoridades primero

**Prevención:**
- Backups regulares y probados (regla 3-2-1)
- Actualización de software
- Formación de usuarios
- Segmentación de red
- Privilegios mínimos
- Plan de respuesta a incidentes

**Respuesta ante ataque:**
1. Aislar sistemas infectados
2. Identificar la variante de ransomware
3. Buscar herramientas de descifrado gratuitas
4. Restaurar desde backups limpios
5. Reportar a autoridades
6. Analizar cómo ocurrió el ataque
7. Implementar medidas para prevenir recurrencia

### 9.3. Vectores de infección

**Canales comunes:**

1. **Correo electrónico**
   - Adjuntos maliciosos
   - Enlaces a sitios de descarga
   - Phishing con malware

2. **Descargas de internet**
   - Software pirata
   - Sitios web comprometidos
   - Descargas drive-by

3. **Dispositivos removibles**
   - USB infectados
   - Discos externos
   - Teléfonos móviles

4. **Vulnerabilidades**
   - Software sin parchear
   - Configuraciones inseguras
   - Servicios expuestos

5. **Redes**
   - Tráfico malicioso
   - Ataques MITM (Man-in-the-Middle)
   - Propagación lateral

### 9.4. Prevención del malware

**Estrategias de defensa:**

1. **Software de seguridad**
   - Antivirus/antimalware actualizado
   - Firewall configurado
   - IDS/IPS (sistemas de detección/prevención de intrusiones)
   - EDR (Endpoint Detection and Response)

2. **Actualizaciones**
   - Mantener SO actualizado
   - Parches de seguridad
   - Actualizar aplicaciones
   - Firmware de dispositivos

3. **Buenas prácticas**
   - No abrir correos sospechosos
   - Descargar solo de fuentes oficiales
   - Escanear archivos antes de abrir
   - Usar contraseñas fuertes
   - Habilitar 2FA

4. **Backups**
   - Copias de seguridad regulares
   - Almacenamiento offline
   - Pruebas de restauración
   - Regla 3-2-1

5. **Segmentación**
   - Separar redes
   - Limitar propagación
   - Zonas de cuarentena
   - Control de acceso

6. **Monitorización**
   - Logs del sistema
   - Detección de anomalías
   - Alertas de seguridad
   - Análisis de comportamiento

---

## 10. CONTRASEÑAS SEGURAS

### 10.1. Importancia de las contraseñas

Las contraseñas son la primera línea de defensa para proteger cuentas y sistemas. Una contraseña débil es como dejar la puerta de casa abierta.

**Estadísticas alarmantes:**
- Contraseñas débiles causan el 80% de brechas de datos
- La contraseña más común es "123456"
- El 65% de las personas reutilizan contraseñas
- Los atacantes pueden descifrar contraseñas simples en segundos

### 10.2. Características de una contraseña segura

**Principios fundamentales:**

1. **Longitud**
   - Mínimo 12 caracteres
   - Idealmente 16+ caracteres
   - Cada carácter adicional aumenta exponencialmente la seguridad
   - La longitud es más importante que la complejidad

2. **Complejidad**
   - Mayúsculas (A-Z)
   - Minúsculas (a-z)
   - Números (0-9)
   - Símbolos (!@#$%^&*)
   - Combinación de todos los tipos

3. **Impredecibilidad**
   - No usar información personal
   - No usar palabras del diccionario
   - No usar patrones comunes
   - Evitar secuencias (1234, abcd)

4. **Unicidad**
   - Cada cuenta con contraseña diferente
   - No reutilizar contraseñas
   - Si una cuenta se compromete, las demás están seguras

**Lo que NO se debe hacer:**
- ❌ Usar nombres de familiares o mascotas
- ❌ Usar fechas importantes (cumpleaños, aniversarios)
- ❌ Usar palabras del diccionario
- ❌ Usar patrones de teclado (qwerty, 1234)
- ❌ Reutilizar contraseñas
- ❌ Compartir contraseñas
- ❌ Escribir contraseñas en lugares visibles
- ❌ Usar menos de 12 caracteres

### 10.3. Métodos para crear contraseñas seguras

#### **MÉTODO 1: FRASE DE CONTRASEÑA (Passphrase)**

**Concepto:**
- Usar una frase larga y fácil de recordar
- Combinar palabras aleatorias
- Añadir números y símbolos
- Fácil de recordar, difícil de adivinar

**Ejemplo:**
- Frase: "Me gusta comer pizza los viernes por la noche"
- Contraseña: "MgcPzlVxPN!" (primeras letras + símbolos)
- O: "MeGust@Com3rPizz4L0sVi3rn3s!" (modificaciones)

**Ventajas:**
- Larga y segura
- Fácil de recordar
- Dificil de crackear

#### **MÉTODO 2: PRIMERAS LETRAS**

**Concepto:**
- Tomar una frase, canción o cita
- Usar las primeras letras de cada palabra
- Añadir números y símbolos

**Ejemplo:**
- Canción: "En un lugar de la Mancha de cuyo nombre no quiero acordarme"
- Contraseña: "EuldlMdcnnqa!" (con símbolos y números)

**Ventajas:**
- Personal y memorable
- Fácil de teclear
- Alta entropía

#### **MÉTODO 3: PALABRAS ALEATORIAS**

**Concepto:**
- Combinar 4-5 palabras aleatorias
- Separar con símbolos
- Usar diccionario de palabras seguras

**Ejemplo:**
- Palabras: "caballo-batería-grapa-correcto"
- Contraseña: "Caballo@Batería#Grapa$Correcto"

**Ventajas:**
- Muy segura (alta entropía)
- Relativamente fácil de recordar
- Recomendada por expertos

**Herramientas recomendadas:**
- Diceware (método de dados)
- Generadores de contraseñas seguras
- Bitwarden Password Generator

#### **MÉTODO 4: SUSTITUCIONES**

**Concepto:**
- Tomar una palabra o frase
- Sustituir letras por números/símbolos
- Añadir variaciones

**Ejemplo:**
- Palabra: "seguridad"
- Contraseña: "S3gur1d@d_2024!"

**Advertencia:**
- Las sustituciones comunes son conocidas por los atacantes
- No confiar solo en esto
- Combinar con otros métodos

### 10.4. Gestión de contraseñas

**El problema:**
- Necesitamos muchas contraseñas
- Cada una debe ser única
- Es imposible recordarlas todas
- Reutilizamos por necesidad

**La solución: Gestores de contraseñas**

**¿Qué son?**
- Aplicaciones que almacenan contraseñas cifradas
- Solo necesitas recordar una contraseña maestra
- Generan contraseñas seguras automáticamente
- Rellenan formularios automáticamente

**Gestores recomendados:**

1. **Bitwarden**
   - Código abierto
   - Gratuito y premium
   - Multiplataforma
   - Muy recomendado

2. **1Password**
   - Popular y bien establecido
   - Excelente experiencia de usuario
   - Pago
   - Muy seguro

3. **LastPass**
   - Ampliamente utilizado
   - Versión gratuita limitada
   - Multiplataforma
   - Controversias de seguridad pasadas

4. **KeePass**
   - Código abierto
   - Almacenamiento local
   - Gratuito
   - Para usuarios avanzados

**Características a buscar:**
- Cifrado fuerte (AES-256)
- Generador de contraseñas
- Autocompletar
- Sincronización entre dispositivos
- 2FA para la bóveda
- Auditoría de contraseñas

**Mejores prácticas:**

1. **Contraseña maestra**
   - Debe ser extremadamente segura
   - Larga y compleja
   - No anotarla
   - Recordarla siempre

2. **2FA para el gestor**
   - Habilitar siempre
   - Aplicación de autenticación
   - Token físico si es posible
   - Protege la bóveda completa

3. **Backup**
   - Exportar bóveda periódicamente
   - Almacenar en lugar seguro
   - Cifrar el backup
   - Probar restauración

4. **Actualización**
   - Auditoría regular de contraseñas
   - Cambiar contraseñas débiles
   - Eliminar cuentas no usadas
   - Mantener software actualizado

### 10.5. Principios para contraseñas

**1. ASÉPTICA**
- No usar información personal
- No incluir nombres, fechas, lugares significativos
- Evitar referencias a la vida personal

**2. DIFERENTE**
- Cada servicio con su propia contraseña
- No reutilizar nunca
- Si una se compromete, las demás están seguras

**3. INTRANSFERIBLE**
- No compartir con nadie
- Ni con colegas, amigos o familia
- Cada persona con su propia cuenta

**4. BUEN RECAUDO**
- No dejarla escrita en lugares visibles
- No guardarla en archivos de texto sin cifrar
- Usar gestor de contraseñas
- No enviarla por correo o mensajería

---

## 11. AUTENTICACIÓN MULTIFACTOR

### 11.1. Introducción

La autenticación multifactor (MFA o 2FA) es un método de control de acceso que requiere múltiples factores de verificación para conceder acceso a una cuenta o sistema.

**¿Por qué es necesaria?**
- Las contraseñas pueden ser robadas
- Las contraseñas pueden ser débiles
- Las contraseñas pueden reutilizarse
- MFA añade capas adicionales de seguridad
- Reduce drásticamente el riesgo de acceso no autorizado

**Estadísticas:**
- MFA previene el 99.9% de ataques de cuenta
- Microsoft reporta que MFA bloquea más de 99.9% de ataques
- Es una de las medidas de seguridad más efectivas
- Relativamente fácil de implementar

### 11.2. Factores de autenticación

Existen cuatro categorías principales de factores de autenticación:

#### **FACTOR 1: ALGO QUE CONOCES (Knowledge)**

**Definición:**
- Información que solo el usuario sabe
- Factor más común y tradicional
- Base de la autenticación clásica

**Ejemplos:**
- Contraseñas
- PINs
- Respuestas a preguntas de seguridad
- Patrones de bloqueo
- Frases de contraseña

**Ventajas:**
- Familiar para todos los usuarios
- Fácil de implementar
- No requiere hardware adicional

**Desventajas:**
- Puede ser olvidado
- Puede ser robado (phishing, keyloggers)
- Puede ser adivinado
- Puede ser compartido
- Vulnerable a ataques de fuerza bruta

#### **FACTOR 2: ALGO QUE TIENES (Possession)**

**Definición:**
- Objeto físico que solo el usuario posee
- Algo que se puede tocar o llevar

**Ejemplos:**
- Teléfono móvil (para SMS o apps de autenticación)
- Tokens hardware (YubiKey, Google Titan)
- Tarjetas inteligentes
- Llaves de seguridad
- Certificados digitales en dispositivos

**Ventajas:**
- Más seguro que solo contraseña
- Difícil de replicar
- Requiere acceso físico

**Desventajas:**
- Puede perderse u olvidarse
- Puede ser robado
- Requiere hardware adicional
- No siempre disponible

#### **FACTOR 3: ALGO QUE ERES (Inherence)**

**Definición:**
- Características biométricas únicas del usuario
- Aspectos físicos o de comportamiento

**Ejemplos:**
- Huella dactilar
- Reconocimiento facial
- Escaneo de iris o retina
- Reconocimiento de voz
- Patrones de comportamiento (forma de teclear, caminar)

**Ventajas:**
- No se puede olvidar
- Difícil de falsificar (aunque no imposible)
- Cómodo para el usuario
- Siempre disponible

**Desventajas:**
- Preocupaciones de privacidad
- Falsos positivos/negativos
- No se puede cambiar si se compromete
- Requiere hardware especializado
- Costoso de implementar

#### **FACTOR 4: DESDE DÓNDE ACCEDES (Location)**

**Definición:**
- Ubicación geográfica o de red del usuario
- Contexto de la autenticación

**Ejemplos:**
- Dirección IP
- Geolocalización GPS
- Red WiFi específica
- Código postal
- País o región

**Ventajas:**
- Transparente para el usuario
- Añade capa de seguridad
- Puede detectar accesos sospechosos

**Desventajas:**
- No es un factor fuerte por sí solo
- Puede ser spoofeado (VPNs)
- Problemas de privacidad
- Falsos positivos (viajes)

### 11.3. Tipos de autenticación multifactor

#### **2FA (Two-Factor Authentication)**
- Requiere exactamente 2 factores
- Combinación más común: contraseña + código SMS
- Más seguro que solo contraseña
- Ampliamente adoptado

#### **MFA (Multi-Factor Authentication)**
- Requiere 2 o más factores
- Puede incluir 3 o más factores
- Más seguro que 2FA
- Usado en entornos de alta seguridad

#### **Adaptive Authentication (Autenticación Adaptativa)**
- Evalúa el riesgo en tiempo real
- Solicita factores adicionales según contexto
- Balance entre seguridad y usabilidad
- Basada en:
  - Ubicación
  - Dispositivo
  - Hora del día
  - Comportamiento
  - Sensibilidad de la acción

### 11.4. Métodos de MFA

#### **SMS/Email**
**Cómo funciona:**
- Se envía un código por SMS o email
- El usuario introduce el código
- Valida la posesión del teléfono/email

**Ventajas:**
- Fácil de usar
- No requiere apps adicionales
- Ampliamente soportado

**Desventajas:**
- Vulnerable a SIM swapping
- SMS pueden ser interceptados
- Requiere cobertura móvil
- No el método más seguro

**Recomendación:**
- Mejor que nada, pero no ideal
- Preferir apps de autenticación si es posible

#### **Aplicaciones de Autenticación**
**Cómo funciona:**
- Apps como Google Authenticator, Authy, Microsoft Authenticator
- Generan códigos TOTP (Time-based One-Time Password)
- Códigos cambian cada 30 segundos
- Funcionan offline

**Apps populares:**
- **Google Authenticator**: Simple, ampliamente soportada
- **Authy**: Sincronización entre dispositivos, backups
- **Microsoft Authenticator**: Integración con Microsoft
- **1Password**: Integrado con gestor de contraseñas

**Ventajas:**
- Más seguro que SMS
- Funciona sin conexión
- Códigos de un solo uso
- No depende del operador móvil

**Desventajas:**
- Requiere instalar app
- Si pierdes el dispositivo, pierdes acceso
- Configuración inicial más compleja

**Recomendación:**
- Opción recomendada para la mayoría
- Balance excelente seguridad/usabilidad
- Guardar códigos de respaldo

#### **Tokens Hardware**
**Cómo funciona:**
- Dispositivo físico que genera códigos o usa FIDO2/WebAuthn
- Se conecta por USB, NFC o Bluetooth
- Muy seguro
- Ejemplos: YubiKey, Google Titan, SoloKeys

**Ventajas:**
- Extremadamente seguro
- Resistente a phishing
- No depende de batería o conectividad
- Duradero

**Desventajas:**
- Costo (20-50€ por token)
- Puede perderse
- Requiere puerto USB o NFC
- Menos conveniente

**Recomendación:**
- Para cuentas críticas (email, finanzas)
- Máxima seguridad disponible
- Inversión que vale la pena

#### **Biometría**
**Cómo funciona:**
- Huella dactilar, reconocimiento facial, iris
- Características únicas del usuario
- Integrado en dispositivos modernos

**Ventajas:**
- Muy conveniente
- No se puede olvidar
- Rápido
- Integrado en dispositivos

**Desventajas:**
- Falsos positivos/negativos
- Preocupaciones de privacidad
- No se puede cambiar si se compromete
- Requiere hardware

**Recomendación:**
- Excelente para dispositivos locales
- Combinar con otros factores
- No usar como único factor

#### **Notificaciones Push**
**Cómo funciona:**
- Se envía notificación push al dispositivo
- Usuario aprueba o deniega el acceso
- Puede incluir información de contexto
- Ejemplos: Google Prompt, Microsoft Authenticator

**Ventajas:**
- Muy fácil de usar
- Solo requiere aprobar/denegar
- Información de contexto visible
- Resistente a phishing

**Desventajas:**
- Requiere dispositivo móvil
- Requiere conectividad
- MFA fatigue (aprobar sin pensar)
- Depende de notificaciones

**Recomendación:**
- Muy conveniente
- Bueno para la mayoría de usuarios
- Verificar siempre la información de contexto

### 11.5. Implementación de MFA

**Dónde habilitar MFA (prioridad):**

1. **Crítico (habilitar inmediatamente)**
   - Email principal
   - Gestor de contraseñas
   - Cuentas bancarias
   - Servicios financieros
   - Cuentas de gobierno

2. **Alta prioridad**
   - Redes sociales
   - Tiendas online
   - Servicios en la nube
   - Cuentas de trabajo

3. **Recomendado**
   - Cualquier cuenta importante
   - Servicios con información sensible
   - Cuentas con datos de pago

**Pasos para implementar:**

1. **Inventario de cuentas**
   - Listar todas las cuentas importantes
   - Identificar cuáles soportan MFA
   - Priorizar según criticidad

2. **Elegir método**
   - Apps de autenticación para la mayoría
   - Tokens hardware para cuentas críticas
   - SMS solo si no hay otra opción

3. **Configuración**
   - Habilitar MFA en cada cuenta
   - Guardar códigos de respaldo
   - Probar que funciona
   - Documentar el proceso

4. **Mantenimiento**
   - Actualizar cuando se cambie de teléfono
   - Revisar periódicamente
   - Eliminar dispositivos antiguos
   - Mantener métodos de recuperación actualizados

### 11.6. Códigos de respaldo

**Importancia:**
- Si pierdes acceso al segundo factor, necesitas respaldo
- Sin códigos de respaldo, puedes perder acceso permanentemente
- Esenciales para recuperación de cuenta

**Mejores prácticas:**
- Generar códigos al habilitar MFA
- Imprimir y guardar en lugar seguro (caja fuerte)
- Almacenar cifrados en gestor de contraseñas
- Compartir con persona de confianza (cónyuge, socio)
- Actualizar si se regeneran

**Almacenamiento seguro:**
- Caja fuerte física
- Gestor de contraseñas cifrado
- USB cifrado en lugar seguro
- No en texto plano en la nube
- No en dispositivos sin cifrar

---

## 12. PROTECCIÓN DEL PUESTO DE TRABAJO

### 12.1. Introducción

El puesto de trabajo es la primera línea de defensa en seguridad informática. Un puesto mal protegido puede comprometer toda la red de la organización. La protección del puesto de trabajo abarca aspectos físicos, técnicos y de comportamiento.

### 12.2. Política de mesas limpias

**Definición:**
La política de mesas limpias es un conjunto de reglas para mantener el puesto de trabajo físico seguro y libre de información sensible cuando no se está utilizando.

**Objetivos:**
- Prevenir acceso no autorizado a información
- Proteger documentos sensibles
- Mantener orden y seguridad
- Cumplir con normativas de protección de datos

**Componentes:**

1. **Escritorio ordenado y seguro**
   - No dejar documentos sensibles a la vista
   - Guardar documentos en cajones con llave
   - Limpiar el escritorio al finalizar
   - No dejar notas con contraseñas

2. **Proteger información sensible**
   - Documentos confidenciales bajo llave
   - Pantallas de ordenador orientadas para privacidad
   - Filtros de privacidad en monitores
   - No discutir información sensible en áreas públicas

3. **Dispositivos seguros**
   - Bloquear el ordenador al ausentarse
   - No dejar dispositivos desatendidos
   - Guardar portátiles y tablets
   - Cables de seguridad para equipos

**Implementación:**
- Políticas claras y documentadas
- Formación de empleados
- Auditorías periódicas
- Cultura de seguridad
- Señalización apropiada

### 12.3. Software de protección

#### **Antivirus/Antimalware**
**Función:**
- Detectar, prevenir y eliminar malware
- Escanear archivos en tiempo real
- Analizar comportamiento sospechoso
- Actualizar definiciones regularmente

**Características clave:**
- Protección en tiempo real
- Actualizaciones automáticas
- Escaneo bajo demanda
- Cuarentena de archivos sospechosos
- Reporting y logs

**Soluciones populares:**
- **Empresarial**: CrowdStrike, SentinelOne, Microsoft Defender for Endpoint
- **PYME**: Bitdefender, Kaspersky, ESET
- **Personal**: Windows Defender (gratuito y efectivo)

**Mejores prácticas:**
- Mantener siempre actualizado
- No deshabilitar protección en tiempo real
- Escanear regularmente
- No instalar múltiples antivirus (conflictos)
- Complementar con antimalware (Malwarebytes)

#### **Firewall**
**Función:**
- Controlar tráfico de red entrante y saliente
- Bloquear conexiones no autorizadas
- Filtrar tráfico malicioso
- Proteger contra accesos no autorizados

**Tipos:**
- **Firewall de software**: Integrado en el SO (Windows Firewall)
- **Firewall de hardware**: Dispositivo dedicado o router
- **Firewall personal**: Para equipos individuales
- **Firewall empresarial**: Para redes corporativas

**Configuración básica:**
- Bloquear todo el tráfico entrante no solicitado
- Permitir solo aplicaciones necesarias
- Registrar actividad sospechosa
- Actualizar reglas regularmente

#### **Actualizaciones de software**
**Importancia:**
- Corregir vulnerabilidades de seguridad
- Mejorar rendimiento y estabilidad
- Añadir nuevas características
- Mantener compatibilidad

**Riesgos de no actualizar:**
- Vulnerabilidades conocidas sin parchear
- Exposición a ataques
- Incompatibilidad con software seguro
- Incumplimiento de normativas

**Estrategia de actualización:**
- Actualizaciones automáticas cuando sea posible
- Pruebas antes de despliegue masivo
- Priorizar parches de seguridad
- Mantener inventario de software
- Plan de actualizaciones regular

### 12.4. Cifrado de datos

**Importancia:**
- Proteger datos en caso de robo del dispositivo
- Cumplir con normativas de protección de datos
- Prevenir acceso no autorizado
- Especialmente importante para portátiles y dispositivos móviles

**Tipos de cifrado:**

1. **Cifrado de disco completo**
   - Todo el disco está cifrado
   - Transparente para el usuario
   - Requiere autenticación al arrancar
   - Ejemplos: BitLocker (Windows), FileVault (Mac), LUKS (Linux)

2. **Cifrado de archivos/carpetas**
   - Solo archivos o carpetas específicas
   - Más selectivo
   - Puede ser más complejo de gestionar
   - Ejemplos: VeraCrypt, 7-Zip con cifrado

3. **Cifrado de dispositivos externos**
   - USBs, discos externos
   - Hardware o software
   - Importante para datos portables
   - Ejemplos: USBs con teclado, VeraCrypt

**Implementación:**
- Habilitar cifrado en todos los dispositivos
- Gestionar claves de recuperación
- Backups de claves
- Formación de usuarios
- Políticas claras

### 12.5. Dispositivos externos

**Riesgos:**
- Introducción de malware
- Pérdida de datos sensibles
- Robo de información
- Conexión de dispositivos no autorizados

**Políticas de control:**

1. **Dispositivos USB**
   - Restringir uso de USBs desconocidos
   - Escanear antes de usar
   - Prohibir USBs personales
   - Usar USBs corporativos cifrados

2. **Dispositivos móviles**
   - No conectar dispositivos personales sin autorización
   - MDM (Mobile Device Management) para dispositivos corporativos
   - Políticas de BYOD claras

3. **Medios ópticos**
   - CDs, DVDs
   - Escanear antes de usar
   - Restringir grabación de datos

**Controles técnicos:**
- Deshabilitar puertos USB si no son necesarios
- Software de control de dispositivos
- DLP (Data Loss Prevention)
- Listas blancas de dispositivos

### 12.6. BYOD (Bring Your Own Device) y trabajo remoto

**BYOD - Trae tu propio dispositivo:**

**Ventajas:**
- Empleados más cómodos
- Reducción de costos de hardware
- Familiaridad con dispositivos
- Flexibilidad

**Riesgos:**
- Mezcla de datos personales y corporativos
- Dificultad de controlar seguridad
- Pérdida de datos si se pierde el dispositivo
- Compliance regulatorio

**Políticas BYOD:**
- Definir qué dispositivos están permitidos
- Requerir cifrado
- Requerir contraseñas fuertes
- Habilitar borrado remoto
- MDM obligatorio
- Separación de datos personales/corporativos
- Acuerdos de uso

**Trabajo remoto:**

**Riesgos adicionales:**
- Redes WiFi públicas inseguras
- Dispositivos compartidos con familia
- Menor supervisión
- Dificultad de soporte técnico

**Medidas de protección:**

1. **VPN (Red Privada Virtual)**
   - Cifrar todo el tráfico
   - Acceso seguro a recursos corporativos
   - Obligatorio para trabajo remoto
   - Soluciones: OpenVPN, WireGuard, soluciones empresariales

2. **Acceso seguro**
   - MFA obligatorio
   - Acceso basado en roles
   - Sesiones con timeout
   - Logs de acceso

3. **Dispositivos seguros**
   - Cifrado de disco
   - Antivirus actualizado
   - Firewall habilitado
   - Parches al día

4. **Concienciación**
   - Formación específica para trabajo remoto
   - Buenas prácticas para WiFi público
   - Seguridad física del dispositivo
   - Reporte de incidentes

### 12.7. Bloqueo de sesión

**Importancia:**
- Prevenir acceso no autorizado cuando nos ausentamos
- Proteger información sensible
- Requisito de muchas normativas
- Hábito fundamental de seguridad

**Configuración:**
- Bloqueo automático tras inactividad (5-10 minutos)
- Contraseña o biometría para desbloquear
- Windows + L para bloqueo manual inmediato
- No compartir contraseñas de desbloqueo

**Buenas prácticas:**
- Bloquear SIEMPRE al ausentarse, incluso brevemente
- No dejar sesiones abiertas en áreas públicas
- Cerrar sesión al finalizar el día
- No anotar contraseñas cerca del ordenador

### 12.8. Copias de seguridad

**Importancia en el puesto de trabajo:**
- Protección contra fallos de hardware
- Recuperación ante ransomware
- Preservación de trabajo del usuario
- Cumplimiento de políticas de retención

**Responsabilidades:**
- **TI**: Proporcionar herramientas y automatización
- **Usuario**: Seguir políticas y verificar backups
- **Ambos**: Garantizar que los datos críticos están protegidos

**Mejores prácticas:**
- Guardar archivos en ubicaciones respaldadas automáticamente
- No almacenar datos críticos solo en el escritorio
- Verificar que los backups se realizan
- Conocer el proceso de restauración
- Reportar problemas inmediatamente

### 12.9. Uso adecuado de recursos empresariales

**Principios:**
- Usar recursos solo para fines profesionales
- Respetar políticas de uso aceptable
- No instalar software no autorizado
- Reportar problemas de seguridad
- Proteger credenciales de acceso

**Actividades prohibidas:**
- Descarga de contenido ilegal
- Uso personal excesivo
- Instalación de software pirata
- Acceso a sitios inapropiados
- Compartir credenciales

**Consecuencias:**
- Sanciones disciplinarias
- Despido
- Acciones legales
- Daño reputacional

---

## 13. CONCLUSIONES

### 13.1. Ideas clave de la ciberseguridad

1. **La ciberseguridad empieza en cada persona**
   - La tecnología no es suficiente
   - El factor humano es crítico
   - Cada empleado es una línea de defensa
   - La concienciación es fundamental

2. **Una contraseña segura es una puerta cerrada**
   - Las contraseñas son la primera barrera
   - Deben ser largas, complejas y únicas
   - Usar gestores de contraseñas
   - Habilitar MFA siempre que sea posible

3. **La prevención siempre es mejor que la defensa**
   - Formar a los empleados continuamente
   - Mantener sistemas actualizados
   - Implementar múltiples capas de seguridad
   - Planificar para incidentes

### 13.2. Principios fundamentales

**Defensa en profundidad:**
- Múltiples capas de seguridad
- No confiar en una única medida
- Combinar tecnología, procesos y personas
- Redundancia en controles críticos

**Mejora continua:**
- La seguridad no es un destino, es un viaje
- Las amenazas evolucionan constantemente
- Adaptarse a nuevas técnicas de ataque
- Aprendizaje de incidentes

**Balance seguridad/usabilidad:**
- Seguridad excesiva puede ser contraproducente
- Los usuarios deben poder trabajar
- Encontrar el punto óptimo
- Comunicación clara de políticas

### 13.3. Tendencias futuras

**Amenazas emergentes:**
- IA generativa para ataques más sofisticados
- Deepfakes para ingeniería social
- Ataques a la cadena de suministro
- Ransomware como servicio
- Amenazas a IoT y dispositivos conectados

**Tecnologías defensivas:**
- Zero Trust Architecture
- AI/ML para detección de amenazas
- Automatización de respuesta (SOAR)
- Seguridad en la nube nativa
- Identidad como nuevo perímetro

**Regulación:**
- Mayor exigencia de cumplimiento
- Responsabilidad personal de directivos
- Sanciones más severas
- Armonización internacional

### 13.4. Recomendaciones finales

**Para organizaciones:**
1. Invertir en formación y concienciación
2. Implementar múltiples capas de seguridad
3. Mantener sistemas actualizados
4. Planificar para incidentes
5. Realizar auditorías regularmente
6. Fomentar cultura de seguridad

**Para individuos:**
1. Usar contraseñas fuertes y únicas
2. Habilitar MFA en todas las cuentas
3. Mantener software actualizado
4. Ser escéptico con correos y mensajes
5. Hacer backups regularmente
6. Reportar incidentes de seguridad

**Recuerda:**
- La seguridad es responsabilidad de todos
- Pequeñas acciones hacen gran diferencia
- La prevención es la mejor estrategia
- Mantente informado y actualizado

---

## GLOSARIO DE TÉRMINOS CLAVE

- **Activo**: Cualquier recurso que tiene valor para la organización
- **Phishing**: Técnica de ingeniería social para obtener información sensible
- **Malware**: Software malicioso diseñado para dañar o explotar sistemas
- **Ransomware**: Tipo de malware que cifra datos y pide rescate
- **MFA/2FA**: Autenticación multifactor/de dos factores
- **Cifrado**: Proceso de convertir información en forma no legible
- **Backup**: Copia de seguridad de datos
- **Firewall**: Sistema que controla el tráfico de red
- **Vulnerabilidad**: Debilidad que puede ser explotada
- **Breach/Brecha**: Acceso no autorizado a datos o sistemas
- **Ingeniería social**: Manipulación psicológica para obtener información
- **Zero Trust**: Modelo de seguridad que no confía por defecto
- **DLP**: Prevención de pérdida de datos
- **SIEM**: Gestión de eventos e información de seguridad
- **EDR**: Detección y respuesta en endpoints
- **Incident Response**: Respuesta a incidentes de seguridad
- **Compliance**: Cumplimiento de normativas y estándares
- **GDPR/RGPD**: Reglamento General de Protección de Datos
- **SOC**: Centro de operaciones de seguridad
- **Penetration Testing**: Pruebas de intrusión para evaluar seguridad

---

## NORMATIVA Y ESTÁNDARES DE REFERENCIA

**Regulaciones:**
- RGPD (UE) 2016/679 - Protección de datos
- LOPDGDD 3/2018 - Adaptación española
- NIS2 - Seguridad de redes y sistemas de información
- ePrivacy - Privacidad en comunicaciones electrónicas

**Estándares:**
- ISO 27001 - Sistemas de gestión de seguridad de la información
- ISO 27002 - Controles de seguridad
- NIST Cybersecurity Framework - Marco de ciberseguridad
- PCI DSS - Seguridad de datos de tarjetas de pago

**Mejores prácticas:**
- ITIL - Gestión de servicios de TI
- COBIT - Gobernanza de TI
- CIS Controls - Controles de seguridad críticos

---

## RECURSOS ADICIONALES

**Organismos de referencia:**
- INCIBE (Instituto Nacional de Ciberseguridad de España)
- AEPD (Agencia Española de Protección de Datos)
- CCN-CERT (Centro Criptológico Nacional)
- ENISA (Agencia de Ciberseguridad de la UE)

**Portales de información:**
- osi.incibe.es - Oficina de Seguridad del Internauta
- aepd.es - Agencia Española de Protección de Datos
- ccn-cert.cni.es - Centro Criptológico Nacional
- haveibeenpwned.com - Verificar brechas de datos

**Formación:**
- Coursera: Cybersecurity Specialization
- edX: Introduction to Cyber Security
- SANS Institute: Formación especializada
- Certificaciones: CISSP, CISM, CEH, Security+

---

*Documento elaborado para la Unidad Didáctica 6: Ciberseguridad*
*Digitalización aplicada a los sectores productivos*
