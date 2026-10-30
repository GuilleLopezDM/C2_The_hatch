# The Hatch C2

## Archivos de entrega

```text
data/
  housing.csv
  WA_Fn-UseC_-Telco-Customer-Churn.csv
notebooks/
  housing.ipynb
  churn.ipynb
C2_The_hatch.md
requirements.txt
README.md
```

Cada notebook contiene su análisis, gráficos y conclusiones, y puede ejecutarse
de forma independiente. `housing.ipynb` resuelve regresión y `churn.ipynb`
clasificación. Se conservaron los resultados de la ejecución original.
El notebook combinado `notebooks/challenge.ipynb` se conserva como respaldo.
El enunciado está en `C2_The_hatch.md`; las fuentes de los datasets están citadas
dentro de cada notebook. No hace falta descargar ni generar archivos adicionales.

## Ejecutar en VS Code

Con Python 3.11, desde la raíz del proyecto:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

Si ya existe `.venv`, usá ese entorno. Abrí cada notebook, seleccioná el kernel
`.venv\Scripts\python.exe` y ejecutá **Run All**.

Para entregar, copiá únicamente los archivos y carpetas del esquema anterior.
