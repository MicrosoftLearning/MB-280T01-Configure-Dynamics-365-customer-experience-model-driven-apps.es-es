---
lab:
  title: 'Laboratorio 4.3: Crear un panel'
---

# Laboratorio 4.3: Crear un panel 

## Escenario
Bellows College es una organización educativa con varios campus y programas. Muchos de los instructores y administradores de Bellow Colleges necesitan asistir a eventos y comprar artículos. Históricamente, el seguimiento de estos gastos ha sido un problema.
La administración del campus desea modernizar su sistema de informes de gastos y así proporcionar a los empleados un método digital de notificar los gastos.
A lo largo de este curso, creará aplicaciones y realizará la automatización para que los empleados de Bellows College puedan administrar los gastos.

## Pasos de alto nivel del laboratorio
Al completar este laboratorio, harás lo siguiente:
- Crear una nueva aplicación basada en modelo
- Crear un panel personal que muestre la información del informe de gastos
- Adición de vistas y paneles a la aplicación basada en modelo

## Requisitos previos
- Finalización del Módulo 1 Laboratorio 0: Validación del entorno de laboratorio

## Ejercicio 1: Creación de un panel personal

### Tarea n.º 1: Crea tu nueva aplicación basada en modelo
1. Si aún no lo estás, inicia sesión en `https://make.powerapps.com`.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. En la barra de comandos, selecciona el botón **+ Nuevo**.
6. En el menú que aparece, ve a **Aplicación > Aplicación basada en modelo.**
7. Escribe *`Employee Expense Management`* en Nombre y selecciona **Crear.**

### Tarea n.º 2: Crear una nueva vista denominada Mis informes de gastos activos
1. Si aún no lo estás, inicia sesión en `https://make.powerapps.com`.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. Busca y selecciona la tabla Informe de gastos.
6. En Experiencias de datos, selecciona **Vistas**.
7. Abre la vista **Informes de gastos activos**.
8. Selecciona el botón **Guardar como**.
9. Cambia el nombre a *`My Active Expense Reports`*.
10. Selecciona el botón **Guardar**.
11. En la sección Filtrar por, selecciona **Editar filtros.**
12. Selecciona el botón **Agregar**. En el menú que aparece, selecciona **Agregar fila.**
13. Selecciona la flecha desplegable en la primera fila en blanco. En el menú que aparece, selecciona la columna **Propietario**.
14. Cambia el campo **Igual a** por Igual al usuario actual.
15. Selecciona el botón **Aceptar**.
16. Seleccione el botón **Guardar y publicar**.

### Tarea n.º 3: Agregar una sección Paneles a la aplicación Administración de gastos de los empleados
1. Si aún no lo estás, inicia sesión en https://make.powerapps.com.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. Selecciona **Aplicaciones**.
6. Busca la aplicación de Administración de gastos de los empleados.
7. Selecciona los **Puntos suspensivos verticales**, y en el menú que aparece, selecciona **Editar.**
8. Selecciona el botón **Agregar página**.
9. Seleccione **Panel**.
10. Explora los paneles del sistema que están disponibles de forma predeterminada. Cuando estés listo, selecciona uno de los paneles que deseas agregar a la aplicación.
11. Seleccione **Agregar**.
12. Mantén el puntero sobre el grupo Informes de gastos en Navegación.
13. Seleccione los **puntos suspensivos**. En el menú que aparece, selecciona **Nuevo grupo.**
14. Con nuevo grupo seleccionado, cambia el título a **Paneles.**
15. Selecciona los puntos suspensivos situados junto a los paneles y elige **Subir.** El panel ahora debe encontrarse encima de Informes de gastos.
16. Busca y selecciona el panel del sistema que has agregado anteriormente en la tarea.
17. Selecciona los puntos suspensivos y, en el menú que aparece, selecciona **Subir.**
18. Repite el paso 17 para mover el panel del sistema encima de la vista Informes de gastos.
19. Repite el paso 17 una vez más para mover el panel del sistema al grupo Paneles.
20. Selecciona el botón **Guardar**.
21. Una vez completado el guardado selecciona el botón **Publicar**.

### Tarea n.º 4: Agregar un panel personal a la aplicación Administración de gastos de los empleados
1. Si aún no lo estás, inicia sesión en `https://make.powerapps.com`.
2. Selecciona el entorno al que has importado la solución Informe de gastos en la parte superior derecha si aún no está seleccionada.
3. En el panel de navegación de la izquierda, selecciona **Soluciones.**
4. Abre la solución Informe de gastos.
5. Selecciona **Aplicaciones**.
6. Busca la aplicación basada en modelo de Administración de gastos de los empleados.
7. Selecciona los **puntos suspensivos verticales**. En el menú que aparece, selecciona **Reproducir.**
8. En el grupo Paneles, selecciona el panel del sistema que has agregado en la tarea 3.
9. Seleccione el botón **Nuevo**.
10. En el menú que aparece, selecciona **Panel de Dynamics 365.**
11. Elige **Panel normal de 2 columnas.**
12. Selecciona el botón **Crear**.
13. Cambia el nombre del panel a *`Expense Report Dashboard`*.
14. En la sección superior izquierda, selecciona el **icono Lista.**
15. Configura la lista como sigue:
    - Tipo de registro: informes de gastos
    - Vista: informes de gastos que vencen hoy.
16. Selecciona el botón **Agregar**.
17. En la sección superior derecha, selecciona el **icono Lista.**
18. Configura la lista como sigue:
    - Tipo de registro: informes de gastos
    - Vista: mis informes de gastos activos.
19. Selecciona el botón **Agregar**.
20. En la sección inferior izquierda, selecciona el **icono Lista.**
21. Configura la lista como sigue:
    - Tipo de registro: líneas de gastos
    - Vista: mis líneas de gastos activos.
22. Selecciona el botón **Agregar**.
23. En la sección inferior derecha, selecciona el **icono Lista.**
24. Configura la lista como sigue:
    - Tipo de registro: contactos
    - Vista: contactos activos.
25. Selecciona el botón **Agregar**.
26. Selecciona el botón **Guardar** en la esquina superior izquierda.
27. Una vez guardado el panel, selecciona el **botón Cerrar**.
28. Debes ir al panel Informe de gastos.
29. En la barra de comandos de la parte superior, selecciona **Establecer como predeterminado.**
