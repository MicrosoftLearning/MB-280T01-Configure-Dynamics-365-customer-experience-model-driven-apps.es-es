---
lab:
  title: 'Laboratorio 4.1: Visualizar datos con vistas'
---

# Laboratorio 4.1: Visualizar datos con vistas

## Escenario

Bellows College es una organización educativa con varios campus y programas. Muchos de los instructores y administradores de Bellow Colleges necesitan asistir a eventos y comprar artículos. Históricamente, el seguimiento de estos gastos ha sido un problema.

La administración del campus desea modernizar su sistema de informes de gastos y así proporcionar a los empleados un método digital de notificar los gastos.

A lo largo de este curso, creará aplicaciones y realizará la automatización para que los empleados de Bellows College puedan administrar los gastos.

## Pasos de alto nivel del laboratorio

Como parte de la creación de la aplicación basada en modelo, completará lo siguiente:

Crea vistas diferentes para ver los elementos del informe de gastos.

Trabajaremos con los siguientes componentes:

Vistas: Las vistas permiten al usuario mostrar los datos existentes en la tabla del formulario.

## Requisitos previos

Finalización del Módulo 1 Laboratorio 0: Validar el entorno de laboratorio

## Ejercicio 1: Administración de vistas

**Objectivo:**  en este ejercicio, crearás una nueva vista que se puede usar más adelante en aplicaciones controladas por modelos.

### Tarea n.º 1: Editar las distintas vistas de líneas de gastos

1. Si aún no lo estás, inicia sesión en https://make.powerapps.com.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. Busca y abre la tabla Línea de gastos.
6. En Experiencias de datos, selecciona **Vistas**.
7. Abre la vista **Líneas de gastos activos**.
8. Haz clic en **Seleccionar columna de vista.** Selecciona **Fecha de gasto, Descripción del elemento, Tipo de gasto** y **Importe de gastos.**
9. Busca y selecciona la columna **Fecha de creación**. En el menú que aparece, selecciona **Quitar.**
10. La vista debe tener las columnas Título de gastos, Fecha de gasto, Descripción del elemento, Tipo de gasto y Importe de gastos en ella.
11. Selecciona el botón **Guardar y publicar**.
12. Selecciona el botón Atrás para volver a la lista de vistas.

Después, repetiremos ese proceso para actualizar la vista asociada a la línea de gastos. Esta es la vista que aparecerá cuando examines las líneas de gastos de una tabla principal, como el informe de gastos.

### Tarea n.º 2: Actualizar la vista asociada de la línea de gastos 

1. Busca y abre la vista asociada de línea de gastos.
2. Haz clic en **Seleccionar columna de vista.** Selecciona **Fecha de gasto, Descripción del elemento, Tipo de gasto** y **Importe de gastos.**
3. Busca y selecciona la columna **Fecha de creación**. En el menú que aparece, selecciona **Quitar.**
4. La vista debe tener las columnas Título de gastos, Fecha de gasto, Descripción del elemento, Tipo de gasto y Importe de gastos en ella.
5. Selecciona el botón **Guardar y publicar**.
6. Selecciona el botón Atrás para volver a la lista de vistas.

Por último, repetiremos ese proceso una vez más para actualizar la Búsqueda rápida de líneas de gastos activas. Esta es la vista que se usa cada vez que un usuario usa el campo de búsqueda para buscar una línea de gastos específica.

### Tarea n.º 3: Actualizar la vista Búsqueda rápida

1. Busca y abre la vista Búsqueda rápida de líneas de gastos activos.
2. Haz clic en **Seleccionar columna de vista.** Selecciona **Fecha de gasto, Descripción del elemento, Tipo de gasto** e **Importe de gastos.**
3. Busca y selecciona la columna **Fecha de creación**. En el menú que aparece, selecciona **Quitar.**
4. La vista debe tener las columnas Título de gastos, Fecha de gasto, Descripción del elemento, Tipo de gasto y Importe de gastos en ella.
5. En el lado derecho de la pantalla, en la sección Buscar por, selecciona **Editar columnas de tabla de búsqueda.**
6. Agrega las siguientes columnas:
    - Fecha del gasto
    - Tipo de gasto
