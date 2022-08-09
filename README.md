# Cookiecutter Template
Platilla para proyectos de Ciencia de Datos.

## Requerimientos
* Anaconda > 4.x
* Git > 2.x 
* Cookiecutter Python Package > 1.4.0

<code> pip install cookiecutter </code>

o

<code> conda install -c conda-forge cookiecutter </code>

## Crear un nuevo proyecto
Copia en el directorio en el que vas a iniciar un nuevo proyecto
```bash
cookiecutter https://github.com/PabloJRW/cookiecutter-template 
```

## Estructura de la plantilla

    {{ cookiecutter.project_slug }}
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.
