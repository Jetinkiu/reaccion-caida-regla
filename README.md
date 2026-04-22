# ⏱️ Tiempo de Reacción a la Caída de una Regla

## 📝 ¿De qué trata este laboratorio?

Este proyecto analiza el **tiempo de reacción humano** a partir de la caída de una regla. 📏💨  
Se basa en mediciones reales de distancia recorrida por la regla antes de ser atrapada, y las convierte en **tiempos de reacción** usando la fórmula de caída libre:

\[
t = \sqrt{\frac{2h}{g}}
\]

Donde:
- `h` = distancia medida en metros (convertida desde cm)  
- `g` = aceleración de la gravedad en La Paz (9.775 m/s²) 🌍

---

## 🧪 Datos experimentales

Se tomaron **30 muestras** de distancia (en cm) que una regla recorrió antes de ser detenida por diferentes personas.  
A partir de esas distancias, se calcularon los tiempos de reacción correspondientes.

---

## 📊 Análisis estadístico realizado

El código aplica conceptos fundamentales de estadística para procesar los datos:

- ✅ **Regla de Sturges** → para determinar el número óptimo de intervalos en el histograma.
- ✅ **Cálculo de rango, mínimo, máximo y ancho de intervalo**.
- ✅ **Distribución de frecuencias** → agrupación de los tiempos en intervalos.
- ✅ **Gráfico de barras (histograma)** con **Chart.js** 📈
- ✅ **Cálculo de incertidumbre** del tiempo de reacción usando propagación de errores relativos.

---

## 🧠 Fórmula de diferencia (incertidumbre)

La incertidumbre del tiempo de reacción se estima con:

\[
\Delta t = \frac{1}{2} \cdot t_{\text{medio}} \left( \frac{\Delta h}{h_{\text{medio}}} + \frac{\Delta g}{g} \right)
\]

Donde:
- `Δh` = incertidumbre en la medida de distancia (0.1 cm)
- `Δg` = incertidumbre en la gravedad (0.39 m/s²)

---

## 👥 Equipo de trabajo

El sitio incluye páginas individuales para cada integrante:
- Imanol  
- Leydi  
- Giovanni  
- Lorena  
- Y una vista **grupal** con todos los datos combinados 🤝

---

## 🖥️ Tecnologías utilizadas

- HTML5  
- CSS3  
- JavaScript (vanilla)  
- Chart.js para gráficos interactivos

---

## 📁 Estructura del proyecto
