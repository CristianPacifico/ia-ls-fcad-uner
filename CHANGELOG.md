# Changelog

Todas las novedades relevantes del material de la catedra se registran en este archivo.

## 2026-06-05

### Agregado
- `06_Problemas_Satisfaccion_Restricciones.ipynb` — Introducción a CSPs con ejemplos usando `python-constraint` y `OR-Tools`:
  - Conceptos fundamentales: variables, dominios, restricciones
  - Ejemplos simples y problemas clásicos (Coloreo de mapas, N-Reinas, Sudoku, Criptaritmo)
  - Comparativa de librerías y recomendaciones de uso

## 2026-05-22

### Cambiado
- Renombrado `00_Laberinto_BFS_DFS.ipynb` → `01a_Laberinto_BFS_DFS.ipynb`
- Agregado `01b_Laberinto_simpleai.ipynb` — Laberinto resuelto con `simpleai` (BFS, DFS, UCS, IDS)
- Actualizado H1 de todos los notebooks `search/` a `Unidad 3: Búsqueda, Optimización y Agentes Inteligentes`
- Corregidas las rutas de los badges de Colab en todos los notebooks de `notebooks/search/` (de `notebooks/ml/search/` a `notebooks/search/`)
- Actualizado README.md: tabla "Búsqueda en IA" con numeración `01a`, `01b`, `01`–`05` y rutas correctas

## 2026-05-09

### Agregado
- `00_Laberinto_BFS_DFS.ipynb` — Resolución de laberinto 6×6 con BFS y DFS implementados desde cero con `numpy`, `queue` y `matplotlib`. Notebook introductorio de la unidad de Búsqueda.

## 2026-05-08

### Agregado
- Nueva sección **Búsqueda en IA** con 2 notebooks en `notebooks/ml/search/`:
  - `01_BusquedaNoInformada.ipynb` — BFS, DFS, UCS, IDS con `simpleai` sobre el Mapa de Rumanía
  - `02_BusquedaInformada.ipynb` — Greedy Best-First, A\*, IDA\* con heurística admisible
  - `03_BusquedaAdversaria.ipynb` — Minimax y Alpha-Beta Pruning sobre Tic-Tac-Toe
  - `04_BusquedaLocal.ipynb` — Hill Climbing, Simulated Annealing y Algoritmos Genéticos sobre 8-Reinas con `simpleai`
  - `05_Planificacion_PDDL.ipynb` — Planificación simbólica con PDDL (Blocksworld y Gripper) usando `pyperplan`
- Sección "Búsqueda en IA" agregada al README.md con badges de Colab.

## 2026-04-20

### Agregado
- Nuevos notebooks de ML del 23 al 27:
  - 23_Preprocessing.ipynb
  - 24_KNN.ipynb
  - 25_SVM.ipynb
  - 26_Normalization_vs_Standardization.ipynb
  - 27_Classification_vs_Clustering.ipynb
- Nuevos recursos visuales en notebooks/ml/images.

### Actualizado
- Mejora de portadas con imagenes y creditos en:
  - 01_LinealRegression_Intro.ipynb
  - 14_RandomForest_Tuning_Grid.ipynb
  - 16_FeatureImportances.ipynb
- Normalizacion de titulos entre README.md y la primera celda de los notebooks 01 al 27 para mantener consistencia de catalogo.
