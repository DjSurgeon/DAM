# 1. Introducción a las Bases de Datos (BBDD)

Las bases de datos (BBDD) son esenciales en los sistemas informáticos. Aunque existen diversas definiciones, nos centraremos en las relacionadas con la informática.

### Concepto

Una base de datos se define como una agrupación de datos relacionados entre sí, almacenados en formato digital con una estructura determinada, que permite un acceso rápido a la información.

### Propiedades principales

- Representan elementos abstractos o concretos del mundo real.
- Están diseñadas para un objetivo específico.
- Pueden almacenar grandes cantidades de información.
- Están habilitadas para un grupo concreto de usuarios.

## Evolución Histórica de las BBDD

El concepto de bases de datos como conjunto de datos organizados y accesibles está ligado al origen de la escritura y la historia humana.

- **Prehistoria**: Los primeros registros escritos, como los de la civilización sumeria, servían para registrar transacciones comerciales o inventarios (ej. cantidad de arroz cosechado o animales tras una transacción). Estos datos se almacenaban en tablillas cuneiformes para consultas posteriores.
- **Evolución tecnológica**: Con el tiempo, se pasó de tablillas de arcilla a papel y tinta, y finalmente a ordenadores digitales.

### Siglo XX en adelante

- **1900-1950**: Primeros pasos de la informática con invenciones como el tubo de vacío, la puerta lógica AND, la máquina de Turing, la Harvard Mark I (electromecánica) y la arquitectura de von Neumann.
- **Años 60**: Aparecen los sistemas por lotes (batch processing), que ejecutan programas sin supervisión continua del usuario. Surge la comercialización de la informática, el Database Task Group (CODASYL) y el sistema SABRE (IBM y American Airlines) para gestionar pasajeros y vuelos.
- **Años 70**: Edgar Frank Codd publica el modelo relacional, nace Oracle, y aparece el modelo entidad-relación (E-R) para facilitar el diseño de BBDD.
- **Años 80**: La informática se extiende, y las BBDD se vuelven más accesibles con la estandarización del lenguaje SQL (Structured Query Language). Surgen los primeros ordenadores personales capaces de gestionar BBDD a nivel de usuario.
- **Años 90**: Amplia adopción de BBDD en empresas, con mejoras en el rendimiento de los sistemas gestores. Microsoft lanza Microsoft Access, enfocado en usuarios individuales.
- **Años 2000 en adelante**: Dominio de Oracle, IBM y Microsoft. Se integran multimedia (imágenes, sonido) mediante tipos abstractos de datos (TAD), que incluyen valores, operaciones y propiedades. Las BBDD evolucionan hacia la orientación a objetos (OO) debido al éxito de la programación orientada a objetos (POO) y su uso en páginas web.

## Ventajas e Inconvenientes de las BBDD

### Ventajas

- Procesamiento independiente de la información con mínima redundancia gracias a un buen diseño relacional.
- Máxima información con mínima cantidad de datos.
- Garantizan integridad y coherencia en los resultados.
- Ofrecen alta seguridad.
- Reducen el espacio de almacenamiento frente a medios físicos como el papel.
- Almacenan datos de forma eficiente.

### Desventajas

- Requieren mantenimiento por un administrador cualificado.
- Necesitan hardware costoso, lo que las hace poco rentables a corto plazo.
- Ocupan mucho espacio en memoria y disco duro.

## Almacenamiento de la Información

Las BBDD son la técnica más eficiente para guardar información estructurada y accesible, presentes en múltiples ámbitos:

- **Educación**: Registro de alumnos y calificaciones.
- **Sanidad**: Historiales médicos de pacientes.
- **Banca**: Datos de clientes y cuentas.
- **Telefonía móvil**: BBDD en aplicaciones.

### Ficheros

En informática, la información se almacena en ficheros (o archivos), secuencias de dígitos binarios con una estructura lógica que contienen datos como informes, imágenes o canciones.

### Tipos de ficheros según el método de acceso

- **Ficheros planos**: Registros en orden contiguo; requieren recorrido secuencial para acceder a un registro.
- **Ficheros indexados**: Dividen datos en índice (tabla de claves) y registros, permitiendo acceso rápido.
- **Ficheros de acceso directo**: Usan la clave como dirección física; acceso inmediato con tamaño fijo.
- **Otros**: Ficheros con funciones hash (algoritmo clave-posición).

### Operaciones básicas en ficheros

