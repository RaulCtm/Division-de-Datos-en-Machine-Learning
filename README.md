# 📊 División de Datos en Machine Learning

> **Entrenamiento, Validación y Prueba** — Una introducción práctica con ejemplos reales en Python.

---

## 🎯 Propósito del repositorio

Este repositorio nació como material de apoyo para una presentación de clase, con el objetivo de explicar de forma clara y práctica uno de los conceptos más fundamentales del Machine Learning: **cómo y por qué dividimos nuestros datos en tres conjuntos**.

Si alguna vez te has preguntado:

- ¿Por qué no entrenamos con todos los datos disponibles?
- ¿Qué diferencia hay entre validación y prueba?
- ¿Cómo sé si mi modelo está aprendiendo o solo memorizando?

...este repositorio es para ti.

---

## 📁 Estructura del proyecto

```
data-split-ml/
│
├── README.md                        ← Estás aquí
│
├── notebooks/
│   └── division_datos_completo.ipynb   ← Tutorial completo, paso a paso
│
├── src/
│   ├── basic_split.py               ← División simple 80-20
│   ├── train_val_test_split.py      ← División completa 70-15-15
│   ├── stratified_split.py          ← División estratificada
│   └── time_series_split.py         ← División para series temporales
│
├── data/
│   └── README.md                    ← Descripción de los datasets usados
│
└── requirements.txt                 ← Dependencias necesarias
```

---

## 🧠 Conceptos

| Concepto | Descripción | Archivo |
|----------|-------------|---------|
| Tutorial completo | Todos los conceptos + visualizaciones | `notebook/` |

---

## 🚀 Cómo empezar

### 1. Clona el repositorio

```bash
git clone https://github.com/RaulCtm/Division-de-Datos-en-Machine-Learning.git
cd Division-de-Datos-en-Machine-Learning
```

### 2. Instala las dependencias

```bash
pip install -r requirements.txt
```

### 3. Abre el notebook

```bash
jupyter notebook notebooks/division_datos_completo.ipynb
```

O si prefieres ir directamente a la uubicacion del notebook manualmente.


---

## 📦 Requisitos

- Python 3.8+
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

Todos incluidos en `requirements.txt`.

---

## 📖 ¿Por dónde empezar?

Si eres nuevo en el tema, te recomendamos este orden:

1. **Lee este README** completo (5 min)
2. **Abre el notebook** y ejecútalo celda por celda
3. **Revisa los scripts** en `src/` para ver el código limpio y reutilizable
4. **Experimenta**: cambia los porcentajes, usa tus propios datos

---

## 💡 La idea central (en dos líneas)

> Dividimos los datos para saber si nuestro modelo realmente **aprendió** los patrones del problema,
> o si solo **memorizó** los ejemplos que vio durante el entrenamiento.

---

## 🤝 Contribuciones

Este repositorio es material educativo. Si encuentras errores, tienes sugerencias o quieres añadir ejemplos, abre un Issue o un Pull Request. ¡Toda ayuda es bienvenida!

---
