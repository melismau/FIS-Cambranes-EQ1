# Documento de Requerimientos

## Introducción

### Propósito del proyecto
El propósito de este proyecto es crear una aplicación móvil y de escritorio para el aprendizaje autónomo, divertido y accesible de la lengua maya. Esto se logrará mediante lecciones gamificadas, ejercicios prácticos y audios grabados por hablantes nativos. La aplicación busca ser un instrumento cultural que promueva la diversidad lingüística y el acceso inclusivo al conocimiento cultural.

### Convención del documento
Este documento emplea las siguientes convenciones y acrónimos para asegurar la uniformidad en la interpretación de los requisitos:

- Los requisitos funcionales se enumeran de la forma “RF-n”.
- Los requisitos no funcionales se enumeran de la forma “RNF-n”.
- “MoSCoW” es un modelo de priorización que clasifica los requisitos de la forma Must Have (Esencial), Should Have (Importante), Could Have (Deseable).

### Audiencia objetivo y sugerencias de lectura
Este documento está dirigido al equipo de desarrollo para ayudar a comprender la lógica, el comportamiento y los requisitos que tendrá el sistema.  
Sugerencias de lectura: Descripción del proyecto, requisitos funcionales y requisitos no funcionales.

### Alcance del proyecto
El proyecto contará con los siguientes aspectos:

- Diseño de una interfaz amigable con ilustraciones y elemento visuales inspirados en la cultura maya.
- Ofrecer más de 50 lecciones gamificadas por niveles (principiante, intermedio, avanzado).
- Incluir ejercicios interactivos de opción múltiple, dictado y arrastrar y soltar.
- Incluir ejercicios de vocabulario, gramática, comprensión auditiva y traducción.
- Biblioteca de audios con frases cotidianas, palabras claves y diálogos breves.
- Interfaz de usuario con estadísticas de avance mediante puntos, niveles y logros.

El proyecto contará con las siguientes limitaciones:

- No incluirá las funciones de conversación en tiempo real.
- Requiere conexión a internet para futuras actualizaciones.
- No incluye certificación oficial ni validación académica del aprendizaje.
- La aplicación no está diseñada para personas con discapacidades visuales o auditivas.

---

## Descripción del proyecto

### Importancia y propuesta de valor
La lengua maya es un patrimonio de la Península de Yucatán y una joya cultural que porta la historia y cultura del pueblo maya. Sin embargo, enfrenta un riesgo creciente de desaparición debido a la falta de recursos educativos modernos y atractivos para las nuevas generaciones.

El valor principal de la aplicación es:

- Revitalizar el idioma maya yucateco.
- Promover la inclusión y el respeto cultural.
- Fortalecer la identidad regional, conectando a los usuarios con su herencia ancestral.
- Ofrecer una experiencia integral, accesible y actualizada que actualmente no existe en otras iniciativas digitales.

### Clases y características del usuario
El público ideal está compuesto por personas a partir de los 12 años en adelante. Estos perfiles dictan las funciones y el diseño intuitivo de la aplicación.

| Perfil de usuario         | Uso previsto                                                                 |
|---------------------------|------------------------------------------------------------------------------|
| Estudiantes               | Usar la aplicación como recurso didáctico de apoyo para complementar estudios académicos. |
| Profesores del idioma     | Integrar la aplicación a las clases como herramienta o evaluación complementaria. |
| Jóvenes y adultos interesados | Utilizar la aplicación de forma autodidacta en su tiempo libre para dominar la lengua progresivamente. |
| Hablantes nativos del maya| Usar la aplicación como medio de preservación lingüística y apoyo en la enseñanza comunitaria. |

### Ambiente de operación
El software está diseñado para operar en un ambiente multiplataforma con requisitos mínimos específicos:

- **Sistemas Operativos.** Android (versión 9.0 en adelante), iOS (versión 13 en adelante) y Windows (Versión 10 en adelante).
- **Dispositivos.** Debe funcionar en dispositivos móviles, tablets o computadoras, adaptándose a pantallas de distinto tamaño.
- **Conectividad.** Se requiere conexión a internet para las futuras actualizaciones. La aplicación soporta funcionalidad offline completa para las lecciones previamente descargadas.

### Restricciones de Diseño e Implementación
Estas restricciones, basadas en los requisitos no funcionales y las limitaciones del alcance, guiarán el desarrollo:

- **Restricción de Seguridad y Privacidad:** Toda la información del usuario debe almacenarse de forma segura y cifrada.
- **Restricción de Accesibilidad:** La aplicación no está diseñada para personas con discapacidades visuales o auditivas. Sin embargo, se incluyen opciones de accesibilidad (tamaño de fuente y contraste).
- **Restricción de Escalabilidad:** El diseño de la arquitectura debe soportar al menos 2,000 usuarios activos simultáneamente sin degradación significativa.
- **Restricción de Desarrollo (Lean):** El proceso de desarrollo deberá seguir los principios de Lean Manufacturing y la metodología ágil, priorizando el valor al cliente y la mejora continua.

