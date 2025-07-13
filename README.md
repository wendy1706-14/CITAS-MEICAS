
 ## Sistema de Gestion de Citas Medicas 

## Descripcion del Proyecto

Este proyecto tiene como objetivo crear una base de datos para gestionar las citas medicas en una clinica. Permite registrar pacientes, medicos, especialidades y agendar citas de forma organizada.

La solucion facilita el acceso a informacion clave, como los datos del paciente, el medico asignado, la especialidad medica, as como la fecha y hora de cada cita.

## Estructura de la Base de Datos

La base de datos esta compuesta por las siguientes tablas:

- Paciente: almacena la informacion personal del paciente.
- Medico: contiene los datos del medico y su consultorio.
- Especialidad: define las diferentes especialidades medicas disponibles.
- Cita: registra las citas entre pacientes y medicos.

## Relaciones

- Un medico pertenece a una especialidad.
- Una cita se agenda para un paciente y la atiende un medico.

## Archivos Incluidos

- `ModeloER/modeloER.png`: Imagen del modelo Entidad-Relacion.
- `Scripts/clinica_citas.sql`: Script SQL con la creacion de tablas y registros de prueba.
- `Documentacion/modelo_relacional.pdf`: Documento del modelo relacional.
- `Documentacion/diccionario_datos.xlsx`: Diccionario de datos.
- `README.md`: Este archivo, con la descripcion general del proyecto.


---

**Proyecto academico** para fines de practica y aprendizaje.
