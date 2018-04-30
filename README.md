JMS-Receiver
============

Aplicacion Java que al ejecutarse monitoreara la cola de mensajes `payment-queue`. Al encontrar un mensaje nuevo, procedera a procesarlo por medio de una invocacion al 
_gateway_ de pagos. Recibira el resultado de dicho proceso de pago y lo enviara a la cola `payment-status-queue`.
