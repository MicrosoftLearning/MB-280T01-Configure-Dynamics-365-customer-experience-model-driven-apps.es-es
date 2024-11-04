---
lab:
  title: 'Laboratorio 2.1: Creación de campos calculados y consolidados'
---

# Laboratorio 2.1: Creación de campos calculados y consolidados 

## Escenario
Bellows College es una organización educativa con varios campus y programas. Muchos de los instructores y administradores de Bellow Colleges necesitan asistir a eventos y comprar artículos. Históricamente, el seguimiento de estos gastos ha sido un problema.
La administración del campus desea modernizar su sistema de informes de gastos y así proporcionar a los empleados un método digital de notificar los gastos.
Idealmente, quieren que sus usuarios completen un informe de gastos después de cada evento o compra. Para cada informe de gastos, quieren que puedan agregar elementos de línea de gastos individuales. Ya han empezado a trabajar en esta solución. Se ha creado la tabla Informe de gastos. Se te ha pedido que tomes el control del proyecto y lo completes.

## Pasos de alto nivel del laboratorio
Al completar este laboratorio, harás lo siguiente:
- Agregar nuevos campos a una tabla existente
- Crear un campo consolidado
- Crear un campo calculado

## Requisitos previos
- Finalización del Módulo 1 Laboratorio 0: Validar el entorno de laboratorio y el Laboratorio 1.1, en el que has importado la solución Informe de gastos.

## Cuestiones que tener en cuenta antes de comenzar
- Convenciones de nomenclatura: escriba los nombres con cuidado.

## Ejercicio 1: Crear campos calculados y consolidados
**Objetivo:** en este ejercicio, crea un paquete consolidado y un campo calculado en la tabla de informe de gastos.

### Tarea n.º 1: Agregar un campo acumulativo a la tabla Informe de gastos
1. Si es necesario, ve al portal de Power Apps Maker.
2. Asegúrate de que estás trabajando en el entorno al que has importado la solución Informe de gastos durante el último ejercicio.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Busca y selecciona la solución Informe de gastos.
5. Busca y selecciona la tabla Informe de gastos.
6. En el grupo Esquema, selecciona **Columnas.**
7. Selecciona **+Nueva columna.**
8. Escribe *`Report Total`* en Nombre para mostrar.
9. Selecciona **Moneda** para Tipo de datos.
10. En Obligatorio, selecciona **Opcional.**
11. En el campo Comportamiento, selecciona **Consolidado.**
12. Selecciona el botón **Guardar**. (Debes guardar la columna para poder configurarla.)
13. Una vez guardada la columna, debería aparecer una ventana emergente. (Si recibes un mensaje emergente, es posible que tengas que permitir elementos emergentes.)
14. En ENTIDAD RELACIONADA, selecciona **+Agregar entidad relacionada.**
15. Selecciona **(Líneas de gastos) Informe de gastos.**
16. Selecciona el botón Marca de verificación para aceptar el cambio.
17. En AGREGACIÓN, selecciona **+Agregar agregación.**
18. Establece la función de agregado en **Suma.**
19. Establece el campo Entidad relacionada agregada en **(Línea de gastos) Importe de gastos.**
20. Selecciona la marca de verificación verde y después selecciona el botón **Guardar y cerrar**.

### Tarea n.º 2: Agregar un campo calculado de fórmula Power FX a la tabla Informe de gastos
1. Si es necesario, ve al portal de Power Apps Maker.
2. Asegúrate de que estás trabajando en el entorno al que has importado la solución Informe de gastos durante el último ejercicio.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Busca y selecciona la solución Informe de gastos.
5. Busca y selecciona la tabla Informe de gastos.
6. En el grupo Esquema, selecciona **Columnas.**
7. Selecciona **+Nueva columna.**
8. Escribe *`Last Date for approval`* en Nombre para mostrar.
9. Selecciona **Fórmula** en Tipo de datos.
10. Escribe la siguiente fórmula: `DateAdd('Report Due Date',2)`
11. Establece el campo Formato en **Solo fecha.**
12. Selecciona el botón **Guardar**. (Debes guardar la columna para poder configurarla.)
