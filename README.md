# 📊 Análisis Estratégico y Visualización de Datos: Alura Store

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

<img width="688" height="471" alt="Captura de Pantalla 2026-03-05 a la(s) 23 40 06" src="https://github.com/user-attachments/assets/9719afc3-ae5e-489d-b9e2-4bbb42ec807e" />


## 🎯 Objetivo del Proyecto
Este proyecto fue desarrollado para asistir a la Dirección General de **Alura Store** (Sr. Juan) en una decisión comercial crítica: **identificar y justificar qué sucursal de la cadena debe ser vendida** para financiar un nuevo emprendimiento. 

A través del análisis exploratorio de datos (EDA) y la visualización avanzada, el objetivo es ir más allá de los números superficiales y encontrar la verdadera eficiencia operativa, evaluando ingresos, satisfacción del cliente, rotación de inventario y cuota de mercado (Market Share) a nivel nacional.

---

## 🎨 Filosofía de Diseño y UI/UX
A diferencia de los reportes de datos tradicionales, las visualizaciones de este proyecto fueron construidas aplicando principios de comunicación gráfica corporativa. 

Se diseñó una interfaz en **Dark Mode** (Fondo `#473472`) con una paleta de colores de alto contraste para reducir la carga cognitiva del espectador. La integración de los datos exactos dentro de las barras y la eliminación de ejes redundantes permite que cualquier *Stakeholder* comprenda la historia de los datos en menos de 5 segundos.

---

## 📈 Hallazgos Principales

1. **La Paradoja de la Satisfacción vs. Ingresos:**
   El análisis cruzado demostró que la correlación entre una buena calificación y altos ingresos es nula en esta cadena. La **Tienda 1** posee la calificación más baja (3.97 ⭐) pero es el motor financiero de la empresa (+$1.15 Billones). Por otro lado, la **Tienda 4** tiene buena calificación, pero los ingresos más deficientes.

2. **Capital Estancado (Inventario Muerto):**
   Al realizar un diagnóstico profundo a la Tienda 4, se detectaron 5 categorías de productos con niveles críticos de estancamiento (Refrigeradores, Cursos de Python, Guitarras y Armarios), moviendo apenas entre 33 y 38 unidades, lo que representa una ineficiencia en el manejo de bodega.

3. **Pérdida de Market Share (Participación de Mercado):**
   El análisis geográfico porcentual reveló que la Tienda 4 no posee dominio territorial. En plazas clave como Armenia (11%), Manizales (15%) y Cúcuta (17%), está siendo severamente canibalizada por el resto de las sucursales.

---

## 💡 Conclusión y Recomendación Estratégica
Basado en la evidencia de los datos, la recomendación oficial para la Dirección General es **proceder con la liquidación de la Tienda 4**. 

Es la sucursal con el menor Retorno de Inversión (ROI), el inventario menos eficiente y la presencia geográfica más débil. Su venta representa el movimiento financiero más seguro para capitalizar el nuevo proyecto sin afectar el núcleo de ingresos de la empresa.

---

## 🛠️ Estructura del Código
El análisis se llevó a cabo utilizando **Python** en el entorno de **Google Colab**.
* **Limpieza y manipulación de datos:** Extracción, agrupación y cálculo de porcentajes utilizando `Pandas`.
* **Visualización de datos:** Gráficos de barras estilizados, gráficos de barras apiladas al 100% y formateo de etiquetas utilizando `Matplotlib`.

---

> *"Los datos no solo deben procesarse; deben saber contar una historia que impulse la acción corporativa."*
