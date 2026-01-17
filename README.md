# 🏪 Alura Store: Análisis Estratégico para la Optimización de Activos

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-ffffff?style=for-the-badge&logo=python&logoColor=black)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-444444?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org/)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)


## 📝 Propósito del Análisis
El objetivo principal de este proyecto es fundamentar la decisión de **vender una de las cuatro tiendas de Alura Store**. Esta desinversión tiene como fin reinvertir el capital obtenido en proyectos con mayor potencial de crecimiento. 

Para lograrlo, se evaluó el desempeño operativo mediante un sistema de puntuación basado en métricas clave como ingresos totales, costos de envío y satisfacción del cliente.

## 📂 Estructura del Proyecto y Organización
El repositorio se organiza de la siguiente manera:
* **Notebook Principal**: `alura_challenge_store.ipynb` 
* **Datasets**: Cuatro archivos csv correspondientes a cada una de las tiendas
* **Módulos**:
    * Sección de Análisis Operativo (Ingresos, Costos, Calificaciones).
    * Sección de Análisis Geográfico (Mapeo de coordenadas).

## 📊 Gráficos e Insights Obtenidos

### 1. Decisión de Venta (Métrica Principal)

<img width="1001" height="547" alt="image" src="https://github.com/user-attachments/assets/af249d45-5bc9-4c64-9b3f-fc3afc86a269" />

<img width="1023" height="547" alt="image" src="https://github.com/user-attachments/assets/97329964-485c-4caf-92dd-71cc2b1d050c" />

<img width="655" height="658" alt="image" src="https://github.com/user-attachments/assets/171d5f96-51b1-4adb-903d-c284a5f1dfa0" />

Tras evaluar las métricas, se detectó un empate en puntaje entre la **Tienda 1** y la **Tienda 4**. El desempate se definió por el ingreso total:
* **Ingresos Tienda 1**: $1,150,880,400.0.
* **Ingresos Tienda 4**: $1,038,375,700.0.
* **Resultado**: Se decidió vender la **Tienda 4** por generar aproximadamente **112.5 millones menos** que la Tienda 1.

### 2. Distribución Geográfica (Análisis Extra)

<img width="999" height="702" alt="image" src="https://github.com/user-attachments/assets/933f73c6-08f6-491c-a6da-7e052ffc62a4" />


Mediante el uso de gráficos de dispersión con `lat` y `lon`, se identificaron los siguientes patrones:
* **Tienda 1**: Posee un dominio claro en el eje norte y centro, con el alcance geográfico más amplio.
* **Tienda 2**: Presenta pocos puntos de entrega pero con ingresos elevados, lo que sugiere una estrategia de **calidad sobre cantidad** (productos de alto valor unitario).
* **Tienda 4**: Sus ventas están altamente concentradas en una zona específica (3 círculos juntos), lo que explica su eficiencia en costos de envío por proximidad geográfica.

## 🚀 Instrucciones para Ejecutar el Notebook
1.  **Entorno**: Abra el archivo `.ipynb` en [Google Colab](https://colab.research.google.com/) o Jupyter Notebook.
2.  **Carga de Datos**: Asegúrese de cargar los archivos CSV o definir los DataFrames de las 4 tiendas al inicio del script.
3.  **Dependencias**: Instale las librerías necesarias ejecutando:
    ```bash
    pip install pandas matplotlib seaborn
    ```
4.  **Ejecución**: Ejecute las celdas de forma secuencial para generar los gráficos de barras, matrices de calor y el mapa de dispersión final.


## 🚀 Instrucciones de Ejecución
Para replicar este análisis, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/alura-store.git](https://github.com/tu-usuario/alura-store.git)
