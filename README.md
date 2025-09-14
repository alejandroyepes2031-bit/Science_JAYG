# Science_JAYG

Este repositorio contiene material educativo en ciencias naturales, diseñado para estudiantes de secundaria, preuniversitario y primeros años de universidad.

## Objetivos
- Enseñar ciencias naturales mediante ejemplos prácticos.
- Promover el aprendizaje reproducible con Jupyter Notebooks, Python, R y Bash.
- Fomentar el uso de GitHub como aula abierta.

## Estructura del repositorio
```
Science_JAYG/
│
├── notebooks/   # Notebooks de Jupyter con lecciones paso a paso
├── data/        # Datos de ejemplo (FASTA, CSV, etc.)
├── scripts/     # Scripts reutilizables en Python/R/Bash
├── docs/        # Documentación en Markdown
└── README.md    # Explicación del proyecto
```

## Primeros pasos
1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/tu-usuario/Science_JAYG.git
   cd Science_JAYG
   ```

2. Instalar dependencias mínimas (ejemplo en Ubuntu):  
   ```bash
   sudo apt update && sudo apt install python3-pip r-base
   pip install jupyterlab biopython pandas matplotlib seaborn
   ```

3. Abrir JupyterLab:  
   ```bash
   jupyter lab
   ```

4. Navegar a la carpeta `notebooks/` y abrir el tutorial de interés.

## Licencia
Este material se distribuye bajo licencia MIT (código) y CC-BY (contenidos educativos).
