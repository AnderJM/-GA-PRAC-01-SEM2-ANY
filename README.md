# GA-PRAC-01-SEM2-ANY

Práctica GA-PRAC-01 de Ingeniería de Requerimientos (ISR-401), UTEQ, paralelo A, período 2026-2027: comparación entre los modelos de proceso de requisitos (cascada, iterativo e incremental y ágil) en los cuatro escenarios del material complementario.

Grupo ANY:
- Aldas Zambrano Alan Andrés
- Naranjo Flores Anderson Jeampiere
- Yépez Guagua Luis Antonio

## Estructura

| Archivo | Contenido |
| --- | --- |
| `main.tex` | Documento principal |
| `escenarios/e1.tex` a `escenarios/e4.tex` | Matriz comparativa, recomendación y riesgos de cada escenario |
| `escenarios/framework.tex` | Actores y framework de IR del escenario elegido |
| `referencias.bib` | Referencias en formato BibTeX |

## Cómo compilar

- Compilador: pdfLaTeX con BibTeX.
- Archivo principal: `main.tex`.
- Orden de comandos, desde la raíz del repositorio:

```
pdflatex main
bibtex main
pdflatex main
pdflatex main
```

- Dependencias: una distribución LaTeX con los paquetes `inputenc`, `fontenc`, `babel` (español), `lmodern`, `geometry`, `array`, `tabularx`, `booktabs`, `xcolor`, `hyperref` y el estilo bibliográfico `IEEEtran` (incluidos en TeX Live y MiKTeX). También compila en Overleaf con pdfLaTeX.

## Datos personales

Este repositorio no contiene datos personales de terceros.
