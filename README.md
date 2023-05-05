# JSEventDelegation

Event Delegation, una técnica muy utilizada en nuestras aplicaciones web realizadas con Javascript.


Delegación de eventos
La captura y el burbujeo nos permiten implementar uno de los patrones de manejo de eventos más poderosos llamado delegación de eventos .

La idea es que si tenemos muchos elementos manejados de manera similar, en lugar de asignar un controlador a cada uno de ellos, ponemos un solo controlador en su ancestro común.

En el controlador podemos event.targetver dónde ocurrió realmente el evento y manejarlo.
