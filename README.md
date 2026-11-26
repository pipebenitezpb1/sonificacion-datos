# Sonificación de Datos · CO₂ y temperatura

**Unidad 1 · Interfaces Sonoras · Entrega 4.1** · Taller de Diseño de Interfaces, Universidad Adolfo Ibáñez · 2026
Autor: Luis-Felipe Benítez · Ficha: https://portafolio.insta3d.cl/sonificacion/ · Entrega 4.2 (imagen): https://github.com/pipebenitezpb1/sonificador-imagenes

## Objetivos
- Traducir un conjunto de datos a una melodía que permita **oír su tendencia** sin ver un gráfico.
- Justificar cada decisión de mapeo (variable → parámetro musical).
- Ofrecer un explorador donde cualquiera cargue su propio CSV y ajuste el mapeo.

## Descripción
La pieza oficial sonifica la evolución anual del CO₂ y de la temperatura global, hecha en TwoTone con datos de datahub.io: las dos variables suenan en paralelo (órgano y violín) y suben de tono cuando aumentan. El explorador interactivo aplica la misma lógica a cualquier dataset.
**Público y contexto:** público general y personas con baja visión; divulgación de datos climáticos en clases o exposiciones.

## Mapeo
| Dato | Parámetro sonoro |
|---|---|
| Orden de las filas (año) | Tiempo |
| Variable numérica | Altura de la nota, cuantizada a una escala |
| Variable categórica | Timbre (instrumento) |

## Tecnologías
TwoTone (pieza oficial), HTML + JavaScript + **Web Audio API** (explorador), CSV/XLSX.

## Cómo ejecutarlo
Abre `index.html` en el navegador. Archivos: `twotone-co2-temperatura.mp3` (pieza) y `dataset-co2-temperatura.xlsx` (datos).

## Proceso
> 📌 **Por aportar:** capturas del proyecto en TwoTone, la tabla de mapeo trabajada y pruebas de escucha (carpeta `proceso/`).

## Video demostrativo
> 📌 **Por aportar:** video reproduciendo la pieza y usando el explorador, subido a YouTube y enlazado aquí.
