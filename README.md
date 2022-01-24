# ProgramaDegestion

- Aprende lo básico de SQL realizando un mini programa de gestión para una empresa X. 
Se va realizar una aplicacion para mejorar la eficiencia laboral, debido a que existe problema en la planificacion de los proyectos y de los empleados.

## Instalación  de SQL Server developer 2019 👇 

- https://www.microsoft.com/es-es/sql-server/sql-server-downloads#%20Salto%20de%20p%C3%A1gina
- Recomendacion : digitar una contraseña ⚙ facil de recordar. 
- Instalar SQL Server Management studio (SSMS). 
  https://docs.microsoft.com/es-es/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15
- Guardar todo en la misma carpeta de SQL.

## Empecemos a construir la base de datos 🛠️
### Datos generales 

* **_Empleado:_** id-empleado, id-cargo, cedula, nombre, correo, teléfono.
* **_Cargo:_**  id-cargo, nombre, descripción, salario.
* **_Proyecto:_** id-proyecto, id-empleado, id-estadoProyecto, descripción, fechaAsignación, fechaInicio y fechaFin.
* **_Actividad:_** id-actividad, id-proyecto, id-estadoActividad, nombre, descripción, fechaInicio, fechaFin.
* **_EstadoActividad:_** id-estadoActividad, nombre, descripción.
* **_EstadoProyecto:_** id-estadoProyecto, id-estadoActividad, nombre, descripción.
* **_Notificación:_** id-notificacion, id-empleado, correo, mensaje.


### Modelo Entidad Relacion 📄.

![texto_alternativo](https://github.com/Rinaplata/ProgramaDegestion/blob/main/ModeloEntidadRelacion.jpg?raw=true)

### Creacion de las tabla con SQL.

* **CREATE TABLE** Se utiliza para crear una nueva tabla en una base de datos.

## Ejemplo👇

![texto_alternativo](https://carbon.now.sh/?bg=rgba%28255%2C255%2C255%2C1%29&t=material&wt=none&l=sql&ds=true&dsyoff=20px&dsblur=68px&wc=true&wa=true&pv=56px&ph=56px&ln=false&fl=1&fm=Hack&fs=14px&lh=133%25&si=false&es=2x&wm=false&code=CREATE%2520TABLE%2520EMPLEADO%250A%28%250AID_EMPLEADO%2520NUMERIC%2810%29%2520NOT%2520NULL%252C%2520%250AID_CARGO%2520NUMERIC%2810%29%2520NOT%2520NULL%252C%250ANOMBRE%2520NVARCHAR%2830%29%2520NOT%2520NULL%252C%250ACEDULA%2520NVARCHAR%2810%29%2520NOT%2520NULL%252C%250ATELEFONO%2520NUMERIC%2810%29%2520NOT%2520NULL%252C%250ACORREO%2520NVARCHAR%2830%29%2520NOT%2520NULL%252C%250A%250APRIMARY%2520KEY%28ID_EMPLEADO%29%250A%29)

