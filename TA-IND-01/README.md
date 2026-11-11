# TA-IND-01 — IEEE 29148 y tipos de requisitos de un sistema conocido

**Estudiante:** Mayra Lucila Córdova Carreño  
**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Sistema analizado:** Wattpad

## Contenido
- `main.tex`: informe en LaTeX (resumen, glosario, 15 requisitos, clasificación, autoevaluación, correcciones y reflexión).
- `main.pdf`: versión compilada del informe.
- `referencias.bib`: fuentes bibliográficas utilizadas.
- `figuras/`: tres capturas propias (`01_busqueda.png`, `02_lectura.png`, `03_votacion.png`).

## Compilación
Se requiere una distribución de LaTeX con `pdflatex` y los paquetes `babel` (español), `geometry`, `graphicx`, `longtable`, `array`, `booktabs`, `enumitem` y `microtype`.

Desde la carpeta `TA-IND-01`, ejecutar:

```bash
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```

El documento incluye bibliografía en estilo numérico IEEE directamente en `main.tex` para permitir compilarlo con `pdflatex` sin BibTeX; `referencias.bib` conserva los registros editables de las fuentes. Mantener los nombres de las imágenes exactamente como se indican.

## Alcance académico y transparencia
Los requisitos y umbrales propuestos son ejemplos de análisis académico y no representan métricas medidas en los servidores de Wattpad. Se utilizó asistencia de IA para organizar y revisar redacción, tablas y LaTeX; las afirmaciones normativas y la interpretación final deben contrastarse con las fuentes originales. No se distribuyen copias completas de normas protegidas por derechos de autor.
