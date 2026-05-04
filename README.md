## Ejercicio-semana3

### Parte 1
* Trabajar en un archivo llamado cuaderno1.ipynb
* Crear un conjunto de datos usando la librería https://faker.readthedocs.io/en/master/
* El número de registros que se debe generar es de 10000
* El conjunto de datoss tendrá las siguientes características:
    * Para cada registro usar las características: fake.name(), fake.last_name(), fake.email(), fake.address()
* Pasar los registros a un dataframe de pandas
* Agregar dos características más:
    * Edad, comprendidas entre 30 y 40 años
    * Provincia, entre las opciones (Loja, Pichincha, Guayas, Azuay, Manabí)
* Pasar el dataframe a un archivo csv
  
### Parte 2

* Trabajar en un archivo llamado cuaderno2.ipynb
* Leer el archivo previo generado
* Visualizar la información a través de PyGWalker (instalar previo - https://github.com/Kanaries/pygwalker)
 * Un gráfico que muestre el número de registros por cada edad
 * Un gráfico que muestre el número de registros por cada provincia 
