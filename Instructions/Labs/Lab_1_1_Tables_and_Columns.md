---
lab:
  title: 'Laboratorio 1.1: Creación y administración de tablas y columnas'
---

# Laboratorio 1.1: Creación y administración de tablas y columnas

## Escenario
Bellows College es una organización educativa con varios campus y programas. Muchos de los instructores y administradores de Bellow Colleges necesitan asistir a eventos y comprar artículos. Históricamente, el seguimiento de estos gastos ha sido un problema.
La administración del campus desea modernizar su sistema de informes de gastos y así proporcionar a los empleados un método digital de notificar los gastos.
Idealmente, quieren que sus usuarios completen un informe de gastos después de cada evento o compra. Para cada informe de gastos, quieren que puedan agregar elementos de línea de gastos individuales. Ya han empezado a trabajar en esta solución. Se ha creado la tabla Informe de gastos. Se te ha pedido que tomes el control del proyecto y lo completes.

## Pasos de alto nivel del laboratorio
Al completar este laboratorio, harás lo siguiente:
- Importa una solución a tu entorno que incluya la tabla Informe de gastos.
- Crear tabla de elementos de línea de gastos
- Agrega las columnas necesarias a la tabla de elementos de línea de gastos
- Agregue algunos datos de ejemplo.

## Requisitos previos
- Finalización del Módulo 1 Laboratorio 0: Validación del entorno de laboratorio

## Cuestiones que tener en cuenta antes de comenzar
- Convenciones de nomenclatura: escriba los nombres con cuidado.

## Ejercicio 1: Importar la solución Informe de gastos a tu entorno
**Objetivo:** en este ejercicio, importarás la solución Informe de gastos que incluye la tabla Informe de gastos.

### Tarea n.º 1: Importar la solución
La tabla Informe de gastos contendrá información sobre el informe de gastos que va a enviar el individuo.
1. Si aún no has iniciado sesión, inicia sesión en `make.powerapps.com` con tus credenciales de entorno.
2. En el menú Entorno de la parte superior derecha, asegúrate de que está en el entorno al que deseas importar la solución.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. En la barra de comandos de la parte superior, selecciona **Importar solución.**
5. Seleccione el botón **Examinar**.
6. Busca y selecciona el archivo de solución `ExpenseReport_1_0_0_1` que se encontraba en tus materiales del curso.
7. Seleccione el botón de **importación**.

*Nota: La solución puede tardar varios minutos en importarse al entorno.*

## Ejercicio 2: Crear tablas y columnas
**Objetivo:** en este ejercicio, importarás la solución Informe de gastos que incluye la tabla Informe de gastos.

### Tarea n.º 1: Crear tabla de línea de gastos
1. Si es necesario, ve al portal de Power Apps Maker.
2. Asegúrate de que estás trabajando en el entorno al que has importado la solución `ExpenseReport_1_0_0_1` durante el último ejercicio.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Busca y selecciona la solución Informe de gastos.
5. Seleccione el botón **Nuevo**.
6. En el menú que aparece, ve a **Tabla.** A continuación, selecciona **Establecer propiedades avanzadas.**
7. Configura tu nueva tabla de la siguiente manera:
   - Nombre para mostrar: `Expense Line`
   - Nombre en plural: `Expense Lines`
   - Habilitar datos adjuntos (incluyendo notas y archivos): seleccionado
8. Selecciona la pestaña Columna principal y cambia el Nombre para mostrar a Título del gasto.
9. Selecciona el botón Guardar.

*Nota: La creación de la tabla puede tardar uno o dos minutos.*

### Tarea n.º 2: Agregar las columnas necesarias a la tabla Línea de gastos
1. Con la tabla Línea de gastos abierta, selecciona Columnas en el grupo Esquema.
2. Seleccione **+ Nueva columna**.
3. Escribe **`Expense Type`** en Nombre para mostrar.
4. Selecciona **Opción > Opción** para Tipo de datos.
5. En Obligatorio, selecciona **Opcional.**
6. Establece Sincronizar con opción global en **Sí (recomendado)**.
7. En Sincronizar esta opción con el campo, selecciona **+ Nueva opción.**
8. En el campo Nombre para mostrar, escribe *`Expense Type`*.
9. En el campo Etiqueta de la primera opción, escribe *`Meals`*.
10. Selecciona **+ Nueva opción.**
11. En el campo Etiqueta, escribe *`Lodging`*.
12. Repite los pasos 10 y 11 para agregar las siguientes opciones:
    - `Travel`
    - `Entertainment`
    - `Supplies / Equipment`
    - `Other`
13. Selecciona el botón **Guardar**.
14. En el campo Sincronizar esta opción con, selecciona la opción **Tipo de gasto** que acabas de crear.
15. Establece el campo Opción predeterminada en **Ninguno.**
16. Seleccione **Guardar**.

### Tarea 3: Creación de la columna Importe del gasto
1. Seleccione + Nueva columna.
2. Escribe `Expense Amount` en Nombre para mostrar.
3. Selecciona Moneda para Tipo de datos.
4. Seleccione Guardar.

### Tarea 4: Creación de la columna Descripción del artículo
1. Seleccione **+ Nueva columna**.
2. Escribe *`Item Description`* en Nombre para mostrar.
3. Selecciona **Varias líneas de texto > Texto sin formato** para Tipo de datos.
4. Seleccione **Guardar**.

### Tarea 5: Creación de la columna Fecha del gasto
1. Seleccione **+ Nueva columna**.
2. Escribe *`Expense Date`* en Nombre para mostrar.
3. Selecciona **Solo fecha** en el grupo Fecha y hora del campo Tipo de datos.
4. Expanda **Opciones avanzadas**.
5. Establece el campo de ajuste Zona horaria en **Local del usuario.**
6. Seleccione **Guardar**.

### Tarea 6: Crear una columna Informe de gastos
1. Seleccione **+ Nueva columna**.
2. Escribe *`Expense Report`* en Nombre para mostrar.
3. Selecciona **Búsqueda** en el grupo Búsqueda del campo Tipo de datos.
4. En el campo Tabla relacionada, selecciona **Informe de gastos.**
5. Seleccione **Guardar**.

## Ejercicio 3: Editar tabla
**Objetivo:** en este ejercicio, modificarás manualmente una tabla.

### Tarea n.° 1: Modificación de las columnas mostradas
1. Si es necesario, ve al portal de Power Apps Maker.
2. Asegúrate de que estás trabajando en el entorno en el que has importado la solución **ExpenseReport_1_0_0_1** durante el último ejercicio.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Busca y selecciona la solución **Informe de gastos**.
5. En el panel de navegación de la izquierda, seleccione **Tablas**.
6. Abre la tabla Línea de gastos que se creó en el ejercicio anterior.
7. Junto a la columna Importar secuencia, selecciona **+[X] más**. (El número que se muestra aquí dependerá del tamaño del explorador).
8. En el menú que aparece, selecciona las columnas siguientes:
   - Cantidad del gasto (base)
   - Fecha del gasto (si aún no está seleccionada)
   - Informe de gastos
   - Tipo de gasto
   - Importe del gasto
   - Descripción del elemento
9. Seleccione el botón **Guardar**.
10. Busca la columna **Creado por** y selecciónala.
11. En el menú que aparece, selecciona **Ocultar.**
12. Repite los pasos 10 y 11 para quitar las columnas siguientes:
    - Creado por
    - Línea de gastos
    - Importar secuencia
