# Requisitos Funcionales

| **ID** | **Requisito Funcional** | **Prioridad (MoSCoW)** |
|:-------|:------------------------|:-----------------------:|
| **RF-01** | Gestión de Autenticación y Cuentas de Usuario | Must Have |
| **RF-01.1** | Proporcionar múltiples métodos de registro: correo electrónico/contraseña y autenticación OAuth (Google, Facebook, Apple ID). | Must Have |
| **RF-01.2** | Implementar funcionalidad de recuperación de contraseñas mediante verificación por correo electrónico. | Should Have |
| **RF-01.3** | El sistema deberá guardar localmente el progreso del usuario en su dispositivo y permitir la sincronización manual con la nube. | Must Have |
| **RF-01.4** | Soportar autenticación multifactor opcional (SMS, aplicaciones TOTP, códigos PIN). | Could Have |
| **RF-01.5** | Proporcionar funcionalidad de exportación e importación del progreso mediante archivos de respaldo. | Could Have |
| **RF-02** | Gestión de Privacidad y Datos Personales | Must Have |
| **RF-02.1** | Presentar obligatoriamente la política de privacidad durante el proceso de registro. | Must Have |
| **RF-02.2** | Proporcionar funcionalidad de eliminación permanente de cuenta y todos los datos. | Must Have |
| **RF-02.3** | Permitir la exportación completa de datos personales y progreso en formato estándar. | Should Have |
| **RF-03** | Interfaz de Usuario y Experiencia | Must Have |
| **RF-03.1** | Ejecutar un tutorial interactivo obligatorio en el primer acceso. | Should Have |
| **RF-03.2** | Mostrar indicadores visuales de progreso, estadísticas de rendimiento y retroalimentación en el panel principal. | Must Have |
| **RF-03.3** | Proporcionar opciones de accesibilidad (ajuste de tamaño de fuente y configuraciones de contraste). | Should Have |
| **RF-03.4** | Adaptar automáticamente la interfaz según el sistema operativo, resolución de pantalla y tipo de dispositivo. | Should Have |
| **RF-04** | Contenido Educativo y Estructura Curricular | Must Have |
| **RF-04.1** | Presentar lecciones estructuradas y progresivas que guíen desde nivel básico hasta avanzado. | Must Have |
| **RF-04.2** | Incorporar pronunciación auténtica del maya yucateco mediante grabaciones de hablantes nativos certificados. | Must Have |
| **RF-04.3** | Ofrecer lecciones interactivas y dinámicas. | Must Have |
| **RF-04.4** | Implementar diversos tipos de ejercicios: traducción bidireccional, completar oraciones, selección múltiple, etc. | Must Have |
| **RF-04.5** | Organizar el contenido en módulos temáticos progresivos (saludos, familia, números, etc.). | Must Have |
| **RF-04.6** | El sistema deberá mostrar ejemplos gramaticales básicos del maya yucateco asociados a cada palabra o frase dentro de la lección, en formato de texto o nota emergente, para facilitar la comprensión del uso en contexto. | Should Have |
| **RF-04.7** | Incluir contenido cultural auténtico que contextualice el aprendizaje dentro de la tradición maya yucateca. | Should Have |
| **RF-05** | Sistema de Gamificación y Motivación | Must Have |
| **RF-05.1** | Implementar un sistema integral de puntuación y logros. | Must Have |
| **RF-05.2** | Permitir la repetición ilimitada de lecciones y ejercicios completados. | Must Have |
| **RF-05.3** | Mantener registro de rachas diarias de estudio y enviar notificaciones de recordatorio configurables por horario y frecuencia. | Must Have |
| **RF-05.4** | Otorgar insignias y reconocimientos por alcanzar objetivos específicos. | Could Have |
| **RF-06** | Optimización de Rendimiento y Conectividad | Must Have |
| **RF-06.1** | Implementar descarga progresiva y automática de lecciones según el avance del usuario. | Should Have |
| **RF-06.2** | Proporcionar funcionalidad offline completa para lecciones previamente descargadas. | Should Have |
| **RF-06.3** | Adaptar dinámicamente la calidad y peso del contenido según las condiciones de conectividad y capacidad del dispositivo. | Should Have |
| **RF-07** | Herramientas de Estudio Avanzadas | Should Have |
| **RF-07.1** | El sistema descargará automáticamente las próximas 3 lecciones basándose en el progreso actual del usuario. | Could Have |
| **RF-07.2** | Proporcionar recomendaciones personalizadas de áreas de mejora. | Could Have |
| **RF-08** | Personalización y Accesibilidad Avanzada | Must Have |
| **RF-08.1** | El sistema deberá mostrar subtítulos opcionales en las pantallas que incluyan contenido de audio o pronunciación, con la posibilidad de activar o desactivar la visualización del texto que transcriba o traduzca el audio del maya yucateco al español. | Should Have |
| **RF-08.2** | Permitir control de velocidad de reproducción de audio con rango configurable. | Should Have |
| **RF-09** | Mascota interactiva | Should Have |
| **RF-09.1** | Incluir una mascota digital visible en la interfaz principal de la aplicación. | Must Have |
| **RF-09.2** | La mascota reaccionará visualmente según el progreso o las acciones del usuario. | Must Have |
| **RF-09.3** | Permitir que la mascota brinde mensajes de motivación o consejos breves durante las lecciones. | Could Have |
| **RF-09.4** | Asociar la mascota al sistema de recompensas, desbloqueando accesorios o personalizaciones al cumplir metas de estudio. | Could Have |
| **RF-10** | Compras dentro de Mayapprendo | Must Have |
| **RF-10.1** | Mostrar una sección visual de tienda dentro de la app que presente elementos disponibles. | Should Have |
| **RF-10.2** | El sistema debe permitir realizar transacciones reales y mostrar al usuario un mensaje de confirmación del pago exitoso o fallido, proporcionando información clara sobre el estado de la compra y los pasos a seguir en caso de error. | Must Have |
| **RF-10.3** | Cada transacción debe ser validada por el sistema para garantizar su autenticidad y evitar operaciones duplicadas o fraudulentas. El sistema deberá verificar el estado de la conexión, el método de pago y la confirmación del servidor antes de completar la compra. | Must Have |
| **RF-10.4** | Todas las operaciones de pago deben realizarse mediante protocolos de seguridad cifrados (como HTTPS y TLS) para proteger los datos financieros del usuario. Además, los métodos de pago deben cumplir con estándares de seguridad reconocidos (como PCI DSS). | Must Have |