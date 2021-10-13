__PASOS COMUNES DEL FLUJO DE TRABAJO EN GITHUB__

Ahora que ya sabemos algo de git, revisa [este enlace](https://victorhckinthefreeworld.com/2018/08/09/6-errores-comunes-al-utilizar-git-y-como-solucionarlos/)

Los pasos normales, en secuencia y ordenados por actor son:   
**PROPIETARIO**
- CREAR REPOSITORIO EN GITHUB; con mínimo un README.md o desde Local
- CREAR ISSUE/INCIDENCIA; necesitamos alguien que se encarge de alguna feature  

**COLABORADOR**  
- COMENTAR O CREAR ISSUE; Indicas que puedes colaborar y asumir la responsabilidad
- FORK; Clonas el proyecto en tu GitHub  

**PROPIETARIO**  
- ASIGNAR ISSUE AL COMENTADOR; Aceptamos la colaboración

**COLABORADOR**  
- CREAR RAMA; En Local o en la nube creamos la rama de desarrollo
- CLONAR A LOCAL; y trabajamos en local
- PROGRAMAMOS Y MODIFICAR ARCHIVOS EN RAMA LOCAL; actuamos en nuestro equipo
- COMMIT RAMA; Confirmamos que hemos solucionado la issue
- PUSH RAMA; La subimos
- CREAR UN PULL REQUEST DE RAMA EN MASTER O EN DONDE QUERAMOS INFLUIR; y pedimos que se incorpore a la rama que corresponda

**PROPIETARIO**  
- REVISAR ISSUE; Para confirmar que es correcto
- SI INTERESA MERGE Y COMMIT, o CANCEL; y actuar en consecuencia
- CIERRA ISSUE; Si la damos por concluida

**COLABORADOR**  
- BORRA RAMA; Si ya no tiene más sentido
- FETCH UPSTREAM, REFRESCA master; Actualizamos el origen.
- GIT PULL; y lo descargamos.


