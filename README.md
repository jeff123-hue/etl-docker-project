la carpeta etl-docker-proyect contiene los siguientes archivos:

-Crea_BD_Tablas.txt----Contiene el Sql para la creacion de la BD y las tablas 'ususarios' y 'propiedades'
-deployment.yaml-------Despliega la aplicación en un clúster de Kubernetes.
-Dockerfile------------Construye la imagen Docker necesaria para ejecutar la aplicación.
-etl.ipynb-------------Contiene el codigo Python de la Etl desarrollada para la extraccion transformacion y carga en la BD desde el XML
-feed.xml--------------Contiene la data para extraery cargar a la BD
-Respuestas_Consultas_Problema.txt----Conntine los Slq para dar solución a las preguntas de negocio

-Detalles de conexión a la base de datos
-Host 'Localhost' 
-Usuario BD 'root'
-Password 'root123'
-database 'realestatedb'
