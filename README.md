# Ley de Israel: La Constante del Mapache (ℳ)

Este repositorio documenta la formalización de la relación de proporcionalidad inversa entre la aceleración gravitatoria y el alcance horizontal en movimientos parabólicos.

---

## 📝 Resumen Académico (Abstract)
El presente documento expone la deducción de una relación constante e invariable en el movimiento parabólico, denominada **Constante del Mapache (ℳ)**. A través de la unificación de las ecuaciones de Movimiento Rectilíneo Uniforme (MRU) y Caída Libre (MRUA), se demuestra que el alcance horizontal ($d$) de un proyectil es **inversamente proporcional** a la aceleración de la gravedad ($g$) del entorno, siempre que las condiciones iniciales de lanzamiento permanezcan estáticas. Esta relación, definida como **Ley de Israel**, permite simplificar el cálculo de trayectorias en diferentes cuerpos celestes mediante una proporción de magnitudes.

## 🚀 Fundamentación Matemática
Partiendo de las ecuaciones fundamentales de la cinemática:
1. **Eje X (MRU):** $d = v_0 \cos(\theta) \cdot t$
2. **Eje Y (Caída Libre):** $t = \frac{2 v_0 \sin(\theta)}{g}$

Al sustituir el tiempo de vuelo en la distancia, obtenemos la función general del alcance:
$$d = \frac{v_0^2 \sin(2\theta)}{g}$$

### Postulado de la Ley de Israel
Al aislar los componentes variables de los componentes constantes, se deduce que:
$$\mathbf{g \cdot d = v_0^2 \sin(2\theta)}$$

Dado que el término $v_0^2 \sin(2\theta)$ depende únicamente del impulso inicial y el ángulo, se define como la **Constante del Mapache (ℳ)**:
$$\mathbf{g \cdot d = ℳ}$$

## 🌌 Aplicación Interplanetaria
La **Ley de Israel** establece que para comparar el comportamiento de un mismo lanzamiento en dos mundos diferentes (como la Tierra y la Luna), se cumple la siguiente igualdad:

$$\frac{g_{Tierra}}{g_{Luna}} = \frac{d_{Luna}}{d_{Tierra}}$$

### Ejemplo práctico:
Si un objeto alcanza **40 m** en la Tierra ($g \approx 9.81$), la Constante del Mapache es:
$$\mathcal{M} = 9.81 \times 40 = 392.4$$

### Tabla de Referencia para Cálculos

Puedes usar estos valores de ejemplo en tus cálculos:

| Variable | Descripción | Valor de Ejemplo |
| :--- | :--- | :--- |
| `g` | Gravedad | 9.81 m/s² |
| `d` | Distancia | 10 metros |

Para hallar la distancia en Marte ($g \approx 3.71$):
$$d_{Marte} = \frac{392.4}{3.71} = 105.76 \text{ m}$$

---
**Autor:** Israel Guzman  
**Fecha de Registro:** Febrero 2026  
**Licencia:** MIT (Atribución requerida)