7. Seleccione el botón **Aplicar**.
8. Selecciona el botón **Guardar y publicar**.
9. Selecciona el botón Atrás para volver a la lista de vistas.

### Tarea n.º 4: Editar las distintas vistas de informes de gastos

1. Si aún no lo estás, inicia sesión en https://make.powerapps.com.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. Busca y selecciona la tabla Informe de gastos.
6. En Experiencias de datos, selecciona **Vistas**.
7. Abre la vista **Informes de gastos activos**.
8. Haz clic en **Seleccionar columna de vista.** Selecciona **Propósito del informe, Fecha de vencimiento del informe, Total del informe** y **Fecha de última aprobación.**
9. Busca y selecciona la columna **Fecha de creación**. En el menú que aparece, selecciona **Quitar.**
10. La vista debe tener las columnas Propósito del informe, Fecha de vencimiento del informe, Total del informe y Fecha de última aprobación.
11. Selecciona el botón **Guardar y publicar**.
12. Selecciona el botón Atrás para volver a la lista de vistas.

A continuación, repetiremos ese proceso para actualizar la vista Informes de gastos inactivos.

### Tarea n.º 5: Actualizar la vista Informes de gastos inactivos

1. Busca y abre la vista Informes de gastos inactivos.
2. Haz clic en **Seleccionar columna de vista.** Selecciona **Propósito del informe, Fecha de vencimiento del informe, Total del informe** y **Fecha de última aprobación.**
3. Busca y selecciona la columna **Fecha de creación**. En el menú que aparece, selecciona **Quitar.**
4. La vista debe tener las columnas Propósito del informe, Fecha de vencimiento del informe, Total del informe y Fecha de última aprobación.
5. Selecciona el botón **Guardar y publicar**.
6. Selecciona el botón Atrás para volver a la lista de vistas.

### Tarea nº 6: Actualizar la vista Búsqueda rápida de informes de gastos activos 

Por último, repetiremos ese proceso una vez más para actualizar la vista Búsqueda rápida de informes de gastos activos. Esta es la vista que se usa cada vez que un usuario usa el campo de búsqueda para buscar un informe de gastos específico.

1. Busca y abre la vista Búsqueda rápida de informes de gastos activos.
2. Haz clic en **Seleccionar columna de vista.** Selecciona **Propósito del informe, Fecha de vencimiento del informe, Total del informe** y **Fecha de última aprobación.**
3. Busca y selecciona la columna **Fecha de creación**. En el menú que aparece, selecciona **Quitar.**
4. La vista debe tener las columnas Propósito del informe, Fecha de vencimiento del informe, Total del informe y Fecha de última aprobación.
5. En el lado derecho de la pantalla, en la sección Buscar por, selecciona **Editar columnas de tabla de búsqueda.**
6. Agrega la columna Propósito del informe.
7. Seleccione el botón **Aplicar**.
8. Selecciona el botón **Guardar y publicar**.
9. Selecciona el botón Atrás para volver a la lista de vistas.

### Tarea n.º 7: Crear una nueva vista denominada Informes de gastos que vencen hoy

1. Si aún no lo estás, inicia sesión en https://make.powerapps.com.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. Busca y selecciona la tabla Informe de gastos.
6. En Experiencias de datos, selecciona **Vistas**.
7. Abra la vista Informes de gastos activos.
8. Selecciona el botón **Guardar como**.
9. Cambia el nombre a *Informes de gastos que vencen hoy.*
10. Selecciona el botón **Guardar**.
11. En la sección Filtrar por, selecciona **Editar filtros.**
12. Selecciona el botón **Agregar**. En el menú que aparece, selecciona **Agregar fila.**
13. Selecciona la flecha desplegable en la primera fila en blanco. En el menú que aparece, selecciona la columna **Fecha de vencimiento del informe**.
14. Cambia el campo Igual a **Hoy.**
15. Selecciona el botón **Aceptar**.
16. Seleccione el botón **Guardar y publicar**.
