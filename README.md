# StudentHub

StudentHub es una plataforma para gestionar servicios académicos universitarios.

## Funcionalidades

- Gestión de estudiantes
- Gestión de cursos

## Equipo

- Developer A
- Developer B

El proyecto será desarrollado colaborativamente utilizando Git y GitHub.

## Preguntas de Reflexion

1. ¿Cuál es la diferencia entre git add y git commit?

- No se puede hacer un commit sin añadir un archivo o archivos a hacer commit

2. ¿Cuál es la diferencia entre git push y git pull?

- Git push, hace push al repositorio remoto, git pull hace fetch y merge del repositorio remoto al local automaticamente

3. ¿Cuál es la diferencia entre un repositorio local y uno remoto?

- Un repositorio local esta directamente guardado en tu dispositivo, el remoto utiliza un servicio de terceros para sincronizar con tu repositorio local y guardar cambios de los cuales podrias hacer un error localmente

4. ¿Qué problema resuelve una rama?

- El problema que resuelve una rama es la organizacion, y el añadido es que es un espacio cerrado en el cual puedes modificar codigo sin dañar el codigo en produccion

5. ¿Qué diferencia existe entre git merge y git rebase?

- git merge toma los cambios a una rama y los une a otra mediante un nuevo commit, rebase desarraiga tus commits y vuelve a aplicarlos uno por uno

6. ¿Por qué ocurre un conflicto?

- El conflicto ocurre porque git no sabe que cambio utilizar si varios desarrolladores cambian el mismo codigo y hacen merge

7.  ¿Quién debe decidir cómo resolver un conflicto?

- Cualquiera de ambos desarrolladores

8. ¿Qué problema resuelve un Pull Request?

- El pull request ayuda mucho en la organizacion y jerarquia de manera que el admin o desarrollador con permisos tiene que revisar el codigo cambiado con el original y hacer review de el nuevo codigo para ver si esta apto para hacer merge

9. ¿Por qué es recomendable revisar un Pull Request antes de integrarlo?

- Ayuda a ver los cambios de codigo, es como un diff pero en el repositorio remoto

10. ¿Qué ventaja tiene trabajar en una rama en lugar de modificar directamente main?

- No modificar el codigo de produccion y realizar algun daño.