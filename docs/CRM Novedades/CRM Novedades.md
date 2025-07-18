Tareas

identificar todos los scripts .sql del sistema

relevar consultas embebidas en el codigo php, javascript

detectar orms ( doctrine, sequelize ) y revisar consultas generadas

localizar reportes con jobs, procedimineots almacenados y triggers

extraer consultas desde archivos de configuracion, logs o trazas

listar cada consulta sql encontrada

clasificar tipo de consulta select insert update delete ddl

registrar base de datos usada nombre o conexion

listar tablas involucradas por consulta

identificar si hay joins y entre q tablas

analizar si hay subconsultas group by having order by, etc

determinar porposito funcional ejemplo listado de polizas, carga de siniestros

asociar cada consulta al modulo o funcionalidad donde se usa

registrar archivo o funcion que ejecuta la consulta

identificar si es una consulta puntual o parte de procesos periodicos

verficar si modifica datos crititcos o sensibles

documentar si depende configuraciones externas ( parametros, permisos, flags)

crear una plantilla de notion con columnas: Id consulta, Tipo ( select, intert, etc ), archivo origen, modulo funcional, base de datos, tablas afectadas, joins, objetivo, impacto ( lectura, escritura, ambos), observaciones