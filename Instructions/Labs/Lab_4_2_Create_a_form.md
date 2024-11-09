---
lab:
  title: 'Laboratorio 4.2: Crear formularios'
---

# Laboratorio 4.2: Crear formularios

## Escenario
Bellows College es una organización educativa con varios campus y programas. Muchos de los instructores y administradores de Bellow Colleges necesitan asistir a eventos y comprar artículos. Históricamente, el seguimiento de estos gastos ha sido un problema.
La administración del campus desea modernizar su sistema de informes de gastos y así proporcionar a los empleados un método digital de notificar los gastos.
A lo largo de este curso, creará aplicaciones y realizará la automatización para que los empleados de Bellows College puedan administrar los gastos.

## Pasos de alto nivel del laboratorio
Tras finalizar correctamente este laboratorio, habrás completado lo siguiente:
- Personaliza el formulario de tabla para que se adapte mejor a tus necesidades.

Trabajaremos con los siguientes componentes:
- Formularios: Aquí es donde el usuario crea/actualiza nuevas filas en las tablas.

## Requisitos previos
- Finalización del Módulo 1 Laboratorio 0: Validación del entorno de laboratorio

## Ejercicio 1: Personalizar las vistas y los formularios
**Objetivo:** En este ejercicio, personalizará las vistas y formularios de las tablas creadas de manera personalizada que se utilizarán en la aplicación basada en modelo.

### Tarea n.° 1: Editar formulario de informe de gastos
1. Si aún no lo estás, inicia sesión en `https://make.powerapps.com`.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. Busca y selecciona la tabla Informe de gastos.
6. En la sección Experiencias de datos, selecciona **Formularios** y abra el formulario Información con el tipo de formulario Principal. (Importante: Asegúrese de seleccionar el formulario que tiene el tipo de formato Principal).

**IMPORTANTE:** Dado que, de forma predeterminada, todos los formularios se denominan Información, asegúrate de comprobar que el formulario que seleccionas sea del tipo de formulario Principal y no cualquier otro. De forma predeterminada, el formulario tiene dos campos: Nombre del informe y Propietario.

### Tarea n.º 2: Seleccionar columnas para el formulario
1. En la parte derecha de la pantalla, en el panel Propiedades, selecciona el campo **Nombre** y cámbialo por `Report Information`.
2. Selecciona **Columnas de tabla** en el panel de navegación izquierdo y agrega los campos siguientes debajo del campo Propietario. Para ello, arrastra las columnas hasta el formulario o simplemente haz clic en los nombres de las columnas:
    - Descripción
    - Propósito del informe
    - Fecha de vencimiento del informe
    - Total del informe
3. Arrastre la columna **Razón para el estado** y suéltela en el encabezado del formulario. El encabezado está en la parte superior derecha del formulario. Es posible que deba contraer el panel Propiedades en el lado derecho de la pantalla para ver el campo en el formulario.
4. Arrastre la columna **Última fecha de aprobación** y suéltela junto a Razón para el estado en el encabezado del formulario.
5. Seleccione el campo **Propietario**. En el panel Propiedades, cambia la etiqueta por *`Requestor`*.
6. Con la navegación de la izquierda, selecciona **Componentes.**
7. Selecciona la sección de 1 columna para agregarla debajo de la sección actual.
8. En la pantalla Propiedades, cambia la etiqueta por **`Expense Lines`**.
9. Con la sección Línea de gastos aún seleccionada, busca y selecciona el componente **Subgrid**.
10. Selecciona la casilla **Mostrar registros relacionados**.
11. Establece la tabla en **Líneas de gastos (Informe de gastos).**
12. Establece la vista predeterminada en **Líneas de gasto activas.**
13. Seleccione **Listo**.
14. Seleccione el botón **Guardar y publicar** en la parte superior derecha y espere a que se complete la operación.
15. Selecciona el botón Atrás en la parte superior izquierda de la pantalla. Ahora debería estar de nuevo en los formularios de la tabla Informe de gastos.

### Tarea n.º 3: Editar formulario Línea de gastos activos
En esta tarea, modificaremos el formulario que se usa para agregar elementos de línea de gastos.

1. Si aún no lo está, inicie sesión en `https://make.powerapps.com`
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona Soluciones.
4. Abre la solución Informe de gastos.
5. Busca y abre la tabla Línea de gastos.
6. En la sección Experiencias de datos, seleccione Formularios y abra el formulario Información con el tipo de formulario Principal. (Importante: Asegúrese de seleccionar el formulario que tiene el tipo de formato Principal).

**IMPORTANTE:** Dado que, de forma predeterminada, todos los formularios se denominan Información, asegúrate de comprobar que el formulario que seleccionas sea del tipo de formulario Principal y no cualquier otro. De manera predeterminada, el formulario tiene dos campos: Título del gasto y Propietario.

1. En el lado derecho de la pantalla, en el panel **Propiedades**, selecciona el campo **Nombre para mostrar** y cámbialo a `Item Details`.
2. Selecciona **Columnas de tabla** en el panel de navegación izquierdo y agrega los campos siguientes debajo del campo Propietario. Para ello, arrastra las columnas hasta el formulario o simplemente haz clic en los nombres de las columnas:
    - Tipo de gasto
    - Descripción del elemento
    - Importe del gasto
    - Informe de gastos
3. Arrastre la columna **Razón para el estado** y suéltela en el encabezado del formulario. El encabezado está en la parte superior derecha del formulario. Es posible que deba contraer el panel Propiedades en el lado derecho de la pantalla para ver el campo en el formulario.
4. Seleccione el botón **Guardar y publicar**.
