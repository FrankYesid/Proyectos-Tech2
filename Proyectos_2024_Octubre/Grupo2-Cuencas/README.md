# Grupo 2 - Cuencas Hidrográficas
## Predicción del Recurso Hídrico en Colombia

### 📋 Descripción del Proyecto

Este proyecto desarrolla modelos predictivos para analizar y predecir variables hidrológicas en cuencas colombianas. El objetivo es contribuir a la gestión sostenible del recurso hídrico mediante el análisis de datos del IDEAM y la aplicación de técnicas de machine learning.

### 🎯 Objetivos

- **Analizar variables hidrológicas** en cuencas colombianas
- **Desarrollar modelos predictivos** para recursos hídricos
- **Identificar patrones** en series temporales hidrológicas
- **Contribuir a la gestión sostenible** del agua

### 📊 Datasets Utilizados

#### 1. Datos IDEAM
- **Fuente**: Instituto de Hidrología, Meteorología y Estudios Ambientales
- **Contenido**: Variables meteorológicas e hidrológicas
- **Variables**: Precipitación, temperatura, caudal, humedad

#### 2. Información de Cuencas
- **Fuente**: Datos geográficos y ambientales
- **Contenido**: Características de cuencas hidrográficas
- **Variables**: Área, pendiente, cobertura vegetal, uso del suelo

#### 3. Variables Complementarias
- **Fuente**: Múltiples fuentes oficiales
- **Contenido**: Factores que influyen en el recurso hídrico
- **Variables**: Clima, geología, actividades humanas

### 🛠️ Metodología

#### 1. Análisis Exploratorio de Datos (EDA)
- Exploración de series temporales
- Análisis de correlaciones entre variables
- Identificación de patrones estacionales
- Detección de outliers y valores atípicos

#### 2. Preprocesamiento de Datos
- Limpieza de datos faltantes
- Normalización de variables
- Creación de features temporales
- Manejo de valores extremos

#### 3. Modelado Predictivo
- **Modelos de Regresión**: Predicción de caudales
- **Series Temporales**: Análisis de tendencias
- **Validación Cruzada**: Evaluación de modelos
- **Optimización de Hiperparámetros**: Mejora de rendimiento

### 📈 Resultados Principales

#### Modelos Desarrollados
1. **Predicción de Caudales**
   - Modelo de regresión múltiple
   - Variables predictoras: precipitación, temperatura, humedad
   - Métricas de evaluación: R², RMSE, MAE

2. **Análisis de Tendencias**
   - Identificación de patrones estacionales
   - Detección de cambios en el régimen hídrico
   - Proyecciones futuras

3. **Correlaciones Identificadas**
   - Relación entre precipitación y caudal
   - Influencia de la temperatura en la evapotranspiración
   - Impacto de actividades humanas

### 📁 Estructura del Proyecto

```
Grupo2-Cuencas/
├── 1. BASES DE DATOS SELECCIONADAS/
│   ├── CNE_IDEAM.xls
│   ├── CNE_OE.xls
│   ├── GlosarioVariables.xlsx
│   └── [otros archivos de datos]
├── 2. DOCUMENTO PROYECTO/
│   ├── Proyecto FINAL Talento Tech Predicción del recurso hidrico-2024.pdf
│   ├── Metodologia CRISP-DM.docx
│   ├── Explicacion lineas de codigo cuaderno de IA.docx
│   └── [documentación adicional]
├── 3. CODES/
│   ├── [archivos de código]
│   └── [notebooks y scripts]
└── README.md
```

### 🔍 Archivos Principales

#### Documentación
- **`Proyecto FINAL Talento Tech Predicción del recurso hidrico-2024.pdf`**: Documento final del proyecto
- **`Metodologia CRISP-DM.docx`**: Metodología aplicada
- **`Explicacion lineas de codigo cuaderno de IA.docx`**: Explicación detallada del código

#### Datos
- **`CNE_IDEAM.xls`**: Datos del IDEAM
- **`CNE_OE.xls`**: Datos complementarios
- **`GlosarioVariables.xlsx`**: Descripción de variables

### 🎯 Aplicaciones y Usos

#### Gestión Ambiental
- **Planificación hidrológica** a nivel regional
- **Identificación de riesgos** de sequía o inundación
- **Evaluación de impacto** de cambio climático

#### Sector Agrícola
- **Planificación de riego** y cultivos
- **Optimización de recursos** hídricos
- **Reducción de pérdidas** por eventos climáticos

#### Generación de Energía
- **Planificación hidroeléctrica**
- **Gestión de embalses**
- **Optimización de producción** energética

### 📊 Métricas de Evaluación

- **R² (Coeficiente de Determinación)**: Bondad de ajuste
- **RMSE (Error Cuadrático Medio)**: Precisión de predicciones
- **MAE (Error Absoluto Medio)**: Error promedio
- **Validación Cruzada**: Robustez del modelo

### 🚀 Cómo Ejecutar el Proyecto

1. **Instalar dependencias**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn xlrd
   ```

2. **Cargar los datos**:
   - Abrir archivos Excel del IDEAM
   - Revisar glosario de variables

3. **Seguir la metodología CRISP-DM**:
   - Comprensión del negocio
   - Comprensión de los datos
   - Preparación de datos
   - Modelado
   - Evaluación
   - Despliegue

### 📝 Hallazgos Principales

#### Patrones Identificados
- **Estacionalidad clara** en variables hidrológicas
- **Correlación fuerte** entre precipitación y caudal
- **Influencia significativa** de la temperatura

#### Aplicaciones Prácticas
- **Sistema de alertas** para eventos extremos
- **Herramientas de planificación** para agricultores
- **Modelos de gestión** para autoridades ambientales

### 🔬 Tecnologías Utilizadas

- **Python**: Pandas, NumPy, Scikit-learn
- **Análisis de Series Temporales**: Statsmodels, Prophet
- **Visualización**: Matplotlib, Seaborn, Plotly
- **Validación**: Cross-validation, Métricas de evaluación

### 📝 Conclusiones

El proyecto logra desarrollar modelos predictivos efectivos para la gestión del recurso hídrico, proporcionando:
- **Herramientas de predicción** confiables
- **Insights valiosos** para la toma de decisiones
- **Base metodológica** para futuros estudios hidrológicos

---

*Proyecto desarrollado por Grupo 2 - Cohort Octubre 2024 - Tech2* 