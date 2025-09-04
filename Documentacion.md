# DentalCare - Consultorio Odontologico.

Bienvenido al consultorio **DentalCare**. Aqui podremos atenter cualquier necesidad que tenga y resolver todos sus problema odontologicos. Por medio de controles e intervenciones quirurjicas de la mano de los mejores odontologos del pais.

## Estructura del Proyecto.

- **DentalCare.py** Se encuentra el sistema principal.
- **datos_consultorio.json** Se encuntran los datos de los turnos y de la cuentas creadas.
- **Modelado.png** Se encuentra el modelado de la Interfaz Grafica.
- **DER.png** Se encuentra el diagrama de entidad relacion.

## Funcionalidades.

- Por medio de un Log In tendremos las funciones de **Ingresar** y **Resgistrase**. La vista dependera del usuario que se ingrese, el medico solo tendra acceso a la funcionalidades que necesite para su trabajo(Ver Turnos, ), el paciente solo vera(Ver Turnos, Ingresar turno, eliminar turno) y el administrador podra tener acceso a todas las funciones que tiene el sistema.
- Un paciente al registrase se le asigna automaticamente un numero de socio.
- Para sacar un turno el Usuario debera seleccionar la opcion de **Ingresar turno**, dentro de esta opcion se le pedira al paciente tanto datos personales como el tratamiento que desea y on que medico dispoonible quiere hacerlo.
- Aqui nos encontramos en con la segunda funcionalidad con variente que tiene el codigo esta vista dependera del usuario  que este registrado. En el caso de ser **medico** este solo vera los turnos que tiene asignado ordenado por fecha, en el **paciente** podra ver todos sus turnos solicitados hasta el momento y el **administrador** vera todos los turnos que esten vigentes **Ver turnos**.
- Tanto el paciente como el Administrador pueden eliminar turnos **Eliminar turno**.
- Nos permite agregar a un empleado a la Base de Datos **Agregar doctor**.
- Nos permite eliminar a un empleado a la Base de Datos **Eliminar doctor**.
- Permite visualizar todos los empleados que tenemos activos en el consutorio con sus especializacion **Mostrar Doctores**.
- Esta opcion nos permitira salir del sistema **Salir**.

## Instrucciones de uso.

1. Abrir **DentalClaere.py**.
2. Una vez visualalizado la venta de Log In elija entre las dos opciones **Ingresar** o **Registrarse**.
3. Si elija **Ingresar** ingrese su usuario y contraseña.
4. Si elija **Registrarse** ingrese su usuario y contraseña y luego ingrese los datos solicitados.
5. Una vez logueado el sistema nos permitira visualizar todas las opciones disponibles dependiendo el perfil.
6. Si el usuario es un paciente podra visualizar los turnos activos y eliminarlos.
7. Si el usuario es un doctor podra visualizar los turnos activos y agregar nuevos.
8. Si el usuario es un administrador podra visualizar todos las funciones disponibles del sistema.
9. Si desea **Ingrear Turno** selecciona dicho boton y procede a rellenar los datos de la ventanas emergentes.
10. si desea **Ver Turnos** selecciona dicho boton y podra visualizar todos los turnos activos hasta el momento.
11. Si desea eliminar algun turno selecciona el boton **Eliminar Turno**.
12. Ingrese en la ventana emergente el codigo de usuario del turno que desea eliminar.
13. Ingresando el ID del paciente y el dia y horario del turno.
14. Si desea **Agregar Doctor** selecciona dicho boton y proceda a rellenar los datos solicitados.
15. Si desea **Eliminar Doctor** selecciona dicho boton y proceda a rellenar los del doctor que desea eliminar.
16. Si desea **Mostrar Doctores** selecciona dicho boton y podra visualizar todos los doctores disponibles.
17. Si desea **Salir** selecciona dicho boton y el sistema se cerrara.

## Tegnologias usadas.
- Python.
- Json.
- Tkinter.
- Figma.

## Update
Version 2.0 en proceso
- Cambio en el almacenamiento de los datos, se cambiara el JSON por un archivo .sql en mysql.
- Cambio de la interfaz de a TKInter a 