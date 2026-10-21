# Parcial 2do Corte
### Actividad Práctica: Uso de GIT
Universidad el Bosque		
<br/>
Facultad de Comunicación y Creación 
<br/>
Programa de Creación Digital 
<br/><br/><br/>
- A continuación encontrará la actividad a desarrollar como su Parcial Práctico (equivalente al 60% de la nota) en el que se evaluarán sus conocimientos básicos en GIT.
- Puede usar tanto el terminal de comandos de ```GIT``` como ```GitHub Desktop``` para solucionar el ejercicio.
- Por favor no elimine ninguna de las ramas creadas para el ejercicio.
- Recuerde: Después de crear las ramas solicitadas, debe hacer el ```pull request``` y el ```merge``` correspondiente para que los cambios queden en la rama ```main```.
- Debe registrar el link del su repositorio en el siguiente formulario [https://forms.cloud.microsoft/r/aLN15gWr1H](https://forms.cloud.microsoft/r/aLN15gWr1H)
#### HORA LÍMITE DEL FORMULARIO: 08:50.
<br/><br/><br/>
## Instrucciones:
1. Cree un repositorio PÚBLICO con el nombre de la siguiente forma:
```
ApellidosNombres_Grupo_(Letra que le corresponde)
Ejemplo: RicardoPerez_Grupo3_(H)
```
2. Clone este repositorio y continúe su parcial en el repositorio creado. *NOTA: Por favor verifique que SU repositorio esté correctamente creado revisando tanto en el sistema de carpeta de archivos como en su cuenta de GitHub consultando en el navegador.*
3. Ya que el segundo paso esté completado y verificado, elimine los archivos de las recetas que NO corresponden a la asignada y deje únicamente el archivo que va a trabajar (además de este archivo ```README.md```).
4. En la rama ```main``` agregue el link de la imagen que se encuentra comentada en la línea 3.
5. Cree una rama llamada ```corregir-titulos``` para arreglar el título y subtítulos de las secciones en el formato correspondiente, aquí el fragmento de código con la sintaxis:
```
# Título (Nombre del personaje)
## Subtítulos (Información personal y Aportes)
```
6. Cree una rama (usted determinará el nombre más adecuado) y en las fechas de nacimiento y defunción, escriba las fechas en formato ```DD/MM/AAAA```, así:
```
quince de agosto de mil novecientos noventa y dos   ➡   15/08/1992
```
7. Cree una rama llamada ```ordenar-informacion```, ordene en la información así:
- Fecha de Nacimiento
- Fecha de Fallecimiento
- Ocupación
- Área de conocimiento
- Estudios
8. En la sección de Aportes hay 7 errores de ortografía, cree una rama (con el nombre que usted considere más apropiado) y corrija los 7 errores de ortografía que se encuentran en mayúsculas.
*NOTA: Haga un commit por cada error de ortografía corregido con el siguiente mensaje:*
```
Palabra <equivocada> corregida por <correcta>.
Ejemplo: Palabra SIUDAD corregida por ciudad.
```
9. Finalmente, en la rama ```main``` al final de la receta, escriba su nombre completo y documento de identidad.
<br><br><br>
## Puntos Negativos (-0.05)
- No usar Visual Studio Code como herramienta de modificación de código.
- Mal nombramiento de ramas.
- Commits vacíos.
- Commits mal escritos.
- Commits hechos después de la hora del parcial (09:00).
- Crear ```fork``` del repositorio original.
- Eliminar alguna de las ramas creadas.
- NO seguir las instrucciones detalladas de este documento.
<br><br><br>
## Tabla de Resumen de Comandos de Git más utilizados
| Comando | Función |
| --- | --- |
| git init | Inicializar repositorio |
| git status | Ver estado de archivos |
| git add . / git add archivo | Agregar al staging area |
| git commit -m "mensaje" | Confirmar cambios |
| git commit --amend --no-edit | Modificar último commit |
| git log --oneline | Ver historial resumido |
| git log --oneline --graph --all | Ver historial con gráfico de ramas |
| git log rama1..rama2 --oneline | Ver commits exclusivos de una rama |
| git diff | Ver cambios sin staging |
| git diff --staged | Ver cambios en staging |
| git diff rama1 rama2 | Comparar dos ramas |
| git diff --stat rama1 rama2 | Resumen estadístico de diferencias |
| git restore archivo | Descartar cambios |
| git restore --staged archivo | Sacar del staging |
| git branch | Listar ramas locales |
| git branch -a | Listar todas las ramas (locales y remotas) |
| git branch -d nombre | Eliminar rama local |
| git checkout rama | Cambiar de rama |
| git checkout -b rama | Crear y cambiar de rama |
| git checkout hash | Explorar un commit antiguo |
| git merge rama | Fusionar rama |
| git stash | Guardar cambios temporalmente |
| git stash list | Ver lista de stashes |
| git stash pop | Recuperar cambios guardados |
| git revert HEAD --no-edit | Deshacer commit creando uno nuevo |
| git reset --soft HEAD~n | Retroceder commits manteniendo cambios |
| git remote add origin URL | Conectar repositorio remoto |
| git remote -v | Ver remotos configurados |
| git push -u origin rama | Subir rama con seguimiento |
| git push origin rama | Subir cambios al remoto |
| git push origin --delete rama | Eliminar rama remota |
| git fetch origin | Descargar sin fusionar |
| git pull origin rama | Descargar y fusionar |
<br><br><br>
> ## IMPORTANTE
> En caso de uso de inteligencias artificiales tanto en consulta como coautor del repositorio, el parcial quedará automáticamente ANULADO..
