# setup-great-expectations
- Charla sobre Data Quality
- Codigo explicando como arrancar a utilizar Great Expectations y como implementarlo en Airflow.


## Abrir el archivo GreatExpectations.ipynb con Jupyter Notebooks/Lab. 
## Ahi se explican las formas basicas para arrancar a usar Great Expectation.

### Forma manual:
1. Establecer un Data Context
2. Definir una fuente de datos (datasource)
3. Definir / Crear Expectativas
4. Correr un Checkpoint de las validaciones

### Forma automatica:
1. Establecer un Data Context
2. Definir una fuente de datos (datasource)
3. Crear un Batch Request
4. Crear un Expectation Suite vacio
5. Correr el Data Assistant asignando el Batch y la Suite
6. Correr Checkpoint usando el Batch y la Suite generada

### Tambien se explica como generar los documentos para ver los resultados y como editar una Suite.

## Una vez que se entiende el concepto de GX, segun la necesidad de implementarlo en Airflow los pasos a seguir se encuentran en SetupAirflowGX.txt .
### Pero tambien se puede implementar con un operador normal de Airflow y el codigo clasico de GX
