# Verificación y Validación  de Software, Metodologías y Herramientas
- Se basa en un planificado y sistemático diseño de acciones y métodos requeridos para garantizar la calidad del mismo
- La calidad es importante en el desarrollo de un producto o servicio
- La calidad en ingeniería del software se obtiene mejorando día a día el proceso de producción
- Para optimizar la calidad de los productos y/o servicios es necesario conocer al cliente y sus necesidades
## Para poder cumplir con esto, es necesario:

### Aseguramiento de la calidad del software
- Un software de calidad es aquel que concuerde los requisitos funcionales y de rendimiento explícitamente
establecidos
- Así como con los estándares de desarrollo explícitamente documentados, y con las características implícitas de todo el Software
- Un componente importante del aseguramiento de la calidad del Software son las actividades de verificación y validación del mismo
- Dicho proceso provee una evaluación objetiva de los productos y del proceso desarrollados durante el ciclo de vida del software

### Verificación y validación
- Procesos de comprobación y análisis que aseguran que el software que se desarrolla está acorde a su especificación
- Es importante llevarla a cabo al inicio pues es fácil cometer errores durante el análisis de requerimientos de sistema
#### Dentro del proceso de verificación y validación se utilizan dos técnicas de comprobación y análisis de sistemas, que son:
##### Pruebas de Software
- Es un proceso por medio del cual se evalúa la funcionalidad de un software y se intenta identificar posibles errores
- El proceso de una prueba de software consiste en examinar, analizar, observar y evaluar diferentes aspectos que ocurren en el desempeño del software
###### Las pruebas de Software cumplen los siguientes objetivos:
- Las pruebas podrían ser llevadas a cabo para encontrar defectos
- Las pruebas podrían ser llevadas a cabo para brindar confianza a la gente en cuanto al nivel de calidad del sistema
- Los objetivos de las pruebas pueden cambiar dependiendo de la fase o del nivel de pruebas con el que estemos involucrados
##### Inspecciones de Software
- Es una técnica de validación estática, es decir, no requieren que el código se ejecute
- Se analizan las diferentes representaciones del sistema, como lo son los diagramas de requerimientos
- Este proceso debe tener criterios de entrada que determinen si el proceso de inspección está listo para comenzar
###### Las etapas del proceso de inspección son:
- Planificación
- Reunión de resumen
- Preparación
- Reunión de inspécción
- Rehacer
- Seguimiento

#### Algunos objetivos de la verificación y validación de datos son
- Facilitar la detección y corrección temprana de errores
- Mejorar la administración del proceso y los riesgos del producto
- Apoyar el proceso del ciclo de vida para asegurar el cumplimiento de los requerimientos de rendimiento
### Tipos de pruebas
- La prueba de insuficiencias o defectos del programa se obtiene analizando las respuestas que proporciona y buscando anomalías respecto a lo esperado
#### Entre los principales tipos de pruebas están:
##### Prueba Unitaria
- Se revisan los componentes individuales del software para comprobar si estos se comportan de acuerdo a los requerimientos
##### Prueba de Integración
- Se prueban los componentes individuales o módulos cuando han sido combinados en un grupo
##### Prueba de Regresión
- Los casos prueba antiguos de toda la aplicación se ejecutan luego de que se implementa una nueva funcionalidad
##### Prueba de Sistema
- Se realizan los casos de prueba para comprobar el cumplimiento de software integrado y sus especificaciones mediante el examinador
##### Prueba de Humo
- Comprueba los errores tempranamente revisando el sistema constantemente
#### Entre las diferentes etapas dedesarrollo se utilzan los siguentes tipos de prueba:
##### Pruebas de defectos
- Pretenden encontrar las inconsistencias entre un programa y su especificación
- Estas inconsistencias se deben habitualmente a los fallos o defectos en el código del programa
- Una prueba de defectos exitosa es aquella que descubre un fallo
##### Pruebas estadísticas
- Se utilizan para probar el desempeño y la fiabilidad del programa y comprobar cómo trabaja bajo condiciones operacionales
- Las pruebas se diseñan para reflejar las entradas de los usuarios y su frecuencia
- La capacidad del programa se valora midiendo el tiempo de ejecución y el tiempo de respuesta del sistema
##### Pruebas funcionales
- Estrategia para seleccionar las pruebas de fallos basándose en las especificaciones de los componentes y programas
- Este enfoque se puede aplicar de igual forma a los sistemas que están organizados como librerías de funciones, o como objetos
##### Pruebas estructurales
- Se seleccionan en función del conocimiento que se tiene de la implementación del módulo, suelen ser aplicadas a módulos pequeños
- El probador analiza el código y deduce cuantos y que conjuntos de valores de entrada han de probarse para que al menos se ejecute una vez cada sentencia del código
##### Pruebas de integración
- Se prueban las respuestas de grupos de módulos interconectados a fin de detectar fallos resultantes de la interacción entre los componentes
- Siempre se realizan con referencia a las especificaciones del programa y su principal dificultad es la localización de los fallos}
- Para facilitar la detección de los errores se utilizan técnicas incrementales

