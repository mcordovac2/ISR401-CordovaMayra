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

El propósito del repositorio es conservar las respuestas originales, facilitar su revisión y documentar el proceso de transcripción digital realizado después de la evaluación presencial.

## 2. Estructura del directorio

La organización de referencia para los archivos de la actividad es:

```text
EV-PRAC-01/
├── README.md
├── main.tex
├── evidencias/
│   ├── hoja-01.jpg
│   ├── hoja-02.jpg
│   └── hoja-03.jpg
└── main.pdf/
    └── main.pdf
```

**Nota sobre la estructura actual:**

Durante la organización del repositorio en GitHub se generaron directorios con nombres visualmente similares debido a un espacio adicional al final de `EV-PRAC-01`.

Asimismo, durante los intentos de cargar el documento compilado se crearon directorios denominados `main.pdf`.

Después de verificar que el PDF definitivo podía visualizarse correctamente desde GitHub, se decidió conservar la organización funcional alcanzada.

La estructura presentada es una referencia simplificada de los archivos principales. El historial de commits conserva las operaciones de creación, eliminación y reorganización efectuadas durante el proceso.

## 3. Evidencias manuscritas

La carpeta `evidencias/` contiene las tres fotografías originales de las respuestas elaboradas durante la evaluación presencial:

- `hoja-01.jpg`: T1 — Conceptos aplicados al caso.
- `hoja-02.jpg`: T2 — Clasificación y auditoría.
- `hoja-03.jpg`: T4 — Sustento normativo de la calidad.

Estas fotografías permiten contrastar las respuestas manuscritas con su transcripción digital.

Las evidencias también se incorporaron como anexos al documento LaTeX, conservando su contenido original.

Cada fotografía fue incorporada mediante un commit independiente para registrar progresivamente las evidencias de la evaluación.

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

La transcripción se organizó en las siguientes secciones:

**T1. Conceptos aplicados al caso:** definición de requisito, clasificación de ejemplos según StRS, SyRS y SRS, y actividades del proceso de Ingeniería de Requisitos.

**T2. Clasificación y auditoría:** transcripción de la tabla manuscrita con identificadores, tipos de requisitos, documentos y justificaciones registradas durante la evaluación.

**T4. Sustento normativo de la calidad:** transcripción de las respuestas relacionadas con inconsistencia, contradicción e incompletitud.

El documento se ajustó para reducir los espacios vacíos innecesarios y mejorar la presentación, sin modificar el contenido académico original.

## 5. Instrucciones de compilación

**Compilador:** pdfLaTeX  
**Archivo principal:** `main.tex`  
**Archivo de salida generado:** `main.pdf`

### 5.1. Dependencias

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

### 5.2. Compilación local

Desde el directorio que contiene `main.tex` y la carpeta `evidencias/`, ejecutar los siguientes comandos en este orden:

```bash
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```

La primera ejecución genera el documento PDF y la segunda permite actualizar las referencias internas que correspondan.

### 5.3. Compilación en Overleaf

También es posible compilar el proyecto mediante Overleaf:

1. Crear o abrir un proyecto LaTeX.
2. Incorporar el archivo `main.tex`.
3. Crear la carpeta `evidencias/`.
4. Cargar las fotografías `hoja-01.jpg`, `hoja-02.jpg` y `hoja-03.jpg`.
5. Seleccionar pdfLaTeX como compilador.
6. Ejecutar la compilación.
7. Descargar el PDF generado.

### 5.4. Resultado de la compilación

El resultado esperado es un documento de cinco páginas:

- Dos páginas correspondientes a la transcripción digital.
- Tres páginas correspondientes a las evidencias manuscritas.

El archivo compilado conserva las respuestas originales y las fotografías de respaldo.

**Ubicación del PDF en GitHub:**

Durante la organización del repositorio, el documento definitivo se incorporó dentro de un directorio denominado `main.pdf`, por lo que su ruta de consulta es:

`main.pdf/main.pdf`

Esta ubicación corresponde al almacenamiento del archivo en GitHub y no modifica el procedimiento de compilación. Al ejecutar pdfLaTeX desde la carpeta del proyecto, el archivo generado se denomina `main.pdf`.

## 6. Uso de `.gitkeep` y organización en GitHub

Durante la preparación del repositorio se utilizó el archivo `.gitkeep` como recurso auxiliar para registrar directorios.

### 6.1. ¿Por qué se utilizó `.gitkeep`?

Git no registra directorios vacíos de manera independiente.

Por esta razón, es habitual incorporar un archivo auxiliar denominado `.gitkeep` dentro de una carpeta para permitir que Git registre su existencia.

Inicialmente, este procedimiento se utilizó para organizar la carpeta `evidencias/`, destinada a almacenar las fotografías manuscritas.

Posteriormente, durante los intentos de incorporar el PDF compilado, se volvió a utilizar este procedimiento para crear directorios desde la interfaz web de GitHub.

