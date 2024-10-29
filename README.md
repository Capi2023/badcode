# Badcode

## Escenario de Código Mal Diseñado en .NET 8 - "Gestión de Inventario para una Librería"
### Descripción del Problema:Una librería ha creado una aplicación en .NET 8 para gestionar su inventario. Sin embargo, la arquitectura del código es deficiente, lo que dificulta el mantenimiento y escalabilidad. El sistema tiene clases monolíticas sin abstracción adecuada y violaciones del principio de responsabilidad única, lo que ha generado código confuso y poco eficiente. Esta situación presenta una oportunidad para que los desarrolladores apliquen patrones de diseño GoF (Gang of Four) para mejorar la estructura.

### Objetivos de Mejora:

| Objetivo                                | Descripción                                                                                                       |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| 1. Refactorizar la Clase Libreria       | Aplicar el patrón Facade para simplificar la interacción con las múltiples funcionalidades de gestión de inventario. |
| 2. Implementar el Patrón Singleton      | Garantizar que solo exista una instancia de conexión a la base de datos.                                          |
| 3. Aplicar Factory Method               | Crear una fábrica para instanciar objetos de Libro, Revista o Periódico según el tipo de publicación.             |
| 4. Simplificar el Proceso de Pedido     | Usar el patrón Observer para notificar a diferentes módulos cuando hay un cambio de estado en el inventario.      |
| 5. Mejorar la Abstracción de Almacenamiento | Aplicar Repository para desacoplar la lógica de negocio del acceso a datos.                                       |
| 6. Utilizar el Patrón Strategy          | Implementar estrategias para calcular descuentos según el tipo de cliente (estudiante, regular, corporativo).     |
| 7. Optimizar la Gestión de Pedidos      | Integrar Command para encapsular pedidos de compra y mejorar la trazabilidad.                                     |
| 8. Reducir Duplicación de Cálculos      | Usar el patrón Template Method para definir algoritmos de cálculo de precios con variantes en métodos específicos. |
| 9. Asegurar Consistencia de Datos       | Emplear Proxy para manejar operaciones en el inventario y validar permisos de usuario.                            |
| 10. Crear un Servicio de Notificación de Clientes | Aplicar Mediator para coordinar notificaciones y eventos entre módulos de pedidos, pagos y usuarios.           |


#### Este proyecto permitirá mejorar la eficiencia, reducir la deuda técnica y facilitar el mantenimiento del sistema.
