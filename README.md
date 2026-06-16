# 🌾 IAgroCorr - Inteligencia Territorial para el NEA

IAgroCorr es una plataforma de análisis predictivo orientada a la toma de decisiones estratégicas en el sector agropecuario del Litoral argentino. Este proyecto combina Inteligencia Artificial Geoespacial (GeoAI), análisis satelital y arquitecturas *Cloud-Native* para generar un **Triple Impacto**:
- **Económico**: Reducción de costos operativos y optimización en la planificación de siembra.
- **Ambiental**: Monitoreo de huella de carbono y promoción de la salud del suelo.
- **Social**: Democratización del acceso a herramientas de alta tecnología para todos los estratos productivos.

## 🚀 Módulos y Funcionalidades
- **1. Análisis de Rinde**: Evaluación del rendimiento histórico, control de costos y planificación de la producción.
- **2. Gemelos Climáticos Globales**: Algoritmos de Machine Learning para buscar zonas homólogas a nivel mundial, descubriendo nuevas oportunidades y mercados para la rotación de cultivos.
- **3. Proyección Ambiental**: Alertas de estrés hídrico y acceso a nuevos mercados de crédito sostenible.

## 🛠 Stack Tecnológico y Fuentes de Datos
El proyecto está construido bajo una arquitectura modular y escalable:
- **Core & Backend**: Python, FastAPI.
- **Persistencia Espacial**: PostgreSQL + PostGIS.
- **Despliegue**: Docker (Contenedorización para alta disponibilidad).
- **Integración de Datos**: Google Earth Engine (GEE), IDERA, Mapas certificados del INTA.

## 📋 Metodologías de Desarrollo e Investigación
El ciclo de vida se rige por la integración de tres marcos de trabajo, documentados a través de GitHub y Jira:
- **DSR (Design Science Research)**: Creación y validación de un artefacto tecnológico para resolver problemáticas reales del terreno.
- **CRISP-DM**: Aplicado al pipeline de Inteligencia de Datos (Comprensión, Preparación, Modelado, Evaluación y Despliegue).
- **Arquitectura Medallion (ETL/ELT)**: Preprocesamiento en capas Bronce (datos crudos de GEE/IDECorr), Plata (limpios e integrados) y Oro (listos para el modelo de ML).
- **Scrum Ágil**: Adaptado a dupla de desarrollo con Sprints quincenales.

---
*Desarrollado en el marco del Proyecto Final de Carrera - Licenciatura en Sistemas (UNNE).*
*Autores: Julio César Pintos & Giovanni Piazza.*
