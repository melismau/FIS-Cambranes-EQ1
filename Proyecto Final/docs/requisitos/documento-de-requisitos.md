# Documento de Requisitos

## Introducción

### Propósito del proyecto
El propósito de este proyecto es crear una aplicación móvil y de escritorio para el aprendizaje autónomo, divertido y accesible de la lengua maya. Esto se logrará mediante lecciones gamificadas, ejercicios prácticos y audios grabados por hablantes nativos. La aplicación busca ser un instrumento cultural que promueva la diversidad lingüística y el acceso inclusivo al conocimiento cultural.

### Convención del documento
Este documento emplea las siguientes convenciones y acrónimos para asegurar la uniformidad en la interpretación de los requisitos:

- Los requisitos funcionales se enumeran de la forma “RF-n”.
- Los requisitos no funcionales se enumeran de la forma “RNF-n”.
- “MoSCoW” es un modelo de priorización que clasifica los requisitos de la forma Must Have (Esencial), Should Have (Importante), Could Have (Deseable).
- Verificabilidad en la tabla de requisitos determina si son requisitos testeables.

### Audiencia objetivo y sugerencias de lectura
Este documento está dirigido al equipo de desarrollo para ayudar a comprender la lógica, el comportamiento y los requisitos que tendrá el sistema.  
Sugerencias de lectura: Descripción del proyecto, requisitos funcionales y requisitos no funcionales.

### Alcance del proyecto
El proyecto contará con los siguientes aspectos:

- Diseño de una interfaz amigable con ilustraciones y elemento visuales inspirados en la cultura maya.
- Ofrecer 15 lecciones gamificadas por niveles (principiante, intermedio, avanzado).
- Incluir ejercicios interactivos de opción múltiple y escribir respuesta.
- Incluir ejercicios de vocabulario y gramática.
- Interfaz de usuario con estadísticas de avance mediante puntos, niveles y logros.

El proyecto contará con las siguientes limitaciones:

- No incluirá las funciones de conversación en tiempo real.
- Requiere conexión a internet.
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

### Documentación del Usuario
La documentación de usuario se enfocará en la guía in-app para garantizar una adopción rápida:

- **Tutorial Interactivo:** Se requiere un tutorial interactivo obligatorio durante el primer acceso.
- **Ayuda Integrada:** La interfaz debe incluir retroalimentación visual y mensajes de error, en caso que lo haya.

---

## Requisitos

### Requisitos funcionales

| ID | Requisito Funcional | Prioridad (MoSCoW) | Verificabilidad |
|----|----------------------|--------------------|----------------|
| **Gestión de Autenticación y Cuentas de Usuario** |  |  |  |
| RF-01 | Proporcionar un método de registro: correo/contraseña. | Must Have | Verificable |
| RF-02 | Implementar funcionalidad de inicio de sesión mediante el método: correo/contraseña. | Should Have | Parcialmente verificable (únicamente simulable). |
| RF-03 | Proporcionar funcionalidad de eliminación permanente de cuenta. | Should Have | Parcialmente verificable (únicamente simulable, porque no guardamos cuentas). |
| **Interfaz de Usuario y Experiencia** |  |  |  |
| RF-04 | Ejecutar un tutorial interactivo obligatorio en el primer acceso. | Must Have | Verificable |
| RF-05 | Acceder a un apartado de progreso, estadísticas de rendimiento y puntuación. | Must Have | Parcialmente verificable (no existe base de datos para guardar progreso). |
| RF-06 | Proporcionar opciones de accesibilidad (ajuste de tamaño de fuente y configuraciones de contraste). | Should Have | Verificable |
| **Contenido Educativo y Estructura Curricular** |  |  |  |
| RF-07 | Acceder a lecciones estructuradas y progresivas que guíen desde nivel básico hasta avanzado. | Must Have | Verificable |
| RF-08 | Acceder a diversos tipos de ejercicios interactivos: completar oraciones y selección múltiple. | Must Have | Verificable |
| RF-09 | Permitir la repetición ilimitada de lecciones y ejercicios completados. | Must Have | Verificable |
| **Mascota Interactiva** |  |  |  |
| RF-10 | Incluir una mascota digital visible en la interfaz principal de la aplicación al igual que su apartado específico. | Should Have | Verificable |
| **Compras dentro de Mayapprendo** |  |  |  |
| RF-11 | Mostrar una sección visual de tienda dentro de la app que presente elementos disponibles. | Could Have | Verificable |

---

### Requisitos no funcionales

| ID | Requisito No Funcional (RNF) | Prioridad | Verificabilidad |
|----|-------------------------------|------------|----------------|
| **Usabilidad** |  |  |  |
| RNF-01 | El diseño debe seguir principios de accesibilidad, incluyendo tipografía legible y botones grandes para los diversos dispositivos. | Must Have | Verificable |
| RNF-02 | Organizar el contenido en módulos temáticos progresivos (saludos, familia, números, etc.). | Must Have | Verificable |
| **Compatibilidad** |  |  |  |
| RNF-03 | La aplicación debe adaptarse a pantallas de distinto tamaño para dispositivos móviles, tablets o computadoras. | Must Have | Verificable |
| **Disponibilidad** |  |  |  |
| RNF-04 | En caso de error, debe mostrar un mensaje corto mencionando que hubo un error, adjuntando una imagen de la mascota y ofrecer una opción para regresar al inicio. | Should Have | Verificable |
| **Localización** |  |  |  |
| RNF-05 | La aplicación debe estar disponible en español. | Must Have | Verificable |

---

## Referencias

- Andreu, I. (2024, 3 octubre). *Lean Manufacturing: ¿qué es y cuáles son sus principios?* APD España. https://www.apd.es/lean-manufacturing-que-es/  
- DiagramasUML. (s.f.). *Diagrama de casos de uso.* https://diagramasuml.com/casos-de-uso/  
- Team Asana. (2025, 8 de enero). *Cómo redactar un documento de requisitos de software (incluye una plantilla).* https://asana.com/es/resources/software-requirement-document-template  
- TIC Portal. (2022, 26 septiembre). *Método MOSCOW.* TIC Portal. https://www.ticportal.es/glosario-tic/metodo-moscow  
- UNESCO. (2022). *Decenio Internacional de las Lenguas Indígenas (2022-2032).* https://www.unesco.org/es/decades/indigenous-languages  
