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

## Notas
- El repositorio ignora temporales de Office (`~$*`) y archivos de sistema.
- Si prefieres, el archivo puede renombrarse a `.xlsx` (no hay macros).
