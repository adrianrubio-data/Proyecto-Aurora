# 🕹️ Proyecto Aurora – Análisis F2P Multicanal (Steam + Canal B)
**Autor:** Adrián Rubio  
**Tecnologías:** Python · Pandas · NumPy · Matplotlib · Seaborn · Tableau · SQL (experimental)

## 1. Descripción del Proyecto
Este proyecto analiza el rendimiento de un juego Free-to-Play distribuido a través de dos canales independientes:
- **Canal A:** Plataforma de distribución tradicional (Steam).
- **Canal B:** Plataforma móvil/web con un ecosistema más orientado a microtransacciones y eventos.

El objetivo es construir un ecosistema de datos end-to-end, integrar datasets heterogéneos y generar un FACT DAILY consolidado para analizar actividad, monetización y estabilidad del negocio.

## 2. Objetivos del Proyecto
1. Pipeline de datos limpio y reproducible.
2. Integración de 7 datasets distintos.
3. Análisis de actividad (DAU, descargas, concurrencia).
4. Análisis de monetización (sales, ARPU, ARPDAU, whales).
5. Comparativa Canal A vs. Canal B.
6. Dashboards orientados a negocio.

## 3. Estructura del Repositorio
proyecto_aurora/
├── data/
│   ├── raw/
│   ├── cleaned/
│   └── final/
├── EDA/
├── notebooks/
├── sql/
└── README.md

## 4. Datasets Utilizados
### Canal A (Steam)
- Descargas diarias
- Ventas netas
- DAU y usuarios concurrentes
- Microtransacciones

### Canal B (Notaku + Playfab)
- DAU, Gold Spent, ARPU
- Eventos transaccionales reales

## 5. Limpieza de Datos
- Conversión robusta de fechas
- Normalización monetaria
- Renombrado y tipificación de columnas
- Control de nulos y coherencia

## 6. FACT DAILY
Incluye métricas como:
- Total_Revenue_USD
- Steam_Revenue_Share
- Steam_ARPU_approx
- Total_DAU_approx
- Game_ARPU_total
- Rolling de 7 y 30 días

## 7. EDA y Dashboards
- Tendencias temporales
- Distribuciones y correlaciones
- Comparativa entre canales
- Identificación de whales

## 8. Insights
- Canal A es estable y consistente.
- Canal B depende de eventos y compras impulsivas.
- Riesgo por volatilidad en monetización.
- Combinación de canales aporta equilibrio.

## 9. Recomendaciones
- Mejorar conversión inicial del Canal B.
- Reducir dependencia de eventos.
- Mejorar retención en Canal A.
- Crear base de datos unificada.
- Automatizar el pipeline.

## 10. Futuras Líneas de Trabajo
- Cohortes
- LTV
- Segmentación de whales
- Modelos predictivos
- ETL automatizado

## 11. Contacto
GitHub: https://github.com/adrianrubio-data  
LinkedIn: https://www.linkedin.com/in/adrian-rubio-m/