### Documentación del Usuario
La documentación de usuario se enfocará en la guía in-app para garantizar una adopción rápida:

- **Tutorial Interactivo:** Se requiere un tutorial interactivo obligatorio durante el primer acceso.
- **Ayuda Integrada:** La interfaz debe incluir retroalimentación visual y mensajes de error amigables.

### Suposiciones y dependencias
- **Conectividad:** Se asume que el usuario tendrá acceso a conexión a internet para la descarga inicial de la aplicación y para recibir futuras actualizaciones.
- **Tecnología IA:** Se asume que la tecnología de reconocimiento de voz con IA para la evaluación fonética será implementada con éxito como un componente clave.

---

## Requisitos funcionales

| ID       | Requisito Funcional                                                                                 | Prioridad (MoSCoW) |
|----------|-----------------------------------------------------------------------------------------------------|--------------------|
| RF-01    | Gestión de Autenticación y Cuentas de Usuario                                                       | Must Have          |
| RF-01.1  | Proporcionar múltiples métodos de registro: correo electrónico/contraseña y autenticación OAuth (Google, Facebook, Apple ID). | Must Have |
| RF-01.2  | Implementar funcionalidad de recuperación de contraseñas mediante verificación por correo electrónico. | Must Have |
| RF-01.3  | Sincronizar automáticamente el progreso del usuario entre múltiples dispositivos.                    | Must Have |
| RF-01.4  | Soportar autenticación multifactor opcional (SMS, aplicaciones TOTP, códigos PIN).                  | Could Have |
| RF-01.5  | Proporcionar funcionalidad de exportación e importación del progreso mediante archivos de respaldo.  | Could Have |
| RF-02    | Gestión de Privacidad y Datos Personales                                                             | Must Have |
| RF-02.1  | Presentar obligatoriamente la política de privacidad durante el proceso de registro.                 | Must Have |
| RF-02.2  | Proporcionar funcionalidad de eliminación permanente de cuenta y todos los datos.                   | Must Have |
| RF-02.3  | Permitir la exportación completa de datos personales y progreso en formato estándar.                 | Should Have |
| RF-03    | Interfaz de Usuario y Experiencia                                                                    | Must Have |
| RF-03.1  | Ejecutar un tutorial interactivo obligatorio en el primer acceso.                                   | Must Have |
| RF-03.2  | Mostrar indicadores visuales de progreso, estadísticas de rendimiento y retroalimentación en el panel principal. | Must Have |
| RF-03.3  | Proporcionar opciones de accesibilidad (ajuste de tamaño de fuente y configuraciones de contraste).  | Should Have |
| RF-03.4  | Adaptar automáticamente la interfaz según el sistema operativo, resolución de pantalla y tipo de dispositivo. | Should Have |
| RF-04    | Contenido Educativo y Estructura Curricular                                                          | Must Have |
| RF-04.1  | Presentar lecciones estructuradas y progresivas que guíen desde nivel básico hasta avanzado.        | Must Have |
| RF-04.2  | Incorporar pronunciación auténtica del maya yucateco mediante grabaciones de hablantes nativos certificados. | Must Have |
| RF-04.3  | Ofrecer lecciones interactivas y dinámicas.                                                         | Must Have |
| RF-04.4  | Implementar diversos tipos de ejercicios: traducción bidireccional, completar oraciones, selección múltiple, etc. | Must Have |
| RF-04.5  | Organizar el contenido en módulos temáticos progresivos (saludos, familia, números, etc.).          | Must Have |
| RF-04.6  | Incluir explicaciones gramaticales contextuales del maya yucateco con ejemplos prácticos.            | Must Have |
| RF-04.7  | Incluir contenido cultural auténtico que contextualice el aprendizaje dentro de la tradición maya yucateca. | Should Have |
| RF-05    | Sistema de Gamificación y Motivación                                                                | Must Have |
| RF-05.1  | Implementar un sistema integral de puntuación y logros.                                             | Must Have |
| RF-05.2  | Permitir la repetición ilimitada de lecciones y ejercicios completados.                             | Must Have |
| RF-05.3  | Mantener registro de rachas diarias de estudio y enviar notificaciones de recordatorio configurables. | Must Have |
| RF-05.4  | Otorgar insignias y reconocimientos por alcanzar objetivos específicos.                             | Could Have |
| RF-06    | Tecnología de Pronunciación y Audio                                                                 | Must Have |
| RF-06.1  | Integrar tecnología de reconocimiento de voz con inteligencia artificial para evaluar la pronunciación. | Must Have |
| RF-06.2  | Proporcionar retroalimentación inmediata y específica sobre la pronunciación con sugerencias de mejora. | Must Have |
| RF-06.3  | El sistema de IA deberá filtrar automáticamente ruido de fondo y variaciones de tono para evaluar únicamente la precisión fonética. | Should Have |
| RF-07    | Optimización de Rendimiento y Conectividad                                                          | Must Have |
| RF-07.1  | Implementar descarga progresiva y automática de lecciones según el avance del usuario.              | Must Have |
| RF-07.2  | Proporcionar funcionalidad offline completa para lecciones previamente descargadas.                  | Must Have |
| RF-07.3  | Adaptar dinámicamente la calidad y peso del contenido según las condiciones de conectividad y capacidad del dispositivo. | Must Have |
| RF-08    | Herramientas de Estudio Avanzadas                                                                   | Could Have |
| RF-08.1  | Generar reportes detallados de progreso por habilidades específicas.                                | Could Have |
| RF-08.2  | Proporcionar recomendaciones personalizadas de áreas de mejora.                                     | Could Have |
| RF-09    | Personalización y Accesibilidad Avanzada                                                            | Should Have |
| RF-09.1  | Proporcionar subtítulos opcionales para todo el contenido audio.                                    | Should Have |
| RF-09.2  | Permitir control de velocidad de reproducción de audio con rango configurable.                      | Should Have |

