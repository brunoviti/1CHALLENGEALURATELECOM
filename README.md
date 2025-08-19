# 1CHALLENGEALURATELECOM
En este desafío, el enfoque está en el proceso de extracción de datos desde la API, limpieza y transformación

**Telecom X - Análisis de Datos Exploratorios (EDA)**


## Propósito del Proyecto
Este proyecto se centra en el Análisis Exploratorio de Datos (EDA) para la empresa de telecomunicaciones ficticia, Telecom X. El objetivo principal es identificar los factores y comportamientos clave que influyen en el abandono de clientes (Churn). Los hallazgos de este análisis servirán como base fundamental para que el equipo de ciencia de datos pueda desarrollar modelos predictivos robustos.

## 2. Hallazgos e Insights Clave
El análisis de datos ha revelado varios factores que están fuertemente correlacionados con la propensión de un cliente a cancelar sus servicios. Estos insights se pueden resumir en los siguientes puntos:

Tasa de Abandono (Churn): La distribución de la variable de abandono (Churn) es desequilibrada, con un número significativo de clientes que han cancelado, lo que confirma la importancia de abordar este problema.

Antigüedad del Cliente (tenure): Existe una relación inversa entre la antigüedad del cliente y el abandono. Los clientes con menor antigüedad son los más propensos a cancelar sus servicios.

Cargos y Contrato:

Cargos Mensuales (Charges.Monthly): Los clientes con cargos mensuales más altos tienden a tener una mayor tasa de abandono.

Cargos Totales (Charges.Total): Los cargos totales bajos están asociados al abandono, lo cual es consistente con la corta antigüedad de los clientes que se van.

Tipo de Contrato (Contract): Los contratos mes a mes están fuertemente ligados a una tasa de abandono considerablemente más alta, a diferencia de los contratos de uno o dos años.

Servicios e Internet:

Servicios Adicionales: Los clientes que no tienen servicios como OnlineSecurity, OnlineBackup, DeviceProtection y TechSupport muestran una mayor probabilidad de abandonar.

Servicio de Internet (InternetService): El servicio de Fibra Óptica presenta una tasa de abandono más alta en comparación con el servicio DSL.

Datos Demográficos y de Pago:

Demografía: Los SeniorCitizen y los clientes sin Partner ni Dependents tienen una mayor tendencia a cancelar sus servicios.

Método de Pago (PaymentMethod): El método de pago cheque electrónico está asociado a una alta tasa de abandono.

## 3. Estructura del Proyecto y Archivos
notebook/: Contiene el cuaderno de Jupyter donde se realizó el análisis.

data/: Almacena el conjunto de datos utilizado.

diccionario/: archivo con el detalle de las columnas y sus nombres


## 4. Instrucciones de Ejecución
    Para ejecutar el cuaderno y replicar el análisis, siga estos pasos:

    Clonar el repositorio:
    git clone https://github.com/tu-usuario/nombre-del-repo.git

    Instalar bibliotecas: El proyecto requiere las siguientes bibliotecas. Se recomienda utilizar un entorno virtual.
    pip install pandas / matplotlib / seaborn

    Cargar los datos: Asegúrese de que el archivo telecom_data.csv esté en la carpeta data/.

    Ejecutar el cuaderno: Abra el archivo notebook/telecom_eda.ipynb en su entorno de Jupyter y ejecute las celdas en orden.
