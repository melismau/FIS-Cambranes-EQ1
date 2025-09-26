# Requisitos Funcionales

## RF-01: Gestión de Autenticación y Cuentas de Usuario

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-01.1 | El sistema deberá proporcionar múltiples métodos de registro: correo electrónico/contraseña y autenticación OAuth mediante Google, Facebook y Apple ID.  |
| ✅ | RF-01.2 | El sistema deberá implementar funcionalidad de recuperación de contraseñas mediante verificación por correo electrónico. |
| ✅ | RF-01.3 | El sistema deberá soportar autenticación multifactor opcional incluyendo: verificación por SMS, aplicaciones TOTP y códigos PIN personalizados. |
| ✅ | RF-01.4 | El sistema deberá sincronizar automáticamente el progreso del usuario entre múltiples dispositivos vinculados a la misma cuenta. |
| ✅ | RF-01.5 | El sistema deberá proporcionar funcionalidad de exportación e importación del progreso del usuario mediante archivos de respaldo. |

## RF-02: Gestión de Privacidad y Datos Personales

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-02.1 | El sistema deberá presentar obligatoriamente la política de privacidad durante el proceso de registro antes de crear la cuenta. |
| ✅ | RF-02.2 | El sistema deberá permitir la exportación completa de datos personales y progreso del usuario en formato estándar. |
| ✅ | RF-02.3 | El sistema deberá proporcionar funcionalidad de eliminación permanente de cuenta y todos los datos asociados. |

## RF-03: Interfaz de Usuario y Experiencia

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-03.1 | El sistema deberá ejecutar un tutorial interactivo obligatorio durante el primer acceso para familiarizar al usuario con la interfaz y mecánicas de la aplicación. |
| ✅ | RF-03.2 | El sistema deberá proporcionar opciones de personalización de accesibilidad, incluyendo ajuste de tamaño de fuente y configuraciones de contraste. |
| ✅ | RF-03.3 | El sistema deberá adaptar automáticamente la interfaz según el sistema operativo, resolución de pantalla y tipo de dispositivo del usuario. |
| ✅ | RF-03.4 | El sistema deberá mostrar indicadores visuales de progreso, estadísticas de rendimiento y retroalimentación del aprendizaje mediante el panel principal. |

## RF-04: Contenido Educativo y Estructura Curricular

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-04.1 | El sistema deberá presentar lecciones estructuradas y progresivas que guíen al usuario desde nivel básico hasta avanzado mediante un plan de estudios definido. |
| ✅ | RF-04.2 | El sistema deberá incorporar pronunciación auténtica del maya yucateco mediante grabaciones de audio de hablantes nativos certificados. |
| ✅ | RF-04.3 | El sistema deberá ofrecer lecciones interactivas y dinámicas que refuercen vocabulario y gramática a través de múltiples metodologías pedagógicas. |
| ✅ | RF-04.4 | El sistema deberá incluir contenido cultural auténtico que contextualice el aprendizaje del idioma dentro de la tradición maya yucateca. |
| ❌ | RF-04.5 | El sistema deberá garantizar accesibilidad universal mediante cumplimiento de estándares WCAG 2.1 nivel AA. |
| ✅ | RF-04.6 | El sistema deberá implementar diversos tipos de ejercicios: traducción bidireccional, completar oraciones, selección múltiple, ordenamiento de palabras y comprensión auditiva. |
| ✅ | RF-04.7 | El sistema deberá organizar el contenido en módulos temáticos progresivos (saludos, familia, números, gramática básica, etc.). |
| ✅ | RF-04.8 | El sistema deberá incluir explicaciones gramaticales contextuales del maya yucateco con ejemplos prácticos. |
| ❔ | RF-04.9 | El sistema deberá proporcionar un diccionario interactivo español-maya con funcionalidad de pronunciación y búsqueda bidireccional. |

