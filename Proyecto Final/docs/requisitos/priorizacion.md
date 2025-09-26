# Priorización

Para determinar la prioridad de los requerimientos y las historias de usuario, se
utilizará el modelo MoSCoW (Must have, Should have, Could have, Won't have)

## Must Have
Requisitos esenciales que permiten el funcionamiento básico del software. Se
priorizó la seguridad mínima y todo aquello referente al registro, acceso, aprendizaje
del vocabulario/gramática, pronunciación, práctica de ejercicios y retroalimentación
inmediata.

| ID | Descripción |
|----|-------------|
| RF-01.1 | Métodos de registro (correo electrónico y Auth). |
| RF-01.2 | Recuperación de contraseñas. |
| RF-01.4 | Sincronización automática del progreso en múltiples dispositivos. |
| RF-02.1 | Presentación obligatoria de la política de privacidad. |
| RF-02.3 | Eliminación permanente de cuenta y datos. |
| RF-03.1 | Tutorial interactivo obligatorio en el primer acceso. |
| RF-03.4 | Indicadores visuales de progreso, estadísticas y retroalimentación. |
| RF-04.1 | Lecciones estructuradas y progresivas. |
| RF-04.2 | Pronunciación auténtica del maya yucateco por hablantes nativos. |
| RF-04.3 | Lecciones interactivas y dinámicas. |
| RF-04.6 | Ejercicios variados (traducción, completar oraciones, selección múltiple, etc.). |
| RF-04.7 | Organización de contenidos en módulos temáticos progresivos. |
| RF-04.8 | Explicaciones gramaticales contextuales. |
| RF-05.1 | Sistema integral de puntuación y logros. |
| RF-05.2 | Repetición ilimitada de lecciones. |
| RF-05.3 | Registro de rachas diarias y notificaciones configurables. |
| RF-06.1 | Reconocimiento de voz con lA. |
| RF-06.3 | Retroalimentación inmediata y específica en pronunciación. |
| RF-07.1 | Descarga progresiva de lecciones. |
| RF-07.2 | Funcionalidad offline de lecciones descargadas. |
| RF-07.3 | Adaptación dinámica de calidad de contenido según conectividad y dispositivo. |
- La interfaz debe ser intuitiva y accesible para todas las edades, con navegación clara y retroalimentación visual.
- El diseño debe seguir principios de accesibilidad, incluyendo tipografía legible y botones grandes.
- La aplicación debe cargar las lecciones en menos de 5 segundos en condiciones de red estable.
- Los audios deben reproducirse sin interrupciones ni retrasos perceptibles.
- Debe funcionar en dispositivos Android (9.0+), iOS (13+) y Windows (10+).
- La aplicación debe adaptarse a pantallas de distintos tamaños (móviles, tablets, computadoras).
- Toda la información del usuario (progreso, perfil, preferencias) debe almacenarse de forma segura y cifrada.
- El sistema debe prevenir accesos no autorizados mediante autenticación básica (correo y contraseña o acceso por redes sociales).
- No se debe recopilar información sensible sin consentimiento explícito del usuario.

## Should Have
Requisitos que permiten que el software se sienta más accesible, inclusivo y
cómodo, además de enriquecer el aprendizaje y ajustarse a los gustos del usuario.

| ID | Descripción |
|----|-------------|
| RF-02.2 | Exportación de datos personales en formato estándar. |
| RF-03.2 | Opciones de accesibilidad (ajuste de fuente y contraste). |
| RF-03.3 | Adaptación automática de la interfaz a dispositivo y sistema operativo. |
| RF-04.4 | Inclusión de contenido cultural auténtico. |
| RF-06.2 | Filtrado de ruido y precisión fonética en la lA. |
| RF-11.2 | Subtítulos opcionales para todo el contenido en audio. |
| RF-11.3 | Control de velocidad de reproducción de audio. |
- La arquitectura debe permitir agregar nuevas lecciones, módulos o variantes lingüísticas sin afectar el rendimiento general.
- En caso de caída, debe mostrar un mensaje de error amigable y ofrecer una opción para reintentar.
- Las actualizaciones deben poder implementarse sin necesidad de reinstalar la aplicación.

## Could Have
Requisitos que mejoran la experiencia a nivel motivacional y perfectas para seguir
un progreso, mas no son esenciales para el aprendizaje inicial y no afectan en la
utilidad básica del software.

| ID | Descripción |
|----|-------------|
| RF-01.3 |  Autenticación multifactor opcional. |
| RF-01.5 |  Exportación e importación de progreso mediante archivos. |
| RF-05.4 |  Insignias y reconocimientos. |
| RF-08.3 |  Compartir logros en redes sociales externas. |
| RF-09.3 |  Reportes detallados de progreso por habilidades. |
| RF-09.4 |  Recomendaciones personalizadas de mejora. |
| RF-11.1 |  Múltiples temas visuales y modo nocturno. |
- Debe soportar hasta 20,000 usuarios activos simultáneamente sin degradación significativa.
- El código debe estar documentado y modularizado para facilitar futuras actualizaciones y correcciones.
- Los contenidos culturales deben adaptarse al contexto de Yucatán, respetando la cultura maya.

## Won't Have
No se consideran para esta fase debido a su complejidad o gran desviación del
enfoque principal, tales como interacciones sociales o expansiones culturales
extensas.

| ID | Descripción |
|----|-------------|
| RF-04.9 | Diccionario interactivo español-maya. |
| RF-05.5 | Tablas de clasificación para competencias entre usuarios. |
| RF-05.6 | Sistema de vidas/energías regenerables. |
| RF-05.7 | Desafíos semanales temáticos. |
| RF-08.1 | Conexiones entre usuarios |
| RF-08.2 | Foros de discusión culturales |
| RF-09.1 | Flashcards personalizables. |
| RF-09.2 | Práctica intensiva y evaluaciones de preparación. |
| RF-10.1 | Contenido cultural multimedia. |
| RF-10.2 | Variantes dialectales con identificación geográfica. |
| RF-10.3 | Contenido cultural avanzado. |
- La app debe estar disponible en español e inglés, con posibilidad de agregar más idiomas en el futuro.
