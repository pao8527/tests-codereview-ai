# FAILURE.MODES.md - Catálogo de fallos de IA en payments-svc > ## Categoría: Generación de tests
# FALURE.NODES.md - catalogo de fallos de IA en payments-svc

## Categoria: Generación de tests
- [n1] Para amount == 0 den calculate_fee/total_with_fee, la IA documentó el comportamiento actual del código (sin fee) com osiguera el contrato del negocio, sin cuestionar si debería aplicar el fee mínimo como en cualquier otro monto.
