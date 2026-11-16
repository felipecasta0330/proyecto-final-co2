# Emisiones de CO₂ per cápita: limpieza, visualización y regresión lineal

Proyecto final del curso **Ciencia de Datos** — Actividad 4  
**Fundación Universitaria Agraria de Colombia (UNIAGRARIA)** · 2026

Análisis de la sección **"Per capita CO₂ emissions"** del artículo [*CO₂ emissions*](https://ourworldindata.org/co2-emissions) de Our World in Data (Ritchie & Roser, 2020), con los datos abiertos de [owid/co2-data](https://github.com/owid/co2-data).

**Pregunta:** ¿qué tanto explica el ingreso (PIB per cápita) las emisiones de CO₂ per cápita de los países?

## Integrantes y roles

| Integrante | Usuario de GitHub | Rol | Notebook |
|---|---|---|---|
| Juan Felipe Castañeda Rodríguez | [@felipecasta0330](https://github.com/felipecasta0330) | Coordinador: repositorio, datos y limpieza | [01 · Limpieza de datos](notebooks/01_limpieza_datos.ipynb) |
| José Alejandro Ochoa | [@Jos38a](https://github.com/Jos38a) | Visualización y análisis exploratorio | [02 · Visualización y EDA](notebooks/02_visualizacion_eda.ipynb) |
| Ricardo José Díaz | [@requiempax](https://github.com/requiempax) | Modelo de regresión e interpretación | [03 · Regresión lineal](notebooks/03_regresion_lineal.ipynb) |

## Estructura

```
proyecto-final-co2/
├── README.md
├── .gitignore
├── data/
│   ├── owid-co2-data.csv          ← datos originales de Our World in Data
│   ├── owid-co2-codebook.csv      ← diccionario de variables
│   ├── co2_paises_limpio.csv      ← generado por el notebook 01
│   ├── co2_mundo.csv              ← generado por el notebook 01
│   └── co2_grupos_ingreso.csv     ← generado por el notebook 01
└── notebooks/
    ├── 01_limpieza_datos.ipynb
    ├── 02_visualizacion_eda.ipynb
    └── 03_regresion_lineal.ipynb
```

Los notebooks se ejecutan en orden: el 01 produce los archivos limpios que usan el 02 y el 03.

## Resultados principales

Se completarán al terminar los tres notebooks.

## Cómo ejecutar

```bash
git clone https://github.com/felipecasta0330/proyecto-final-co2.git
cd proyecto-final-co2
pip install pandas numpy matplotlib scipy scikit-learn notebook
jupyter notebook
```

También se pueden ver directamente en GitHub (con las salidas ya ejecutadas) o abrir en Google Colab.

## Flujo de trabajo

Cada integrante trabajó en su propio notebook y lo subió desde su cuenta en dos entregas (primera parte y versión final), en días distintos, ejecutando `git pull` antes de cada sesión.

## Referencias

- Ritchie, H., & Roser, M. (2020). *CO₂ emissions*. Our World in Data. https://ourworldindata.org/co2-emissions
- Our World in Data. *Data on CO₂ and greenhouse gas emissions*. https://github.com/owid/co2-data
- Pedregosa, F. et al. (2011). Scikit-learn: Machine Learning in Python. *JMLR*, 12, 2825–2830.
