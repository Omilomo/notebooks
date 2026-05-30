# 📊 Análisis de Clientes ConnectaTel

## 🎯 Objetivo del Proyecto
Analizar el comportamiento de los clientes de ConnectaTel, una empresa de
telecomunicaciones en México y Colombia, para identificar patrones de uso,
detectar valores atípicos y crear segmentos de clientes que permitan
optimizar la oferta comercial.

---

## 📁 Datasets Utilizados

| Archivo            | Descripción                                              |
|--------------------|----------------------------------------------------------|
| `plans.csv`        | Planes disponibles: precio, minutos, GB y costos extra   |
| `users_latam.csv`  | Clientes: edad, ciudad, fecha de registro, plan, churn   |
| `usage.csv`        | Uso real: llamadas (duración) y mensajes (longitud)      |

---

## 🔍 Etapas del Análisis

1. **Carga y exploración** de los tres datasets
2. **Identificación de problemas** de calidad: nulos, sentinels y fechas
3. **Limpieza de datos**: corrección de valores inválidos y fechas fuera de rango
4. **Agrupación por usuario**: métricas de mensajes, llamadas y minutos
5. **Visualización de distribuciones** y detección de outliers
6. **Segmentación de clientes** por nivel de uso y grupo de edad
7. **Insight ejecutivo** con hallazgos y recomendaciones para el negocio

---

## ▶️ Cómo Ejecutar el Notebook

### Opción A – Google Colab (recomendado)
1. Abre [Google Colab](https://colab.research.google.com/)
2. Ve a **File → Open notebook → GitHub**
3. Pega el link de este repositorio
4. Abre el archivo `.ipynb`

### Opción B – Localmente
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
   ```
2. Instala las dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Abre el notebook con Jupyter

---

## 🔁 Guía de Reproducción

1. Descarga los datasets desde los links del notebook o colócalos en `/datasets/`
2. Ejecuta las celdas **en orden** de arriba hacia abajo
3. Asegúrate de tener instaladas: `pandas`, `matplotlib`, `seaborn`
4. Los resultados y gráficos se generan automáticamente al correr cada celda