---

## Requisitos no funcionales

| ID       | Requisito No Funcional (RNF)                                                                 | Prioridad   |
|----------|-----------------------------------------------------------------------------------------------|-------------|
| RNF-01   | La interfaz debe ser intuitiva y accesible para usuarios de todas las edades, con navegación clara y retroalimentación visual. | Must Have |
| RNF-01.1 | El diseño debe seguir principios de accesibilidad, incluyendo tipografía legible y botones grandes para los diversos dispositivos. | Must Have |
| RNF-02   | La aplicación debe cargar las lecciones en menos de 5 segundos en condiciones de red estable. | Must Have |
| RNF-03   | Los audios deben reproducirse sin interrupciones ni retrasos perceptibles.                     | Must Have |
| RNF-04   | Debe funcionar en dispositivos Android (versión 9.0 en adelante), iOS (versión 13 en adelante) y Windows (Versión 10 en adelante). | Must Have |
| RNF-04.1 | La aplicación debe adaptarse a pantallas de distinto tamaño para dispositivos móviles, tablets o computadoras. | Must Have |
| RNF-05   | Toda la información del usuario (progreso, perfil, preferencias) debe almacenarse de forma segura y cifrada. | Must Have |
| RNF-05.1 | El sistema debe prevenir accesos no autorizados mediante autenticación básica (correo y contraseña o acceso por redes sociales). | Must Have |
| RNF-05.2 | No se debe recopilar información sensible sin consentimiento explícito del usuario.             | Must Have |
| RNF-06   | El código debe estar documentado y modularizado para facilitar futuras actualizaciones y correcciones. | Must Have |
| RNF-06.1 | Las actualizaciones deben poder implementarse sin necesidad de reinstalar la aplicación.       | Should Have |
| RNF-07   | La arquitectura debe permitir agregar nuevas lecciones, módulos o variantes lingüísticas sin afectar el rendimiento general. | Should Have |
| RNF-08   | Debe soportar hasta 2,000 usuarios activos simultáneamente sin degradación significativa.      | Should Have |
| RNF-08.1 | En caso de caída, debe mostrar un mensaje de error amigable y ofrecer una opción para reintentar. | Should Have |
| RNF-09   | La aplicación debe estar disponible en español.                                                | Must Have |
| RNF-10   | Los contenidos culturales deben adaptarse al contexto de Yucatán, respetando la cultura maya. | Could Have |

---

## Referencias

- Andreu, I. (2024, 3 octubre). *Lean Manufacturing: ¿qué es y cuáles son sus principios?* APD España. https://www.apd.es/lean-manufacturing-que-es/  
- DiagramasUML. (s.f.). *Diagrama de casos de uso.* https://diagramasuml.com/casos-de-uso/  
- Team Asana. (2025, 8 de enero). *Cómo redactar un documento de requisitos de software (incluye una plantilla).* https://asana.com/es/resources/software-requirement-document-template  
- TIC Portal. (2022, 26 septiembre). *Método MOSCOW.* TIC Portal. https://www.ticportal.es/glosario-tic/metodo-moscow  
- UNESCO. (2022). *Decenio Internacional de las Lenguas Indígenas (2022-2032).* https://www.unesco.org/es/decades/indigenous-languages  
