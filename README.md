# The Hatch C2

## Archivos de entrega

```text
data/
  housing.csv
  WA_Fn-UseC_-Telco-Customer-Churn.csv
notebooks/
  challenge_supervisado.ipynb
C2_The_hatch.md
requirements.txt
README.md
```

El notebook contiene el análisis, los gráficos y las conclusiones ejecutadas.
El enunciado está en `C2_The_hatch.md`; las fuentes de los datasets están citadas
dentro del notebook. No hace falta descargar ni generar archivos adicionales.

## Ejecutar en VS Code

Con Python 3.11, desde la raíz del proyecto:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

Si ya existe `.venv`, usá ese entorno. Abrí el notebook, seleccioná el kernel
`.venv\Scripts\python.exe` y ejecutá **Run All**.

Para entregar, copiá únicamente los archivos y carpetas del esquema anterior.
