
# FraudDetectAI: Banking Account Fraud Prevention

**FraudDetectAI** es un proyecto de machine learning cuyo objetivo es detectar el fraude en la apertura de cuentas bancarias utilizando un conjunto de datos sintéticos generados por un CTGAN entrenado con datos anonimizados del mundo real. Este proyecto proporciona una solución basada en modelos predictivos para identificar posibles fraudes en las solicitudes de apertura de cuentas bancarias.

## Descripción

El conjunto de datos utilizado tiene el propósito de crear un modelo de machine learning para detectar patrones de fraude en la apertura de cuentas bancarias. Cada instancia en el conjunto de datos representa una solicitud de apertura de cuenta bancaria y contiene características diseñadas para simular situaciones reales de fraude.

## Objetivo

El objetivo principal de **FraudDetectAI** es construir un modelo de machine learning que pueda predecir y clasificar solicitudes de apertura de cuentas bancarias como fraudulentas o no fraudulentas, ayudando a las instituciones financieras a prevenir y detectar actividades fraudulentas.

## Tecnologías utilizadas

- **Python**: Lenguaje de programación principal para el desarrollo del proyecto.
- **Scikit-learn**: Biblioteca de machine learning para el desarrollo de los modelos.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **Matplotlib / Seaborn**: Bibliotecas para visualización de datos.
- **Jupyter Notebooks**: Entorno interactivo para el desarrollo y la documentación del modelo.

## Instalación

Para ejecutar este proyecto, es necesario tener instalado Python y las siguientes dependencias. Puedes instalar las dependencias utilizando `pip` o `conda`:

### Usando pip:
```bash
pip install -r requirements.txt
```

### Usando conda:
```bash
conda create --name fraud-detect-ai python=3.x
conda activate fraud-detect-ai
conda install --file requirements.txt
```

## 📂 Estructura del Proyecto
```
📁 FraudDetectAI
│-- 📂 config/             # Archivos de configuración del entorno (Miniconda/Conda/Pip)
│-- 📂 data/               # Datos del proyecto
│   ├── raw/              # Datos en su estado original
│   ├── processed/        # Datos intermedios preprocesados
│   ├── final/            # Datos listos para entrenamiento y visualización
│-- 📂 notebooks/         # Libretas de experimentación
│-- 📂 models/            # Modelos entrenados
│-- README.md            # Documentación del proyecto
```
