# SKU Forecast & Safety Stock Analyzer

**🔗 Demo en vivo / Live demo:** https://jvazquezh79-svg.github.io/sku-forecast-analyzer/

Aplicación HTML **100% standalone** (sin servidor, sin dependencias externas) para análisis ejecutivo de inventarios y pronósticos por SKU. Funciona directamente en el navegador: carga tu Excel/CSV o usa el demo integrado de **2,500 SKUs × 100 semanas**.

*Fully standalone HTML app (no server, no external dependencies) for executive SKU-level inventory and forecasting analysis. Runs entirely in the browser: upload your Excel/CSV or use the built-in demo (2,500 SKUs × 100 weeks).*

---

## ✨ Funcionalidades / Features

| Español | English |
|---|---|
| Clasificación de demanda (Smooth, Intermittent, Erratic, Lumpy) vía matriz ADI vs CV² | Demand classification (Syntetos-Boylan ADI vs CV² matrix) |
| Segmentación ABC / XYZ con mapa de calor | ABC / XYZ segmentation with heatmap |
| Safety stock básico y avanzado, punto de reorden (ROP) | Basic & advanced safety stock, reorder point (ROP) |
| Selección automática de modelo por SKU: Naive, Moving Average, SES, Holt, Holt-Winters, Croston, SBA, TSB (backtesting WMAPE) | Automatic per-SKU model selection with WMAPE backtesting |
| Detección y exclusión de outliers (regla IQR) | Outlier detection & exclusion (IQR rule) |
| Detalle interactivo por SKU: serie histórica, outliers y forecast | Interactive SKU drill-down: history, outliers and forecast |
| Interfaz bilingüe ES/EN y tema claro/oscuro | Bilingual ES/EN interface, light/dark theme |
| Exportación a Excel, CSV y PDF ejecutivo | Excel, CSV and executive PDF export |
| Template Excel descargable para cargar tus propios datos | Downloadable Excel template for your own data |

## 🚀 Uso / Usage

1. Abre la [demo en vivo](https://jvazquezh79-svg.github.io/sku-forecast-analyzer/) o descarga `index.html` y ábrelo en Chrome/Edge.
2. Haz clic en **"Cargar demo"** para explorar con datos sintéticos, o **"Descargar template Excel"** para preparar tus propios datos.
3. Sube tu archivo `.xlsx` o `.csv`, revisa el mapeo de columnas y presiona **"Analizar SKUs"**.

*Open the [live demo](https://jvazquezh79-svg.github.io/sku-forecast-analyzer/) or download `index.html` and open it in Chrome/Edge. Click "Load demo" to explore, or "Download Excel template" to prepare your own data.*

## 📄 Formato de datos / Data format

Una fila por SKU: columnas de metadatos (Descripción, Familia, Planta…), `LT` (lead time), `GR processing` (tránsito) y columnas numéricas contiguas de periodos de consumo (semanas, meses o genéricos). El template incluido documenta el formato con 20 filas de ejemplo.

## ⚠️ Disclaimer

Herramienta analítica para diagnóstico y planeación (S&OP, MRP, inventarios). No sustituye la validación operativa de parámetros maestros, capacidad, MOQ, vida de anaquel ni acuerdos de servicio.

---

© 2026 **Jesús Vázquez** — Todos los derechos reservados / All rights reserved.
📎 [LinkedIn: /in/jvazquezh](https://www.linkedin.com/in/jvazquezh/)
