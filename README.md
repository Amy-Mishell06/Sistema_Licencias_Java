Requisitos del Sistema

- Sistema Operativo: Windows
- Conexión a Internet
- Java JDK 25 instalado

Ejecutar el .jar o .exe

Credenciales de Prueba

- Analista

Usuario: amy

Contraseña: amy06

- Solicitante

Usuario: 1725984267

Contraseña: 1725984267JUAN



MANUAL DE USUARIO

Introducción

El presente Manual de Usuario describe el uso del sistema de gestión de trámites de licencias vehiculares. Su objetivo es orientar al usuario en el manejo correcto de cada módulo del sistema, permitiendo realizar los procesos de forma clara, rápida y segura.
El sistema está diseñado para ser utilizado por administradores, analistas y solicitantes, mostrando diferentes opciones según el rol con el que se acceda.

Acceso al Sistema

Al iniciar la aplicación se presenta la pantalla de inicio de sesión.
El usuario debe ingresar su nombre de usuario y contraseña para acceder al sistema.
El sistema cuenta con tres tipos de usuarios:

•	Administrador

•	Analista
<img width="481" height="362" alt="image" src="https://github.com/user-attachments/assets/9d2054e8-98ed-493f-9ba2-f0ea4b70573e" />

•	Solicitante
<img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/5168f4d3-ea66-499f-b67e-32993e803319" />


En caso de ingresar credenciales incorrectas tres veces, la cuenta del solicitante será deshabilitada automáticamente.

-	Menú Principal

Una vez iniciada la sesión, el sistema muestra el menú principal correspondiente al rol del usuario. Desde este menú se puede acceder a los diferentes módulos del sistema mediante botones de navegación claros e intuitivos.

<img width="730" height="365" alt="image" src="https://github.com/user-attachments/assets/472886eb-7cb8-4f47-8767-c6734595ff02" />

-	Registrar Solicitante

Este módulo permite registrar a una persona que desea iniciar un trámite de matriculación.
El usuario debe ingresar el número de cédula, el nombre completo y seleccionar el tipo de licencia. Al guardar la información, el sistema crea automáticamente el usuario del solicitante.
El nombre de usuario del solicitante será su número de cédula y la contraseña será la cédula seguida del primer nombre en mayúsculas.

<img width="542" height="362" alt="image" src="https://github.com/user-attachments/assets/4caf0bd1-4f2f-4ca0-a5e5-5db8247aede5" />

-	Gestión de Trámites

En este módulo se visualiza la lista de solicitantes registrados junto con el estado actual de su trámite.
El sistema permite realizar búsquedas por cédula, nombre o tipo de licencia, así como aplicar filtros por estado y tipo de licencia. También se puede acceder al detalle del trámite y exportar la información mostrada en formato CSV o PDF.

<img width="1102" height="552" alt="image" src="https://github.com/user-attachments/assets/ea8cbbe9-bea0-4f07-8384-c0c29084f2fa" />

-	Verificación de Requisitos

Este módulo permite verificar si el solicitante cumple con los requisitos necesarios para continuar con el trámite. Se valida la existencia de certificado médico, pagos realizados, multas pendientes y se pueden agregar observaciones.
Si el solicitante no cumple con los requisitos establecidos, no podrá avanzar al siguiente módulo.

<img width="665" height="423" alt="image" src="https://github.com/user-attachments/assets/89841436-3d97-40a5-b262-748e1d5e4253" />

-	Registro de Exámenes

En este módulo se registran las calificaciones teóricas y prácticas del solicitante. El sistema valida que los requisitos hayan sido aprobados antes de permitir el registro de las notas.
Si el promedio obtenido es menor a 14, el solicitante deberá repetir el proceso correspondiente. En caso de aprobar, el trámite avanzará al módulo de generación de licencia.

<img width="537" height="300" alt="image" src="https://github.com/user-attachments/assets/7e7c167b-7fde-44eb-b0c7-952266b0de61" />

-	Generación de Licencia

Este módulo permite generar la licencia del solicitante una vez que el trámite ha sido aprobado. El sistema registra la fecha de emisión y la fecha de vencimiento de la licencia.
Solo se generará la licencia si el estado del trámite es aprobado.

<img width="265" height="140" alt="image" src="https://github.com/user-attachments/assets/86239646-dfa6-4903-af78-0af24a75ff06" />

Adicional como administrador cuenta con el modulo:

-	Gestion de usuarios

El cual permite la gestión de usuarios solicitantes aquí podremos cambiar el username, contraseña y estado del solicitante.

-	Reportes

Que permite al admistrador generar un reporte ya sea en CSV o PDF mediante filtros que van desde cedula, nombre, tipo de licencia y estado.


- Como solicitante:

•	Consulta del Trámite

El solicitante tendrá acceso únicamente a la información relacionada con su propio trámite. Desde su perfil podrá visualizar el estado del proceso, las etapas completadas y las observaciones registradas.
Cuando el trámite haya finalizado y la licencia se encuentre emitida, el solicitante podrá descargar su licencia en formato PDF.

•	Cierre de Sesión
El usuario puede cerrar sesión en cualquier momento para finalizar el uso del sistema y regresar a la pantalla de inicio.

<img width="1106" height="543" alt="image" src="https://github.com/user-attachments/assets/1d88797f-68cf-47e9-8de1-bb0c2a68ec2c" />


Recomendaciones de Uso

Se recomienda verificar cuidadosamente la información antes de guardarla, no compartir las credenciales de acceso y cerrar sesión al finalizar el uso del sistema para garantizar la seguridad de la información.
