# 📘 Casos de uso – Aplicación *Mayapprendo*

---

## 🧩 Caso de uso 1: Registrarse en la aplicación
**Actor:** Usuario nuevo  
**Descripción:** El usuario crea una cuenta proporcionando sus datos básicos para acceder a la aplicación.

### Flujo principal:
1. El usuario selecciona la opción “Registrarse”.  
2. Ingresa nombre, correo y contraseña.  
3. El sistema valida los datos.  
4. El sistema crea la cuenta y muestra un mensaje de bienvenida.

### Flujo alterno:
- Si el correo ya está registrado, el sistema muestra un mensaje indicando que debe iniciar sesión.

---

## 🔑 Caso de uso 2: Iniciar sesión
**Actor:** Usuario  
**Descripción:** El usuario accede a su cuenta para continuar con su progreso de aprendizaje.

### Flujo principal:
1. El usuario abre la aplicación.  
2. Selecciona la opción “Iniciar sesión”.  
3. Ingresa su correo y contraseña.  
4. El sistema valida los datos.  
5. El usuario accede a su perfil.

### Flujo alterno:
- Si las credenciales son incorrectas, el sistema muestra un mensaje de error y solicita reintentar.

---

## 📖 Caso de uso 3: Acceder a un tutorial
**Actor:** Usuario nuevo  
**Descripción:** El usuario realiza un tutorial para aprender las funciones de la app.

### Flujo principal:
1. El usuario selecciona “Comenzar tutorial”.  
2. El sistema le explica al usuario lo básico de la app y algunos términos presentes dentro de esta.  
3. El usuario realiza ejercicios de práctica.  
4. El usuario termina el tutorial.

### Flujo alterno:
- El usuario selecciona la opción de omitir tutorial, y el sistema lo envía a la página principal.

---

## 📚 Caso de uso 4: Acceder a lecciones
**Actor:** Alumno  
**Descripción:** El usuario puede acceder al contenido educativo organizado por niveles (básico, intermedio, avanzado).

### Flujo principal:
1. El usuario selecciona el módulo “Lecciones”.  
2. El sistema muestra los niveles disponibles.  
3. El usuario selecciona una lección.  
4. El sistema despliega el contenido interactivo correspondiente.

### Flujo alterno:
- Si el usuario no ha iniciado sesión, el sistema le pide hacerlo antes de acceder a las lecciones.

---

## 🧠 Caso de uso 5: Acceder a ejercicios interactivos
**Actor:** Alumno  
**Descripción:** El usuario realiza actividades prácticas para reforzar lo aprendido en las lecciones.

### Flujo principal:
1. El usuario accede a una lección.  
2. Selecciona un ejercicio.  
3. El sistema muestra preguntas o actividades (opción múltiple, arrastrar y soltar, dictado).  
4. El usuario responde los ejercicios.  
5. El sistema muestra la calificación obtenida.

### Flujo alterno:
- Si el usuario no completa el ejercicio, el sistema guarda el progreso parcial.

---

## 📈 Caso de uso 6: Consultar progreso de aprendizaje
**Actor:** Alumno  
**Descripción:** Permite al usuario visualizar sus avances, logros y estadísticas dentro de la aplicación.

### Flujo principal:
1. El usuario accede al apartado “Mi progreso”.  
2. El sistema muestra los puntos, logros y nivel actual.  
3. El usuario puede consultar detalles de cada actividad.

### Flujo alterno:
- Si el usuario no tiene registros previos, el sistema muestra un mensaje indicando que aún no hay datos de progreso.

---

## 🐾 Caso de uso 7: Acceder a la mascota virtual
**Actor:** Usuario  
**Descripción:** El usuario puede interactuar con su mascota virtual como parte del sistema de recompensas de aprendizaje.

### Flujo principal:
1. El usuario selecciona el apartado “Mi mascota”.  
2. El sistema muestra la mascota y sus estadísticas.  
3. El usuario puede alimentarla o jugar con ella.  
4. El sistema otorga puntos o recompensas según la interacción.

### Flujo alterno:
- Si el usuario no ha completado las lecciones requeridas, el sistema bloquea temporalmente ciertas funciones de la mascota.

---

## 👥 Caso de uso 8: Acceder a un grupo de estudio
**Actor:** Alumno  
**Descripción:** El usuario entra a un grupo donde se ven temas específicos y tienen un plan de estudio.

### Flujo principal:
1. El usuario selecciona la opción “Acceder a grupo”.  
2. El usuario coloca el código del grupo.  
3. Accede al grupo y ya forma parte de este.  
4. El usuario puede interactuar con las modalidades del grupo.

### Flujo alterno:
- Si el código del grupo no existe, el sistema muestra un mensaje indicando que el grupo no fue encontrado.

---

## ⚙️ Caso de uso 9: Configurar preferencias de usuario
**Actor:** Usuario  
**Descripción:** Permite ajustar las opciones personales de la aplicación (idioma, sonido, accesibilidad).

### Flujo principal:
1. El usuario abre el menú de configuración.  
2. Modifica los parámetros deseados.  
3. El sistema guarda los cambios automáticamente.

### Flujo alterno:
- Si ocurre un error al guardar, el sistema muestra un mensaje y permite reintentar.

---

## 💰 Caso de uso 10: Realizar compras de la moneda de la aplicación
**Actor:** Usuario  
**Descripción:** El usuario compra digitalmente la moneda que da beneficios dentro de la app.

### Flujo principal:
1. El usuario accede a la tienda dentro de la aplicación.  
2. Selecciona el apartado “Comprar monedas”.  
3. El sistema muestra el costo y solicita confirmación.  
4. El usuario confirma la compra.  
5. El sistema muestra un mensaje de confirmación.  
6. El sistema añade las monedas a la cuenta del usuario.

### Flujo alterno:
- Si ocurre un error en la transacción, el sistema cancela la compra.

---

## 👨‍🏫 Caso de uso 11: Crear un grupo de estudio
**Actor:** Maestro  
**Descripción:** El usuario crea un grupo de estudio para ayudar a sus alumnos a aprender mejor.

### Flujo principal:
1. El usuario selecciona la opción “Crear grupo”.  
2. Coloca los detalles del grupo.  
3. Accede al grupo y ahora es el administrador de este.  
4. El usuario puede copiar el código del grupo para enviárselo a sus alumnos.

### Flujo alterno:
- El usuario puede cancelar la acción de crear grupo cuando está colocando los detalles.