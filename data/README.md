# Carpeta de datos

Acá va la información operativa del negocio, en CSV (se abren en Excel, Google Sheets o cualquier planilla).

## Archivos

| Archivo | Qué guarda |
|---|---|
| `proveedores.csv` | Lista de proveedores con contactos y condiciones. |
| `precios.csv` | Precio por producto y proveedor (mayorista vs menudeo → margen). |
| `clientes.csv` | Tiendas/clientes: dirección, zona, rutero, teléfono. |
| `compras.csv` | Compras a proveedores (fecha, producto, cantidad, costo). |
| `ventas.csv` | Ventas a tiendas (fecha, cliente, producto, cantidad, precio). |

> [!NOTE]
> Los CSV están como **plantilla**: se van llenando a medida que avanza el negocio. Una fila por movimiento.

## Regla de oro

Todo margen se calcula como `precio de venta − costo mayorista`. Sin el costo mayorista real, cualquier precio de menudeo es solo un techo.
