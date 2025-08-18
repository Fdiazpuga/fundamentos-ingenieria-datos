# Tarea L3 — Obtención de Datos desde Archivos con Pandas

**Curso:** Fundamentos de Ingeniería de Datos  
**Estudiante:** Fabián Díaz

Notebook: [`Tarea_L3.ipynb`](./Tarea_L3_Módulo_3.ipynb)

## Objetivo
Implementar un flujo reproducible con **Pandas** para:
1) Cargar datos desde **CSV**, **Excel** y **Web**.  
2) **Limpiar** (nulos, duplicados, tipos).  
3) **Transformar** (selección/renombrado y orden).  
4) **Exportar** resultados a CSV/Excel.

## Fuentes
- **CSV:** IMDB 1000 (`title, genre, content_rating, duration, star_rating`).  
- **Excel:** `data/oscar_winners.xlsx` (generado por script del notebook).  
- **Web:** tabla “Películas más taquilleras de 2025” (Wikipedia, `read_html`).

## Cómo ejecutar (Colab recomendado)
1. Abrir `Tarea_L3.ipynb`.  
2. Ejecutar la celda que **genera** `data/oscar_winners.xlsx`.  
3. Sección 1: Carga (CSV, Excel, Web).  
4. Sección 2: Limpieza.  
5. Sección 3: Transformación.  
6. Sección 4: Exportación.

## Salidas
- `peliculas_imdb_limpio.csv`  
- `peliculas_imdb_limpio.xlsx`

> La comparación **antes vs. después** y las impresiones de verificación están dentro del notebook.
