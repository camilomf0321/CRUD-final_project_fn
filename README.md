# CRUD-final_project_fn

<h1>Hello, world!</h1>

Este es mi proyecto final para el curso BD
<br><br><br><br>

## Contents<br><br>

- [Introducción]<br>
- [Requerimientos]<br>
  - [Requerimientos funcionales]<br>
  - [Requerimientos no funcionales]<br>
- [Herramientas usadas para la solución]<br>
- [Necesidad]<br>
- [Arquitectura de software]<br>
- [Metodología usada]<br>

<br><br><br><br>
## Introducción<br><br>
Software de inventario de empleados<br><br>

El presente trabajo tiene como objetivo presentar una propuesta de software con funciones CRUD para la gestion sobre datos de empleados 
Adicionalmente el informe tendrá los requerimientos relacionados con los alcances del proyecto, el diseño de la interfaz, el modelo entidad relación, el código de la aplicación del escritorio, la metodología usada y los resultados obtenidos a partir de este.
<br><br><br><br>
# Requerimientos<br>

<br><br />

## Requerimientos funcionales

<br><br>

| Número de requerimiento | RF001 |<br>
| ------------------------------ | -----|<br>
| Nombre de requerimiento | Modulo de inventario empleados.|<br>
| Tipo | Requisito |<br>
| Fuente del requerimiento | Administrador |<br>
| Proceso | La aplicación debe permitir el control del inventario de un operario acerca de los empleados registrados.|<br>
| Prioridad del requerimiento | Alta/Esencial |<br>

<br<br>



| Número de requerimiento | RF003 |<br>
| ------------------------------ | -----|<br>
| Nombre de requerimiento | Infraestructura de la aplicación |<br>
| Tipo | Requisito |<br>
| Fuente del requerimiento | Administrador |<br>
| Proceso | La aplicación debe desarrollarse en Visual Basic con el SDK de .net, para poder ser usada en sistemas operativos tales como Windows.|<br>
| Prioridad del requerimiento | Alta/Esencial |<br>

<br><br>

| Número de requerimiento | RF004 |<br>
| ------------------------------ | -----|
| Nombre de requerimiento | Disponibilidad de la aplicación. |<br>
| Tipo | Requisito |<br>
| Fuente del requerimiento | Administrador |<br>
| Proceso | El sistema deberá funcionar las 24 horas del día y los 7 días a la semana para todos los usuarios.|<br>
| Prioridad del requerimiento | Alta/Esencial |<br>


<br><br>

| Número de requerimiento | RF006 |<br>
| ------------------------------ | -----|<br>
| Nombre de requerimiento | Respaldo de datos |<br>
| Tipo | Requisito |<br>
| Fuente del requerimiento | Administrador |<br>
| Proceso | Los datos de la aplicación deben respaldarse cada 24 horas en una ubicación segura a la cual solo tengan acceso usuarios autorizados.|<br>
| Prioridad del requerimiento | Alta/Esencial |

<br><br>



| Número de requerimiento | RF008 |<br>
| ------------------------------ | -----|<br>
| Nombre de requerimiento | Memoria <br>
| Tipo | Restricción |<br>
| Fuente del requerimiento | Administrador |<br>
| Proceso | La aplicación no podrá ocupar más de 5 GB de espacio en disco. |<br>
| Prioridad del requerimiento | Media/Deseado <br>

## Requerimientos no funcionales<br><br>



| Número de requerimiento | RNF001 |<br>
| ------------------------------ | -----|<br>
| Nombre de requerimiento | Usabilidad de la aplicación.|<br>
| Tipo | Requisito |<br>
| Fuente del requerimiento | Usuario |<br>
| Proceso | La aplicación debe ser intuitiva y fácil de usar por parte de los operarios de que controlan el inventario. Esta puede medirse con una encuesta de satisfacción.|<br>
| Prioridad del requerimiento | Alta/Esencial |<br>
<br><br>

