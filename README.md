# Inteligencia Artificial & Metaheurísticas — Cuadernos de Actividades

Colección de Jupyter Notebooks que cubren fundamentos de Machine Learning y algoritmos de optimización metaheurística, desarrollados como actividades prácticas de curso.

---

## Contenido del repositorio

| Actividad | Tema |
|-----------|------|
| `actividad0` | Introducción a Python |
| `actividad_1` | Regresión lineal con scikit-learn |
| `actividad_2` | Análisis exploratorio de datos (EDA) |
| `actividad_3` | Modelos de regresión y evaluación |
| `actividad_4 – actividad_9` | Machine Learning: clasificación, validación, métricas |
| `actividad_11 – actividad_13` | Modelos supervisados avanzados |
| `actividad_15` | Algoritmos Genéticos — modelado con UML |
| `actividad_16` | Algoritmos Genéticos — análisis de convergencia |
| `actividad_17` | Algoritmos Genéticos — optimización de funciones multivariable con DEAP |
| `actividad_18` | Optimización por Enjambre de Partículas (PSO) |
| `actividad_19` | PSO aplicado a función Six-Hump Camel |
| `actividad_20` | Optimización por Colonia de Hormigas (ACO) — Problema del Viajante (TSP) |
| `actividad_equipos` | Proyecto colaborativo en equipo |

---

## Tecnologías

- **Python 3**
- [NumPy](https://numpy.org/) — cómputo numérico
- [Pandas](https://pandas.pydata.org/) — manipulación de datos
- [Matplotlib](https://matplotlib.org/) / [Seaborn](https://seaborn.pydata.org/) — visualización
- [scikit-learn](https://scikit-learn.org/) — Machine Learning
- [DEAP](https://deap.readthedocs.io/) — algoritmos evolutivos

---

## Temas cubiertos

### Machine Learning
- Regresión lineal simple y múltiple
- Métricas de evaluación: MSE, R²
- División de conjuntos de entrenamiento/prueba

### Algoritmos Genéticos (AG)
- Codificación binaria de cromosomas
- Operadores: selección por ruleta, cruce en un punto, mutación
- Decodificación fenotípica y función de aptitud
- Análisis de convergencia

### Particle Swarm Optimization (PSO)
- Modelado de partículas con inercia, componente cognitiva y social
- Minimización de la función Six-Hump Camel
- Seguimiento de mejor posición local y global

### Ant Colony Optimization (ACO)
- Generación de matrices de distancias aleatorias
- Selección probabilística de ciudad basada en feromonas y heurística
- Actualización y evaporación de feromonas
- Resolución del Problema del Viajante (TSP)

---

## Estructura de carpetas

```
notebook/
├── actividad0/
├── actividad_1/
│   ├── actividad1.1.ipynb
│   ├── actividad1.2.ipynb
│   └── data/
├── actividad_2/
│   ├── actividad2.ipynb
│   └── data/
├── ...
└── actividad_20/
    └── actividad20.ipynb
```

---

## Requisitos

```bash
pip install numpy pandas matplotlib seaborn scikit-learn deap jupyter
```

## Uso

```bash
jupyter notebook
```

Abre el notebook de la actividad deseada desde el explorador de Jupyter.

---

## Autor

**Juan Limberg Hernandez del Rio**
