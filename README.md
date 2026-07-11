
# Premier League Insights

Sistema de análisis de datos de la Premier League desarrollado en Python mediante programación orientada a objetos, análisis exploratorio de datos y visualización interactiva con Streamlit.

## Institución

**Colegio Universitario de Cartago — Costa Rica**

## Descripción

Premier League Insights es un proyecto de análisis de datos deportivos que procesa información de jugadores de la Premier League.

El sistema permite cargar un archivo CSV, limpiar y transformar los datos, generar estadísticas descriptivas, representar jugadores y equipos mediante clases de Python y visualizar los resultados mediante gráficos y un dashboard interactivo.

El proyecto aplica conceptos de:

- Programación orientada a objetos.
- Carga y validación de archivos CSV.
- Limpieza y transformación de datos.
- Análisis exploratorio de datos.
- Visualización estadística.
- Desarrollo de dashboards con Streamlit.

## Dataset

El proyecto utiliza el archivo:

```text
premier.csv


El conjunto de datos contiene aproximadamente:

* 4 270 registros.
* 33 columnas.
* 140 910 valores.
* 0,04 % de datos faltantes.
* 0 registros duplicados.

Los datos incluyen variables relacionadas con el rendimiento de jugadores, como goles, asistencias, minutos, posición, equipo y otras estadísticas deportivas.

## Funcionalidades

### Carga de datos

La clase `CargadorDatos` permite:

* Leer el archivo CSV.
* Verificar la cantidad de filas y columnas.
* Examinar los tipos de datos.
* Identificar valores faltantes.
* Mostrar un resumen general del dataset.

### Limpieza y análisis exploratorio

El módulo de EDA permite:

* Corregir tipos de datos.
* Procesar valores faltantes.
* Normalizar variables categóricas.
* Calcular estadísticas descriptivas.
* Analizar distribuciones.
* Generar matrices de correlación.
* Exportar una versión limpia del dataset.

### Programación orientada a objetos

El proyecto incluye clases para representar entidades del dominio deportivo.

#### Jugador

Representa información como:

* Nombre.
* Equipo.
* Posición.
* Edad.
* Minutos jugados.
* Goles.
* Asistencias.

#### Equipo

Representa un club de la Premier League y permite asociar una colección de jugadores.

### Visualización

El proyecto genera visualizaciones como:

* Histogramas.
* Gráficos de dispersión.
* Matrices de correlación.
* Comparaciones entre goles, asistencias y minutos.
* Rankings de jugadores.
* Análisis por equipo y posición.

### Dashboard

La carpeta `DASHBOARD` contiene una aplicación desarrollada con Streamlit para explorar los datos de forma interactiva.

## Estructura del proyecto

```text
Premier_League_Insights/
│
├── PREMIER_LEAGUE/
│   ├── CARGA_DATA/
│   │   ├── cargador_datos.py
│   │   └── modulo.py
│   │
│   ├── CLASES/
│   │   ├── Equipo.py
│   │   ├── Jugador.py
│   │   └── modulo.py
│   │
│   ├── DASHBOARD/
│   │   └── app.py
│   │
│   ├── DATA/
│   │   ├── PROCESSED(LIMPIO)/
│   │   └── RAW(CRUDO)/
│   │
│   ├── EDA/
│   │   ├── modulo.py
│   │   └── Procesador_eda.py
│   │
│   ├── NOTEBOOKS/
│   │   ├── 01_EDA.ipynb
│   │   └── 02_Visualizacion.ipynb
│   │
│   └── VISUALIZACION/
│
└── README.md
```

## Tecnologías utilizadas

* Python
* pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Streamlit
* Jupyter Notebook

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/Isaakkko/Premier_League_Insights.git
cd Premier_League_Insights
```

Crear un entorno virtual:

```bash
python -m venv .venv
```

Activarlo en PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Instalar las dependencias:

```bash
python -m pip install pandas numpy matplotlib seaborn plotly streamlit jupyter
```

## Ejecución del dashboard

Desde la raíz del repositorio:

```bash
python -m streamlit run PREMIER_LEAGUE/DASHBOARD/app.py
```

Streamlit abrirá normalmente la aplicación en:

```text
http://localhost:8501
```

## Ejecución de los notebooks

Iniciar Jupyter Notebook:

```bash
python -m jupyter notebook
```

Después, abrir los archivos ubicados en:

```text
PREMIER_LEAGUE/NOTEBOOKS/
```

## Objetivo académico

El objetivo del proyecto es aplicar programación orientada a objetos, análisis exploratorio y visualización de datos en un caso deportivo real.

El sistema permite convertir datos crudos de la Premier League en información comprensible para analizar el desempeño de jugadores y equipos.

## Uso

Proyecto desarrollado con fines académicos y de aprendizaje.

```
```
