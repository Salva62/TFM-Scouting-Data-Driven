# TFM – Salvador Álvarez Sánchez  
## Modelo Data-Driven de Scouting en la Premier League  

---

## Descripción del Proyecto

Este Trabajo Fin de Máster desarrolla un modelo integral de scouting basado en datos aplicado a la Dirección Deportiva de un club de la Premier League.

El proyecto integra:
- Ingeniería de datos (ETL)
- KPIs tácticos por posición
- Machine Learning (clustering y similitud)
- Evaluación coste-rendimiento
- Visualización en Tableau

---

## Metodología

Metodología CRISP-DM:
1. Comprensión del negocio  
2. Comprensión de los datos  
3. Preparación de los datos  
4. Modelado  
5. Evaluación  
6. Despliegue  

## Dashboard interactivo (Tableau Public)

El dashboard interactivo del proyecto está disponible en Tableau Public, permitiendo explorar de forma dinámica los resultados del modelo:

https://public.tableau.com/app/profile/salvador.lvarez.s.nchez/viz/AnlisisCoste-Rendimiento/PlanificcinEstratgicadelOnceIdeal?publish=yes

A través del dashboard es posible analizar:
- Comparación coste-rendimiento de jugadores  
- Evaluación por posición táctica  
- Identificación de oportunidades de mercado  
- Construcción del once ideal  

---

## Estructura del Proyecto

```
TFM_Salvador_Alvarez/
│
├── 01_MEMORIA/
│   └── TFM_Salvador_Alvarez.pdf
│
├── 02_CODIGO/
│   ├── requirements.txt
│   └── TFM_Scouting_Premier/
│
├── 03_DASHBOARD/
│   ├── Analisis_Coste_Rendimiento.twb
│   ├── Analisis_Estrategico_Mercado_1.twb
│   ├── Analisis_Estrategico_Mercado_2.twb
│   └── Planificacion_Once_Ideal.twb
│
├── 04_PRESENTACION/
│   └── Presentación TFM - Documento Marco.pptx
│
└── README.md
```
│


---

## Tecnologías

- Python (pandas, numpy, scikit-learn)
- Web Scraping (BeautifulSoup, Selenium)
- MySQL
- Tableau

---

## Ejecución

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python TFM_Scouting.py