| Número de requerimiento | RNF002 <br>
| ------------------------------ | -----|<br>
| Nombre de requerimiento | Usabilidad de la aplicación.|<br>
| Tipo | Requisito |<br>
| Fuente del requerimiento | Usuario <br>
| Proceso | La aplicación debe ser intuitiva y fácil de usar por parte de los operarios de que controlan el inventario.|<br>
| Prioridad del requerimiento | Alta/Esencial <br>


<br><br>

## Herramientas usadas para la solución.<br><br>

Instale el SDK de .NET Core 2.1 <br>
Instale Visual Studio 2017 v15.7 <br>
Instale la extensión ASP.NET Core Blazor Language Services <br>
Descargue e instale la edición comunitaria de MongoDB. <br>
<br><br>
### C#

<br<br>
El lenguaje más popular de Microsoft, inspirado en C y C++ de propósito general, especialmente usado para el desarrollo dentro de la plataforma .NET pero también en productos como Xamarin y Unity.<br>

C# es uno de los lenguajes más populares de la industria del software. Es el lenguaje de cabecera de Microsoft, aunque se puede usar en múltiples plataformas de desarrollo de aplicaciones de todo tipo.<br>

C# es un lenguaje de tipado estático y multiparadigma, aunque principalmente orientado a objetos. Microsoft presenta actualizaciones muy frecuentes, por lo que resulta bastante evolucionado, ofreciendo herramientas poderosas para los desarrolladores.<br>







<br><br><br>
## Arquitectura de software

<br><br>

El proyecto se basará en el Modelo Vista Controlador debido a su gran utilización en el mercado, esto se debe a que la estructura desarrollada por modulos, permite al desarrollador trabajar en paralelo sin afectar la operación del software.<br>

Porlo tanto si un usuario desea navegar en una pagina y decide visualizar el estado de un producto, este relalizara una peticiòn directa a un controlador en especifico. Posteriormente este realizarà la solicitud con la secciòn modelo para que este a su vez realice una consulta a la base de datos.<br>
Posteriormente se enviará la información al controlador y desde allí a la vista quien finalmente presentará la respuesta al usuario con la solicitud.

<br><br>

Unas de las caracteristicas y ventajas más destacadas de este modelo son:<br>
- Fácil mantenimiento del código.<br>
- Fácil de extender y crecer (facilidad de modificación).<br>
- Los componentes del modelo MVC pueden ser probados por separado del usuario ya que todas las clases y objetos son independientes entre sí.<br>

<br><br>

Metodología de desarrollo.

Para el desarrollo de este proyecto haremos uso de conocimientos no solamente de la unidad de estudio sino de 
metodologías de gestión de proyectos Scrum – Agile con un componente KANBAN que nos permita 
seguimiento a las actividades y estará basado en desarrollo iterativo de 2 sprints con backlog.

Para establecer la estimación delas actividades y construir un backlog realizamos un sprint planning 
donde identificamos las actividades a realizar, refinamos las actividades y posteriormente 
realizaremos la estimación de acuerdo a las actividades definidas
Backlog preliminar.

Sprint 1:
<br><br>
• Definir plataforma de desarrollo
<br>
• Definir diseño de la aplicación 
<br>
• Hacer un prototipo de la web con el MVP definido
<br>
• Codificar solución
<br>
• Pruebas unitarias
<br>
• Pilotear
<br>
• Despliegue
<br>
• Testear prototipo y realizar ajustes si se requieren
<br><br>

Sprint 2:
<br><br>
• Definición de nuevas funcionalidades
<br>
• Prototipito de nuevas funcionalidades
<br>
• Testear prototipo y realizar ajustes si se requieren
<br>
• Codificar solución
<br>
• Pruebas unitarias
<br>
• Pilotear
<br>
• Despliegue


<br><br>
Bibliografia y referencias
<br>
https://www.youtube.com/watch?v=2GFNi2MVEf0&t=21s
