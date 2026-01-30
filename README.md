# ✈️ Análisis de Vuelos – Mendoza
Proyecto desarrollado en Python (Jupyter Notebook) para el análisis del estado operativo de vuelos con destino a Mendoza, a partir de horarios programados, horarios reales y estados del vuelo.
El análisis se basa en datos cargados manualmente y está orientado a aplicar lógica de clasificación operativa en un contexto realista.
## 📅 Contexto del análisis
Los vuelos analizados corresponden a la fecha 23/01/2026.
La información fue cargada manualmente con fines analíticos, simulando un escenario de control operativo de vuelos.
La fecha se utiliza como caso de estudio para evaluar cumplimiento horario, demoras y cancelaciones.
## 🎯 Objetivo del proyecto
Clasificar vuelos según su estado operativo para facilitar el análisis y la toma de decisiones, permitiendo identificar rápidamente:  
Vuelos en horario  
Atrasos leves  
Atrasos graves  
Cancelaciones  
Vuelos a consultar  
El proyecto busca unificar criterios de análisis entre distintas aerolíneas.
## 🧠 Lógica de clasificación
Cada vuelo se evalúa comparando la hora programada con la hora real de partida o su estado informado.  
Estados definidos:  
🟢 En horario  
🟡 Atraso leve  
🔴 Atraso grave  
❌ Cancelado  
❓ A consultar  
La lógica permite aplicar reglas consistentes independientemente de la aerolínea.  
## 🛠️ Tecnologías utilizadas
Python 3  
Jupyter Notebook  
Estructuras condicionales  
Manejo de fechas y horarios  
Carga manual de datos
## 📁 Estructura del proyecto
Copiar código

analisis-vuelos-mendoza/  
 │  
├── analisis_vuelos_mendoza.ipynb  
└── README.md
## ▶️ Cómo utilizar el proyecto
Abrir el archivo analisis_vuelos_mendoza.ipynb en Jupyter Notebook
Ejecutar las celdas en orden
Ingresar manualmente:  
Aerolínea  
Número de vuelo  
Hora programada  
Hora real o estado del vuelo  
Visualizar la clasificación final del vuelo
## 📌 Casos de uso
Este proyecto puede utilizarse como:  
Ejercicio de análisis operativo  
Simulación de control de vuelos  
Práctica de lógica condicional en Python  
Proyecto de portfolio orientado a análisis de datos
## 🔮 Posibles mejoras futuras
Automatizar la carga de datos  
Exportar resultados a Excel  
Agregar métricas por aerolínea  
Visualizar demoras mediante gráficos  
Historial de vuelos por fecha
## 👨‍💻 Autor
Matías Alejandro Taborda  
Proyecto desarrollado como parte de portfolio en Python, orientado a análisis de datos y lógica operativa.
