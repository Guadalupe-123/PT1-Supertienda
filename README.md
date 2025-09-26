# PT1 Supertienda (Excel, sin macros)

Proyecto realizado exclusivamente en **Excel** para simular la gestión de una tienda (productos, clientes y ventas) y practicar análisis con tablas, fórmulas y tablas dinámicas. **No utiliza macros**; el archivo conserva extensión `.xlsm` por compatibilidad.

## Estructura del archivo

- **raw**: datos originales (fuente en bruto). No editar fórmulas ni formatos.
- **datos**: datos limpios/normalizados a partir de *raw* (tipos corregidos, columnas derivadas).
- **analisis**: métricas y cálculos intermedios (p. ej. ventas, ticket promedio, margen, top N).
- **dashboard**: indicadores y visualizaciones finales para lectura ejecutiva.

## Uso
1. Abrir `PT1 Supertienda.xlsm` *(no es necesario habilitar macros)*.
2. Actualizar/pegar nuevos registros en **raw** siguiendo el mismo esquema de columnas.
3. Revisar **datos** (validaciones) y **analisis** (cálculos).
4. En caso de usar tablas dinámicas o conexiones: **Datos → Actualizar todo**.
5. Consultar el tablero en **dashboard** y el documento `Informe_Ejecutivo_Supertienda_Ximena.docx`.

## KPIs (referenciales)
- Ventas totales y **ticket promedio**.
- **Top productos / clientes** por ventas.
- **Márgenes** (si aplica) y **rotación**.
- Tendencias por **mes** y **categoría**.
## KPIs (resumen)
- Ventas totales: _
- Ticket promedio: _
- Top 3 productos: _
- Clientes activos: _
- Margen (si aplica): _

## Diccionario de datos (plantilla)
| Campo        | Tipo   | Ejemplo        | Descripción                          |
|--------------|--------|----------------|--------------------------------------|
| fecha        | date   | 2025-06-01     | Fecha de la venta                    |
| producto     | text   | A001-Taza      | Código / nombre del producto         |
| categoria    | text   | Hogar          | Categoría del producto               |
| cliente      | text   | C123           | Identificador del cliente            |
| cantidad     | int    | 2              | Unidades vendidas                    |
| precio_unit  | number | 120.00         | Precio unitario                      |
| descuento    | number | 0.10           | Descuento aplicado (0–1)             |
| importe      | number | 216.00         | cantidad * precio_unit * (1-desc.)   |

## Notas
- El repositorio ignora temporales de Office (`~$*`) y archivos de sistema.
## Vistas
![Dashboard](docs/Dashboard%20supertienda.jpg)

📂 Descarga el archivo principal: [PT1 Supertienda.xlsm](./PT1%20Supertienda.xlsm)

- Si pre
fieres, el archivo puede renombrarse a `.xlsx` (no hay macros).
