# Análisis de pingüinos

Proyecto de ciencia de datos para analizar un conjunto de datos sobre pingüinos.
Este repositorio contiene el entorno de desarrollo listo para replicar; el análisis
se desarrollará en `analisis.py`.

## Estructura

```
analisis_pinguinos/
├── .venv/              # entorno virtual (no se sube al repositorio)
├── analisis.py         # script de análisis
├── requirements.txt    # dependencias con versiones fijadas
└── README.md
```

## Requisitos

- Python 3.14 (versión con la que se creó el entorno y se fijaron las dependencias)

## Configuración del entorno

Ejecuta los siguientes pasos desde la carpeta `analisis_pinguinos`.

### 1. Crear el entorno virtual

```bash
python -m venv .venv
```

### 2. Activar el entorno

Windows (PowerShell):

```powershell
.venv\Scripts\Activate.ps1
```

Windows (CMD):

```cmd
.venv\Scripts\activate.bat
```

macOS / Linux:

```bash
source .venv/bin/activate
```

Al activarlo, el prompt de la terminal mostrará el prefijo `(.venv)`.

### 3. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 4. Verificar la instalación

```bash
python -c "import pandas, matplotlib, seaborn; print('Entorno listo')"
```

## Librerías principales

| Librería   | Uso                                      |
|------------|------------------------------------------|
| pandas     | Manipulación de datos                    |
| matplotlib | Visualización                            |
| seaborn    | Visualizaciones estadísticas             |

## Desactivar el entorno

```bash
deactivate
```
