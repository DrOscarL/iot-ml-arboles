# 🌳 Explorador de Árboles de Decisión — IoT ML

Herramienta interactiva para explorar el comportamiento de árboles de decisión
en datos de sensores IoT, sin instalar nada.

**→ [Abrir el explorador](https://YOUR_USER.github.io/iot-ml-arboles)**

---

## Qué puedes explorar

| Parámetro | Qué observar |
|-----------|-------------|
| `max_depth` | Cómo la frontera de decisión se vuelve más compleja y luego sobreajusta |
| `min_samples_leaf` | Cómo las hojas con pocas muestras generan reglas poco confiables |
| `criterion` | Diferencia visual entre Gini y Entropía |
| Tab **Overfitting** | La curva de accuracy vs profundidad — dónde está el punto óptimo |
| Tab **Reglas IF-THEN** | Las reglas que exportaría `export_text()` de sklearn |

---

## Cómo publicar en GitHub Pages

1. Crear un repo en GitHub (puede ser público o privado con Pages habilitado)
2. Subir `index.html` a la rama `main`
3. Ir a **Settings → Pages → Source: Deploy from branch → main / root**
4. En ~1 minuto el sitio está en `https://TU_USUARIO.github.io/NOMBRE_REPO`

---

## Dataset simulado

Motor industrial con 3 estados:

| Clase | Temperatura | Vibración |
|-------|-------------|-----------|
| Normal (0) | ~62°C | ~0.8 mm/s |
| Sobrecalentamiento (1) | ~85°C | ~0.9 mm/s |
| Falla mecánica (2) | ~68°C | ~2.5 mm/s |

---

## Parte del curso

Esta herramienta complementa el **Laboratorio de la Semana 5** del curso de
Especialización IoT · Machine Learning.

- Colab del laboratorio: `Laboratorio_Arboles_Decision.ipynb`
- Algoritmos cubiertos: CART · Random Forest · XGBoost

---

*Dr. Oscar Loyola Valenzuela · Especialización IoT · Machine Learning*
