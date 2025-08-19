# 1CHALLENGEALURATELECOM
En este desafío, el enfoque está en el proceso de extracción de datos desde la API, limpieza y transformación

**Telecom X - Análisis de Datos Exploratorios (EDA)**
## 1. Propósito del Proyecto
    El objetivo principal de este proyecto fue realizar un análisis exploratorio de datos (EDA) para comprender las principales características y el comportamiento de los clientes de la empresa de telecomunicaciones ficticia Telecom X. A través del análisis de datos, buscamos identificar patrones, tendencias e insights clave sobre los servicios y la demografía de los clientes para entender mejor el problema de la cancelación de clientes (churn).

## 2. Estructura del Proyecto
    El repositorio está organizado de la siguiente manera para garantizar un flujo de trabajo claro:

        notebook/: Contiene el cuaderno de Jupyter (telecom_eda.ipynb) donde se realizó todo el análisis.

        data/: Almacena el conjunto de datos original (telecom_data.csv) y la versión tratada del mismo.

        images/: Carpeta para guardar los gráficos y visualizaciones generadas durante el análisis.

## 3. Gráficos e Insights Clave
    El análisis exploratorio reveló hallazgos importantes sobre los datos, los cuales fueron visualizados a través de gráficos:

    Distribución del Churn: Se observó que una parte significativa de los clientes (26.5%) ha cancelado sus servicios. Esta tasa de churn resalta la urgencia de la empresa para abordar este problema.

    Influencia del Tipo de Contrato: El análisis mostró una fuerte correlación entre el tipo de contrato del cliente y la tasa de abandono. Los clientes con contratos mensuales tienen una tasa de churn mucho más alta en comparación con aquellos con contratos anuales o bianuales.

    Relación entre Servicios y Churn: Se encontró que los clientes que no tienen servicios adicionales como seguridad en línea (OnlineSecurity) o soporte técnico (TechSupport) tienden a cancelar con mayor frecuencia. Esto sugiere que estos servicios son importantes para la retención.

    Distribución de Cargos Mensuales: La distribución de los cargos mensuales mostró una concentración de clientes con cargos bajos. Sin embargo, los clientes con cargos mensuales más altos tenían una mayor propensión a cancelar sus servicios.

## 4. Instrucciones de Ejecución
    Para ejecutar el cuaderno y replicar el análisis, siga estos pasos:

    Clonar el repositorio:
    git clone https://github.com/tu-usuario/nombre-del-repo.git

    Instalar bibliotecas: El proyecto requiere las siguientes bibliotecas. Se recomienda utilizar un entorno virtual.
    pip install pandas / matplotlib / seaborn

    Cargar los datos: Asegúrese de que el archivo telecom_data.csv esté en la carpeta data/.

    Ejecutar el cuaderno: Abra el archivo notebook/telecom_eda.ipynb en su entorno de Jupyter y ejecute las celdas en orden.



## **Diccionario de datos**
customerID: número de identificación único de cada cliente
Churn: si el cliente dejó o no la empresa
gender: género (masculino y femenino)
SeniorCitizen: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
Partner: si el cliente tiene o no una pareja
Dependents: si el cliente tiene o no dependientes
tenure: meses de contrato del cliente
PhoneService: suscripción al servicio telefónico
MultipleLines: suscripción a más de una línea telefónica
InternetService: suscripción a un proveedor de internet
OnlineSecurity: suscripción adicional de seguridad en línea
OnlineBackup: suscripción adicional de respaldo en línea
DeviceProtection: suscripción adicional de protección del dispositivo
TechSupport: suscripción adicional de soporte técnico, menor tiempo de espera
StreamingTV: suscripción de televisión por cable
StreamingMovies: suscripción de streaming de películas
Contract: tipo de contrato
PaperlessBilling: si el cliente prefiere recibir la factura en línea
PaymentMethod: forma de pago
Charges.Monthly: total de todos los servicios del cliente por mes
Charges.Total: total gastado por el cliente