## RF-05: Sistema de Gamificación y Motivación

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-05.1 | El sistema deberá implementar un sistema integral de puntuación y logros que el usuario pueda monitorear mediante la interfaz principal. |
| ✅ | RF-05.2 | El sistema deberá permitir la repetición ilimitada de lecciones y ejercicios completados anteriormente. |
| ✅ | RF-05.3 | El sistema deberá mantener registro de rachas diarias de estudio y enviar notificaciones de recordatorio configurables. |
| ✅ | RF-05.4 | El sistema deberá otorgar insignias y reconocimientos por alcanzar objetivos específicos de aprendizaje. |
| ❔ | RF-05.5 | El sistema deberá incluir tablas de clasificación opcionales para competencia amistosa entre usuarios conectados. |
| ❌ | RF-05.6 | El sistema deberá implementar un sistema de vidas/energía que se regenere temporalmente y motive el uso constante. |
| ❔ | RF-05.7 | El sistema deberá generar desafíos semanales temáticos para mantener el engagement del usuario. |

## RF-06: Tecnología de Pronunciación y Audio

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-06.1 | El sistema deberá integrar tecnología de reconocimiento de voz con inteligencia artificial para evaluar la pronunciación del usuario. |
| ✅ | RF-06.2 | El sistema de IA deberá filtrar automáticamente ruido de fondo, variaciones de tono y timbre para evaluar únicamente la precisión fonética. |
| ✅ | RF-06.3 | El sistema deberá proporcionar retroalimentación inmediata y específica sobre la pronunciación con sugerencias de mejora. |

## RF-07: Optimización de Rendimiento y Conectividad

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-07.1 | El sistema deberá implementar descarga progresiva y automática de lecciones según el avance del usuario para minimizar tiempos de carga. |
| ✅ | RF-07.2 | El sistema deberá proporcionar funcionalidad offline completa para lecciones previamente descargadas. |
| ✅ | RF-07.3 | El sistema deberá adaptar dinámicamente la calidad y peso del contenido según las condiciones de conectividad y capacidad del dispositivo. |

## RF-08: Funcionalidades Sociales y Comunitarias

| Estado | ID | Descripción |
|--------|----|-------------|
| ❔ | RF-08.1 | El sistema deberá permitir conexiones entre usuarios para seguimiento mutuo del progreso y motivación social. |
| ❔ | RF-08.2 | El sistema deberá incluir foros de discusión moderados enfocados en cultura y práctica del maya yucateco. |
| ✅ | RF-08.3 | El sistema deberá proporcionar funcionalidad de compartir logros y progreso en redes sociales externas. |

## RF-09: Herramientas de Estudio Avanzadas

| Estado | ID | Descripción |
|--------|----|-------------|
| ❔ | RF-09.1 | El sistema deberá incluir tarjetas de repaso (flashcards) personalizables con algoritmos de repetición espaciada. |
| ❔ | RF-09.2 | El sistema deberá ofrecer modos de práctica intensiva y evaluaciones de preparación. |
| ✅ | RF-09.3 | El sistema deberá generar reportes detallados de progreso por habilidades específicas (comprensión, pronunciación, gramática, vocabulario). |
| ✅ | RF-09.4 | El sistema deberá proporcionar recomendaciones personalizadas de áreas de mejora basadas en análisis de rendimiento. |

## RF-10: Características Culturales Específicas

| Estado | ID | Descripción |
|--------|----|-------------|
| ❔ | RF-10.1 | El sistema deberá incluir contenido multimedia sobre tradiciones, historia y costumbres de la cultura maya yucateca. |
| ❔ | RF-10.2 | El sistema deberá incorporar variantes dialectales regionales del maya yucateco con identificación geográfica. |
| ❔ | RF-10.3 | El sistema deberá incluir contenido cultural avanzado: recetas tradicionales, leyendas, cuentos y expresiones idiomáticas en contexto. |

## RF-11: Personalización y Accesibilidad Avanzada

| Estado | ID | Descripción |
|--------|----|-------------|
| ✅ | RF-11.1 | El sistema deberá ofrecer múltiples temas visuales incluyendo modo nocturno y esquemas de alto contraste. |
| ✅ | RF-11.2 | El sistema deberá proporcionar subtítulos opcionales para todo el contenido audio. |
| ✅ | RF-11.3 | El sistema deberá permitir control de velocidad de reproducción de audio con rango configurable. |
| ❌ | RF-11.4 | El sistema deberá soportar navegación por comandos de voz para funcionalidades básicas de accesibilidad. |
