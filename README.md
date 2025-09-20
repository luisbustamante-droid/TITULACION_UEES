# 📌 Clasificación explicable de arritmias cardíacas a partir de electrocardiogramas transformados en espectrogramas mediante redes neuronales convolucionales

## 📖 Descripción
Este repositorio contiene la documentación, código y entregables asociados al proyecto **[Nombre del Proyecto]**, cuyo objetivo es [breve objetivo en una línea].  
El desarrollo sigue una metodología ágil con enfoque investigativo, técnico y práctico, alineado con estándares académicos e industriales.

---

## 📂 Componentes del Proyecto

### 1. 📚 Mapa del Estado del Arte
- Revisión sistemática de **+20 papers (últimos 5 años)**  
- Comparación de **5 enfoques principales**  
- Identificación de **gaps** en soluciones actuales  
- Posicionamiento claro de la propuesta  

**Entregables:**
- Tabla comparativa de metodologías  
- Timeline de avances (últimos 5 años)  
- Matriz de fortalezas/debilidades  
- Gap definido y justificado  

---

### 2. 📊 Análisis de Datasets Disponibles
- Revisión de **3+ datasets potenciales**  
- Evaluación técnica: calidad, tamaño, accesibilidad  
- Análisis de sesgos y limitaciones  
- Plan de preprocesamiento y plan alternativo  

**Entregables:**
- Tabla comparativa de datasets  
- Recomendación del dataset principal  
- Estrategia de fallback (Plan B)  

---

### 3. 📏 Definición de Métricas de Éxito
- **Métricas técnicas**: Accuracy, F1-score, Precision, Recall, AUC, RMSE  
- **Métricas de impacto**: KPIs de negocio, adopción y satisfacción de usuarios  
- **Umbrales de éxito**: mínimos aceptables vs. objetivos de excelencia  

**Entregables:**
- Lista de métricas técnicas y de impacto  
- Benchmarks frente a soluciones existentes  
- Valores objetivo documentados  

---

### 4. 👥 Análisis de Stakeholders
- Identificación de actores: primarios, secundarios y clave  
- Matriz de influencia/interés  
- Análisis de expectativas y resistencias  
- Plan de comunicación diferenciado  

**Entregables:**
- Tabla con roles, necesidades y barreras  
- Estrategia de involucramiento por stakeholder  

---

### 5. 🎯 Documento de Alcance
- Objetivos SMART (general + específicos)  
- Entregables claros con criterios de aceptación  
- Limitaciones y supuestos explícitos  

**Entregables:**
- Objetivo general y específicos  
- Alcance incluido y excluido  
- Criterios de aceptación  

---

### 6. ⏱️ Cronograma Ágil (Scrum)
Duración: **6 semanas (4 sprints)**  

- **Sprint 1**: Investigación y diseño  
- **Sprint 2**: Desarrollo core  
- **Sprint 3**: Optimización y validación  
- **Sprint 4**: Finalización y documentación  

---

### 7. 🛠️ Plan de Recursos
- **Humanos**: desarrollador, analista, PM, consultores externos  
- **Técnicos**: servidores, GPUs, software, datasets 

---

### 8. 🏆 Hitos y Entregables
- 8 hitos principales distribuidos en 6 semanas  
- Entregables medibles y revisados  
- Procedimientos de aprobación y control de riesgos  

---

## 📑 Formato de Entrega
- **Documento técnico:** PDF, 25–30 páginas, formato IEEE  
- **Repositorio GitHub:** Código inicial + documentación  
- **Materiales complementarios:** samples de datasets, diagramas, wireframes  

---

## 🚀 Tecnologías y Herramientas
- **Lenguajes:** [Python]  
- **Frameworks IA/ML:** [PyTorch, TensorFlow, Scikit-learn]  
- **Gestión Ágil:** Scrum
- **Infraestructura:** [Sevidor en arquitectura Linux]  

---

## 👨‍💻 Equipo
- **Project Manager:** [Luis Bustamante]  
- **Desarrollador:** [Damaris Alarcón - Luis Bustamante]  
- **Analista de Datos:** [Damaris Alarcón - Luis Bustamante]    

---

## 📅 Cronograma General
| Sprint | Semanas | Objetivos principales         |
|--------|----------|------------------------------|
| 1      | 1        | Investigación y diseño       |
| 2      | 2        | Desarrollo core              |
| 3      | 3,4      | Optimización y validación    |
| 4      | 5,6      | Testing y documentación      |

---

## 📂 Datasets
Este proyecto hace uso de datasets públicos de **PhysioNet**:  

- [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/)  
- [ECG Arrhythmia Dataset](https://physionet.org/content/ecg-arrhythmia/1.0.0/)  
- [PhysioNet Challenge 2021](https://physionet.org/content/challenge-2021/1.0.3/)  

---

## 📂 Datasets Samples

Además de los datasets completos de PhysioNet, este repositorio hace referencia a versiones adaptadas/publicadas en otras plataformas para facilitar el acceso y el uso en pruebas rápidas.  

### 🔹 Kaggle – MIT-BIH Arrhythmia Database (Modern 2023)
📎 [MIT-BIH Arrhythmia Database (Modern 2023)](https://www.kaggle.com/datasets/protobioengineering/mit-bih-arrhythmia-database-modern-2023?resource=download)  

- **Origen:** MIT-BIH Arrhythmia Database (PhysioNet).  
- **Formato:** Archivos `.csv` listos para uso directo.  
- **Contenido:** Registros completos y anotaciones clínicas preprocesadas.  
- **Ventaja:** Evita trabajar con los formatos originales `.dat` y `.hea`, ofreciendo una versión moderna y accesible para proyectos en Python, R o notebooks de Kaggle.  
- **Uso recomendado:** Entrenamiento rápido de modelos y exploración inicial de datos.  

---

### 🔹 Mendeley Data – ECG signals (1000 fragments)
📎 [ECG signals (1000 fragments)](https://data.mendeley.com/datasets/7dybx7wyfn/3)  

- **Origen:** MIT-BIH Arrhythmia Database (PhysioNet).  
- **Formato:** Archivos `.csv` con fragmentos de 10 segundos.  
- **Contenido:** 1000 fragmentos de señales ECG con etiquetas de clases (ritmos normales y arritmias).  
- **Ventaja:** Tamaño reducido y fragmentación lista para pruebas rápidas sin necesidad de extraer manualmente.  
- **Uso recomendado:** Prototipado, validación de pipelines y generación de ejemplos representativos en repositorios o notebooks.  

---

📌 **Nota:** Ambos samples provienen del dataset original **MIT-BIH Arrhythmia Database**, pero están publicados en formatos adaptados para facilitar su uso en investigación y enseñanza.  

---

## 📜 Licencia
Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más información.  
