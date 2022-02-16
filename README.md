# Parcial16-02-22




Aplicacion ADF con proyecto Modelo creado

El proyecto Model debe contar con las EntityObject para las tablas CURSOS y MATERIAS.

El proyecto Model debe contar con las VoewObject para las tablas CURSOS y MATERIAS.

Se debe contar con datos en las tablas CURSOS y MATERIAS.

Se debe contar con una conexion funcionando a la Base de Datos y esquema donde estas tablas existan.

Crear proyecto ViewController que implemente las siguientes funcionalidades:

-Una pagina que liste Cursos(seleccion simple y sin edicion) y las Materias de cada curso (Maestro Detalle) o dos listas enlazadas (Lista Cursos, al seleccioar un curso se muestra un alista con las Materias del curso)

-La lista de Cursos debe contar con las siguientes operaciones en forma de botones: Modificar, Borrar, Nuevo.

-El boton Borrar debe eliminar un registro de la lista de Cursos y refrescar las listas tras realiar la operacion. Debera levantar un popUp solicitando confirmacion. -El boton Modificar debera abrir una pagina nueva presentando un formulario con la informacion y posibilidad de editar los campos, mas las opciones de Aceptar (commit) y Cancelar(Rollback). Tras realizar cualquiera de ambas, se debera dovler a la pagina anterior y refrescar la tabla de Cursos -El boton Nuevo, debera arbri una pagina nueva, presentando un formulario vacio para cargar los datos de un nuevo curso. El formulario debera hacer uso de una lista desplegable que muestre los nombres de materias para asociar una al curso que se da de alta (LOV, list of Values); y las opciones Aceptar(Commit) y Cancelar(Rollback). Tras realizar cualquiera de ambas, se debera dovler a la pagina anterior y refrescar la tabla de Cursos para visualizar el nuevo registro

En los casos del boton Aceptar y Cancelar de las operaciones Modificar y Nuevo, al seleccionar cualquiera de ambos se debera resentar un popUp solicitando confirmacion de a operacion.

IMPORTANTE: de las 2 operaciones NUEVO, MODIFICAR se debera elegir al menos 1 e implementar de forma programatica, haciendo y uso de un backing Bean.

Observaciones: pueden Usar un backing bean donde crean conveniente, mas alla de lo solicitado.

NOTA EXTRA: Empaquetar y desplegar la apiacion en un servidor weblogic local.
