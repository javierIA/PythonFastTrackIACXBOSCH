# Primeros pasos github
Paso 1: Configurar Git en tu computadora
1. Descarga e instala Git en tu computadora desde el sitio web oficial (https://git-scm.com).
2. Abre la terminal o línea de comandos y configura tu nombre de usuario y dirección de correo electrónico usando los siguientes comandos:
   ```
   git config --global user.name "Tu nombre"
   git config --global user.email "tu@email.com"
   ```

Paso 2: Crear un repositorio en GitHub
1. Ve a la página principal de GitHub (https://github.com) y crea una cuenta si aún no tienes una.
2. Haz clic en el botón "New" (Nuevo) en la esquina superior derecha para crear un nuevo repositorio.
3. Asigna un nombre al repositorio y proporciona una descripción opcional.
4. Puedes elegir hacer el repositorio público o privado (requiere una cuenta de pago).
5. Haz clic en "Create repository" (Crear repositorio) para finalizar la creación.

Paso 3: Clonar el repositorio en tu computadora
1. Copia la URL del repositorio que has creado en GitHub.
2. Abre la terminal o línea de comandos y navega hasta la ubicación donde deseas clonar el repositorio.
3. Ejecuta el siguiente comando para clonar el repositorio en tu computadora:
   ```
   git clone <URL_del_repositorio>
   ```
   (reemplaza `<URL_del_repositorio>` con la URL que copiaste anteriormente)

Paso 4: Realizar cambios y subirlos al repositorio
1. Haz cambios en los archivos dentro de la carpeta del repositorio clonado en tu computadora.
2. Una vez que hayas realizado los cambios, abre la terminal o línea de comandos en la carpeta del repositorio.
3. Usa el siguiente comando para ver el estado de los archivos modificados:
   ```
   git status
   ```
4. Utiliza el comando `git add <nombre_del_archivo>` para agregar los cambios al área de preparación. Si deseas agregar todos los cambios, puedes usar `git add .`.
5. Luego, utiliza el comando `git commit -m "Mensaje del commit"` para confirmar los cambios con un mensaje descriptivo.
6. Finalmente, utiliza el comando `git push` para subir los cambios al repositorio en GitHub.

¡Y eso es todo! Has completado los primeros pasos de Git en GitHub. Ahora podrás realizar cambios, confirmarlos y subirlos a tu repositorio en GitHub. Te recomiendo explorar más sobre Git y GitHub para aprovechar al máximo estas herramientas.




# sRamas (Opcional)
Paso 1: Crear una rama
1. Abre la terminal o línea de comandos en la carpeta de tu repositorio clonado.
2. Para crear una nueva rama, utiliza el siguiente comando:
   ```
   git branch <nombre_de_rama>
   ```
   (reemplaza `<nombre_de_rama>` con el nombre que deseas darle a tu rama).

Paso 2: Cambiar a la rama creada
1. Utiliza el siguiente comando para cambiar a la nueva rama:
   ```
   git checkout <nombre_de_rama>
   ```
   (reemplaza `<nombre_de_rama>` con el nombre de la rama que creaste).
2. Ahora estarás trabajando en la nueva rama y podrás hacer cambios sin afectar la rama principal (normalmente llamada "main" o "master").

Paso 3: Realizar cambios en la rama
1. Haz los cambios necesarios en los archivos de tu proyecto.
2. Utiliza los comandos `git add` y `git commit` para agregar y confirmar los cambios en la rama actual, de la misma manera que lo harías en la rama principal.

Paso 4: Fusionar la rama con la rama principal
1. Una vez que hayas completado los cambios y estés listo para fusionar la rama con la rama principal, primero cambia a la rama principal utilizando el comando `git checkout main` (o `git checkout master` si es la rama principal).
2. Luego, utiliza el siguiente comando para fusionar la rama creada con la rama principal:
   ```
   git merge <nombre_de_rama>
   ```
   (reemplaza `<nombre_de_rama>` con el nombre de la rama que creaste).

Paso 5: Eliminar una rama
1. Después de fusionar exitosamente la rama con la rama principal, puedes eliminar la rama si ya no la necesitas.
2. Utiliza el siguiente comando para eliminar una rama:
   ```
   git branch -d <nombre_de_rama>
   ```
   (reemplaza `<nombre_de_rama>` con el nombre de la rama que deseas eliminar).

¡Eso es todo! Ahora sabes cómo crear ramas, cambiar entre ellas, hacer cambios y fusionar ramas en Git. Recuerda que trabajar con ramas te permite desarrollar nuevas funcionalidades, experimentar y colaborar de manera segura sin afectar la rama principal de tu proyecto.