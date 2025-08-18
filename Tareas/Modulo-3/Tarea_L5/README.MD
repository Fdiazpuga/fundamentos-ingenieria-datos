# Tarea L5 — Data Wrangling con Pandas (Bank Marketing)

**Curso:** Fundamentos de Ingeniería de Datos  
**Estudiante:** Fabián Díaz

Notebook: [`Tarea_L5.ipynb`](./Tarea_L5.ipynb)

## Objetivo
Aplicar un flujo reproducible de **carga → limpieza → transformación → exportación** con **Pandas**:
1) Cargar el CSV de **Bank Marketing (UCI)**  
2) Limpiar nulos/`unknown`, eliminar duplicados, mapear `yes/no`→`1/0`  
3) Transformar: seleccionar/renombrar columnas, `groupby` y filtros  
4) Exportar resultados a **CSV** y **Excel**

## Dataset
- **Bank Marketing (UCI)** – archivo usado: `bank-additional-full.csv`  
  Fuente: https://github.com/alexkataev/Case-Study-UCI-Bank-Marketing-Dataset  
  *(Separador `;`)*

## Cómo ejecutar (Colab recomendado)
1. Abrir `Tarea_L5.ipynb` en Colab.  
2. Ejecutar en orden las secciones **1 a 4**.  
3. Verificar mensajes de salida y vistas “antes vs. después”.

## Salidas
- `bank_marketing_limpio.csv`  
- `bank_marketing_limpio.xlsx`

> Las impresiones de verificación (`head`, nulos, duplicados, segmentos y filtros) están dentro del notebook.
