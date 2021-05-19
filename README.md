proyectoAlexFin
===============

Trabajo propuesto por Enrique

### About
Primera version del trabajo final.
Solo se ha hecho el menu de configuracion con los sliders, el dropdown y la table.
Se ha escondido el menu lateral para que encaje bien en el smartphone.
Conexion mqtt al broker del profesor.
Dashboard para mostrar los datos de 4 raspberrypi, dos de Enrique y dos de Eneko. Los datos son Temperatura, cpu y Memoria.
Configuracion de alertas con sliders deslizantes, dropdown desplegable y table de informacion.

Segunda version del trabajo final.
Se crea una nueva tab en el dasboard Envio de E-mail, con el icono send.
Se crea un archivo para guardar la direccion de email.
Puedes ver la direccion que esta guardada y puedes cambiarla.
Cuando uno de los dispositivos se sale de sus parametros,
envio un email y cuando vuelve tambien.

Tercera version del trabajo final.
Se usa la funcion (de tabulator) updateData, para no actualizar toda la tabla cada vez que deslizas un slider, sino solo una fila.

Cuarta version del trabajo final
Guardar un dato por cada n datos recibidos.
Saco el promedio X/n de tres lotes de datos, separados por su topic,
los ordeno para el caso de que no llegen siempre en el mismo orden,
espero un timeout para el caso en que falle una recepcion,
anado el timestamp y guardo los tres datos.
Graficar archivos.
Leo el archivo csv y creo el payload especial para chart-node.
Puedes enviar un archivo. Recibiras una advertencia.
Puedes reiniciar los 4 archivos. Tienes que escribir la clave 1234.