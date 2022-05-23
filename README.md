# 🤙🏼 Reportes de Gestión Ágil

### ¿De que trata este repo? 👀
Este repositorio tiene como fin será parte de un entregable para la materia de gestión ágil, la cual estará relacionada con la metodología de trabajo SCRUM, el proyecto estará dividido en la sección de documentación y desarrollo. El software a entregar será una aplicación de 'Integration Services' usando <img src="https://1000logos.net/wp-content/uploads/2020/08/Visual-Studio-Logo.png" 
alt="IMAGE ALT TEXT" height="13"/> Visual Studio como IDE, <img src="https://img.icons8.com/color/480/microsoft-sql-server.png" 
alt="IMAGE ALT TEXT" height="13"/> Sql Server como motor de base de datos y <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" 
alt="IMAGE ALT TEXT" height="13"/> GitHub como gestor de versiones, por otro lado, para la administración de tareas usaremos <img src="https://seeklogo.com/images/C/clickup-symbol-logo-BB24230BBB-seeklogo.com.png" 
alt="IMAGE ALT TEXT" height="13"/> ClickUp para los sprints y el ambiente de Google para los <img src="https://cdn-icons-png.flaticon.com/512/5968/5968517.png" 
alt="IMAGE ALT TEXT" height="13"/> documentos a llenar, igualmente estaremos subiendo los docs a la carpeta documentación.

### Caso de Estudio 📚

Emasa S.A en busca de convertirse en la empresa más exitosa del rubro automotriz decidió en conjunto con el directorio de la compañía, incorporar a su área de inteligencia de negocios un grupo de ingenieros que permitan apoyar con informes diarios la toma de decisiones. Usted y su equipo de trabajo deberán liderar esta iniciativa y permitir a los directivos tomar las mejores decisiones tácticas y estratégicas para mantener a sus clientes al día con respecto a los productos que está solicitando durante un periodo determinado. Esto para cumplir con el compromiso de la gerencia general que es entregar el mejor servicio de distribución y atención al cliente en Chile, Perú y Colombia.

#### REQUERIMIENTOS GENERAL: 

1. 🤖 Automatizar una tarea que envíe un correo electrónico con un reporte adjunto.


+ Reporte_1 debe evidenciar lo siguiente:

Totalizar cantidad por owner. (Debe mostrar owner y la cantidad totalizada). Debe generar archivo Excel con los datos requeridos y enviar por correo adjunto. Considere que el reporte se debe generar de manera automática de lunes a viernes a las 08:30 hrs.
>Nota: Recuerde que para automatizar su modelo debe utilizar el catálogo de integración de servicios. Importante, el archivo debe ser enviado a la dirección da.carrascod@profesor.duoc.cl

2. 👩🏼‍🔬 Generar reporte en Excel que permita obtener la siguiente información. Considere como nombre de la hoja Reporte General

>Importante, considere que el reporte debe quedar almacenado en la siguiente ruta C:\Informes_diarios. Esto debe ser parte de su proyecto, esto con el fin de automatizar por completo el ejercicio

Nombre_areticulo | Id_articulo | Procedencia | Cantidad | Dia | Mes | Año | Comuna
--- | --- | --- | --- | --- | --- | --- | ---


+ Evidencia de estadísticas iniciales de su planilla (Max, Min y Promedio) Hoja Ventas
+ Agrupe por mes y owner, evidenciando la cantidad total asociada. Hoja Venta_Owner 
+ Agrupe owner y procedencia, posteriormente debe evidenciar la cantidad total asociada. Hoja Venta_Procedencia
>Nota Importante: Deberá documentar el paso a paso de los puntos requeridos en esta actividad

3. 📃 Por un requerimiento especial se requiere generar un nuevo reporte que muestre:
+ Nombre de comuna y cantidad total de artículos vendidos.
+ Nombre del owner y cantidad de despachos realizados a cada comuna.
>Es importante resaltar que una ventana emergente debe controlar si se lleva a cabo la acción de este reporte. Considere dentro del proceso la creación de un directorio en la raíz del disco C con el nombre de Reporte_Especial.
