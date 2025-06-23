[⬅️ Volver a Proyectos_2025_Marzo](/Proyectos_2025_Marzo)

# Proyecto G1 - Formalización Empresarial

## Índice rápido
- [CÓDIGOS](/Proyectos_2025_Marzo/G1/CÓDIGOS)
- [DATOS](/Proyectos_2025_Marzo/G1/DATOS)
- [DOCUMENTOS](/Proyectos_2025_Marzo/G1/DOCUMENTOS)
- [EVIDENCIAS](/Proyectos_2025_Marzo/G1/EVIDENCIAS)

## Evaluación del Impacto de la Formalización Empresarial en Colombia

### 📋 Descripción del Proyecto

Este proyecto desarrolla modelos no supervisados para analizar el impacto de la formalización empresarial en Colombia. Utilizando datos de micronegocios y encuestas empresariales del DANE, se busca identificar patrones y segmentos que permitan entender mejor el proceso de formalización y sus efectos en el desarrollo económico.

### 🎯 Objetivos

- **Analizar patrones de formalización** empresarial en Colombia
- **Identificar segmentos de micronegocios** con características similares
- **Evaluar el impacto** de la formalización en variables económicas
- **Desarrollar modelos de clustering** para segmentación empresarial
- **Generar insights** para políticas de formalización

### 📊 Datasets Utilizados

#### 1. Encuesta de Micronegocios (2021-2023)
- **Fuente**: DANE (Departamento Administrativo Nacional de Estadística)
- **Contenido**: Información detallada de micronegocios colombianos
- **Variables**: Estado de formalización, ingresos, empleo, características del negocio

#### 2. Datos de Formalización Empresarial
- **Fuente**: Registros oficiales y encuestas
- **Contenido**: Procesos de formalización, barreras, incentivos
- **Variables**: Tipo de formalización, tiempo en el proceso, costos

#### 3. Variables Económicas y Sociales
- **Fuente**: Múltiples fuentes oficiales
- **Contenido**: Indicadores económicos y sociales
- **Variables**: PIB, empleo, pobreza, desarrollo regional

### 🛠️ Metodología

#### 1. Análisis Exploratorio de Datos (EDA)
- Exploración de patrones de formalización
- Análisis de correlaciones entre variables
- Identificación de outliers y valores atípicos
- Visualización de distribuciones y tendencias

#### 2. Preprocesamiento de Datos
- Limpieza de datos faltantes
- Normalización de variables numéricas
- Codificación de variables categóricas
- Manejo de valores extremos

#### 3. Modelado No Supervisado
- **K-Means Clustering**: Agrupación por similitud
- **Análisis de Componentes Principales (PCA)**: Reducción de dimensionalidad
- **Hierarchical Clustering**: Análisis jerárquico
- **Validación de clusters**: Métricas de silueta, inercia

### 📈 Resultados Principales

#### Segmentos Identificados
1. **Micronegocios Altamente Formalizados**
   - Registro mercantil completo
   - Cumplimiento tributario
   - Acceso a crédito formal
   - Mayor estabilidad económica

2. **Micronegocios en Proceso de Formalización**
   - Registro parcial
   - Cumplimiento básico
   - Acceso limitado a servicios financieros
   - Potencial de crecimiento

3. **Micronegocios Informales**
   - Sin registro mercantil
   - Operación informal
   - Acceso limitado a servicios
   - Vulnerabilidad económica

### 📁 Estructura del Proyecto

```
G1/
├── CÓDIGOS/
│   └── EVALUACIÓN DEL IMPACTO DE LA FORMALIZACIÓN EMPRESARIAL EN COLOMBIA_ UN ENFOQUE BASADO EN MODELOS NO SUPERVISADOS.ipynb
├── DATOS/
│   ├── 2021/
│   ├── 2022/
│   ├── 2023/
│   ├── EDA_df_comparativa cuarta iteracion(50).html
│   ├── EDA_df_comparativa primera iteracion(5).html
│   ├── EDA_df_comparativa tercera iteracion(20).html
│   └── TODOS LOS ARCHIVOS/
├── DOCUMENTOS/
│   ├── EVALUACIÓN DEL IMPACTO DE LA FORMALIZACIÓN EMPRESARIAL EN COLOMBIA UN ENFOQUE BASADO EN MODELOS NO SUPERVISADOS.docx
│   ├── Presentacion EVALUACIÓN DEL IMPACTO DE LA FORMALIZACIÓN EMPRESARIAL EN COLOMBIA_ UN ENFOQUE BASADO EN MODELOS NO SUPERVISADOS.pptx
│   ├── manual de recoleccion y conceptos basicos.pdf
│   ├── ficha metodológica encusta de micronegocios.pdf
│   └── [documentación adicional]
├── EVIDENCIAS/
│   └── Inteligencia Artificial.pdf
└── README.md
```

