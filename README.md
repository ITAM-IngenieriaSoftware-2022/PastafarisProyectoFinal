# PastafarisProyectoFinal

Integrantes:
Diana Espinosa, Andrea Aguilar, Jesús Jauregui y Moises Aguirre. 


AsesoriasColmillo es una aplicación para day y recibir asesorias de materias del ITAM. Son les alumnes los que van a poner en que horarios pueden dar asesorias y las materias de las que pueden dar. Luego, otro alumne es el que va a ver los posibles horarios que existen para la materia que quiere y en caso de coincidir en el horario con alguna va a agendar la asesoria. Con ayuda del ITAM se va a tener registro de los horarios en la que los salones están disponibles, para que a la hora de agendar una asesoria se pueda agendar un salón en caso de disponibilidad, en caso de que no haya disponibilidad dirá "Sin salón". El precio de la asesoria se ve desde la aplicación y el pago va a requerir el direccionamiento a un baco para realizar el pago. 

# Especificación de requerimientos de software

El documento de especificación de requerimientos de software se encuentra en el siguiente enlace:
[Requerimientos de software para AsesoriasColmillo](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/Requerimiento%20de%20Software.md).

Los casos de uso de los requerimientos se encuentran en:
[3 casos de uso](#casos)

Los apartados que no aparecen en el documento de especificación de requerimientos de software se descartaron debido a que la versión actual del producto se encuentra en la fase de prototipo.

## Casos de uso <a name="casos"></a> 

- [Caso de uso para inicio de sesión](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/InicioSesion.png)
- [Caso de uso para establecer horiarios en que un usuario puede dar asesoria](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/EstablecerHorarios.png)
- [Caso de uso para agendar una asesoria](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/AgendarAsesoria.png)

## Plan de Calidad

Para garantizar que la aplicación AsesoriasColmillo cuente con todos los requerimientos de calidad, se seguira este [Plan de Calidad](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal). Implementaremos medidas que fomenten la disponibilidad a la par de medidas que aseguren la autenticación del usuario. Haremos pruebas para medir y mejorar la fiabilidad y rendimiento de nuestra aplicación. Finalmente  cuidaremos que nuestro software sea fácil de mantener para obtener un producto de calidad.


## Arquitectura

Elegimos la arquitectura de microservidores, esto porque vamos a tener diferentes componentes en nuestra aplicación. De esta forma, vamos a tener los diferentes componentes conectados a una base central. En específico, las características que ofrecerá nuestra arquitectura es:

* Agilidad: como los componentes están separados, esto va a permitir funcionar de manera independiente y poder hacer cambios rápidos y adaptables. 
* Fácil despliegue: como los servicios van a estar por separado, va a facilitar el deploy. Y en caso de problemas, es fácil aislarlos y poder resolverlos. 
* Fácil de probar: ya que los servicios están por separado.
* Escalabilidad: se puede escalar rápidamente, ya que si es necesario se puede escalar un servicio a la vez. 
* Fácil de desarrollar: ya que hay una API central que controla todo. 

## Metodología

Se implementa una metodología ágil porque utiliza periodos cortos de desarrollo llamado Sprints. Las razopnes por las que se eligió esta metodología son:

* Su enfoque es adaptativo, lo que permite la posibilidad de hacer cambios y los acepta favorablemente; 
* Permite comunicación directa, lo que mantiene el proyecto transparente para todes les integrantes del equipo. 
* Su estructura, le permite encontrar y arreglar defectos rápidamente y con esto perfeccionar la calidad del producto, además permite completar los objetivos, actualizar las funcionalidades y sacar nuevas versiones del producto.

## Código

La aplicación de AsesoriasITAM se encuentra en el siguiente enlace:

https://aguilaralvaandrea.wixsite.com/asesoriasitam

## Documentación para replicar

  La guía para la visualización la aplicación:
  1. Ingresar al enlace: https://aguilaralvaandrea.wixsite.com/asesoriasitam
  2. Ingresar con tu correo.
  3. Navegar.

## Propuesta económica

Para lograr un balance entre el alcance, tiempo y costo de nuestro proyecto realizamos la siguiente [Propuesta económica para AsesoriasColmillo](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal/blob/main/Costos%20Asesorias%20ITAM%20-%20Hoja%201.pdf)

En cuanto a la facilidad de retribución, una primera alternativa es que se podría considerar una comisión por asesoría implementada, es decir, por cada sesión brindada. Como segunda opción, se podría considerar un pago por suscripción a un número definido de asesorías estandar.


## Presentación del proyecto

En el siguiente documento se explican los elementos fundamentales de nuestro producto, el proceso de creación desde la metodología y los conocimientos generados durante el proyecto.
[Presentación de AsesoriasColmillo](https://github.com/ITAM-IngenieriaSoftware-2022/PastafarisProyectoFinal)
