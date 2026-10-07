# Riesgos del proyecto - Khanauky

| ID | Fase | Riesgo | Probabilidad | Impacto | Mitigación | Responsable |
|---|---|---|---|---|---|---|
| RSK-001 | Inicio | Ampliar el alcance con módulos que no corresponden a esta entrega. | Media | Alto | Definir claramente las secciones "Incluye" y "No incluye" del Documento de Visión y validarlas con el equipo. | Analista |
| RSK-002 | Elaboración | Inconsistencia entre una venta registrada y el stock. | Media | Alto | Diseñar la venta y la actualización de stock como una operación coherente; definir excepción y compensación. | Arquitecto / Desarrollador |
| RSK-003 | Construcción | Permitir vender cantidades superiores al stock disponible. | Media | Alto | Validar existencias antes de confirmar la venta y ejecutar pruebas de límite. | Desarrollador |
| RSK-004 | Transición | El usuario no comprende correctamente el flujo de registro de venta. | Media | Medio | Ejecutar prueba de aceptación, registrar observaciones y elaborar manual breve de uso. | Líder del proyecto |

## Tarjetas sugeridas para la lista "Riesgos" en Trello

### RSK-001 - Alcance fuera del módulo de ventas y almacén

- [ ] Revisar Documento de Visión.
- [ ] Confirmar la sección "No incluye".
- [ ] Validar alcance con el equipo.

### RSK-002 - Inconsistencia venta-stock

- [ ] Diseñar operación coherente entre venta y stock.
- [ ] Definir excepción E3.
- [ ] Definir compensación C1.
- [ ] Validar consistencia final.

### RSK-003 - Venta con stock insuficiente

- [ ] Implementar validación antes de la venta.
- [ ] Definir mensaje de stock insuficiente.
- [ ] Probar cantidades límite.

### RSK-004 - Dificultad de uso

- [ ] Realizar prueba con usuario.
- [ ] Elaborar manual breve.
- [ ] Registrar observaciones.
