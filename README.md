# Halcon Order Management System

## Descripción

**Halcon** es un distribuidor de materiales de construcción que necesita una aplicación web para automatizar sus procesos internos. Esta aplicación permitirá a los clientes consultar el estado de sus pedidos y al personal gestionar el ciclo de vida de los mismos a través de un panel administrativo.

## Características principales

- **Consulta de pedidos**: Los clientes pueden ingresar su número de cliente y número de factura para verificar el estado de su pedido.
- **Estados del pedido**:
  - `Ordenado`: El pedido ha sido ingresado por un ejecutivo de ventas.
  - `En proceso`: Se está preparando o esperando la compra de materiales.
  - `En ruta`: Ha sido asignado para distribución.
  - `Entregado`: Ha sido entregado y se muestra evidencia fotográfica.
- **Dashboard administrativo**:
  - Gestión de usuarios y roles.
  - Registro y seguimiento de pedidos.
  - Carga de evidencia fotográfica para entregas.
  - Edición y eliminación lógica de pedidos.

## Metodología de trabajo

Se adoptará la metodología **Agile**, utilizando iteraciones cortas y retroalimentación continua para asegurar la flexibilidad y la satisfacción del cliente.

## Diagramas del sistema

Se han diseñado los siguientes diagramas para estructurar la aplicación:

- **Diagrama BPMN**: Muestra el flujo de trabajo desde la toma del pedido hasta su entrega.
- **Diagrama de clases**: Define la estructura de datos y relaciones del sistema.
- **Diagramas de actividad**: Representan el flujo de ejecución de procesos clave.
- **Diagrama de casos de uso**: Identifica los actores y sus interacciones con el sistema.
- **Diagrama ER**: Representa la base de datos con sus entidades y relaciones.

## Base de datos

Se utilizará **PostgreSQL** por su estabilidad y capacidad de escalabilidad. Las principales entidades incluyen:
- `Clientes`
- `Pedidos`
- `Productos`
- `Usuarios`
- `Evidencias de entrega`

## Reflexión personal

Este proyecto representa una oportunidad para mejorar habilidades en desarrollo web, gestión de bases de datos y diseño de sistemas. Además, permitirá optimizar los procesos de Halcon mediante la digitalización de su gestión de pedidos.

---
