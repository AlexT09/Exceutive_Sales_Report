# 🔔 Executive Sales Report 

## 🚀 Descripción
Reporte ejecutivo de ventas en Power BI, del dataset **[Sample Superstore](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls)** (9,994 transacciones de retail en EE. UU., 2014-2017).

La plantilla original venía con un archivo Excel de ejemplo con 4 tablas ya relacionadas (Ventas, Productos, Equipos de Venta, Ubicaciones de Tiendas). Este proyecto **reconstruye esas mismas 4 tablas a partir de un único CSV plano** (Superstore), generando las claves de relación con Power Query en vez de tenerlas pre-cargadas.


## 📈 KPIs y métricas (dataset completo, 2014–2017)
- **Total Sales:** $2,297,200.86
- **Total Profit:** $286,397.02
- **Productos únicos:** 1,850
- **"Tiendas" (combinaciones ciudad+estado):** 604
- **"Equipos de venta" (Segmento × Región):** 12

El reporte además calcula automáticamente: variación semana vs. semana y mes vs. mes, banda de percentil sobre la tendencia diaria de ventas, y ranking de productos/equipos/tiendas.

---

## 🛠️ Tecnologías
- Power BI Desktop (.pbix / PBIR + TMDL)
- Power Query (generación de claves subrogadas para las 3 dimensiones desde un único CSV)
- DAX (WoW/MoM, percentiles, ranking, notificación Toast en HTML/CSS dinámico)

---

## 📁 Estructura del repositorio
```
superstore-executive-sales/
├── data/
│   └── Sample_-_Superstore.csv
├── Screamshot/
│   └── Executive Sales Report.png
├── Exceutive_Sales_Report.pbix   ← abrir este archivo
└── README.md
```

