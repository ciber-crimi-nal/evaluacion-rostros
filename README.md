# 📄 Evaluación de rostros faciales para expedición de documentos
## 🎯 Descripción
Este proyecto propone un sistema automático para evaluar la calidad de imágenes faciales usadas en la generación de documentos de identidad oficiales (DNI, pasaportes, etc.). Basado en estándares internacionales y nacionales, establece un proceso de evaluación de tres etapas y seis dimensiones para asegurar la validez biométrica de las fotografías.

## 🚀 Objetivos
- Definir criterios cuantitativos y cualitativos para evaluación facial en expedición de documentos.
- Implementar un sistema automático que asegure el cumplimiento de normativas biométricas vigentes.
- Mejorar la consistencia y fiabilidad del proceso de emisión de documentos.

## 📘 Metodología
El sistema parte de una metodología de evaluación automática de imágenes faciales centrada en verificar el cumplimiento de los requisitos establecidos para la expedición de documentos de identidad oficiales. Esta evaluación se basa en una combinación de:

- Criterios técnicos y biométricos definidos por la normativa española vigente.
- Estándares internacionales de calidad de imagen facial, como la norma ISO/IEC 19794-5.

La metodología busca asegurar que las fotografías cumplen condiciones mínimas para su uso en sistemas de verificación facial automatizada, contribuyendo así a la prevención de fraudes en la expedición de documentos.

## 🔍 Funcionamiento del sistema
El sistema automatizado analiza cada imagen facial a través de una arquitectura modular que ejecuta tres fases consecutivas:

1. Preprocesamiento y normalización
La imagen es redimensionada, convertida a escala de grises (si se requiere) y normalizada para garantizar condiciones uniformes de análisis.

2. Análisis computacional
Se aplican técnicas de visión por computador para extraer atributos clave (posición, nitidez, iluminación, etc.) y comparar sus valores frente a umbrales definidos.

3. Evaluación por dimensiones
El resultado se organiza en seis dimensiones de calidad, cada una con criterios específicos de aceptación o rechazo:

    - Frontalidad: Determina si la cabeza está orientada correctamente, evitando inclinaciones o giros laterales.
    
    - Simetría: Evalúa la alineación del rostro en el eje vertical y horizontal.
    
    - Expresión: Verifica que la expresión facial sea neutra, sin sonrisas ni gestos que distorsionen los rasgos.
    
    - Iluminación: Detecta la presencia de sombras, sobreexposición o subexposición que puedan afectar la identificación.
    
    - Nitidez: Analiza la definición de los contornos faciales, asegurando que la imagen no esté desenfocada.
    
    - Cobertura facial: Comprueba que los elementos faciales (ojos, nariz, boca) sean visibles y no estén cubiertos por objetos o cabello.

Cada dimensión se califica de forma independiente, generando un informe final que indica si la imagen es apta o no apta para su uso en la expedición de documentos, junto a una justificación técnica por dimensión.

## 🧪 Resultados
- Se evaluaron múltiples conjuntos de imágenes, verificando que el sistema detecta con alta fiabilidad imágenes no conformes.
- Validación inicial con expertos comparando calificación manual vs. automática, mostrando fuerte correlación.
- Identificación de casos límite (e.g. sombras, desalineación) y propuestas de mejora.


## 🛠 Futuras mejoras
- Incorporación de algoritmos de aprendizaje automático para refinamiento de clasificación.
- Expansión del dataset y validación en condiciones reales de emisión.
- Integración con módulos de generación de documentos (OCR, firma, validación de datos).

## 🏛 Equipo y Financiación
Fernando Broncano Morgado [fbroncano@unex.es](mailto:fbroncano@unex.es), Victoria Amores Chaparro [vicamoresc@unex.es](mailto:vicamoresc@unex.es), Óscar Mogollón Gutiérrez [oscarmg@unex.es](mailto:oscarmg@unex.es), Alberto López Trigo [albertolt@unex.es](mailto:albertolt@unex.es), José Carlos Sancho Núñez [jcsanchon@unex.es](mailto:jcsanchon@unex.es).

Esta iniciativa se realiza en el se realiza en el marco de los fondos del Plan de Recuperación, Transformación y Resiliencia, financiados por la Unión Europea (Next Generation) - Instituto Nacional de Ciberseguridad (INCIBE) en el proyecto C108/23 “Detección de Falsificación de Documentos de Identidad mediante Técnicas de Visión por Computador e Inteligencia Artificial”.
![BandaLogos_INCIBE_es-100](https://github.com/user-attachments/assets/a2290f37-69d9-4caf-bee1-2b29c47bac97)
