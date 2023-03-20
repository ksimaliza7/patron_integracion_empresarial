# Registro de Decision de Arquitectura - Facturación Electrónica

# Title
Api de un proveedor de Facturación electrónica

## Status

Revisión

## Context

La integración de la facturación electrónica en un ERP Odoo se debe adaptar mediante la integración directa a facturación electrónica del SRI.

## Decision

El proveedor elegido sería TRESCLOUD que brinda este servicio mediante la migración a Odoo versión 16 que cuenta con facturación electrónica ecuatoriana de forma estándar y sin costo adicional.

## Consequences


Integrado al funcionamiento estándar de Odoo, permite facturar desde los módulos de ventas, suscripciones, soporte, proyectos, servicios de campo, entre otros.

Envío automático al SRI, con numeración automática, número de autorización, así como el archivo XML firmado y autorizado electrónicamente.

Cuenta con un RIDE en pdf con los formatos sugeridos por el SRI.

Permiten su envío vía email al cliente mediante el botón de "Enviar por correo".
