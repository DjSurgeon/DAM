1. **¿Qué tipo de base de datos almacena información en una sola ubicación física?**

- Base de datos centralizada.
- Una base de datos centralizada se define como aquella que almacena todos sus datos en una única ubicación física, como una sola máquina. Esto contrasta con las bases de datos distribuidas, que dividen la información en múltiples ubicaciones interconectadas por una red. Las opciones "de red" y "relacional" se refieren a modelos de datos, no a la ubicación física, por lo que la respuesta correcta es "centralizada".

2. **¿Cuál es una característica de los archivos indexados?**

- Permiten el acceso rápido a registros mediante un índice.
- Los ficheros indexados dividen la información en un índice y registros, donde el índice contiene claves que apuntan a las posiciones físicas de los datos. Esto permite un acceso más rápido que en ficheros planos, que requieren una búsqueda secuencial.

3. **Las bases de datos relacionales organizan los datos en una estructura de red.**

- Falso.
- Las bases de datos relacionales organizan la información en tablas (relaciones) con tuplas y atributos, no en una estructura de red. El modelo en red utiliza nodos y enlaces, mientras que el relacional, propuesto por Edgar Codd, se basa en tablas interrelacionadas.

4. **El modelo de datos jerárquico organiza la información en una estructura de árbol.**

- Verdadero.
- El modelo jerárquico organiza los datos en una estructura de árbol invertido, con relaciones padre-hijo, donde un nodo padre puede tener varios hijos, pero un hijo solo un padre. Esto se describe explícitamente como una jerarquía tipo árbol.

5. **Un sistema de archivos indexado no permite la búsqueda rápida de datos.**

- Falso.
- Los ficheros indexados usan una tabla de claves para acceder rápidamente a los registros, evitando la búsqueda secuencial de los ficheros planos. La afirmación contradice esta característica fundamental.

6. **¿Qué tipo de base de datos almacena información en múltiples ubicaciones físicas?**

- Base de datos distribuida
- Las bases de datos distribuidas son aquellas donde los datos se almacenan en múltiples ubicaciones físicas, interconectadas por una red, permitiendo procesamiento autónomo. Esto las diferencia de las centralizadas (una ubicación).

7. **Un archivo plano es un tipo de sistema lógico de almacenamiento.**

- Verdadero.
- Los ficheros planos se describen como un tipo de sistema lógico de almacenamiento, caracterizados por registros en orden contiguo y acceso secuencial. Otros tipos incluyen indexados y de acceso directo, pero los archivos planos son reconocidos como un sistema lógico básico.


8. **¿Qué tipo de base de datos utiliza el modelo de datos orientado a objetos?**

- Base de datos orientada a objetos.
- Las bases de datos orientadas a objetos estructuran la información en objetos y clases, siguiendo el paradigma de programación orientada a objetos (POO). Esto las distingue de las relacionales (tablas), de red (nodos).

9. **¿Cuál de los siguientes NO es un tipo de sistema lógico de almacenamiento?**

- Archivo multimedia.
- Los sistemas lógicos de almacenamiento se describen como métodos para organizar y acceder a datos en ficheros, mencionando específicamente ficheros planos, indexados y de acceso directo, además de otros como los que usan funciones hash. "Archivo multimedia" no se define como un sistema lógico de almacenamiento, sino como un tipo de contenido (ej. imágenes, videos) que se almacena dentro de estos sistemas.

10. **¿A partir de qué año es posible gestionar los sistemas de gestión de bases de datos a nivel de usuario?**

- A partir de los años 80, con la aparición del lenguaje SQL. 
- En los años 80, con la llegada de SQL y los primeros ordenadores personales, los SGBD se volvieron manejables a nivel de usuario, simplificando su uso frente a la necesidad previa de personal cualificado. Aunque Oracle apareció en los 70, SQL (estandarizado en los 80) marcó el cambio hacia la accesibilidad general. Microsoft Access (90s) y los SGBD modernos (2000s) son posteriores.

11. **¿Qué sistemas aparecen en los años 60?**

