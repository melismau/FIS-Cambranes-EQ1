# Mayapprendo - App de Aprendizaje de la Lengua Maya

## Tabla de Contenidos
- [Descripción del Proyecto](#descripción-del-proyecto)
- [Propósito y Justificación](#propósito-y-justificación)
- [Propuesta de Valor](#propuesta-de-valor)
- [Usuarios y Clientes](#usuarios-y-clientes)
- [Características Principales](#características-principales)
- [Requisitos del Sistema](#requisitos-del-sistema)
- [Arquitectura y Tecnologías](#arquitectura-y-tecnologías)
- [Instalación y Configuración](#instalación-y-configuración)
- [Metodología de Desarrollo](#metodología-de-desarrollo)
- [Contribución al Proyecto](#contribución-al-proyecto)

## Descripción del Proyecto

Mayapprendo es una aplicación móvil y de escritorio multiplataforma diseñada para facilitar el aprendizaje autónomo, divertido y accesible de la lengua maya yucateca. El proyecto emplea metodologías de gamificación, ejercicios interactivos y contenido cultural auténtico para crear una experiencia de aprendizaje integral que preserve y revitalice este patrimonio lingüístico de la Península de Yucatán.

### Estado del Proyecto
- **Fase:** Proof of Concept (PoC)
- **Plataformas objetivo:** Android 9.0+, iOS 13+, Windows 10+

## Propósito y Justificación

La lengua maya representa un patrimonio cultural invaluable que enfrenta riesgos crecientes de desaparición debido a la carencia de recursos educativos modernos y atractivos para las nuevas generaciones. Este proyecto surge como respuesta a la necesidad crítica de herramientas digitales que:

- Revitalicen el idioma maya yucateco mediante tecnología educativa moderna
- Promuevan la inclusión y el respeto hacia las lenguas originarias
- Fortalezcan la identidad regional conectando a los usuarios con su herencia ancestral
- Proporcionen una experiencia integral y actualizada que actualmente no existe en iniciativas digitales similares

## Propuesta de Valor

### Valor Principal
La aplicación ofrece una experiencia de aprendizaje única que combina tecnología educativa avanzada con respeto cultural profundo, proporcionando:

#### Características Diferenciadas
- **Más de 50 lecciones gamificadas** estructuradas progresivamente desde nivel básico hasta avanzado
- **Pronunciación auténtica** mediante grabaciones de hablantes nativos certificados del maya yucateco
- **Sistema de reconocimiento de voz con IA** para evaluación precisa de pronunciación
- **Contenido cultural contextual** que incluye tradiciones, mitos y cosmovisión maya
- **Interfaz adaptativa** con elementos visuales inspirados en la cultura maya
- **Funcionalidad offline completa** para lecciones previamente descargadas

#### Impacto Social
- Preservación activa de patrimonio lingüístico intangible
- Democratización del acceso al conocimiento cultural maya
- Fortalecimiento de la identidad regional yucateca
- Apoyo a comunidades indígenas en la transmisión intergeneracional del conocimiento

## Usuarios y Clientes

### Perfiles de Usuario Principal

#### 1. Estudiantes (Secundaria, Preparatoria, Universidad)
- **Necesidad:** Ampliar conocimiento cultural y académico mediante adquisición de vocabulario y expresiones maya
- **Uso esperado:** Recurso didáctico complementario para estudios académicos

#### 2. Jóvenes y Adultos Interesados en Cultura Maya
- **Necesidad:** Aprendizaje autodidacta como parte de identidad o interés cultural
- **Uso esperado:** Utilización en tiempo libre para dominio progresivo de la lengua

#### 3. Educadores y Profesores
- **Necesidad:** Recurso digital para apoyo en enseñanza de lengua y cultura maya
- **Uso esperado:** Integración en clases como herramienta o evaluación complementaria

#### 4. Hablantes Nativos de Lengua Maya
- **Necesidad:** Reforzar, difundir y compartir su lengua con nuevas generaciones
- **Uso esperado:** Medio de preservación lingüística y apoyo en enseñanza comunitaria

### Clientes y Beneficiarios

#### Clientes Potenciales
- **Gobierno del Estado de Yucatán:** Interesado en preservación cultural regional
- **Universidad Autónoma de Yucatán (UADY):** Institución académica para integración en programas educativos

#### Beneficiarios Directos
- **Comunidades Mayas:** Herramienta para mayor visualización y difusión de su lengua
- **Usuarios Individuales:** Estudiantes, educadores y público general con acceso didáctico al idioma

#### Beneficiarios Indirectos
- **Organizaciones Culturales y ONGs:** Promoción de lengua y cultura maya
- **Turistas Nacionales e Internacionales:** Conocimiento de expresiones básicas para mejora de experiencia regional
- **Sociedad General:** Preservación de patrimonio intangible de México

## Características Principales

### Funcionalidades Core
- **Sistema de Lecciones Progresivas:** Más de 50 lecciones estructuradas desde nivel básico hasta avanzado
- **Ejercicios Interactivos:** Traducción bidireccional, completar oraciones, selección múltiple, dictado, arrastrar y soltar
- **Audio Auténtico:** Pronunciación grabada por hablantes nativos certificados del maya yucateco
- **Reconocimiento de Voz con IA:** Evaluación automática de pronunciación con retroalimentación específica
- **Gamificación Integral:** Sistema de puntuación, logros, insignias y seguimiento de rachas diarias
- **Contenido Cultural:** Módulos temáticos que incluyen tradiciones, mitos y cosmovisión maya yucateca

### Funcionalidades Técnicas
- **Funcionalidad Offline:** Acceso completo a lecciones previamente descargadas
- **Sincronización Multi-dispositivo:** Progreso automático entre Android, iOS y Windows
- **Adaptabilidad de Interfaz:** Ajuste automático a diferentes tamaños de pantalla y sistemas operativos
- **Descarga Progresiva:** Contenido descargado según avance del usuario para optimizar almacenamiento

## Requisitos del Sistema

### Requisitos Mínimos

#### Plataformas Soportadas
- **Android:** Versión 9.0 o superior
- **iOS:** Versión 13.0 o superior  
- **Windows:** Versión 10 o superior

#### Especificaciones de Hardware
- **Memoria RAM:** Mínimo 2GB recomendado
- **Almacenamiento:** 500MB disponibles para instalación inicial
- **Conectividad:** Internet requerida para descargas iniciales y actualizaciones
- **Audio:** Altavoces o auriculares para contenido sonoro
- **Micrófono:** Requerido para ejercicios de pronunciación

### Requisitos de Conectividad
- **Conexión Inicial:** Internet necesaria para descarga e instalación
- **Actualizaciones:** Conectividad periódica para nuevos contenidos y mejoras
- **Uso Offline:** Funcionalidad completa sin internet para contenido previamente descargado

## Arquitectura y Tecnologías

### Arquitectura de Sistema
La aplicación implementa una arquitectura modular multiplataforma que permite escalabilidad y mantenimiento eficiente:

- **Frontend Multiplataforma:** Framework común para Android, iOS y Windows
- **Backend de Contenidos:** Gestión centralizada de lecciones, ejercicios y evaluaciones
- **Sistema de IA:** Módulo especializado para reconocimiento y evaluación de pronunciación
- **Base de Datos Local:** Almacenamiento offline de progreso y contenidos descargados
- **Servicio de Sincronización:** Gestión de datos entre dispositivos y plataformas

### Consideraciones de Seguridad
- **Cifrado de Datos:** Toda información de usuario almacenada de forma segura y cifrada
- **Autenticación Multi-factor:** Opcional mediante SMS, TOTP o códigos PIN
- **Privacidad por Diseño:** No recopilación de información sensible sin consentimiento explícito
- **Cumplimiento Normativo:** Adherencia a políticas de privacidad y protección de datos

## Instalación y Configuración

### Instalación para Usuarios Finales
1. **Android:** Descarga desde Google Play Store
2. **iOS:** Descarga desde App Store  
3. **Windows:** Descarga desde Microsoft Store o instalador directo

### Configuración Inicial
1. **Registro de Usuario:** Creación de cuenta mediante email/contraseña o OAuth
2. **Tutorial Interactivo:** Introducción obligatoria a funcionalidades principales
3. **Configuración de Perfil:** Selección de nivel inicial y preferencias de aprendizaje
4. **Descarga de Contenidos:** Selección y descarga de lecciones iniciales

## Metodología de Desarrollo

### Framework Metodológico
El proyecto emplea principios de **Lean Manufacturing** adaptados al desarrollo de software, complementados con metodologías ágiles:

#### Principios Lean Aplicados
- **Just-in-Time:** Desarrollo de funcionalidades cuando realmente agregan valor al usuario
- **Flujo Continuo:** Organización del trabajo evitando cuellos de botella en el pipeline de desarrollo  
- **Mejora Continua:** Revisión constante de procesos para optimización de resultados
- **Eliminación de Desperdicios:** Priorización de actividades que maximizan valor al cliente

#### Metodología Ágil
- **Entregas Incrementales:** Desarrollo iterativo con entregables funcionales frecuentes
- **Revisiones Continuas:** Adaptación constante según retroalimentación y necesidades del cliente
- **Colaboración Activa:** Comunicación constante entre miembros del equipo
- **Respuesta al Cambio:** Flexibilidad para ajustes en requisitos y prioridades

### Priorización de Requisitos
Implementación del modelo **MoSCoW** para clasificación de requisitos:

- **Must Have (Esencial):** Funcionalidades críticas para operación básica del software
- **Should Have (Importante):** Características que mejoran accesibilidad, inclusión y experiencia de usuario
- **Could Have (Deseable):** Funcionalidades que enriquecen la experiencia motivacional sin afectar utilidad básica
- **Won't Have (No Incluido):** Características excluidas de la fase actual por complejidad o desviación del enfoque principal

## Contribución al Proyecto

### Estructura del Equipo

#### Roles y Responsabilidades
- **Líder de Proyecto:** [Danna Sansores](https://github.com/dannasansores) - Propuesta de valor y métrica de contribución individual
- **Desarrollador Backend:** [Leonardo Isaías](https://github.com/manriqueespinosaleonardo) - Descripción de productos y requisitos no funcionales  
- **Especialista en Procesos:** [Maru Perdomo](https://github.com/marunui) - Priorización y descripción del proceso
- **Analista de Negocio:** [Octavio Pérez](https://github.com/octavpg) - Usuarios/clientes y gestión del proceso
- **Documentalista:** [Eli Scott](https://github.com/melismau) - Organización, documentación del repositorio y requisitos funcionales
- **Diseñador:** [Eithel Soberanis](https://github.com/eithelsoberanis-coder) - Formato de presentación y artefactos

### Métrica de Contribución Individual
La distribución de responsabilidades se basa en una división equitativa del 100% de las actividades del proyecto:

- **Líder de Proyecto:** XX% - Coordinación general y propuesta de valor
- **Desarrollador Backend:** XX% - Arquitectura técnica y requisitos no funcionales
- **Especialista en Procesos:** XX% - Metodología y priorización de requisitos
- **Analista de Negocio:** XX% - Análisis de usuarios y gestión de procesos
- **Documentalista:** XX% - Requisitos funcionales y documentación técnica
- **Diseñador:** XX% - Presentación visual y artefactos

### Proceso de Contribución
1. **Asignación de Tareas:** Distribución según especialización y capacidad del equipo
2. **Desarrollo Incremental:** Entregables parciales con revisión continua
3. **Integración Colaborativa:** Consolidación de componentes individuales en producto cohesivo
4. **Validación Cruzada:** Revisión mutua de entregables para asegurar calidad y consistencia

---

## Enlaces de Documentación Adicional

Para información detallada sobre aspectos específicos del proyecto, consulte la documentación especializada en el repositorio:

- **[Requisitos Funcionales](./docs/requisitos/requisitos-funcionales.md)**
- **[Requisitos no Funcionales](./docs/requisitos/requisitos-no-funcionales.md)**
- **[Casos de Uso e Historias de Usuario](./docs/requisitos/casos-de-uso.md)**
- **[Metodología de Desarrollo](./docs/gestion-del-proyecto/metodologia.md)**

**Universidad Autónoma de Yucatán**  
**Facultad de Matemáticas - Ingeniería de Software**  
**Fundamentos de Ingeniería de Software**  
**Período: Agosto-Diciembre 2025**
