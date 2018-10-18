# experiencia_laboral_crud
API de experencia laboral, Integración con CI
experiencia_laboral_crud master/develop
 ## Requirements
Go version >= 1.8.
 ## Preparation:
    Para usar el API, usar el comando:
        - go get github.com/udistrital/experiencia_laboral_crud
 ## Run
 Definir los valores de las siguientes variables de entorno:
  - `EXPERIENCIA_LABORAL_HTTP_PORT`: Puerto asignado para la ejecución del API
 - `EXPERIENCIA_LABORAL_CRUD__PGUSER`: Usuario de la base de datos
 - `EXPERIENCIA_LABORAL_CRUD__PGPASS`: Clave del usuario para la conexión a la base de datos  
 - `EXPERIENCIA_LABORAL_CRUD__PGURLS`: Host de conexión
 - `EXPERIENCIA_LABORAL_CRUD__PGDB`: Nombre de la base de datos
 - `EXPERIENCIA_LABORAL_CRUD__SCHEMA`: Esquema a utilizar en la base de datos
 ## Example:
EXPERIENCIA_LABORAL_HTTP_PORT=8095 EXPERIENCIA_LABORAL_CRUD__PGUSER=postgres EXPERIENCIA_LABORAL_CRUD__PGPASS=password EXPERIENCIA_LABORAL_CRUD__PGURLS=localhost EXPERIENCIA_LABORAL_CRUD__PGDB=local EXPERIENCIA_LABORAL_CRUD__SCHEMA=core_new bee run
 ## Model DB
![image](https://github.com/udistrital/experiencia_laboral_crud/blob/dev/modelo_experiencia_laboral.png).
