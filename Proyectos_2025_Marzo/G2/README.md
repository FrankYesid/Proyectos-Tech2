# G2 - Mascotas en Riesgo
## "Huellas en Peligro" - Identificación de Razas con Mayor Riesgo de Abandono

### 📋 Descripción del Proyecto

Este proyecto desarrolla modelos no supervisados para identificar razas de mascotas con mayor riesgo de abandono en Manizales-Caldas. Utilizando datos de adopción, abandono y características de mascotas, se busca crear herramientas que permitan diseñar estrategias preventivas y programas de protección animal más efectivos.

### 🎯 Objetivos

- **Identificar razas de mascotas** con mayor riesgo de abandono
- **Analizar patrones** de adopción y abandono
- **Desarrollar modelos de clustering** para segmentación
- **Generar insights** para programas de protección animal
- **Crear herramientas** de prevención del abandono

### 📊 Datasets Utilizados

#### 1. Datos de Mascotas en Manizales
- **Fuente**: Organizaciones de protección animal, clínicas veterinarias
- **Contenido**: Información detallada de mascotas en la región
- **Variables**: Raza, edad, sexo, estado de salud, origen

#### 2. Información de Razas y Características
- **Fuente**: Bases de datos de razas caninas y felinas
- **Contenido**: Características físicas y comportamentales
- **Variables**: Tamaño, temperamento, necesidades de cuidado, esperanza de vida

#### 3. Datos de Adopción y Abandono
- **Fuente**: Refugios, organizaciones de rescate
- **Contenido**: Historial de adopciones y abandonos
- **Variables**: Fecha de adopción/abandono, motivo, destino

### 🛠️ Metodología

#### 1. Análisis Exploratorio de Datos (EDA)
- Exploración de patrones de abandono por raza
- Análisis de correlaciones entre características
- Identificación de factores de riesgo
- Visualización de distribuciones y tendencias

#### 2. Preprocesamiento de Datos
- Limpieza de datos faltantes
- Normalización de variables numéricas
- Codificación de variables categóricas
- Manejo de valores extremos

#### 3. Modelado No Supervisado
- **K-Means Clustering**: Agrupación por similitud de riesgo
- **Análisis de Componentes Principales (PCA)**: Reducción de dimensionalidad
- **Hierarchical Clustering**: Análisis jerárquico
- **Validación de clusters**: Métricas de silueta, inercia

### 📈 Resultados Principales

#### Segmentos Identificados
1. **Razas de Alto Riesgo**
   - Mayor tasa de abandono
   - Características específicas de vulnerabilidad
   - Necesidad de programas especiales

2. **Razas de Riesgo Medio**
   - Tasa moderada de abandono
   - Factores de riesgo identificables
   - Potencial de mejora con intervenciones

3. **Razas de Bajo Riesgo**
   - Baja tasa de abandono
   - Características protectoras
   - Modelos de éxito replicables

### 📁 Estructura del Proyecto

```
G2/
├── codigos/
│   └── HUELLAS EN PELIGRO_ Identificación de Razas con Mayor Riesgo de Abandono en Manizales-Caldas mediante Modelos No Supervisados.ipynb
├── Datos/
│   └── Proyecto mascotas con proposito IA.xlsx
├── documentos/
│   ├── "HUELLAS EN PELIGRO_ Identificación de Razas con Mayor Riesgo de Abandono en Manizales-Caldas mediante Modelos No Supervisados".docx
│   ├── EDA_df_huellas_en_peligro_modelo.html
│   ├── EDA_df_huellas_en_peligro.html
│   └── [documentación adicional]
└── README.md
```

### 🔍 Archivos Principales

#### Código Principal
- **`HUELLAS EN PELIGRO_ Identificación de Razas con Mayor Riesgo de Abandono en Manizales-Caldas mediante Modelos No Supervisados.ipynb`**: Notebook principal con el análisis completo

#### Documentación
- **`"HUELLAS EN PELIGRO_ Identificación de Razas con Mayor Riesgo de Abandono en Manizales-Caldas mediante Modelos No Supervisados".docx`**: Documento final del proyecto

