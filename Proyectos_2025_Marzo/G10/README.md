# G10 - Exportaciones Colombianas
## Modelo Predictivo de Exportaciones Colombianas

### 📋 Descripción del Proyecto

Este proyecto desarrolla un modelo predictivo avanzado para analizar y predecir las exportaciones colombianas. Utilizando datos históricos de comercio exterior y variables económicas internacionales, se busca identificar factores clave que influyen en las exportaciones y desarrollar herramientas de predicción para la toma de decisiones estratégicas.

### 🎯 Objetivos

- **Analizar tendencias** en las exportaciones colombianas
- **Identificar factores clave** que influyen en el comercio exterior
- **Desarrollar modelos predictivos** para exportaciones
- **Generar insights** para estrategias comerciales
- **Crear herramientas** de planificación para el sector exportador

### 📊 Datasets Utilizados

#### 1. Datos de Exportaciones (2019-2024)
- **Fuente**: DIAN, Banco de la República, DANE
- **Contenido**: Información detallada de exportaciones colombianas
- **Variables**: Valor exportado, productos, destinos, volúmenes

#### 2. Variables Económicas Internacionales
- **Fuente**: FMI, Banco Mundial, OCDE
- **Contenido**: Indicadores económicos globales
- **Variables**: PIB mundial, precios de commodities, tipos de cambio

#### 3. Información de Comercio Exterior
- **Fuente**: Organizaciones internacionales de comercio
- **Contenido**: Acuerdos comerciales, aranceles, barreras
- **Variables**: Acuerdos vigentes, preferencias arancelarias, restricciones

### 🛠️ Metodología

#### 1. Análisis Exploratorio de Datos (EDA)
- Exploración de series temporales de exportaciones
- Análisis de correlaciones entre variables
- Identificación de patrones estacionales y tendencias
- Detección de outliers y valores atípicos

#### 2. Preprocesamiento de Datos
- Limpieza de datos faltantes
- Normalización y estandarización de variables
- Creación de features temporales
- Manejo de valores extremos

#### 3. Modelado Predictivo
- **XGBoost**: Modelo principal de predicción
- **Regresión Lineal**: Modelo de referencia
- **Random Forest**: Validación de resultados
- **Validación Cruzada**: Evaluación robusta de modelos

### 📈 Resultados Principales

#### Modelos Desarrollados
1. **Modelo XGBoost Principal**
   - Alta precisión en predicciones
   - Identificación de features importantes
   - Manejo efectivo de no-linealidades

2. **Análisis de Tendencias**
   - Identificación de patrones estacionales
   - Detección de cambios estructurales
   - Proyecciones futuras confiables

3. **Factores Clave Identificados**
   - Precios de commodities
   - Tipo de cambio
   - Demanda internacional
   - Acuerdos comerciales

### 📁 Estructura del Proyecto

```
G10/
├── CÓDIGOS/
│   ├── Imagenes Caracteristicas relevantes del modelo/
│   ├── Imagenes comparacion Vres reales Vs predichos/
│   ├── informes EDA/
│   ├── Otros/
│   └── Proyecto_final_IA_exportaciones.ipynb
├── DATOS/
│   ├── 2019 unificado.xlsx
│   ├── 2020 unificado.xlsx
│   ├── 2021 unificado.xlsx
│   ├── 2022 unificado.xlsx
│   ├── 2023 unificado.xlsx
│   └── 2024 unificado.xlsx
├── DOCS/
│   ├── MODELO PREDICTIVO EXPORTACIONES COLOMBIANAS.pdf
│   ├── PROYECTO grado IA .docx
│   ├── PRESENTACIÓN PROYECTO IA.pptx
│   ├── Verificacion Estructura base x año de variables.xlsx
│   ├── Anexo Tablas Equivalencias de Variables.xlsx
│   ├── PROYECTO grado IA  PROTOTIPO MARGARITA.docx
│   ├── Proyecto escrito FINAL.docx
│   └── EDA_df.html
└── README.md
```

### 🔍 Archivos Principales

