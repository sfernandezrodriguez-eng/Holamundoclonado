### Configurar una nueva identidad de usuario localmente.
Ejecuta los siguientes comandos:
git config --local user.name "Tu Nombre"
git config --local user.email "tuemail@ejemplo.com"
Esto configura el usuario solo para este repositorio (no afecta tus otros proyectos).
### Añadir un nuevo repositorio remoto personal (mirepositorio).
Crea un nuevo repositorio vacío en tu cuenta de GitHub, GitLab o Bitbucket.
(Sin README ni archivos, para evitar conflictos.)

Copia la URL del nuevo repositorio
En la terminal de PyCharm, agrega el nuevo remoto:
git remote add mirepositorio https://github.com/tuusuario/mirepositorio.git

### Eliminar el repositorio remoto inicial.
Para eliminar el repositorio utiliza:git remote remove origin

###  Realizar cambios y commit desde PyCharm.
Modifica algún archivo (por ejemplo, edita un .py o un .md).

PyCharm mostrará el cambio en azul o rojo en el panel lateral.

Abre el panel Commit:

Menú: Git → Commit (o clic en la esquina inferior izquierda donde dice Commit).

Escribe un mensaje de commit y haz un push
### Realizar el push al nuevo remoto desde PyCharm.
Menú superior: Git → Push...

En el cuadro de diálogo, PyCharm mostrará el remoto (mirepositorio) y la rama actual (por ejemplo, main o master).

Verifica que esté seleccionada la rama correcta.

Haz clic en Push y listo.