#### Datos
- **`Proyecto mascotas con proposito IA.xlsx`**: Base de datos de mascotas

#### Análisis Exploratorio
- **`EDA_df_huellas_en_peligro_modelo.html`**: Análisis exploratorio del modelo
- **`EDA_df_huellas_en_peligro.html`**: Análisis exploratorio general

### 🎯 Aplicaciones y Usos

#### Organizaciones de Protección Animal
- **Diseño de programas** preventivos específicos
- **Focalización de recursos** en razas de alto riesgo
- **Desarrollo de campañas** de concientización
- **Planificación de adopciones** responsables

#### Clínicas Veterinarias
- **Identificación de pacientes** en riesgo
- **Desarrollo de programas** de seguimiento
- **Educación a propietarios** sobre responsabilidades
- **Prevención de abandonos** por problemas de salud

#### Autoridades Locales
- **Diseño de políticas** de protección animal
- **Asignación de recursos** para control animal
- **Desarrollo de regulaciones** específicas
- **Evaluación de programas** existentes

### 📊 Métricas de Evaluación

- **Coeficiente de Silueta**: Calidad de la agrupación
- **Inercia**: Cohesión interna de clusters
- **Análisis de varianza**: Validación estadística
- **Visualización de clusters**: Interpretación gráfica
- **Estadísticas descriptivas**: Caracterización de segmentos

### 🚀 Cómo Ejecutar el Proyecto

1. **Instalar dependencias**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn plotly openpyxl
   ```

2. **Abrir el notebook principal**:
   - `HUELLAS EN PELIGRO_ Identificación de Razas con Mayor Riesgo de Abandono en Manizales-Caldas mediante Modelos No Supervisados.ipynb`

3. **Seguir el flujo de análisis**:
   - Carga y exploración de datos
   - Preprocesamiento
   - Modelado de clustering
   - Evaluación y validación
   - Interpretación de resultados

### 📝 Hallazgos Principales

#### Factores de Riesgo Identificados
- **Tamaño de la raza** como factor determinante
- **Necesidades de cuidado** específicas
- **Expectativas vs realidad** de los propietarios
- **Costos de mantenimiento** asociados

#### Patrones de Abandono
- **Estacionalidad** en abandonos
- **Correlación** con eventos económicos
- **Diferencias** por región y demografía
- **Impacto** de campañas de concientización

### 🔬 Tecnologías Utilizadas

- **Python**: Pandas, NumPy, Scikit-learn
- **Clustering**: K-Means, Hierarchical Clustering
- **Reducción de Dimensionalidad**: PCA
- **Visualización**: Matplotlib, Seaborn, Plotly
- **Validación**: Métricas de clustering, análisis estadístico

### 🐕 Características del Análisis

#### Variables Analizadas
- **Características físicas**: Tamaño, peso, tipo de pelaje
- **Características comportamentales**: Energía, sociabilidad, entrenabilidad
- **Necesidades de cuidado**: Ejercicio, alimentación, salud
- **Factores económicos**: Costos de mantenimiento, veterinaria

#### Segmentos de Riesgo
- **Alto Riesgo**: Razas grandes, alta energía, costos elevados
- **Medio Riesgo**: Razas medianas, necesidades moderadas
- **Bajo Riesgo**: Razas pequeñas, fácil cuidado, bajo costo

### 📝 Conclusiones

El proyecto logra identificar patrones claros en el abandono de mascotas, proporcionando:
- **Base de datos** para programas preventivos más efectivos
- **Insights valiosos** para organizaciones de protección animal
- **Metodología replicable** para otros estudios similares
- **Herramientas de segmentación** para estrategias específicas

### 🌟 Impacto Social

#### Beneficios Esperados
- **Reducción del abandono** de mascotas
- **Mejora en la calidad de vida** animal
- **Optimización de recursos** de protección animal
- **Concientización** sobre tenencia responsable

#### Aplicaciones Futuras
- **Expansión a otras regiones** del país
- **Desarrollo de aplicaciones** móviles
- **Integración con sistemas** de registro animal
- **Colaboración con** autoridades locales

---

*Proyecto desarrollado por G2 - Cohort Marzo 2025 - Tech2* 