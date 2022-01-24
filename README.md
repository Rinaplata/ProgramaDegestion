# ProgramaDegestion

- Aprende lo básico de SQL realizando un mini programa de gestión para una empresa X. 
Se va realizar una aplicacion para mejorar la eficiencia laboral, debido a que existe problema en la planificacion de los proyectos y de los empleados.

### Instalación  de SQL Server developer 2019 👇 

- https://www.microsoft.com/es-es/sql-server/sql-server-downloads#%20Salto%20de%20p%C3%A1gina
- Recomendacion : digitar una contraseña ⚙ facil de recordar. 
- Instalar SQL Server Management studio (SSMS). 
  https://docs.microsoft.com/es-es/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15
- Guardar todo en la misma carpeta de SQL.

### Empecemos a construir la base de datos 🛠️
#### Datos generales 

Empleado: id-empleado, id-cargo, cedula, nombre, correo, teléfono.
Cargo: id-cargo, nombre, descripción, salario.
Proyecto: id-proyecto, id-empleado, id-estadoProyecto, descripción, fechaAsignación, fechaInicio y fechaFin.
Actividad: id-actividad, id-proyecto, id-estadoActividad, nombre, descripción, fechaInicio, fechaFin.
EstadoActividad: id-estadoActividad, nombre, descripción.
EstadoProyecto: id-estadoProyecto, id-estadoActividad, nombre, descripción.
Notificación: id-notificacion, id-empleado, correo, mensaje.


