## Actividades

### Actividades para el Capítulo de Tipos de Datos en PL/SQL
```

Actividad 1: Identificar Tipos de Datos

Descripción: Investiga y escribe una lista de los tipos de datos escalares, compuestos y LOB en PL/SQL.

Instrucciones:

    Investiga los tipos de datos escalares (NUMBER, CHAR, VARCHAR2, DATE, BOOLEAN).
    Investiga los tipos de datos compuestos (RECORD, TABLE, VARRAY).
    Investiga los tipos de datos LOB (BLOB, CLOB, NCLOB, BFILE).
    Escribe un breve resumen de cada tipo de dato y proporciona un ejemplo de uso.
__________________

Actividad 2: Crear Tablas con Diferentes Tipos de Datos

Descripción: Crea una tabla que utilice una variedad de tipos de datos en sus columnas.

Instrucciones:

    Diseña una tabla llamada employee_data con las siguientes columnas:
        employee_id NUMBER
        first_name VARCHAR2(50)
        last_name VARCHAR2(50)
        birth_date DATE
        salary NUMBER(10, 2)
        is_active BOOLEAN
        resume CLOB
__________________


Actividad 3: Uso de Tipos de Datos Compuestos

Descripción: Crea un bloque PL/SQL que utilice tipos de datos compuestos.

Instrucciones:

    Declara un registro compuesto que contenga información de un empleado (employee_id, first_name, last_name).
    Llena el registro con valores.
    Usa un bucle para mostrar la información del registro.
__________________

```

### Actividades para el Capítulo de Declaración de Variables en PL/SQL

```
Actividad 1: Declaración e Inicialización de Variables

Descripción: Declara e inicializa variables en un bloque PL/SQL y muestra sus valores.

Instrucciones:

    Declara variables student_name (VARCHAR2) y student_id (NUMBER).
    Inicializa student_name con "Alice" y student_id con 101.
    Usa DBMS_OUTPUT.PUT_LINE para mostrar los valores de las variables.
__________________

Actividad 2: Alcance de Variables

Descripción: Demuestra el alcance de variables en bloques anidados.

Instrucciones:

    Declara una variable department_name en el bloque principal.
    Declara una variable employee_count en un sub-bloque.
    Muestra department_name y employee_count dentro del sub-bloque.
    Intenta mostrar employee_count fuera del sub-bloque (esto debe causar un error).   
__________________

Actividad 3: Uso de Constantes

Descripción: Declara y usa una constante en un cálculo matemático.

Instrucciones:

    Declara una constante PI con el valor 3.14159.
    Declara una variable radius e inicialízala con 10.
    Calcula el área de un círculo usando la fórmula PI * radius * radius.
    Muestra el área calculada.

```
### Actividades para el Capítulo de Estructuras de Control en PL/SQL

```
Actividad 1: Condicional IF-THEN

Descripción: Crear un programa en PL/SQL que determine si un número es positivo.

Instrucciones:

    Declara una variable v_num y asígnale un valor.
    Usa una estructura IF-THEN para verificar si el número es positivo.
    Si es positivo, imprime "El número es positivo".
__________________

Actividad 2: Condicional IF-THEN-ELSIF-ELSE

Descripción: Determinar la calificación de un estudiante basado en su nota.

Instrucciones:

    Declara una variable grade.
    Usa IF-THEN-ELSIF-ELSE para evaluar el rango de la nota y asignar una calificación.
    Imprime el resultado.
__________________

Actividad 3: Declaración CASE Simple

Descripción: Usar CASE para determinar la calificación de un estudiante basado en su nota.

Instrucciones:

    Declara una variable grade con un valor.
    Usa CASE para evaluar la nota y asignar una calificación.
    Imprime el resultado.
__________________

Actividad 4: Declaración CASE Buscada

Descripción: Usar Searched CASE para determinar la calificación de un estudiante basado en su nota numérica.

Instrucciones:

    Declara una variable grade con un valor.
    Usa Searched CASE para evaluar el rango de la nota numérica y asignar una calificación.
    Imprime el resultado.
```

### Actividades para el Capítulo de Bucles en PL/SQL

```
Actividad 1: Suma de Números del 1 al 100 con un Bucle FOR

Descripción: Crea un programa que calcule la suma de los números del 1 al 100 utilizando un bucle FOR.

Instrucciones:

    Declara una variable total para almacenar la suma.
    Usa un bucle FOR para iterar del 1 al 100.
    Suma cada número a total y muestra el resultado final.
__________________

Actividad 2: Recorrer una Tabla con un Cursor Explícito en un Bucle FOR

Descripción: Escribe un script que recorra la tabla employees y muestre los nombres de todos los empleados que tengan el campo JOB_ROLE como Developer.

Instrucciones:

    Usa un cursor explícito para seleccionar los empleados con el rol 'Developer'.
    Recorre los resultados con un bucle FOR.
    Imprime los nombres de los empleado
__________________

Actividad 3: Imprimir Números Pares del 1 al 20 con un Bucle WHILE

Descripción: Crea un programa que imprima todos los números pares del 1 al 20 utilizando un bucle WHILE.

Instrucciones:

    Declara una variable counter inicializada en 2.
    Usa un bucle WHILE para imprimir counter y aumentar su valor en 2.
    Detén el bucle cuando counter sea mayor a 20.
```

### Actividades para el Capítulo de Paquetesen PL/SQL