- Los sistemas batch processing.
- En los años 60 surgieron los sistemas por lotes (batch processing), que ejecutaban programas sin supervisión continua, junto con ejemplos como SABRE. Las puertas lógicas AND son de los 40-50, los SGBD se desarrollan más tarde (70s con el modelo relacional), y la estandarización (SQL) llega en los 80.

12. **¿Cuál es una de las funciones principales de un sistema gestor de bases de datos (SGBD)?**

- Administrar y asegurar la integridad de los datos.
- Las funciones principales de un SGBD: definición (estructuras y restricciones), construcción (almacenamiento) y manipulación de datos, con énfasis en mantener seguridad e integridad. Diseñar interfaces es secundario, proveer un SO o crear redes no son funciones del SGBD.

13. **Los sistemas gestores de bases de datos distribuidos no ofrecen ventajas sobre los centralizados.**

- Falso.
- Las ventajas de las BBDD distribuidas sobre las centralizadas, son procesamiento más rápido, autonomía de nodos, fácil expansión y bajo costo en redes pequeñas. Aunque tienen inconvenientes (seguridad, complejidad), sí ofrecen beneficios claros.

14. **¿Cómo se clasifica un SGBD que maneja datos distribuidos en diferentes ubicaciones?**

- SGBD distribuido.
- Un SGBD que maneja datos en múltiples ubicaciones se clasifica como distribuido, diseñado para gestionar BBDD distribuidas con nodos interconectados. "Centralizado" implica una sola ubicación, "de red" y "orientado a objetos" son modelos de datos, no clasificaciones por ubicación.

15. **¿Qué componente del SGBD se encarga de definir la estructura de la base de datos?**

- Lenguaje de definición de datos (DDL).
- El DDL es el lenguaje que define la estructura de la BBDD (tablas, vistas, restricciones). El administrador de almacenamiento gestiona el almacenamiento físico, el controlador de transacciones las operaciones concurrentes, y el DML manipula datos, no los define.

16. **El GDPR es una legislación que protege los datos personales en los Estados Unidos.**

- Falso.
- El GDPR (General Data Protection Regulation) es una legislación europea, implementada en 2018, que regula la protección de datos personales en la Unión Europea. En Estados Unidos, las leyes relevantes incluyen la CCPA (California) o HIPAA (salud), pero no el GDPR.

17. **El Big Data se refiere a la gestión de grandes volúmenes de datos que no pueden ser manejados con técnicas tradicionales.**

- Verdadero.
- Aunque el libro no aborda Big Data explícitamente, el término se define comúnmente como el manejo de volúmenes masivos de datos que superan las capacidades de herramientas tradicionales (como SGBD relacionales clásicos), requiriendo tecnologías específicas (ej. Hadoop, NoSQL). Esto coincide con el conocimiento general, haciendo la afirmación verdadera.

18. ¿Cuál es una ventaja de las bases de datos distribuidas?

- Procesamiento más rápido.
- Una ventaja de las BBDD distribuidas el procesamiento más rápido gracias a la intervención de múltiples nodos. Las otras opciones son incorrectas: son más complejas de gestionar, sí requieren fragmentación (horizontal, vertical, mixta), y necesitan políticas de seguridad debido a riesgos mayores.

19. **La inteligencia de negocios (BI) es el uso de datos para tomar decisiones informadas.**

- Verdadero.
- La inteligencia de negocios (Business Intelligence, BI) se define como el análisis de datos para apoyar decisiones estratégicas y operativas, usando herramientas como informes y visualizaciones. Esto es un estándar en el campo, haciendo la afirmación verdadera.

20. ¿Qué legislación regula la protección de datos personales en Europa?

- GDPR.
- El GDPR (General Data Protection Regulation) es la legislación europea que regula la protección de datos personales desde 2018. SOX (Sarbanes-Oxley) regula finanzas en EE.UU., CCPA (California Consumer Privacy Act) es de California, y HIPAA (Health Insurance Portability and Accountability Act) protege datos de salud en EE.UU., no en Europa.