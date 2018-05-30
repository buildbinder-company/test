# buildbinder Prueba

El examen consiste en crear un portal web en el lenguaje de tu preferencia con las siguientes características:

## Historias de usuario.
1. Como usuario, necesito crear una cuenta de acceso al portal.
2. Como usuario, necesito poder iniciar sesion en el portal, con mi cuenta registrada.
3. Como usuario, necesito poder finalizar mi sesion.
4. Como usuario, quiero crear un proyecto, indicando el tipo de proyecto, nombre, fecha de inicio y fin.
5. Como usuario, quiero editar mi proyecto.
6. Como Usuario, quiero borrar alguno de mis proyectos.
7. Como usuario, quiero ver todos mis proyectos creados, pero no los borrados.

Creación del proyecto: se deberá crear una relación entre el usuario que lo crea, así como indicar un tipo de proyecto.
Borrar Proyecto: se deberá sólo marcar el proyecto como borrado y no borrar de la base de datos.

## Base de datos
La base de datos será en la plataforma de tu preferencia y experiencia, el nombre de la base de datos será de tu elección, las tablas y propiedades serán las siguientes:
* Users
    * Id (PK)
    * Email (String)
    * Name (String)
    * LastName (String)
    * Password (String)
* Projects
    * Id (PK)
    * UserId (FK Users)
    * TypeId (FK Types)
    * Name (String)
    * StartDate (DateTime)
    * FinishDate (DateTime)
    * Deleted (Boolean)
* Types
    * Id (PK)
    * Name (String)

## Puntos a considerar
* Técnica para la resolución del problema
* Seguimiento de las indicaciones
* Sintaxis 
* Lógica
* Conocimiento del lenguaje o framework usado
* Script usado para creación de tablas, o en su defecto indicar si se ha usado Code First

## Plus
* UX
* UI
* Manejo de sesión
* Semilla para poblar la base de datos con algunos registros
* Uso y documentación de commits en git

## Entregable.
1. El proyecto sera alojado en un repositorio de [Github](https://github.com) de su cuenta personal (si no tiene cuenta cree una nueva)
2. Si existe un script para generación, indicar qué base de datos utilizaron, así como la versión
3. Si existiera alguna indicación adicional para ejecutar su proyecto, favor de anexar al repositorio
