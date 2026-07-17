# Finanzas Personales - Dashboard Power BI

Creé este Dashboard de control financiero personal que compara resultados 
reales contra metas y presupuestos, con análisis detallado por 
categoría y evolución mensual. Cubre 2 años completos: 2024 y 2025.

## Modelo de datos

5 tablas relacionadas:
- **Finanzas** — tabla de hechos con transacciones reales
- **Expectativas** — metas y presupuestos planificados
- **Cuotas %** — medidas de cumplimiento porcentual
- **Categorias** — dimensión de categorías de gasto/ingreso
- **Calendario** — tabla de fechas con Año y Año/Mes

## Páginas del informe

| Página | Descripción |
|--------|-------------|
| Principal | Resumen ejecutivo con 4 gauge KPIs navegables: Cuota Ingreso, Cuota Gastos, Cuota Utilidad y Cuota Saldo |
| Medidas | Tabla comparativa de todas las métricas financieras por mes (accesible desde el ícono de ayuda) |
| Cuota Ingreso | Análisis de cumplimiento de ingresos vs meta por categoría y mes |
| Detalle Ingresos | Drill-through con tabla mensual y gráfico por categoría |
| Cuota Gastos | Análisis de gastos vs presupuesto por categoría y mes |
| Detalle Gastos | Heatmap de cumplimiento por categoría y mes + gráfico combinado |
| Cuota Utilidad | Evolución de utilidad vs utilidad esperada |
| Detalle Utilidad | Tabla comparativa de cuotas con formato condicional |
| Cuota Saldo | Evolución del saldo acumulado vs saldo esperado |

## Navegación

- Desde la página Principal, cada gauge KPI y cada gráfico lleva directamente al detalle de esa métrica
- El ícono de información (ⓘ) redirige a la página de Medidas
- Segmentadores de Año y Mes sincronizados en todas las páginas

## Preguntas de negocio que responde

- ¿Se cumplió la cuota de ingresos este mes?
- ¿En qué categorías se sobrepasó el presupuesto de gastos?
- ¿La utilidad real está alineada con la esperada?
- ¿Cómo evoluciona el saldo acumulado respecto al objetivo?
- ¿Qué meses fueron los más críticos en cada métrica?
- ¿Hubo mejora respecto al año anterior?

## Hallazgos principales

### 2024
- Ingresos: **101%** de la meta anual ($229.5K vs $228K) ✅
- Gastos: **102%** del presupuesto ⚠️ — Comida fue la categoría más desviada (116%)
- Utilidad: **95%** de lo esperado, con recuperación en nov-dic (112-113%)
- Saldo acumulado: **95%** del objetivo al cierre ($46.9K vs $49.2K)

### 2025
- Ingresos: **105%** de la meta anual ($264.9K vs $252K) ✅
- Gastos: **100%** del presupuesto — mejora significativa vs 2024 ✅
- Utilidad: **108%** de lo esperado — superó la meta por amplio margen ✅
- Saldo acumulado: **108%** del objetivo al cierre ($132.6K vs $122.4K) ✅
- Diciembre 2025: todas las métricas en verde simultáneamente por primera vez

## Stack

Power BI Desktop · DAX · Power Query · Modelo estrella

## Link informe:

https://app.powerbi.com/view?r=eyJrIjoiZTE5ZTNmNDAtOTNmMC00MDlmLThjNzgtNTZlNjBhNzdhMDc0IiwidCI6IjFlZmUxZjBmLTMwNWUtNDI5Zi1hYzg5LTRkMThmNmI2OTAyMCIsImMiOjR9
