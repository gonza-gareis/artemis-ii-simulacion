# 🚀 Simulación de Trayectoria del Artemis II

> *¿Qué pasa cuando le das mecánica lagrangiana a un cohete de la NASA? Esto.*

Simulación numérica de la trayectoria de la misión **Artemis II** de la NASA, desarrollada como trabajo extra para la materia **Mecánica Clásica** (Ciencias Físicas, FCEN-UBA) bajo la supervisión del Prof. Gabriel Mindlin.

**Autores:** Juan Manuel Carrizo · Gonzalo Gareis Arnedo

---

## 🌍 ¿De qué trata?

En lugar de usar la formulación newtoniana clásica, modelamos el problema en **coordenadas esféricas generalizadas** (r, θ, φ) usando el **formalismo de Euler-Lagrange**. El potencial gravitatorio combinado de la Tierra y la Luna entra directamente en el Lagrangiano del sistema. Elegante, poderoso y sorprendentemente compacto.

La simulación reproduce la trayectoria de transferencia Tierra-Luna, incluyendo:

- 🛸 La nave como masa puntual con **masa variable** durante los primeros 496 segundos de propulsión (ṁ = 4.032 kg/s)
- 🌎 La atracción gravitatoria combinada de la **Tierra y la Luna**
- 📍 Condiciones iniciales reales del **Centro Espacial Kennedy** (28.63°N, 80.62°W)
- 🔄 Rotación terrestre y movimiento orbital lunar

---

## 📁 Contenido del repositorio

| Archivo | Descripción |
|--------|-------------|
| [📹 simulacion.mp4](https://github.com/gonza-gareis/artemis-ii-simulacion/blob/main/simulacion.mp4) | Visualización de la trayectoria simulada |
| [📝 informe.pdf](https://github.com/gonza-gareis/artemis-ii-simulacion/blob/main/Artemis.pdf) | Desarrollo completo en LaTeX |

---

## 🔗 Notebooks de Google Colab

| Notebook | Descripción |
|----------|-------------|
| [Ecuaciones de Euler-Lagrange](https://colab.research.google.com/drive/1oDmBs6ihYSUjf3qZGQGQQuvyrSiAzHx1?usp=sharing) | Derivación simbólica del Lagrangiano y las ecuaciones de movimiento |

---

## ⚙️ Hipótesis del modelo

El modelo adopta las siguientes simplificaciones:

- La nave se trata como una **masa puntual** (su masa es despreciable frente a la Tierra y la Luna)
- La **Tierra se considera fija** en el origen del sistema de referencia
- Se desprecia el **rozamiento atmosférico**
- La pérdida de masa es **constante** durante la fase de propulsión

> La principal limitación aparece en las proximidades de la Luna, donde estas hipótesis dejan de ser suficientes. Y eso también es parte de la física: un modelo no vale por ser perfecto, sino por saber exactamente cuándo y por qué falla.

---

## 📚 Bibliografía

- NASA Jet Propulsion Laboratory. [HORIZONS System](https://ssd.jpl.nasa.gov/horizons/)
- NASA. [Artemis II Reference Guide](https://www.nasa.gov/wp-content/uploads/2026/01/a2-reference-guide-01.pdf)

---

*FCEN · Universidad de Buenos Aires · 2026*
