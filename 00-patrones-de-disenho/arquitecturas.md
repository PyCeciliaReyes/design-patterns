### Arquitectura monolitica:

Se refiere al disenho unificado de un software, donde todo esta acoplado o unido como un solo elemento. Cada componente y sus elementos asociados deben estar presentes para que el codigo se ejecute o compile efectivamente.

Aplicacion fragil

Facil crear fallos criticos del sistema

Quien crea una arquitectura monolitica?
Se inicio asi, empezo a crecer.

### Arquitectura de microservicios:

Existen muchas formas de implementar.

Distirubucion de tareas en bloques separados.

Estos bloques se llaman componentes de servicios y agrupan uno o varios componentes enfocados en realizar una tarea o área de negocio de la aplicación.

Ejemplo: sistema de salud. Cada area de negocio convertir en un componente

Facil de mantener y escalar, ya que estan separadas y no acopladas.

Granuralidad

### Arquitectura de microkernels o arquitectura de pluggins:

Software de terceros

Nucleo central: independiente y funcional. No requiere de otro elemento para trabajar

Pluggins: modulos autocontenidos con una funcionalidad especializada. Similar al sistema operativo.

Una vez instalado el nucleo central, ofrece algun tipo de API y luego hacer los pluggins. Funcionalidad autocontenida. No debe de afectar a otro pluggin y nucleo central.

Ventajas: flexibilidad

Desventaja: todo centralizado en nucleo central, dificil de escalar.

### Arquitectura en capas multiples o multicapas:

Mas conocidos y mas utilizados. Es por defecto utilizado en JAVA.

Capa dedicada a la presentacion: parte visual de la aplicacion.

3 capas frecuentes: 1- presentacion (frameworks de frontends) 2- capa intermedio: calculo. 3- capa de datos: se despacha los datos.

Ejemplo: stack MERN.

### Arquitectura basada en espacio:

Arquitectura en la nube.

Se adapta bien a las necesidades de aplicaciones web.

Esta arquitectura permite escalar operaciones para manejar grandes cantidades de tráfico o uso de recursos, lo que conviene mucho cuando una aplicación se hace viral.

Requerimientos de habilidades tecnicas avanzadas

### Arquitectura dirigida por eventos:

Que es un evento? resultado de una accion. Click a un boton

Cada evento activa una conducta distintas.

Peticion vs Evento:

Peticion: solicitud de datos

Evento: recibiste notificacion de mensajes de whatsapp. Es el resultado de una accion o proceso.

Recibir y procesar informacion en tiempo real.

El evento pasa a un mediador. El mediador envia sus datos a una unidad llamada 'procesador de eventos'

Se destaca en escalabilidad en la nube.

Sistema muy complejo con muchos eventos y dificil de pruebas automatizadas.

### modelo - vista - controlador (MVC):

Para una app completa. Raices en videojuegos.

No funciona para todo tipo de software.

3 areas: 1- modelo: unica fuente de informacion. Cerebro centralizado de software. Datos de la aplicacion 2- vista: interfaz grafica. desplegar la info del modelo 3- controlador: se encarga la interaccion con el usuario a traves de eventos.
