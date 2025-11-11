# Casos de uso

## Caso de uso 1: Proporcionar un método de registro (correo/contraseña)
**Actor:** Usuario nuevo  
**Descripción:** El usuario crea una cuenta proporcionando sus datos básicos para acceder a la aplicación.  

**Flujo principal:**
1. El usuario selecciona la opción “Registrarse”.
2. Ingresa nombre, correo y contraseña.
3. El sistema valida los datos.
4. El sistema crea la cuenta y muestra un mensaje de bienvenida.

**Flujo alterno:**  
Si el correo ya está registrado, el sistema muestra un mensaje indicando que debe iniciar sesión.

---

## Caso de uso 2: Implementar funcionalidad de inicio de sesión
**Actor:** Usuario  
**Descripción:** El usuario accede a su cuenta para continuar con su progreso de aprendizaje.  

**Flujo principal:**
1. El usuario abre la aplicación.
2. Selecciona la opción “Iniciar sesión”.
3. Ingresa su correo y contraseña.
4. El sistema valida los datos.
5. El usuario accede a su perfil.

**Flujo alterno:**  
Si las credenciales son incorrectas, el sistema muestra un mensaje de error y solicita reintentar.

---

## Caso de uso 3: Eliminar cuenta permanentemente
**Actor:** Usuario  
**Descripción:** El usuario puede eliminar su cuenta de manera permanente desde la configuración de su perfil.  

**Flujo principal:**
1. El usuario accede al apartado de configuración.
2. Selecciona “Eliminar cuenta”.
3. El sistema muestra un mensaje de confirmación.
4. El usuario confirma la eliminación.
5. El sistema borra los datos y muestra un mensaje final.

**Flujo alterno:**  
Si el usuario cancela, la cuenta se conserva sin cambios.

---

## Caso de uso 4: Ejecutar un tutorial interactivo obligatorio
**Actor:** Usuario nuevo  
**Descripción:** El usuario realiza un tutorial para aprender las funciones de la app en su primer acceso.  

**Flujo principal:**
1. El usuario selecciona “Comenzar tutorial”.
2. El sistema explica las funciones básicas.
3. El usuario realiza ejercicios de práctica.
4. El usuario finaliza el tutorial.

**Flujo alterno:**  
Si el usuario elige omitir, se le redirige al inicio.

---

## Caso de uso 5: Consultar progreso y estadísticas
**Actor:** Usuario  
**Descripción:** El usuario puede acceder a un apartado donde se muestran sus avances y puntuaciones.  

**Flujo principal:**
1. Selecciona la opción “Mi progreso”.
2. El sistema muestra gráficas o porcentajes.
3. El usuario revisa su rendimiento general.

**Flujo alterno:**  
Si no hay progreso, el sistema muestra el mensaje: *“¡Comienza tu primera lección!”*

---

## Caso de uso 6: Ajustar opciones de accesibilidad
**Actor:** Usuario  
**Descripción:** El usuario puede modificar la interfaz con opciones de accesibilidad.  

**Flujo principal:**
1. El usuario abre *Configuración*.
2. Selecciona “Accesibilidad”.
3. Ajusta tamaño de fuente y contraste.
4. El sistema aplica y guarda los cambios.

**Flujo alterno:**  
Si el usuario restablece la configuración, el sistema vuelve a los valores predeterminados.

---

## Caso de uso 7: Acceder a lecciones estructuradas
**Actor:** Usuario  
**Descripción:** El usuario accede al contenido educativo organizado por niveles.  

**Flujo principal:**
1. Selecciona el módulo “Lecciones”.
2. El sistema muestra los niveles.
3. El usuario elige una lección.
4. El sistema despliega el contenido interactivo.

**Flujo alterno:**  
Si no ha iniciado sesión, el sistema solicita hacerlo.

---

## Caso de uso 8: Realizar ejercicios interactivos
**Actor:** Usuario  
**Descripción:** El usuario realiza actividades prácticas para reforzar lo aprendido.  

**Flujo principal:**
1. Accede a una lección.
2. Selecciona un ejercicio.
3. El sistema muestra preguntas o actividades.
4. El usuario responde.
5. El sistema muestra la calificación obtenida.

**Flujo alterno:**  
Si no completa el ejercicio, se guarda el progreso parcial.

---

## Caso de uso 9: Repetir lecciones y ejercicios completados
**Actor:** Usuario  
**Descripción:** El usuario puede volver a realizar lecciones o ejercicios ya completados.  

**Flujo principal:**
1. Accede a “Lecciones completadas”.
2. Selecciona la lección a repetir.
3. El sistema carga nuevamente el contenido.
4. El usuario repite las actividades.

**Flujo alterno:**  
Si cancela la acción, el sistema vuelve al menú anterior.

---

## Caso de uso 10: Interactuar con la mascota virtual
**Actor:** Usuario  
**Descripción:** El usuario puede cuidar y jugar con su mascota virtual como parte del sistema de recompensas.  

**Flujo principal:**
1. Selecciona “Mi mascota”.
2. El sistema muestra su estado y opciones.
3. El usuario puede alimentarla o jugar.
4. El sistema otorga recompensas.

**Flujo alterno:**  
Si no ha completado las lecciones necesarias, se bloquean algunas funciones.

---

## Caso de uso 11: Realizar compras dentro de la aplicación
**Actor:** Usuario  
**Descripción:** El usuario adquiere monedas o recursos dentro de la app.  

**Flujo principal:**
1. Accede a la tienda.
2. Selecciona “Comprar monedas”.
3. El sistema muestra el costo.
4. El usuario confirma la compra.
5. El sistema agrega las monedas a su cuenta.

**Flujo alterno:**  
Si ocurre un error, el sistema cancela la transacción.
