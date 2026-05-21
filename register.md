**Reporte de Registro de Investigación**

* **Title**: Fusión de Datos Multimodal en la Nueva Era de Percepción Remota: Integración de Sensores Hiperespectrales y SAR mediante Redes Neuronales Profundas para el Monitoreo Crítico

* **Description**:  
La investigación propone una arquitectura de fusión multimodal basada en redes neuronales profundas para integrar datos hiperespectrales (HSI) y radar de apertura sintética (SAR). Mediante extracción de características multi-escala y mecanismos de atención cruzada asimétrica, el modelo aprovecha la riqueza espectral del HSI y la robustez estructural del SAR. Se evalúa en conjuntos de datos públicos como Augsburg, demostrando mejoras significativas en precisión de clasificación (OA 93.7%) y robustez bajo condiciones adversas (nubes, ruido y variabilidad temporal), superando enfoques del estado del arte.

* **General Objective**:  
Desarrollar y validar una arquitectura de fusión multimodal HSI-SAR basada en redes neuronales profundas para mejorar la precisión y robustez en tareas de percepción remota orientadas al monitoreo crítico.

* **Specific Objectives**:  
- Diseñar un módulo de extracción de características multi-escala especializado para cada modalidad sensorial.  
- Implementar un mecanismo de fusión asimétrica con atención cruzada que aproveche las fortalezas complementarias de HSI y SAR.  
- Evaluar cuantitativa y cualitativamente el rendimiento del modelo en datasets públicos representativos.  
- Analizar la robustez del sistema bajo condiciones adversas y realizar estudios de ablación de componentes.  
- Identificar limitaciones actuales y proponer líneas de investigación futuras hacia modelos eficientes y operacionales.

* **Justification**:  
La complementariedad entre sensores hiperespectrales y SAR es esencial para aplicaciones críticas donde la fiabilidad es prioritaria, tales como gestión de desastres naturales, monitoreo agrícola de precisión y vigilancia ambiental. Los métodos tradicionales y muchas aproximaciones profundas actuales presentan limitaciones importantes en alineación, robustez y eficiencia. Esta investigación aborda estas brechas mediante un enfoque asimétrico avanzado, contribuyendo al avance de la percepción remota multimodal y ofreciendo soluciones más confiables para toma de decisiones en escenarios de alta incertidumbre.

* **Methodology**:  
Se adopta un enfoque experimental basado en aprendizaje profundo. Se implementó una arquitectura con ramas paralelas multi-escala, módulo de fusión asimétrica con atención cruzada y pérdida compuesta. El entrenamiento se realizó con optimizador AdamW, augmentaciones específicas para datos remotos y validación cruzada. La evaluación incluye métricas estándar (OA, AA, Kappa, F1), análisis visual de mapas de clasificación y estudios de ablación. Se utilizaron datasets públicos co-registrados HSI-SAR.

* **Scope**:  
Desarrollo y validación experimental de una arquitectura de fusión HSI-SAR en datasets públicos (Augsburg y urbano). No incluye despliegue operativo en satélites ni validación en múltiples regiones geográficas. (87 caracteres)

* **Activities**:  
1. Revisión del estado del arte y definición de arquitectura.  
2. Preprocesamiento, co-registración y preparación de datasets.  
3. Implementación y entrenamiento del modelo propuesto.  
4. Experimentación, evaluación cuantitativa y análisis visual.  
5. Análisis de ablación, discusión de resultados y redacción del artículo.

* **Resources**:  
- Datasets públicos: Augsburg HSI-SAR y conjunto urbano complementario.  
- Software: Python, PyTorch, bibliotecas de teledetección (GDAL, rasterio, scikit-learn).  
- Hardware: GPUs para entrenamiento (entorno con al menos 2 GPUs).  
- Herramientas de visualización y análisis: Matplotlib, QGIS.

* **Limitations**:  
Dependencia de una co-registración precisa entre modalidades, mayor costo computacional respecto a modelos simples, necesidad de volúmenes importantes de datos etiquetados y limitaciones de generalización a regiones geográficas no representadas en los datasets de entrenamiento.