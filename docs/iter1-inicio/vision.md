# Documento de Visión v1 - Sistema Khanauky

## 1. Propósito

Desarrollar y organizar mediante RUP el módulo principal del Sistema Khanauky orientado al **registro de ventas y control de stock del almacén**, permitiendo que el personal encargado pueda registrar una venta correctamente y mantener actualizadas las existencias de los productos.

## 2. Problema

El manejo de las ventas y del stock puede generar inconsistencias cuando la información de los productos vendidos no se actualiza correctamente en el almacén. Esto puede provocar diferencias entre las existencias registradas y las existencias reales, ventas con cantidades no disponibles y dificultades para conocer oportunamente el stock de los productos.

## 3. Alcance

### Incluye

- Consultar y modificar un pedido antes de concretar la venta.
- Validar la disponibilidad de los productos.
- Registrar una venta.
- Registrar o confirmar el pago de una venta.
- Consultar el stock disponible.
- Actualizar el stock como consecuencia de una venta.
- Mostrar el resultado de la operación al vendedor.

### No incluye en esta iteración

- Gestión completa del proceso de producción.
- Administración de proveedores.
- Gestión de certificaciones.
- Seguimiento del reparto o delivery.
- Portal directo para clientes.
- Contabilidad completa de la empresa.
- Gestión de recursos humanos.

## 4. Interesados

| Rol | Necesidad |
|---|---|
| Vendedor | Registrar correctamente las ventas y comprobar la disponibilidad de productos. |
| Encargado de almacén | Mantener actualizado y consultar el stock. |
| Administrador | Disponer de información confiable sobre ventas y existencias. |

> Una misma persona puede desempeñar más de uno de estos roles. Las funciones no se eliminan del modelo por ello.

## 5. Objetivos medibles

- Evitar el registro de ventas cuya cantidad supere el stock disponible.
- Mantener actualizado el stock después de cada venta confirmada.
- Reducir errores entre la información de ventas y las existencias registradas.
- Permitir que el vendedor revise la información antes de confirmar una venta.

## 6. Requisitos de alto nivel

- `REQ-001`: Gestionar stock.
- `REQ-002`: Consultar y modificar pedido.
- `REQ-003`: Registrar venta.
- `REQ-004`: Registrar o confirmar pago.

## 7. Restricciones

- El sistema debe poder ser utilizado por personal autorizado.
- El registro de una venta no debe permitir cantidades superiores al stock disponible.
- La actualización de la venta y del stock debe mantener consistencia entre ambos registros.
- El desarrollo se organizará de manera iterativa utilizando las fases de RUP.
