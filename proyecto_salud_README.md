
# Proyecto Salud - Dataset Sintético de Diabetes

Este proyecto genera un dataset inspirado en el clásico **Pima Indians Diabetes**,
para practicar análisis de datos y machine learning en un contexto de salud.

## Archivos
- `diabetes_sintetico.csv`: Datos crudos con valores faltantes simulados (representados como `0`).
- `diabetes_clean.csv`: Datos limpios, con imputación de valores faltantes y nuevas variables derivadas.

## Transformaciones realizadas
1. Generación de 768 registros con variables biomédicas típicas (glucosa, presión, insulina, BMI, edad, etc.).
2. Inserción de valores faltantes en forma de ceros en ~10% de los datos.
3. Reemplazo de ceros por `NaN` y posterior imputación con **mediana**.
4. Creación de variables derivadas:
   - `BMI_Category`: Clasificación en Bajo peso, Normal, Sobrepeso y Obesidad.
   - `AgeGroup`: Agrupación en rangos etarios (Joven, Adulto, Maduro, Mayor).

## Próximos pasos sugeridos
- Análisis exploratorio de datos (EDA) con gráficos y estadísticas descriptivas.
- Entrenamiento de modelos predictivos (Logistic Regression, Random Forest).
- Construcción de dashboard interactivo con Streamlit.