| Operación | Descripción |
|-----------|-------------|
| Abrir (open) | Prepara el fichero para lectura/escritura. |
| Cerrar (close) | Cierra el fichero, impidiendo más operaciones. |
| Leer (read) | Obtiene información del fichero. |
| Escribir (write) | Guarda información en el fichero. |
| Posicionarse (seek) | Mueve el puntero para lectura/escritura. |
| Fin de fichero (eof) | Marca el final del fichero. |


### Conceptos clave de las BBDD

Una BBDD es una colección de datos relacionados, en formato digital, organizada para maximizar resultados con mínima información, usando tablas bien relacionadas.

- **Dato**: Información específica (ej. edad, fecha de nacimiento).
- **Tipo de dato**: Formato del dato (numérico, fecha, booleano, etc.).
- **Campo**: Propiedad común de los registros en una tabla (ej. apellido en la tabla Persona).
- **Tabla**: Entidad con campos y registros (ej. tabla Persona con nombre, apellidos, DNI).
- **Registro**: Conjunto de datos de un elemento (ej. María, Gómez, 25, Mujer, 47585858X).
- **Campo clave**: Identifica un registro de forma única (ej. DNI).
- **Consulta (query)**: Petición para obtener, insertar, actualizar o eliminar datos.
- **Índice**: Estructura con claves para búsquedas rápidas.
- **Vista**: Tabla virtual con datos de una o más tablas.
- **Informe**: Listado formateado de campos/registros (ej. trabajadores mayores de una empresa).
- **Scripts**: Instrucciones para mantenimiento de datos.
- **Procedimiento**: Script almacenado en la BBDD.

## Sistemas Gestores de Bases de Datos (SGBD)

### Concepto

Un SGBD es un software que facilita la administración de BBDD, permitiendo diseño, consulta y modificación de datos. Ejemplos: Oracle, MySQL, SQL Server, Microsoft Access.
Funciones

- **Definición**: Especifica tipos de datos, estructuras y restricciones, asegurando cohesión e integridad.
- **Construcción**: Almacena datos en medios controlados por el SGBD, conectándose al exterior (ej. protocolo ODBC).
- **Manipulación**: Consulta y modifica datos almacenados.

Los SGBD ofrecen herramientas para estadísticas sobre consultas, actualizaciones e incidencias, diseñadas para simplicidad y rendimiento.

### Tipos según capacidad

- **Ofimáticos**: Para uso doméstico o pequeñas empresas; interfaz sencilla (ej. Microsoft Access).
- **Corporativos**: Para grandes empresas con alta carga de datos; requieren servidores potentes (ej. Oracle).

### Tipos según licencia

- **Comerciales**: Requieren pago; suelen ser de código cerrado con garantía de mantenimiento (ej. Oracle, SQL Server, Access).
- **Libres**: Gratuitos y de código abierto; modificables por el usuario (ej. MySQL, PostgreSQL, MariaDB).

### Objetivos del SGBD

Procesar, describir, administrar y recuperar datos, priorizando seguridad e integridad con herramientas como:

- Creación/especificación de estructuras físicas.
- Manipulación de datos (añadir, modificar, eliminar, consultar).
- Recuperación mediante copias de seguridad.
- Gestión de comunicación, aplicaciones, instalación y exportación/importación.

### Tipos de usuarios

- **Informáticos**: Usuarios avanzados (consultas, diseño, administración).
- **No informáticos**: Usan interfaces simples (formularios).

### Administrador de la BBDD (DBA)

Responsable de:

- Definir esquema y estructuras de almacenamiento.
- Modificar esquema/organización física.
- Asignar autorizaciones y restricciones de integridad.

### Lenguajes de BBDD

- DDL (Data Definition Language): Define estructuras y vistas; genera diccionarios de datos.
- DML (Data Manipulation Language): Manipula datos (insertar, modificar, borrar, consultar).
	- Procedimental: Especifica cómo obtener datos.
	- No procedimental: Solo qué datos obtener.
- DCL (Data Control Language): Controla acceso (GRANT, REVOKE).
- TCL (Transactional Control Language): Administra transacciones (COMMIT, ROLLBACK).

### Diccionario de datos

Almacena información sobre la BBDD (objetos, espacio, valores por defecto, privilegios, restricciones). Ejemplo:

