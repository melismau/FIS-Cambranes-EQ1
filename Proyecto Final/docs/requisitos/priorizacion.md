# Priorización

Para determinar la prioridad de los requerimientos y las historias de usuario, se
utilizará el modelo MoSCoW (Must have, Should have, Could have, Won't have)

## Must Have
Requisitos esenciales que permiten el funcionamiento básico del software. Se
priorizó la seguridad mínima y todo aquello referente al registro, acceso, aprendizaje
del vocabulario/gramática, pronunciación, práctica de ejercicios y retroalimentación
inmediata.

### **Requisitos Funcionales**
- **RF-01:** Proporcionar un método de registro: correo/contraseña.  
  *Verificabilidad:* Verificable.  
- **RF-04:** Ejecutar un tutorial interactivo obligatorio en el primer acceso.  
  *Verificabilidad:* Verificable.  
- **RF-05:** Acceder a un apartado de progreso, estadísticas de rendimiento y puntuación.  
  *Verificabilidad:* Parcialmente verificable (no existe base de datos para guardar progreso).  
- **RF-07:** Acceder a lecciones estructuradas y progresivas que guíen desde nivel básico hasta avanzado.  
  *Verificabilidad:* Verificable.  
- **RF-08:** Acceder a diversos tipos de ejercicios interactivos: completar oraciones y selección múltiple.  
  *Verificabilidad:* Verificable.  
- **RF-09:** Permitir la repetición ilimitada de lecciones y ejercicios completados.  
  *Verificabilidad:* Verificable.  

### **Requisitos No Funcionales**
- **RNF-01:** El diseño debe seguir principios de accesibilidad, incluyendo tipografía legible y botones grandes para los diversos dispositivos.  
  *Verificabilidad:* Verificable.  
- **RNF-02:** Organizar el contenido en módulos temáticos progresivos (saludos, familia, números, etc.).  
  *Verificabilidad:* Verificable.  
- **RNF-03:** La aplicación debe adaptarse a pantallas de distinto tamaño para dispositivos móviles, tablets o computadoras.  
  *Verificabilidad:* Verificable.  
- **RNF-05:** La aplicación debe estar disponible en español.  
  *Verificabilidad:* Verificable.  

## Should Have
Requisitos que permiten que el software se sienta más accesible, inclusivo y
cómodo, además de enriquecer el aprendizaje y ajustarse a los gustos del usuario.

### **Requisitos Funcionales**
- **RF-02:** Implementar funcionalidad de inicio de sesión mediante el método: correo/contraseña.  
  *Verificabilidad:* Parcialmente verificable (únicamente simulable).  
- **RF-03:** Proporcionar funcionalidad de eliminación permanente de cuenta.  
  *Verificabilidad:* Parcialmente verificable (únicamente simulable, porque no guardamos cuentas).  
- **RF-06:** Proporcionar opciones de accesibilidad (ajuste de tamaño de fuente y configuraciones de contraste).  
  *Verificabilidad:* Verificable.  
- **RF-10:** Incluir una mascota digital visible en la interfaz principal de la aplicación al igual que su apartado específico.  
  *Verificabilidad:* Verificable.  

### **Requisitos No Funcionales**
- **RNF-04:** En caso de error, debe mostrar un mensaje corto mencionando que hubo un error, adjuntando una imagen de la mascota y ofrecer una opción para regresar al inicio.  
  *Verificabilidad:* Verificable.  

## Could Have
Requisitos que mejoran la experiencia a nivel motivacional y perfectas para seguir
un progreso, mas no son esenciales para el aprendizaje inicial y no afectan en la
utilidad básica del software.

### **Requisitos Funcionales**
- **RF-11:** Mostrar una sección visual de tienda dentro de la app que presente elementos disponibles.  
  *Verificabilidad:* Verificable.  

## Won't Have
No se consideran para esta fase debido a su complejidad o gran desviación del
enfoque principal, tales como interacciones sociales o expansiones culturales
extensas.

- Descartamos los requisitos anteriores que no están en la fase actual del proyecto.