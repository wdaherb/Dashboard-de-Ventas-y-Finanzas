# Dashboard de Ventas y Finanzas

Este repositorio contiene el dashboard desarrollado en **Power BI**,
enfocado en análisis de ventas, utilidad, margen, ticket promedio,
distribución geográfica y comparativas **MoM** y **YoY**.

## 📊 Descripción del Dashboard

El dashboard incluye: - **Total Venta** mensual - **Utilidad** -
**Margen %** - **Cantidad de Ventas** - **Ticket Promedio** -
Comparativas **MoM** y **YoY** - Gráfico de ventas por fecha - Gráfico
de ventas por categoría - Mapa con distribución por tipo de cliente
(Mayorista / Minorista) - Tabla detallada de ventas

## 📁 Estructura del Repositorio

    📦 dashboard-powerbi
    ├── 📄 README.md
    ├── 📁 assets
    │   ├── dashboard_preview.png
    │   └── dataset_example.csv
    └── 📁 pbix
        └── Dashboard_Ventas.pbix

## 🛠️ Herramientas Utilizadas

-   **Microsoft Power BI Desktop**
-   **DAX** para medidas personalizadas
-   **Power Query** para transformación de datos
-   **Mapas de Bing** integrados en Power BI

## ➕ Medidas DAX Principales

``` dax
Total Ventas = SUM(Ventas[Total_Venta])

Cantidad Ventas = SUM(Ventas[Cantidad])

Utilidad = SUM(Ventas[Utilidad])

Margen % = DIVIDE([Utilidad], [Total Ventas])

Ticket Promedio = DIVIDE([Total Ventas], [Cantidad Ventas])
```

## 📷 Vista Previa

Agrega tu imagen del dashboard en la carpeta `assets` con el nombre
`dashboard_preview.png`.

## 🚀 Cómo usar este repositorio

1.  Clona este repositorio:

```{=html}
<!-- -->
```
    git clone https://github.com/tuusuario/dashboard-powerbi.git

2.  Abre el archivo `.pbix` en Power BI Desktop.
3.  Examina las medidas, gráficos y transforma tu propio dataset.

## 🙌 Contribuciones

¡Sientete libre de mejorar o agregar nuevos dashboards!

## 📩 Contacto

Si necesitas ayuda o soporte, estoy disponible para consultorías en
análisis financiero, FP&A y desarrollo de dashboards.