### Proceso de depuración
- Es el proceso de eliminación de los errores que se descubren durante las fases de prueba
- La depuración es el proceso que localiza el origen y corrige los defectos de la verificaci+on y validación de datos
- Los mejores depuradores buscan patrones en los resultados de las pruebas donde el defecto se detecta
- Para localizar el defecto utilizan el conocimiento que tienen sobre el tipo de defecto
- Los depuradores conocen los errores de los programadores comunes y los comparan contra los patrones observados
- Para localizar un fallo de un programa el programador responsable de la depuración tiene que diseñar programas de prueba adicionales que repitan el fallo original y que ayudan a descubrir el origen del fallo
- Las herramientas de depuración son habitualmente parte de las herramientas de apoyo al lenguaje y que sirven de base al compilador
- Permiten controlar la ejecución paso a paso sobre el código del programa

### Particiones de equivalencia
- Es cada grupo de datos de entrada que generan igual respuesta cualitativa
- Las particiones se identifican utilizando la especificación del programa o la documentación del usuario
#### Los casos de prueba se escogen en función de las particiones:
- Se elige un caso central por partición: caso típico
- Se eligen casos correspondientes a las fronteras con otras particiones: casos atípicos

### Herramienta JUnit
- Es un conjunto de clases que permite desarrollar y ejecutar conjuntos de pruebas de forma sencilla y sistemática
- Está integrada en el entorno Eclipse y está orientada a pruebas unitarias
#### Algunos elementos del framework JUnit son:
##### Casos prueba
- Clases que incluyen una serie de métodos para probar los métodos de una clase concreta
##### Métodos de prueba
- Son los métodos que la herramienta va a ejecutar automáticamente al ejecutar la clase de prueba
##### Aserciones
- Sentencia que nos permite probar una proposición que debería ser siempre cierta de acuerdo con la lógica del programa
##### Grupos de pruebas
- Sirven para agrupar varias clases de prueba y poder ejecutarlas todas seguidas

### Administración del proceso de verificación y validación
- En donde se debe describir la organización, la programación y las responsabilidades para realizar la VV del software
#### Organización
- En esta sección se debe describir la organización del grupo de Verificación y Validación
- Esta organización debe indicar las relaciones con otras tareas del proyecto
- se deben definir las líneas de comunicación con el grupo de verificación y validación
#### Programa de diseño
- Debe describir el ciclo de vida del proceso de VV y los puntos de revisión
- Este programa resume las tareas de VV
- Cuando se planean tareas de VV se deben organizar con la idea de que el proceso de VV sea interactivo
#### Responsabilidades
- Se debe indicar las responsabilidades de los elementos de la organización para cada tarea de VV

### Inspección del código fuente: Análisis estático automatizado
- Los analizadores estáticos de programas son herramientas de software que rastrean el texto fuente de un programa, en busca de errores no detectados por el compilador
- Su función no es habitualmente detectarlos, sino identificar las anomalías o situaciones heterodoxas que pueden serlo
#### Los aspectos usualmente analizados son:
##### Análisis de flujo de datos
- Identifica y señala los bucles con múltiples puntos de salida y las secciones de código no alcanzable
##### Análisis de utilización de datos:
- Señala cómo se utilizan las variables del programa
##### Análisis de interfaces
- Verifica la declaración de las
operaciones y su invocación
##### Análisis de la trayectoria
- Identifica todas las posibles trayectorias del programa y presenta las sentencias ejecutadas en cada trayectoria

### Reportes de verificación y validación
- se presentan durante todo el ciclo de vida del software, donde se describe como todas las pruebas serán documentadas con los resultados de la implementación
#### Los que debe contener el reporte son:
##### Reporte de tareas
- Estos son reportes de VV, sobre tareas individuales que se consideren relevantes y son puestos como reportes necesarios
##### Reporte de anomalías
- Pueden reportarse en la revisión técnica del software si la anomalía no impide el funcionamiento del software, de otra manera será como lo especifique el procedimiento
##### Reporte final de verificación y validación
- Al final de la VV se debe realizar un reporte resumido, indicando los resultados obtenidos de las tareas de VV en cada una de las fases de VV

### Procedimientos administrativos de la verificación y validación
- Es la descripción de los procedimientos administrativos mínimos para el proceso de verificación y validación
#### Estos son:
##### Reporte y resolución de anomalías
- Se realizan conforme a lo especificado en el P.SI-4
- Si es necesario se puede describir algún otro método de informar y resolverse las anomalías
##### Políticas de iteración de tareas
- Esta sección describe el criterio para determinar hasta qué punto una tarea de VV es perfeccionada
- Estos criterios pueden incluir valoraciones de cambio, programación, o efectos de calidad
##### Políticas de desviación
- Describe los procedimientos y formas cuando se encuentra una desviación en el Plan
- La información requerida para las desviaciones incluirá identificación de la tarea, la razón de desviación, y efectos en la calidad del software
- Una forma normal puede prepararse incluyendo la identificación de la tarea y la razón de la desviación
##### Procedimientos de control
- Esta sección identifica los procedimientos de control que serán aplicados al trabajo de VV
- Estos procedimientos describen cómo los productos del software y resultados de software son configurados, protegidos y almacenados
##### Estándares y convenciones
- Esta sección identifica los estándares y convenciones, que gobiernan la ejecución de tareas de VV
- Éstas pueden incluir estándares y políticas de organización interna

### Responsabilidades
#### Algunas responsabilidades que se encuentran dentro de este proceso son:
##### Revisor
- Se realiza la preparación del PVV conforme a este procedimiento y se firma de preparado el PVV generado en el SI
##### Departamento de sistemas informáticos
- Se realiza la revisión del PVV y se firma de revisado el PVV generado en el SI
##### Gerencia de sistemas
- Se asegura la correcta aplicación de este procedimiento y se firma de aprobado el PVV generado en el SI