# Participa

Desde una base de datos sencilla (en formato Microsoft Access) **participa.accdb** se puede centralizar la gestión de una asociación con sus elementos más básicos. "Participa" está destinada a asociaciones pequeñas y también puede servir para entidades, empresas y proyectos de poco tamaño. La agilidad de la aplicación permite que las personas usuarias puedan gestionar de forma muy fácil muchos aspectos de la burocracia habitual. Incluso en el caso del tratamiento de la información económica (que no sustituye a sistemas más completos), permite que responsables de proyectos lleven unos controles fáciles y básicos.

La base de datos, incorpora algo de programación VBA (Visual Basic para aplicaciones) pero, en general, el mantenimiento es sencillo de manera que una persona con conocimientos básicos pueda incluso personalizarla. 

Funciones: listado de socios, entradas y salidas, gastos e ingresos, proyectos, inventario y préstamos, oficina de atención, prensa y contactos.

## Anotaciones de las funciones

#1 Persona usuaria: Debe tener un menú principal desde el que acceder a todas las opciones y estar disponible para regresar a él.

#2 Persona usuaria: El formulario de personas socias debe incorporar pestañas en los que se pueda conocer su actividad (por ejemplo, si participa en proyectos o tiene préstamos del inventario por devolver).

#3 Persona usuaria: Los proyectos deben recoger su distribución económica y su memoria de actividades.

#4 Persona usuaria: Existirá un listado de memoria de actividades asociado a cada proyecto.

#5 Persona usuaria: Los gastos e ingresos deben poder asociarse a programas y subprogramas.

#6 Persona usuaria: Las entradas y salidas registrarán la ubicación o el medio de transmisión.

#7 Persona usuaria: El inventario debe recoger material de distinta procedencia (por ejemplo informático o bibliográfico) y debe poder registrarse su préstamo.

#8 Persona usuaria: La oficina de atención recogerá diferentes tipos de consultas y su estado (abierto, en proceso o cerrado).

#9 Persona usuaria: Los comunicados de prensa se relacionarán con las salidas en los medios de comunicación

#10 Persona usuaria: Existirá una opción para guardar contactos, al centralizarlos cualquier persona usuaria puede recurrir a ellos sin necesidad de guardarlos en su agenda.

#11 Persona usuaria: Las tablas que sirvan de apoyo a opciones de la base de datos y que no tengan un valor constante deben poder actualizarse.

#12 Persona usuaria: Se generarán informes con los listados más importantes de cada opción del menú principal. Los informes deben permitir el copia y pega.

#13 Persona usuaria: Un formulario permitirá configurar opciones básicas de la aplicación.

## Pantallazos

Ejemplos de algunas de las pantallas de la base de datos.

Pantalla principal:

![Pantalla principal](https://user-images.githubusercontent.com/23242976/157652343-f25f28f4-e1ad-43ef-bf5c-14e13829ca6a.png)

Pantalla de gestión de proyectos:

![Pantalla de gestión de proyecto](https://user-images.githubusercontent.com/23242976/157652637-430c5986-416d-4de1-b5bc-739dc546c3a4.png)

Pantalla de gestión de ingresos y gastos por proyecto:

![Pantalla de gestión de ingresos y gastos por proyecto](https://user-images.githubusercontent.com/23242976/157652864-c1ccc9b6-310c-4013-8117-ac30d544a4d2.png)

## Tutorial

- El formulario de inicio se abre de forma automática y se llama Participa (si se cierra por error se puede abrir en cualquier momento).
- En el formulario inicial tenemos acceso a todas las operaciones en la base de datos, además podemos lanzar informes (que son consultas no editables), acceder a la configuración (tablas que podemos personalizar) y salir.
- Desde cualquier formulario podemos volver al inicial, cerrándolo.
- En los formularios tenemos un botón para borrar registros: 
![Botón de borrar registro](https://user-images.githubusercontent.com/23242976/157654831-c327e478-3f32-4939-ae4f-63821be10995.png)
- Podemos movernos por los diferentes registros o añadirlos desde los botones habituales de Access 
![Botones de registros de Access](https://user-images.githubusercontent.com/23242976/157655034-39f2976c-9d51-4145-b3d8-ba2a3342147f.png)
- Filtrar o buscar registros también es posible.
- En el formulario Socios y Socias podemos editar sus datos y las cuotas, además podemos ver si tienen asociados proyectos o préstamos de inventario.
- En el formulario Proyectos podemos editar sus datos y los de los subproyectos, las actividades y los participantes. También podemos acceder a la información económica del proyecto (muy útil para el control de su presupuesto) y las noticias de prensa relacionadas.
- En el formulario Inventario podemos editar sus datos y el de sus préstamos a personas asociadas. El inventario pueden ser cosas como libros o equipamientos.
- En el formulario Gastos e ingresos se puede controlar la actividad económica. Los gastos son números negativos y los ingresos positivos.
- En el formulario Entradas y salidas se controla la correspondencia (se selecciona el Tipo para determinar si es una entrada o una salida).
- En el formulario Prensa se registran los comunicados de prensa y las salidas en medios de comunicación asociadas.
- En el formulario Oficina se registran las consultas realizadas en una posible oficina de atención ciudadana y sus entradas y salidas asociadas
- En el formulario Contactos se centralizan la agenda de personas con las que se mantiene relación.
- Los diferentes Informes se pueden obtener desde el formulario inicial (los listados son consultas a la base de datos que se nombran con un "Listado" inicial). Primero se selecciona y luego se pulsa el botón:
![Informes](https://user-images.githubusercontent.com/23242976/157657117-febf0885-6aa7-4da9-b622-fb3e2d3b4aa5.png)
- Las listas desplegables cargan datos de varias tablas que se pueden modificar desde el formulario Configuración (este tipo de tablas se nombran con una "z" inicial para no confundirlas con tablas más importantes).
![Tablas configurables](https://user-images.githubusercontent.com/23242976/157657268-8c247085-95c8-4a2c-ab8a-7504c8de2713.png)
- Si tienes conocimientos de Access, puedes mejorar algunas cosas. Por ejemplo podrás establecer valores predeterminados algunos campos de la base de datos (La CC.AA más habitual, la cuota de cada año o el máximo de días para un préstamo) o inncluir el logotipo de tu entidad. También podrás separar la parte gráfica de los formularios de los datos de las tablas para reducir la carga si trabajas en red.

## Hacer remix

Puedes hacer remix, respetando la licencia y citando la autoría (https://github.com/jsuarezfer/participa). Por ejemplo,
- Puedes eliminar un montón de campos o, incluso, de formularios que no te aporten nada. Eso será lo más habitual para simplificar la herramienta y trabajar más a gusto pero también puedes generar algún campo o formulario que te resulte necesario.
- Puedes crear Informes más adecuados para el uso que le vayas a dar.
- Puedes generar documentos de Word o de Excel desde la base de datos. Por ejemplo, una carta dirigida a un socio o socia con un formato determinado y repetido o un informe económico en excel con unos campos determinados.
