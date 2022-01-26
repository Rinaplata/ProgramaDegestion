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

```
* Empleado: id-empleado, id-cargo, cedula, nombre, correo, teléfono.
* Cargo: id-cargo, nombre, descripción, salario.
* Proyecto: id-proyecto, id-empleado, id-estadoProyecto, descripción,      fechaAsignación, fechaInicio y fechaFin.
* Actividad: id-actividad, id-proyecto, id-estadoActividad, nombre, descripción, fechaInicio, fechaFin.
* EstadoActividad: id-estadoActividad, nombre, descripción.
* EstadoProyecto: id-estadoProyecto, id-estadoActividad, nombre, descripción.
* Notificación: id-notificacion, id-empleado, correo, mensaje.

```

### Modelo Entidad Relacion 📄.

![Modelo entidad Relacion](https://github.com/Rinaplata/ProgramaDegestion/blob/main/Imagen/ModeloEntidadRelacion.jpg)

### Lenguaje de manipulación de Datos (DML)📄.

```
* SELECT: recupera datos de la base de datos.
* INSERT: añade nuevas filas de los datos a la base datos.
* DELETE: elimina filas de la base de datos.
* UPDATE: modifica datos existentes de la base de datos.
```
### Lenguaje de Definición de Datos (DDL)📄.

```
* CREATE TABLE: Añade una nueva tabla a la base de datos.
* DROP TABLE:   Suprime una tabla de la base de datos.
* ALTER TABLE:  Modifica la estructura de una tabla existente. 
* CREATE VIEW:  Añade una nueva vista a la base de datos.

```

## Creacion de las tabla con SQL.

* **CREATE TABLE** Se utiliza para crear una nueva tabla en una base de datos.

### Ejemplo👇
```
CREATE TABLE EMPLEADO
(
ID_EMPLEADO NUMERIC(10) NOT NULL, 
ID_CARGO NUMERIC(10) NOT NULL,
NOMBRE NVARCHAR(30) NOT NULL,
CEDULA NVARCHAR(10) NOT NULL,
TELEFONO NUMERIC(10) NOT NULL,
CORREO NVARCHAR(30) NOT NULL,

PRIMARY KEY(ID_EMPLEADO)
)

```

<a href="url"><img src="https://github.com/Rinaplata/ProgramaDegestion/blob/main/Imagen/CreateTable.png"  height="350" width="350" ></a>

* **INSERT INTO** se utiliza para insertar nuevos registros en una tabla.

### Ejemplo👇

<a href="url"><img src="https://github.com/Rinaplata/ProgramaDegestion/blob/main/Imagen/INSERT%20INTO.png?raw=true"  height="300" width="1300" ></a>