#### Código Principal
- **`Proyecto_final_IA_exportaciones.ipynb`**: Notebook principal con el análisis completo

#### Documentación
- **`MODELO PREDICTIVO EXPORTACIONES COLOMBIANAS.pdf`**: Documento final del proyecto
- **`PROYECTO grado IA .docx`**: Documento técnico detallado
- **`PRESENTACIÓN PROYECTO IA.pptx`**: Presentación final
- **`Proyecto escrito FINAL.docx`**: Documento ejecutivo

#### Datos
- **`2019-2024 unificado.xlsx`**: Datos de exportaciones por año
- **`Verificacion Estructura base x año de variables.xlsx`**: Verificación de estructura de datos
- **`Anexo Tablas Equivalencias de Variables.xlsx`**: Tablas de equivalencias

#### Análisis Exploratorio
- **`EDA_df.html`**: Análisis exploratorio interactivo

### 🎯 Aplicaciones y Usos

#### Sector Exportador
- **Planificación estratégica** de exportaciones
- **Identificación de oportunidades** de mercado
- **Optimización de recursos** comerciales
- **Gestión de riesgos** cambiarios

#### Políticas Públicas
- **Diseño de políticas** comerciales
- **Evaluación de acuerdos** comerciales
- **Planificación de incentivos** exportadores
- **Análisis de impacto** de medidas económicas

#### Sector Financiero
- **Análisis de riesgo** crediticio
- **Evaluación de proyectos** exportadores
- **Gestión de portafolios** internacionales
- **Desarrollo de productos** financieros

### 📊 Métricas de Evaluación

- **R² (Coeficiente de Determinación)**: Bondad de ajuste
- **RMSE (Error Cuadrático Medio)**: Precisión de predicciones
- **MAE (Error Absoluto Medio)**: Error promedio
- **MAPE (Error Porcentual Absoluto Medio)**: Error relativo
- **Validación Cruzada**: Robustez del modelo

### 🚀 Cómo Ejecutar el Proyecto

1. **Instalar dependencias**:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn plotly openpyxl
   ```

2. **Abrir el notebook principal**:
   - `Proyecto_final_IA_exportaciones.ipynb`

3. **Seguir el flujo de análisis**:
   - Carga y exploración de datos
   - Preprocesamiento y feature engineering
   - Modelado y entrenamiento
   - Evaluación y validación
   - Interpretación de resultados

### 📝 Hallazgos Principales

#### Patrones Identificados
- **Estacionalidad clara** en exportaciones
- **Correlación fuerte** con precios de commodities
- **Influencia significativa** del tipo de cambio
- **Impacto de acuerdos** comerciales

#### Insights Clave
- **Importancia de la diversificación** de mercados
- **Efecto de la volatilidad** cambiaria
- **Oportunidades en mercados** emergentes
- **Necesidad de valor agregado** en exportaciones

### 🔬 Tecnologías Utilizadas

- **Python**: Pandas, NumPy, Scikit-learn
- **XGBoost**: Modelo principal de predicción
- **Análisis de Series Temporales**: Statsmodels, Prophet
- **Visualización**: Matplotlib, Seaborn, Plotly
- **Validación**: Cross-validation, Métricas de evaluación

### 📈 Características del Modelo

#### Features Importantes
- **Precios de commodities** (petróleo, café, carbón)
- **Tipo de cambio** peso-dólar
- **PIB de países** destino
- **Indicadores económicos** globales

#### Capacidades Predictivas
- **Predicción a corto plazo** (1-3 meses)
- **Predicción a mediano plazo** (3-12 meses)
- **Análisis de escenarios** económicos
- **Identificación de tendencias** estructurales

### 📝 Conclusiones

El proyecto logra desarrollar un modelo predictivo robusto para las exportaciones colombianas, proporcionando:
- **Herramientas de predicción** confiables y precisas
- **Insights valiosos** para la toma de decisiones estratégicas
- **Base metodológica** para futuros análisis comerciales
- **Aplicaciones prácticas** para el sector exportador

---

*Proyecto desarrollado por G10 - Cohort Marzo 2025 - Tech2* 