- **Tabla Empleado**: idEmpleado (clave), nombre, apellidos, salarioE, departamentoE, fechaEntrada.
- **Características**: Soporta modelos conceptuales, transferencia, integración en el DBMS, actualización, acceso directo.
- **Tipos**: Off-Line (mantenimiento), On-Line (compilador define datos), In-Line (define al ejecutar).

## ANSI/X3/SPARC: Estándares y Niveles

En 1975, ANSI-SPARC propuso una arquitectura de tres niveles para estandarizar la gestión de BBDD, separando la visión del usuario de los detalles internos:

- **Nivel externo**: Vista del usuario con información pertinente, ocultando datos no permitidos y detalles técnicos.
- **Nivel conceptual**: Organización lógica de datos y relaciones; exclusivo del administrador (DBA).
- **Nivel interno**: Almacenamiento físico (tipos de datos, métodos de acceso); independiente de hardware/software.

No confundir con las fases de diseño (recopilación, E-R, relacional, implementación).

## Modelos de BBDD

Determinan la estructura lógica, organización y operaciones permitidas.
Tipos

- **Jerárquico**: Estructura de árbol (padre-hijo); un padre, múltiples hijos.
- **En red**: Nodos y enlaces; permite múltiples padres.
- **Relacional**: Tablas (relaciones) con tuplas; creado por Codd (1970s); garantiza normalización e integridad referencial.
- **Entidad-Relación (E-R)**: Conceptual; usado para diseño, con variantes como E-R extendido (ERE).
- **Orientado a objetos**: Basado en POO; cohesiona datos y procedimientos; soluciona limitaciones relacionales.

## Reglas de integridad

- **Del modelo**: SGBD evita pérdida de integridad en actualizaciones.
- **Del usuario**: Usuarios cumplen reglas; SGBD ofrece herramientas para reconstruir datos.

## Bases de Datos Centralizadas y Distribuidas

### Centralizadas (BDC)

- **Definición**: Almacenadas en una sola máquina.
- **Características**: Componentes en un solo lugar, pocos elementos de procesamiento (datos, software, almacenamiento).
- **Ventajas**: Sin redundancia/inconsistencia, seguridad, rendimiento óptimo, entrada única por dato.
- **Inconvenientes**: Recuperación compleja, sin reparto de tareas, fallo total si colapsa, alto costo de mainframes.

### Distribuidas (BDD)

- **Definición**: Conjunto de BBDD relacionadas en múltiples ubicaciones, interconectadas por red; procesan autónomamente.
- **Características**: Autonomía, sin red central, lectura/escritura en distintos nodos, transforma transacciones en instrucciones.
- **Ventajas**: Acceso/procesamiento rápido, fácil expansión, modularidad, bajo costo en redes pequeñas, refleja estructuras organizativas.
- **Inconvenientes**: Diseño complejo, mayor riesgo de seguridad, recuperación difícil.
- **Componentes**: Más hardware (nodos), software para interconectar nodos vía red.

### Procesamiento de consultas

- **Locales**: Operan en un solo nodo con esquemas locales.
- **Distribuidos**: Transforman consultas de alto nivel (cálculo relacional) a bajo nivel (álgebra relacional); optimización compleja.

### Bloqueo y concurrencia

- **SGBD** concurrentes ejecutan consultas simultáneamente.
- **Transacciones distribuidas**: Planas o anidadas; acceden a objetos de múltiples servidores; requieren verificación global (atomicidad).

### Distribución de datos

El diseñador decide:

- **Centralizada**: Nodo central, como cliente/servidor; baja disponibilidad.
- **Replicada**: Datos duplicados en nodos; costosa, lenta, alta disponibilidad.
- **Particionada**: Una copia por nodo; fragmentos; menos costo, baja disponibilidad.
- **Híbrida**: Combina replicación y partición.

### Seguridad y recuperación

- **Ataques**: Privacidad, autenticación, denegación de servicio.
- **Herramientas**: Protocolos, cifrado, cortafuegos.
- **Recuperación**: Tolerancia a fallos para continuidad.

### Arquitecturas

- **Federadas**: BBDD cooperativas y autónomas; vistas lógicas sin existencia física.
- **Múltiples**: Interfaz de componentes; acceso uniforme y consistente.

### Diseño y gestión

Pasos:

- Diseñar esquema conceptual.
- Organizar esquema y métodos de acceso.
- Fragmentar la BD (horizontal, vertical, mixta).
- Asignar fragmentos.

- Gestión: Estabilidad, coherencia, interconexión correcta.
- DTM: Administra transacciones distribuidas.