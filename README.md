# 🍫 Dashboard Ejecutivo — Cacao & Co

Suite de dashboards de analítica de ventas para una tienda de chocolatería, con KPIs de rentabilidad, análisis de descuentos, comportamiento del consumidor y un módulo de **predicción de tendencia de ganancias**.

## 🎯 Problema de negocio

La gerencia de Cacao & Co necesita responder rápido preguntas clave del negocio: ¿dónde está el dinero real?, ¿las promociones sí generan más ganancia?, ¿cuál es la hora pico de ventas?, ¿qué ciudad es más rentable? — y anticipar cómo se comportarán las ganancias en las próximas horas.

## 📊 Qué incluye el dashboard (`index.html`)

1. **¿Dónde está el dinero real?** — ganancia neta por producto.
2. **Efecto Promoción** — comparación de ganancia por transacción con y sin descuento (boxplot).
3. **Volumen por ciudad** — unidades vendidas por ciudad (Bogotá, Medellín, Cali).
4. **Hora pico del chocolate** — flujo de ganancias por hora del día y canal de venta (presencial vs. web).
5. **Mix comercial** — proporción de pedidos con y sin descuento.
6. **Motor de IA y Predicción** — proyección de ganancia futura basada en tendencia móvil histórica por hora.

## 🖥️ Versiones incluidas

| Archivo | Descripción |
|---|---|
| `index.html` | Dashboard ejecutivo completo para junta directiva — KPIs, 5 gráficas de negocio y módulo de predicción. **Versión principal.** |
| `dashboard_ejecutivo_premium.html` | Variante con diseño temático premium (fondo de cacao) y exportación a PDF vía impresión del navegador. |
| `analisis_ventas_cacao.py` | Script de análisis exploratorio en Python (Pandas, Matplotlib, Seaborn) que limpia los datos crudos de ventas, calcula los KPIs y genera un dashboard estático como imagen (`.png`). |

## 🚀 Cómo verlo

Los archivos `.html` son **100% autocontenidos** — ábrelos directamente en cualquier navegador, no requieren instalación ni servidor.

Para el análisis en Python:

```bash
pip install pandas matplotlib seaborn
python analisis_ventas_cacao.py
```

## 🛠️ Tecnologías

Plotly.js · HTML/CSS/JavaScript · Python · Pandas · Matplotlib · Seaborn

---
*Proyecto desarrollado por Jensul Villalba Gaitán como parte de su formación práctica en análisis de datos e Inteligencia Artificial aplicada a casos de negocio reales.*
