# Telecom-X — Análisis de Evasión de Clientes (Churn)

## Descripción del Proyecto

Este proyecto realiza un análisis exploratorio de datos (EDA) y limpieza de datos de clientes de **Telecom X**, con el objetivo de detectar patrones de clientes que cancelan sus servicios (churn).

El análisis abarca:

- **Extracción y carga de datos** desde una fuente JSON pública
- **Limpieza de datos**: normalización de estructura anidada, tratamiento de valores nulos y conversión de tipos
- **Análisis exploratorio**: distribuciones de variables, correlaciones y métricas descriptivas
- **Análisis de churn**: identificación de patrones y factores asociados a la evasión de clientes
- **Visualizaciones** comparativas entre clientes que se quedan y los que se van

## Dataset

Los datos provienen de la base de clientes de Telecom X y contienen información sobre:

| Categoría  | Variables                                                                                   |
|------------|--------------------------------------------------------------------------------------------|
| Cliente    | Género, antigüedad, si tiene pareja, dependientes, si es adulto mayor                      |
| Teléfono   | Servicio telefónico, líneas múltiples                                                       |
| Internet   | Tipo de servicio, seguridad en línea, respaldo, protección, soporte técnico, streaming      |
| Cuenta     | Tipo de contrato, facturación digital, método de pago, cargos mensuales y totales           |

## Estructura del Proyecto

```
Telecom-X/
├── TelecomX_Analysis.ipynb   # Notebook principal con el análisis completo
├── requirements.txt           # Dependencias de Python
└── README.md                  # Documentación del proyecto
```

## Instrucciones de Uso

### 1. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 2. Ejecutar el notebook

```bash
jupyter notebook TelecomX_Analysis.ipynb
```

O abre el notebook directamente en [Google Colab](https://colab.research.google.com/).

## Principales Hallazgos

Consulta el notebook `TelecomX_Analysis.ipynb` para ver el análisis completo con visualizaciones y conclusiones detalladas.

## Tecnologías Utilizadas

- **Python 3.x**
- **pandas** — manipulación y limpieza de datos
- **NumPy** — operaciones numéricas
- **Matplotlib & Seaborn** — visualizaciones
- **Jupyter Notebook** — entorno de análisis interactivo