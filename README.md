# Cookiecutter Template
Platilla para proyectos de Ciencia de Datos.

## Requerimientos
- [Anaconda](https://www.anaconda.com/download/) >= 4.x
- [Git](https://git-scm.com/) >= 2.x
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0

```bash
pip install cookiecutter 
```
o
```bash
conda install -c conda-forge cookiecutter 
```
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
        │                         the creator's initials, and a short `-` delimited description.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.