### 🔍 Archivos Principales

#### Código Principal
- **`EVALUACIÓN DEL IMPACTO DE LA FORMALIZACIÓN EMPRESARIAL EN COLOMBIA_ UN ENFOQUE BASADO EN MODELOS NO SUPERVISADOS.ipynb`**: Notebook principal con el análisis completo

#### Documentación
- **`EVALUACIÓN DEL IMPACTO DE LA FORMALIZACIÓN EMPRESARIAL EN COLOMBIA UN ENFOQUE BASADO EN MODELOS NO SUPERVISADOS.docx`**: Documento final del proyecto
- **`Presentacion EVALUACIÓN DEL IMPACTO DE LA FORMALIZACIÓN EMPRESARIAL EN COLOMBIA_ UN ENFOQUE BASADO EN MODELOS NO SUPERVISADOS.pptx`**: Presentación final
- **`ficha metodológica encusta de micronegocios.pdf`**: Metodología de la encuesta

#### Análisis Exploratorio
- **`EDA_df_comparativa cuarta iteracion(50).html`**: Análisis exploratorio final
- **`EDA_df_comparativa primera iteracion(5).html`**: Análisis exploratorio inicial
- **`EDA_df_comparativa tercera iteracion(20).html`**: Análisis exploratorio intermedio

### 🎯 Aplicaciones y Usos

#### Políticas Públicas
- **Diseño de programas** de formalización dirigidos
- **Identificación de barreras** específicas por segmento
- **Evaluación de impacto** de políticas existentes
- **Focalización de recursos** públicos

#### Sector Privado
- **Segmentación de mercados** para servicios financieros
- **Desarrollo de productos** para micronegocios
- **Estrategias de inclusión** financiera
- **Análisis de oportunidades** de negocio

#### Organizaciones de Desarrollo
- **Diseño de programas** de capacitación
- **Identificación de necesidades** de asistencia técnica
- **Evaluación de proyectos** de desarrollo empresarial

### 📊 Métricas de Evaluación

- **Coeficiente de Silueta**: Calidad de la agrupación
- **Inercia**: Cohesión interna de clusters
- **Análisis de varianza**: Validación estadística
- **Visualización de clusters**: Interpretación gráfica
- **Estadísticas descriptivas**: Caracterización de segmentos

### 🚀 Cómo Ejecutar el Proyecto

1. **Instalar dependencias**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn plotly
   ```

2. **Abrir el notebook principal**:
   - `EVALUACIÓN DEL IMPACTO DE LA FORMALIZACIÓN EMPRESARIAL EN COLOMBIA_ UN ENFOQUE BASADO EN MODELOS NO SUPERVISADOS.ipynb`

3. **Seguir el flujo de análisis**:
   - Carga y exploración de datos
   - Preprocesamiento
   - Modelado de clustering
   - Evaluación y validación
   - Interpretación de resultados

### 📝 Hallazgos Principales

#### Patrones Identificados
- **Correlación entre formalización** y estabilidad económica
- **Barreras específicas** por tipo de micronegocio
- **Factores facilitadores** del proceso de formalización

#### Insights Clave
- **Impacto positivo** de la formalización en ingresos
- **Necesidad de programas** diferenciados por segmento
- **Importancia de la asistencia técnica** en el proceso

### 🔬 Tecnologías Utilizadas

- **Python**: Pandas, NumPy, Scikit-learn
- **Clustering**: K-Means, Hierarchical Clustering
- **Reducción de Dimensionalidad**: PCA
- **Visualización**: Matplotlib, Seaborn, Plotly
- **Validación**: Métricas de clustering, análisis estadístico

### 📝 Conclusiones

El proyecto logra identificar patrones claros en el proceso de formalización empresarial, proporcionando:
- **Base de datos** para políticas públicas más efectivas
- **Insights valiosos** para el sector privado
- **Metodología replicable** para futuros estudios
- **Herramientas de segmentación** para programas de desarrollo

---

*Proyecto desarrollado por G1 - Cohort Marzo 2025 - Tech2* 