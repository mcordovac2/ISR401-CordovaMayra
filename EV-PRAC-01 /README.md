# EV-PRAC-01 - SUM

## Evaluación Sumativa — Unidad I

**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Carrera:** Ingeniería de Software  
**Estudiante:** Córdova Carreño Mayra Lucila  
**Fecha:** 18 de noviembre de 2026  
**Caso de estudio:** FRÍOVAC

---

## 1. Descripción

Este directorio reúne el código fuente en LaTeX, las evidencias manuscritas y la documentación correspondiente a la evaluación práctica de la Unidad I de la asignatura Ingeniería de Requisitos.

La evaluación se desarrolló a partir del caso de estudio FRÍOVAC, abordando conceptos fundamentales de Ingeniería de Requisitos, clasificación y auditoría de requisitos y sustento normativo de la calidad.

El propósito de este repositorio es conservar las respuestas originales, facilitar su revisión y documentar el proceso de transcripción digital realizado después de la evaluación presencial.

## 2. Estructura del directorio

La organización prevista para la entrega es:

```text
EV-PRAC-01/
├── README.md
├── main.tex
├── main.pdf
└── evidencias/
    ├── hoja-01.jpg
    ├── hoja-02.jpg
    └── hoja-03.jpg
```

**Nota sobre la estructura actual:** Durante la carga de archivos en GitHub se produjo una duplicación de directorios debido a un espacio adicional al final del nombre `EV-PRAC-01`. También se crearon directorios denominados `main.pdf` al intentar resolver la ubicación del documento compilado.

Estos directorios son distintos de un archivo PDF válido y deberán regularizarse para que la estructura definitiva coincida con la indicada anteriormente.

## 3. Evidencias manuscritas

La carpeta `evidencias/` contiene las tres fotografías originales de las respuestas elaboradas durante la evaluación presencial:

- `hoja-01.jpg`: T1 — Conceptos aplicados al caso.
- `hoja-02.jpg`: T2 — Clasificación y auditoría.
- `hoja-03.jpg`: T4 — Sustento normativo de la calidad.

Estas fotografías permiten contrastar las respuestas manuscritas con la transcripción digital.

Las evidencias también se incorporaron como anexos al documento LaTeX, conservando su contenido original.

## 4. Transcripción en LaTeX

El archivo `main.tex` contiene la transcripción de las respuestas desarrolladas durante la evaluación presencial.

Durante la digitalización se respetaron los siguientes criterios:

- Conservar las respuestas manuscritas originales.
- Omitir los fragmentos identificados como tachados en las hojas.
- Mantener los errores ortográficos y las expresiones tal como fueron escritos.
- Conservar las respuestas incompletas sin añadir información.
- No incorporar soluciones nuevas ni completar actividades que no fueron respondidas.
- Incluir una declaración de transcripción fiel.
- Incorporar las tres fotografías originales como anexos.

El documento se organizó procurando reducir los espacios vacíos innecesarios, sin alterar las respuestas originales.

## 5. Instrucciones de compilación

**Compilador:** pdfLaTeX  
**Archivo principal:** `main.tex`  
**Archivo de salida esperado:** `main.pdf`

### Dependencias

El documento utiliza los siguientes paquetes de LaTeX:

- `inputenc`
- `fontenc`
- `babel`
- `geometry`
- `graphicx`
- `array`
- `longtable`
- `booktabs`
- `xcolor`
- `hyperref`

Para compilar el documento es necesario disponer de una distribución de LaTeX que incluya estos paquetes y mantener las fotografías en las rutas indicadas dentro de `evidencias/`.

### Compilación local

Desde el directorio que contiene `main.tex`, ejecutar:

```bash
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```

También es posible compilar el proyecto mediante Overleaf, seleccionando pdfLaTeX como compilador.

El resultado esperado es un documento de cinco páginas: dos correspondientes a la transcripción y tres a las evidencias manuscritas.

## 6. Uso de `.gitkeep` y organización en GitHub

Durante la organización del repositorio se utilizó el archivo `.gitkeep` como recurso auxiliar para crear y conservar directorios.

### ¿Por qué se utilizó?

Git no registra directorios vacíos de manera independiente. Por esta razón, se puede colocar un archivo `.gitkeep` dentro de una carpeta para permitir que Git registre su existencia.

Inicialmente, este procedimiento se utilizó para organizar la carpeta `evidencias/`, destinada a almacenar las fotografías manuscritas.

Posteriormente, durante los intentos de incorporar `main.pdf`, se volvió a utilizar el mismo procedimiento para crear directorios desde la interfaz web de GitHub.

### Dificultades encontradas

Durante la carga de archivos se identificaron los siguientes inconvenientes:

1. Se generaron dos directorios visualmente similares llamados `EV-PRAC-01`, diferenciados por un espacio adicional al final de uno de sus nombres.
2. Algunos archivos se cargaron en una ruta distinta de la prevista.
3. Se creó inicialmente un archivo `main.pdf` sin contenido PDF válido.
4. Al utilizar nuevamente `.gitkeep`, se crearon directorios denominados `main.pdf`, en lugar de incorporar directamente el archivo binario compilado.

Estos inconvenientes corresponden a la organización de archivos y rutas del repositorio, no al contenido académico de la evaluación.

### Consideración técnica

`.gitkeep` es un archivo auxiliar utilizado por convención; no es un comando especial de Git ni un requisito de compilación de LaTeX.

Su utilización permite conservar carpetas vacías, pero no reemplaza la carga del archivo PDF generado por Overleaf.

Por tanto, la estructura final debe contener `main.pdf` como archivo PDF válido y no como directorio.

## 7. Registro de cambios y commits

El trabajo se documentó mediante commits sucesivos para mantener un historial de las modificaciones realizadas.

Entre las actividades registradas se encuentran:

- Creación del README de la evaluación.
- Organización de la carpeta de evidencias manuscritas.
- Incorporación progresiva de las fotografías originales.
- Elaboración y actualización del archivo `main.tex`.
- Correcciones de formato y fidelidad de la transcripción.
- Incorporación de las fotografías como anexos.
- Intentos de carga y organización del PDF compilado.
- Documentación de las dificultades relacionadas con las rutas y el uso de `.gitkeep`.

Este historial permite identificar la evolución del documento y las operaciones realizadas durante su preparación.

## 8. Referencias

- ISO/IEC/IEEE 29148:2018 — Ingeniería de requisitos.
- SWEBOK v4.0 — Software Engineering Body of Knowledge.
- Material académico de la Unidad I de Ingeniería de Requisitos (ISR-401).
- Guía-rúbrica oficial EV-PRAC-01 - SUM.

## 9. Declaración de integridad académica

El documento digital corresponde a una transcripción fiel de las respuestas manuscritas elaboradas durante la evaluación presencial del 18 de noviembre de 2026.

No se añadieron respuestas nuevas, no se corrigieron contenidos conceptuales ni se completaron apartados que permanecieron sin resolver durante la evaluación.

Los fragmentos tachados se omitieron de la transcripción y las respuestas incompletas se conservaron sin modificaciones de contenido.

Las fotografías originales se mantienen como evidencia para permitir la comparación y verificación de la transcripción.
