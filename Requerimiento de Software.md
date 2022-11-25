# Especificación de requerimientos de software para AsesoriasColmillo
--- 
Autores:
- Diana Esinosa Ruiz
- Andrea Aguilar
- Jesús Jauregui
- Moises Aguirre
---
--- 
Versión 1.0
--- 
Noviembre 2022
---
## Tabla de contenidos
  1. [Introducción](#introduccion)
  2. [Descripción general](#descripcion-general)
  3. [Requerimientos de interfaz externa](#requerimientos1)
  4. [Funcionalidades del sistema](#requerimientos2)
  5. [Otros requerimientos](#otros-requerimientos)

## 1. Introducción <a name="introduccion"></a>
  ### 1.1 Objetivo
  
  El objetivo de este documento es presentar una descripción detallada del software AsesoriasColmillo. Se explicarán los requerimientos y funcionalidades del software, así como las interfaces, el alcance y las restricciones que presenta el sistema en su versión actual.
  
  ### 1.2 Convenciones del documento
  
  Este documento se creó con base en el modelo IEEE para especificación de requerimientos de software (Software Requirements Specification)
  
  ### 1.3 Sugerencias de lectura
  
  Este documento está escrito para estudiantes y profesores del departamento de Ingeniería en Computación del Instituto Tecnológico Autónomo de México (ITAM) que quieran conocer sobre los proyectos desarrollados en el curso de Ingeniería de Software.
  
  ### 1.4 Extensión del producto
  
  AsesoriasColmillo es un proyecto en fase de producto final. El objetivo de AsesoriasColmillo es que los integrantes de la comunidad ITAM puedan apoyarse y contribuir a un ambiente seguro y confiable en el que puedan dar y recibir asesorias de las materias que se dan en el ITAM.
  
  ### 1.5 Referencias
  AsesoriasColmillo (versión actual): https://app.moqups.com

  Repositorio en GitHub: https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal

  IEEE template for Software Requirement Specification: https://goo.gl/nsUFwy

## 2. Descripción general <a name="descripcion-general"></a>

  ### 2.1 Perspectiva del producto
  
  AsesoriasColmillo se desarrolló para los estudiantes de la comunidad ITAM. Es una aplicación en la que les alumnes pueden proponer asesorías para las materias enseñadas en el ITAM y elegir horarios en que las puedan dar. Los alumnes podrán entrar a la aplicación yu buscar si hay alguna asesoría que les interese y reservar la asesoría. De igual forma, los asesorados podrán rankear a los asesores para que las demás personas de la comunidad puedan saber que tan bueno o malo es explicando un tema la persona. 
  ### 2.2 Funciones del producto
  
  Vistas:
  - Iniciar sesión: el usuario inicia sesión con el correo institucional.
  - Página principal: el usuario elige una de las tres opciones de funcionalidades (proponer una asesoria, consultar asesorias, calificar asesoria)
  - Proponer una asesoria: el usuario elige los horarios disponibles y los temas o materias que podría dar.
  - Consultar asesorias: se exhiben las asesorias disponibles en el calendario con su información relevante. 
  - Agendar asesoria: el usuario selecciona una asesoria y la reserva.
  - Calificar asesoria: el usuario puede checar las asesorias pasadas y calificarlas y dejas comentarios.
  ![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/Captura%20de%20pantalla%202022-11-24%20213206.png)


  Página principal:
  - Proponer una asesoria: manda al usuario a la pantalla "Proponer una asesoria".
  - Consultar asesorias: manda al usuario a la pantalla "Consultar asesorias".
  - Calificar asesoria: manda al usuario a la pantalla "Calificar asesoria".
  - Cerrar Sesión: se cierra la sesión actual.
  ![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/WhatsApp%20Image%202022-11-24%20at%208.59.56%20PM.jpeg)
  
  Iniciar sesión:
  - Correo: el usuario ingresa su correo institucional.
  - Contraseña: el usuario ingresa su contraseña.
  - Ingresar: comprueba que los datos ingresados por el usuario sean correctos y lo manda a la página principal.
  
![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/WhatsApp%20Image%202022-11-24%20at%208.59.56%20PM%20(1).jpeg)
  
  Proponer una asesoria:
  - Discussion
  - Create post:
  - Descripción: el usuario da una descripción detallada de la asesoria, como diferentes temas que pueda dar.
  - Horarios: el usuario puede seleccionar uno o varios horarios en los que puede dar la asesoria.
  - Post: comprueba que los datos ingresados por el usuario sean correctos.
  - Página principal: regresa a la vista de la página principal.
  
![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/WhatsApp%20Image%202022-11-24%20at%208.59.56%20PM%20(2).jpeg)

![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/WhatsApp%20Image%202022-11-24%20at%208.59.56%20PM%20(3).jpeg)
  
  Consultar asesorias:
  - El usuario va a haber una lista de posibles asesorias, con su autor y horarios.
  - Botón "Book now": va a abrir la asesoria para mostrar toda la descripción de la asesoria y va a reservar la asesoria y te va a pedir proceder a la sección de pago de la asesoria. 
  - Página principal: regresa a la vista de la página principal.
  
![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/WhatsApp%20Image%202022-11-24%20at%208.59.57%20PM.jpeg)

![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/WhatsApp%20Image%202022-11-24%20at%208.59.57%20PM%20(1).jpeg)

![](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/WhatsApp%20Image%202022-11-24%20at%208.59.57%20PM%20(2).jpeg)


  
  - Página principal: regresa a la vista de la página principal.

  ### 2.3 Clases de usuario y características
  
  Estudiantes y exalumnes del ITAM que buscan participar en el apoyo a les estudiantes de la comunidad ITAM, ya sea a través de dar asesorias o recibirlas. 
  
  ### 2.4 Ambiente de operación

  En su versión actual de aplicación, el ambiente de operación de AsesoriasColmillo está sujeto al ambiente de operación de la página web https://moqups.com.
  
  ### 2.5 Restricciones de diseño e implementación
  
  AsesoriasColmillo está desarrollado como prototipo en el ambiente de desarrollo https://moqups.com. Tanto el diseño como la implementación están en la fase de prototipo y dependen en su totalidad del sistema en el que se están desarrollando. 
  
  ### 2.6 Documentación de usuario

  El documento de replicación del sistema se encuentra en: https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal
  
  ### 2.7 Suposiciones y dependencias
  
  AsesoriasColmillo supone que al proponer las asesorias se pueden empalmar los horarios y una vez que se agende una asesoria se va a registrar ese horario como no disponible. Además, está desarrollado en el ambiente de prototipado https://moqups.com, por lo que requiere de una conexión estable de internet, así como el enlace para visualizar el prototipo del sistema.

## 3. Requerimientos de interfaz externa <a name="requerimientos1"></a>

  ### 3.1 Interfaces de Usuario
  
   #### 3.1.1 Vista "Inicio de sesión"

   ![inicio de sesion]()

   ####  3.1.2 Vista "Página principal" 

   ![página principal]()

  ####  3.1.3 Vista "Proponer asesoria" (Al presionar agregar, aparece un mensaje de proyecto agregado correctamente)

  ![proponer]()

  #### 3.1.4 Vista "Consultar asesorias" (Al escribir la materia aparecera la lista de las asesorias relacionadas)

  ![consultaAsesorias]()
  

  ####  3.1.5 Vista "Califica asesorias" (Aparecen las asesorias que has tomado en la última semana. Seleccionas una y puedes calificarla y agregar comentarios.)

  ![calificar]()


  ### 3.2 Interfaces de hardware
  
  AsesoriasColmillo en su versión actual es accesible a cualquier integrante de la comunidad ITAM que posea el enlace de visualización y un navegador web en cualquier dispositivo que soporte la herramienta de desarrollo https://moqups.com hasta la fecha. Y será accesible a través de cualquier dispositivo que cuente con un navegador de internet.
  - Computadora de escritorio
  - Computadora personal
  - Smartphone
  - Tablet 
  - Otros dispositivos con acceso al navegador
  
  ### 3.3 Interfaces de software
  
  AsesoriasColmillo en su versión actual es accesible a cualquier integrante de la comunidad ITAM que posea el enlace de visualización y un navegador web soporte la herramienta de desarrollo https://moqups.com hasta la fecha.

## 4. Funcionalidades del sistema <a name="requerimientos2"></a>

  ### 4.1 Inicio de sesión

   #### &emsp; 4.1.1 Descripción y prioridad

   &emsp; Prioridad alta. Permitir que les alumnes y exalumnes del ITAM tengan permitido accesar a la aplicacion AsesoriasColmillo.
   #### &emsp; 4.1.2 Secuencia de respuestas

  &emsp; Les usuarios van a proponer asesorias, consultar asesorias y calificar asesorias. 
  
   #### &emsp; 4.1.3 Requerimientos funcionales

  - REQ-1: El usuario pueda escribir sus credenciales y sean autenticadas.
  - REQ-2: De no ser autenticadas, mandar un mensaje de error.

  ### 4.2 Proponer una asesoria

   #### &emsp; 4.2.1 Descripción y prioridad

  &emsp; Prioridad alta. Permitir que les alumnes y exalumnes propongan una asesoria. 

   #### &emsp; 4.2.2 Secuencia de respuestas

  &emsp; Proponer una asesoria que ayude a la comunidad itamita.

   #### &emsp; 4.2.3 Requerimientos funcionales

  - REQ-1. Se debe poder seleccionar el nombre de la asesoria.
  - REQ-2. Se debe poder dar una descripción de la asesoria.
  - REQ-3. Se debe poder seleccionar horarios disponibles.
  - REQ-4. Guardar cambios

  ### 4.3 Consultar asesorias

   #### &emsp; 4.3.1 Descripción y prioridad

  &emsp; Prioridad alta. Permitir que les alumnes del ITAM observen y las asesorias ofrecidas por les otres miembres de la comunidad. 

   #### &emsp; 4.3.2 Secuencia de respuestas

  &emsp; Observar las posibles asesorias que la comunidad está teniendo y ver si alguna coincide con tus horarios.

   #### &emsp; 4.3.3 Requerimientos funcionales

  - REQ-1: Escribir palabras, busque asesorias relacionadas.
  - REQ-2: Poder leer las descripciones de las asesorias.
  - REQ-3: Poder ver la calificación del usuario que da la asesoria.

  ### 4.4 Agendar asesoria

   #### &emsp; 4.4.1 Descripción y prioridad

  &emsp; Prioridad alta. Permitir que un usuario interesado pueda agendar una asesoria. 

   #### &emsp; 4.4.2 Secuencia de respuestas

 &emsp; Agendar asesoria. Si el asesor ofrecia otras asesorias en ese horario eliminarlas ya que ahora ese horario no esta disponible. 

   #### &emsp; 4.4.3 Requerimientos funcionales

  - REQ-1: Agendar la asesoria.
  - REQ-2: Poder eliminar horarios de otras asesorias del asesor.

## 5. Otros requerimientos <a name="otros-requerimientos"></a>

  ### 5.1 Requerimientos de desempeño
  
  AsesoriasColmillo requiere de un equipo con conexión estable a internet que soporte la herramienta de prototipado https://moqups.com, así como el enlace para visualizar la versión actual ()
  
  ### 5.2 Requerimientos de seguridad
  
  Para asegurar que ninguno de les usuarios que visualizan el prototipo de AsesoriasColmillo les desarrolladores sugieren a les usuarios conectarse a una red segura y leer los términos y condiciones del entorno de desarrollo https://moqups.com en el que se manejó el sistema. Además, en su versión final, AsesoriasColmillo deberá seguir las pautas de seguirdad de software.   
  - Autenticación: AsesoriasColmillo implementará la verificación con el correo institucional para validad la identidad de sus usuarios.
  
  ### 5.3 Calidad de software
  
  AsesoriasColmillo ofrece a sus usuarios un ambiente simple, eficiente e intuitivo. Las interfaces de AsesoriasColmillo están diseñadas para ser autoexplicativas para sus usuarios. AsesoriasColmillo cumple con todos los requerimientos funcionales, de desempeño, de seguridad y de calidad que se solicitaron en el proyecto final del curso de Ingeniería de Software del Instituto Tecnológico Autónomo de México.
  AsesoriasColmillo garantiza un software de calidad, ya que sigue los principios:
  - Adaptabilidad: AsesoriasColmillo será accesible para toda la comunidad ITAM.
  - Disponibilidad: AsesoriasColmillo estará disponible para toda la comunidad ITAM en semestres de Primavera y Otoño.
  - Usabilidad: el diseño intuitivo de AsesoriasColmillo estará dirigido a una experiencia de usuario.
