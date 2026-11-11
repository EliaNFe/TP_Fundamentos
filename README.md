# Trabajo Práctico - Fundamentos de la Ciencia de Datos (Grupo 36)

Este repositorio contiene el desarrollo del Trabajo Práctico de análisis exploratorio de datos (EDA), pruebas de hipótesis y regresión lineal múltiple sobre el dataset de publicaciones de Airbnb (`listings.csv`).

---

## Contenido de la entrega

* **`TPE_Grupo36.ipynb`**: Notebook principal con todo el desarrollo del trabajo.
* **`requirements.txt`**: Listado de dependencias necesarias para ejecutar la notebook.
* **`README.md`**: Guia para ejecutar la notebook

---

## Requisitos e instalación

Tener instalado Python-3.
Soporte para el entorno virtual usando: sudo apt install python3-venv
Tener instalado Git.

### 1. Clonar el repositorio
### Dentro de la terminal ejecutar lo siguiente:
git clone https://github.com/EliaNFe/TP_Fundamentos.git
cd TP_Fundamentos/


### 2. Crear y activar el entorno virtual

En Linux / macOS:
Desde la terminal, parados ya en la carpeta del TP, ejecutamos: 
python3 -m venv venvTPE
source venvTPE/bin/activate
```

En Windows (PowerShell):
Desde la terminal, parados ya en la carpeta del TP, ejecutamos:
python -m venv venvTPE
.\venvTPE\Scripts\Activate.ps1
```

### 3. Instalar las dependencias

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

Librerías principales utilizadas:
* `numpy` y `pandas` (manipulación y limpieza de datos)
* `matplotlib`, `seaborn` y `sweetviz` (visualización y análisis exploratorio)
* `scipy` y `statsmodels` (pruebas estadísticas de hipótesis, regresión OLS y validación de supuestos)

### 4. Ejecucion de la notebook
-Abrir el IDE con la carpeta del TPE (TP_Fundamentos)
-Abrir la notebook llamada TPE_Grupo36.ipynb
-Ejecutar en orden las secciones o ejecutar todo con 'Run All'

---

## Organizacion de la notebook
### En la notebook encontramos 3 secciones:
-Seccion 1: Dedicada a la exploracion inicial y la limpieza de la base.
-Seccion 2: Dedicada al planteamiento y validacion de las hipotesis creadas por el grupo.
-Seccion 3: Dedicada al planteamiento y validacion de las hipotesis propuestas por la catedra.
