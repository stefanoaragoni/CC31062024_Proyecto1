# CC31062024_Proyecto1

## Proposito del proyecto
El propósito de este proyecto es entender el funcionamiento de la libreria SHAP y como esta puede ser utilizada para explicar el comportamiento de un modelo de machine learning. Más específicamente, se busca analizar y explicar las predicciones de CHURN (abandono de clientes) en el sector de telecomunicaciones. Para lograr esto, el proyecto tiene los siguientes objetivos:

1. Implementar y evaluar modelos predictivos de churn utilizando árboles de decisión y Random Forest.
2. Aplicar SHAP para interpretar cómo diferentes características afectan las predicciones del modelo.
3. Visualizar la importancia y el efecto de las características en las decisiones del modelo a través de gráficos SHAP.

## Como se ejecuta el proyecto
Para ejecutar el proyecto se debe de correr el archivo `proyecto1.ipynb` el cual se encuentra en la carpeta principal del proyecto. Este archivo se encarga de entrenar un modelo de machine learning y de explicar el comportamiento de este modelo utilizando la libreria SHAP.

Se debe de tener en cuenta que el archivo `proyecto1.ipynb` hace uso del archivo `WA_Fn-UseC_-Telco-Customer-Churn.csv` el cual se encuentra en la carpeta `datasets`. Este archivo es necesario para poder entrenar el modelo.

## Dependencias
Para poder ejecutar el proyecto se deben de instalar las siguientes librerias:

- numpy (1.25.2)
- pandas (2.0.3)
- matplotlib (3.7.3)
- seaborn (0.12.2)
- scikit-learn (1.3.2)
- shap (0.46.0)

Además, este proyecto fue desarrollado utilizando Python 3.9.2.