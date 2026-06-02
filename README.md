# Integridad de Datos en Bases de Datos Relacionales

## Introducción

En la actualidad, las organizaciones dependen de grandes volúmenes de información para realizar sus actividades diarias. Empresas, hospitales, universidades y bancos almacenan datos en bases de datos relacionales para garantizar una gestión eficiente de la información. Sin embargo, para que estos datos sean útiles, deben mantenerse correctos, completos y consistentes. Para ello existen las reglas de integridad, las cuales permiten controlar la calidad y confiabilidad de la información almacenada.

## Concepto de Integridad de Datos

La integridad de datos es la propiedad que garantiza que la información almacenada en una base de datos permanezca exacta, consistente y válida durante todas las operaciones realizadas sobre ella. Su principal objetivo es evitar errores, inconsistencias y pérdidas de información que puedan afectar el funcionamiento de un sistema.

La integridad es uno de los pilares fundamentales del modelo relacional, ya que permite que los datos mantengan relaciones correctas y reflejen la realidad que representan.

---

## Principales Tipos de Integridad

### Integridad de Entidad

Este tipo de integridad asegura que cada fila o registro dentro de una tabla pueda identificarse de forma única.

Se logra mediante el uso de una clave primaria (Primary Key), la cual no admite valores nulos ni duplicados.

#### Ejemplo

En una tabla de empleados, el número de identificación de cada trabajador debe ser único para evitar confusiones o duplicaciones.

#### Ventajas

- Identificación única de registros.
- Evita duplicidad de información.
- Facilita la administración de los datos.

---

### Integridad Referencial

Garantiza que las relaciones entre las tablas sean coherentes.

Cuando una tabla utiliza una clave foránea (Foreign Key), esta debe corresponder a un registro existente en la tabla principal.

#### Ejemplo

Si una tabla de ventas contiene el código de un cliente, dicho cliente debe existir previamente en la tabla de clientes.

#### Ventajas

- Mantiene la consistencia de las relaciones.
- Evita registros huérfanos.
- Mejora la organización de la información.

---

### Integridad de Dominio

Controla los valores permitidos en cada columna de una tabla.

Las restricciones pueden incluir:

- Tipo de dato.
- Tamaño máximo.
- Rangos permitidos.
- Formatos específicos.

#### Ejemplo

Una columna que almacena edades puede aceptar únicamente números positivos entre 0 y 120.

#### Ventajas

- Reduce errores de captura.
- Mejora la calidad de los datos.
- Garantiza formatos adecuados.

---

### Integridad de Negocio o Definida por el Usuario

Corresponde a reglas específicas establecidas según las necesidades de una organización.

#### Ejemplo

En una universidad:

- Un estudiante debe aprobar los prerrequisitos antes de matricular una asignatura.

En un banco:

- Una transferencia no puede exceder el saldo disponible.

#### Ventajas

- Permite personalizar el sistema.
- Garantiza el cumplimiento de políticas internas.

---

## Importancia de la Integridad de Datos

La integridad de datos es esencial porque:

- Incrementa la confiabilidad de la información.
- Reduce errores operativos.
- Facilita la generación de reportes.
- Mejora la toma de decisiones.
- Protege la calidad de los datos a largo plazo.

Sin integridad, una base de datos podría contener información contradictoria o incorrecta, afectando directamente a usuarios y organizaciones.

---

## Aplicaciones en la Vida Real

### Sector Bancario

Los bancos utilizan reglas de integridad para evitar transacciones inválidas y garantizar que los saldos de las cuentas sean correctos.

### Sector Educativo

Las universidades controlan matrículas, notas y datos estudiantiles mediante restricciones que aseguran la consistencia de la información.

### Sector Salud

Los hospitales emplean integridad de datos para mantener historiales médicos precisos y evitar errores en tratamientos o diagnósticos.

### Comercio Electrónico

Las tiendas en línea verifican productos, clientes y pedidos mediante relaciones consistentes entre tablas.

---

## Desafíos para Mantener la Integridad

Algunos factores que pueden afectar la integridad de los datos son:

- Errores humanos.
- Fallos de software.
- Ataques informáticos.
- Actualizaciones incorrectas.
- Diseño deficiente de la base de datos.

Por ello, es necesario implementar mecanismos de control y validación desde el diseño inicial del sistema.

---

## Conclusión

La integridad de datos constituye un elemento indispensable en las bases de datos relacionales. Gracias a las reglas de integridad de entidad, referencial, de dominio y de negocio, es posible garantizar información precisa, consistente y confiable. Su correcta implementación permite que las organizaciones administren sus recursos de información de manera eficiente, reduciendo errores y mejorando la calidad de los procesos que dependen de los datos almacenados.

---

## Referencias

- Connolly, T., & Begg, C. (2015). *Database Systems: A Practical Approach to Design, Implementation, and Management* (6th ed.). Pearson.

- Coronel, C., & Morris, S. (2019). *Database Systems: Design, Implementation, & Management* (13th ed.). Cengage Learning.

- Date, C. J. (2019). *An Introduction to Database Systems* (8th ed.). Pearson Education.

- Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.

- Silberschatz, A., Korth, H. F., & Sudarshan, S. (2019). *Database System Concepts* (7th ed.). McGraw-Hill Education.
