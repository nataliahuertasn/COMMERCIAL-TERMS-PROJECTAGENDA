# Maqueta módulo de Clientes

Toda la maqueta está en `index.html`:

- Pestaña CLIENTS: ficha del cliente con General Information (incluye Payment Terms, Fase 1) y la pestaña CUSTOMER MATRIX del cliente.
- Pestaña CUSTOMER MATRIX: tabla con las columnas, listas y fórmulas del Excel MT01-PRSA-02 (Fase 2), con búsqueda, filtros, indicadores y ordenamiento.
- Settings (engranaje en la barra vertical): Commercial Terms, con el identificador {{PAYMENT_TERMS}} y vista previa por cliente, y Customer Matrix, con los catálogos del Excel (jurisdicción, actividades, trayectoria, montos, programas de seguridad, interpretación y medidas de control) conectados a los cálculos.

`customer-matrix.html` solo redirige a `index.html#matrix` para que el link anterior siga funcionando.

Los datos son de ejemplo. Los campos se pueden editar en la maqueta, pero no guardan datos.
