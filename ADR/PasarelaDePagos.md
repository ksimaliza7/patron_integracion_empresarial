# Registro de Decision de Arquitectura - Pasarela de Pagos

# Title

Recibir pagos mediante el bus de servicios y colas asincronas.

## Status

Revisión

## Context

El tiempo de respuesta de la pasarela de pagos para las transacciones requeridas no es constante y tiende a ser lento para los usuarios.

## Decision

Para recibir los pagos se lo realizará mediante la API de la pasarela de pagos, las peticiones se realizarán a través del sistema de mensajería bus de servicios.

## Consequences

Las interacciones con la funcionalidad de pagos serán mucho más rápidas y eficiente por el procesamiento asíncrono de los datos.