### 6.2. Dificultades encontradas

Durante la carga y organización de archivos se presentaron los siguientes inconvenientes:

1. Se generaron dos directorios visualmente similares denominados `EV-PRAC-01`, diferenciados por un espacio adicional al final del nombre de uno de ellos.
2. Algunos archivos se cargaron inicialmente en rutas distintas de las previstas.
3. Se creó un archivo denominado `main.pdf` que no contenía un documento PDF válido.
4. Se realizaron operaciones de eliminación y reorganización de directorios.
5. Al utilizar `.gitkeep` durante los intentos de organización, se crearon directorios denominados `main.pdf`.
6. Finalmente, se consiguió incorporar el PDF compilado y visualizarlo correctamente desde GitHub.

Estos inconvenientes estuvieron relacionados con la organización de archivos y rutas del repositorio, no con las respuestas académicas de la evaluación.

### 6.3. Consideración técnica

`.gitkeep` es un archivo auxiliar utilizado por convención. No constituye un comando especial de Git ni es un requisito de compilación de LaTeX.

Su función es permitir que Git registre un directorio que, de otro modo, permanecería vacío.

Este archivo no sustituye al documento PDF generado por Overleaf ni interviene en su contenido.

### 6.4. Resultado de la organización

Después de varios intentos de carga y reorganización, se consiguió incorporar el PDF definitivo y visualizarlo correctamente desde GitHub.

Se decidió conservar la organización funcional alcanzada y mantener los commits realizados para documentar las operaciones efectuadas durante la preparación de la actividad.

## 7. Registro de cambios y commits

El trabajo se documentó mediante commits sucesivos con el propósito de mantener un historial de las modificaciones realizadas.

### 7.1. Preparación del repositorio

Se registraron operaciones relacionadas con:

- Creación del README de la actividad.
- Creación de la carpeta de evidencias manuscritas.
- Eliminación de un archivo creado incorrectamente durante la organización inicial.
- Preparación de la estructura del proyecto.

### 7.2. Incorporación de evidencias

Las fotografías manuscritas fueron incorporadas progresivamente mediante commits individuales:

- `Agregar evidencia manuscrita - Hoja 01`
- `Agregar evidencia manuscrita - Hoja 02`
- `Agregar evidencia manuscrita - Hoja 03`

### 7.3. Elaboración del documento LaTeX

Se registraron commits correspondientes a la elaboración del documento:

- `Crear estructura inicial de main.tex`
- `Transcribir T1 - Conceptos aplicados al caso`
- `Transcribir T2(a) - Clasificación y auditoría`
- `Transcribir T4(b) - Sustento normativo de la calidad`
- `Ajustar espacios`
- `Incorporar evidencias manuscritas al documento LaTeX`
- `Correcciones finales del LaTeX`

Estos registros permiten identificar las etapas de construcción y revisión de la transcripción digital.

### 7.4. Organización del PDF

Durante la incorporación del documento compilado se registraron varios intentos de carga, eliminación y reorganización de archivos.

Entre los mensajes de commit utilizados se encuentran:

- `Agregar PDF definitivo con transcripción y evidencias`
- `Ubicar PDF final junto al código LaTeX y evidencias`
- `Create main.pdf`
- `Agregar main.pdf`
- `Subir main.pdf`
- `Delete EV-PRAC-01 directory`

Estas operaciones forman parte del historial técnico de preparación de la entrega.

### 7.5. Actualización de la documentación

Finalmente, se revisó el README para mejorar la claridad de las instrucciones y documentar las particularidades de la estructura del repositorio.

El historial de commits permite consultar la evolución del documento, las evidencias incorporadas y las operaciones realizadas durante su preparación.

## 8. Referencias

- ISO/IEC/IEEE 29148:2018 — Ingeniería de requisitos.
- SWEBOK v4.0 — Software Engineering Body of Knowledge.
- IREB CPRE FL v3.1 — Fundamentos de Ingeniería de Requisitos.
- Material académico de la Unidad I de Ingeniería de Requisitos (ISR-401).
- Guía-rúbrica oficial EV-PRAC-01 - SUM.

Estas referencias corresponden al marco académico de la evaluación y no implican la incorporación de respuestas adicionales a las elaboradas durante la prueba presencial.

## 9. Declaración de integridad académica

El documento digital corresponde a una transcripción fiel de las respuestas manuscritas elaboradas durante la evaluación presencial del 18 de noviembre de 2026.

No se añadieron respuestas nuevas, no se corrigieron contenidos conceptuales ni se completaron apartados que permanecieron sin resolver durante la evaluación.

Los fragmentos tachados se omitieron de la transcripción y las respuestas incompletas se conservaron sin modificaciones de contenido.

Las fotografías originales se mantienen como evidencia para permitir la comparación y verificación de la transcripción.

La organización de los archivos, los ajustes de formato y los procedimientos de compilación no alteran el contenido académico registrado durante la evaluación.