```
Actividad 1: Creación de un Package Specification

Descripción: Crea un package specification que gestione estudiantes, incluyendo procedimientos y funciones para agregar, eliminar y obtener información de los estudiantes.

Instrucciones:

    Declara el package specification llamado student_pkg.
    Define los procedimientos add_student y delete_student.
    Define la función get_student_name.
__________________

Actividad 2: Creación de un Package Body

Descripción: Crea el body para el package student_pkg con las definiciones de los procedimientos y la función declarados en el package specification.

Instrucciones:

    Implementa los procedimientos add_student y delete_student.
    Implementa la función get_student_name.
__________________

Actividad 3: Uso de Variables y Constantes en un Package

Descripción: Crea un package que declare una constante y una variable pública, y un procedimiento que use estos elementos.

Instrucciones:

    Declara una constante PI y una variable radius en el package specification.
    Implementa un procedimiento que calcule y muestre el área de un círculo usando estos elementos.
```

### Actividades para el Capítulo de Funciones y Procedimientos en PL/SQL

```
Actividad 1: Crear un Procedimiento para Agregar Estudiantes

Descripción: Crea un procedimiento llamado add_student que inserte un nuevo estudiante en una tabla students.

Instrucciones:

    Crea la tabla students con las columnas id, name, y age.
    Declara el procedimiento add_student en el package student_pkg.
    Implementa el procedimiento en el package body para insertar un estudiante.
__________________

Actividad 2: Crear una Función Independiente para Conversión de Temperatura

Descripción: Crea una función llamada convert_to_celsius que convierta una temperatura de Fahrenheit a Celsius.

Instrucciones:

    Declara e implementa la función convert_to_celsius.
    La función debe aceptar un parámetro de tipo NUMBER y retornar un NUMBER.
__________________

Actividad 3: Crear un Package para Calcular el Área de un Círculo

Descripción: Crea un package llamado circle_pkg que incluya una función calculate_area para calcular el área de un círculo dado su radio.

Instrucciones:

    Declara el package circle_pkg con la función calculate_area.
    Implementa la función en el package body.

```

### Actividades para el Capítulo de Manejo de Excepciones en PL/SQL

```
Actividad 1: Manejo de Excepciones Predefinidas

Descripción: Crea un procedimiento que intente insertar un valor duplicado en una tabla con una restricción de índice único y maneje la excepción predefinida DUP_VAL_ON_INDEX.

Instrucciones:

    Crea la tabla students con una restricción de índice único.
    Declara e implementa el procedimiento insert_student.
    Maneja la excepción DUP_VAL_ON_INDEX en el bloque de excepciones.
__________________

Actividad 2: Manejo de Excepciones Definidas por el Usuario

Descripción: Crea un procedimiento que divida dos números. Si el divisor es cero, lanza una excepción definida por el usuario y maneja la excepción.

Instrucciones:

    Declara una excepción definida por el usuario en el procedimiento divide_numbers.
    Implementa la lógica para manejar la excepción cuando el divisor sea cero.
__________________

Actividad 3: Uso de DBMS_UTILITY.FORMAT_ERROR_STACK para Manejar Excepciones

Descripción: Crea un procedimiento que intente acceder a una fila que no existe en una tabla y maneje la excepción usando DBMS_UTILITY.FORMAT_ERROR_STACK para mostrar la pila de errores.

Instrucciones:

    Implementa el procedimiento get_student_name que intente seleccionar un nombre de la tabla students.
    Maneja la excepción usando DBMS_UTILITY.FORMAT_ERROR_STACK.
```

### Actividades para el Capítulo de Triggers en PL/SQL

```
Actividad 1: Crear un Trigger para Registrar la Fecha y Hora de Inserción

Descripción: Crea un trigger que automáticamente registre la fecha y hora de inserción en una tabla employees cuando se inserte un nuevo registro.

Instrucciones:

    Crea la tabla employees con las columnas id, name, y hire_date.
    Implementa el trigger trg_insert_employee que se active antes de cada inserción para asignar la fecha y hora actuales a la columna hire_date.
__________________

Actividad 2: Trigger para Auditoría de Eliminación de Registros

Descripción: Crea un trigger que registre en una tabla de auditoría cualquier eliminación de registros en la tabla products.

Instrucciones:

    Crea la tabla products con las columnas product_id y product_name.
    Crea la tabla audit_log con las columnas audit_id, product_id, deleted_at, y deleted_by.
    Implementa el trigger trg_audit_delete que se active antes de cada eliminación en la tabla products y registre la información en la tabla audit_log.
__________________

Actividad 3: Trigger para Actualización de Inventario

Descripción: Crea un trigger que actualice el inventario de un producto en la tabla inventory cuando se realice una inserción en la tabla sales.

Instrucciones:

    Crea la tabla inventory con las columnas product_id y quantity.
    Crea la tabla sales con las columnas sale_id, product_id, y quantity_sold.
    Implementa el trigger trg_update_inventory que se active después de cada inserción en la tabla sales y actualice la cantidad en la tabla inventory.
```

### Operadores
```
Operadores Relacionales

    = : Igual a
    != o <> : Diferente de
    > : Mayor que
    < : Menor que
    >= : Mayor o igual que
    <= : Menor o igual que

Operadores Lógicos

    AND : Verdadero si ambas condiciones son verdaderas
    OR : Verdadero si al menos una condición es verdadera
    NOT : Invierte el valor de verdad de la condición

Operadores de Comparación Especiales

    IS NULL : Verdadero si el valor es NULL
    IS NOT NULL : Verdadero si el valor no es NULL
    LIKE : Verdadero si una cadena coincide con un patrón
    IN : Verdadero si un valor está en una lista de valores
    BETWEEN : Verdadero si un valor está dentro de un rango de valores
```