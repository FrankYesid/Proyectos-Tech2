[⬅️ Volver a Proyectos_2024_Octubre](/Proyectos_2024_Octubre)

# Grupo 1 - Modelo de Agrupación

## Índice rápido
- [1. Datos](/Proyectos_2024_Octubre/Grupo1-Modelo-Agrupacion/1.%20Datos)
- [2. Códigos](/Proyectos_2024_Octubre/Grupo1-Modelo-Agrupacion/2.%20C%C3%B3digos)
- [3. Reportes e informes](/Proyectos_2024_Octubre/Grupo1-Modelo-Agrupacion/3.%20Reportes%20e%20informes)

## Análisis de Condiciones de Vida del Hogar y Tenencia de Bienes

### 📋 Descripción del Proyecto

Este proyecto desarrolla modelos no supervisados para analizar y agrupar hogares colombianos según sus condiciones de vida, acceso a bienes y servicios, y características socioeconómicas. El objetivo es identificar patrones y segmentos de población que permitan diseñar políticas públicas más efectivas.

### 🎯 Objetivos

- **Identificar segmentos de hogares** con características similares
- **Analizar patrones de tenencia de bienes** y acceso a servicios
- **Desarrollar modelos de clustering** para segmentación poblacional
- **Generar insights** para políticas públicas y programas sociales

### 📊 Datasets Utilizados

#### 1. Condiciones de Vida del Hogar y Tenencia de Bienes (2023)
- **Fuente**: DANE (Departamento Administrativo Nacional de Estadística)
- **Contenido**: Información sobre vivienda, servicios públicos, bienes durables
- **Variables**: Tipo de vivienda, acceso a servicios, tenencia de electrodomésticos

#### 2. Educación (2023)
- **Fuente**: DANE
- **Contenido**: Niveles educativos, acceso a educación, características escolares
- **Variables**: Años de educación, tipo de institución, nivel alcanzado

#### 3. Tecnologías de Información y Comunicación (2023)
- **Fuente**: DANE
- **Contenido**: Acceso a internet, dispositivos tecnológicos, uso de TIC
- **Variables**: Tenencia de computadores, smartphones, acceso a internet

### 🛠️ Metodología

#### 1. Análisis Exploratorio de Datos (EDA)
- Limpieza y preparación de datos
- Análisis de correlaciones
- Identificación de outliers
- Visualización de distribuciones

#### 2. Preprocesamiento
- Normalización de variables
- Manejo de valores faltantes
- Codificación de variables categóricas
- Reducción de dimensionalidad (PCA)

#### 3. Modelado
- **K-Means Clustering**: Agrupación por similitud
- **Análisis de Componentes Principales (PCA)**: Reducción de dimensionalidad
- **Validación de clusters**: Métricas de silueta, inercia

### 📈 Resultados Principales

#### Segmentos Identificados
1. **Hogares de Alto Nivel Socioeconómico**
   - Acceso completo a servicios
   - Tenencia de bienes tecnológicos
   - Educación superior

2. **Hogares de Nivel Medio**
   - Acceso parcial a servicios
   - Bienes básicos
   - Educación media

3. **Hogares Vulnerables**
   - Acceso limitado a servicios
   - Poca tenencia de bienes
   - Educación básica

### 📁 Estructura del Proyecto

```
Grupo1-Modelo-Agrupacion/
├── 1. Datos/
│   ├── 2023_Condiciones de vida del hogar y tenencia de bienes.CSV
│   ├── 2023_Educacion.CSV
│   └── 2023_Tecnologias de información y comunicación.CSV
├── 2. Códigos/
│   ├── Modelo Predictivo G1.ipynb
│   ├── Copia de Modelo Predictivo G1.ipynb
│   └── modelo_no_supervisado_accesibilidad_internet.ipynb
├── 3. Reportes e informes/
│   ├── 1_Descripción General Proyecto GRUPO_1.pdf
│   ├── 2. Resumen_Proyecto_Modelo_Agrupacion_G1_TalentoTech.pdf
│   ├── 3. Presentación ModeloAgrupación G1_TalentoTech.pdf
│   └── [otros documentos]
└── README.md
```

### 🔍 Archivos Principales

#### Códigos
- **`Modelo Predictivo G1.ipynb`**: Notebook principal con el análisis completo
- **`modelo_no_supervisado_accesibilidad_internet.ipynb`**: Análisis específico de acceso a internet

#### Documentación
- **`1_Descripción General Proyecto GRUPO_1.pdf`**: Descripción detallada del proyecto
- **`2. Resumen_Proyecto_Modelo_Agrupacion_G1_TalentoTech.pdf`**: Resumen ejecutivo
- **`3. Presentación ModeloAgrupación G1_TalentoTech.pdf`**: Presentación final

### 🎯 Aplicaciones y Usos

#### Políticas Públicas
- **Diseño de programas sociales** dirigidos a segmentos específicos
- **Identificación de necesidades** por región y características
- **Evaluación de impacto** de políticas existentes

#### Sector Privado
- **Segmentación de mercados** para productos y servicios
- **Análisis de demanda** por características socioeconómicas
- **Estrategias de marketing** dirigidas

### 📊 Métricas de Evaluación

- **Coeficiente de Silueta**: Medida de calidad de clusters
- **Inercia**: Medida de cohesión interna
- **Análisis de varianza**: Validación estadística
- **Visualización de clusters**: Interpretación gráfica

### 🚀 Cómo Ejecutar el Proyecto

1. **Instalar dependencias**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

2. **Abrir el notebook principal**:
   - `Modelo Predictivo G1.ipynb`

3. **Seguir el flujo de análisis**:
   - Carga de datos
   - Exploración
   - Preprocesamiento
   - Modelado
   - Evaluación

### 📝 Conclusiones

El proyecto logra identificar patrones claros en las condiciones de vida de los hogares colombianos, proporcionando una base sólida para:
- **Toma de decisiones** basada en datos
- **Diseño de políticas** más efectivas
- **Identificación de oportunidades** de mejora

---

*Proyecto desarrollado por Grupo 1 - Cohort Octubre 2024 - Tech2*
