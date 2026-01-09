# Optimización del Uso de Bodega de Equipaje

## Contexto del problema
Una empresa ficticia de transporte aéreo que busca maximizar el uso de la bodega de equipaje en cada vuelo.
El área de operaciones requiere contar con información confiable al menos 4 horas antes de la salida del vuelo para apoyar la toma de decisiones operativas.

## Objetivo
Desarrollar un prototipo analítico que permita estimar y optimizar el uso de la bodega de equipaje por vuelo, utilizando datos sintéticos y entregando resultados accionables para el área de operaciones.

## Propuesta
La solución se divide en dos partes:
- **Propuesta conceptual**, donde se define qué datos serían necesarios y cómo se construiría el producto analítico.
- **Prototipo técnico**, donde se implementa un ejemplo simplificado con datos sintéticos en Python.

## Datos utilizados
Se generan datos sintéticos que representan:
- Vuelos programados
- Pasajeros
- Equipaje asociado a cada pasajero
- Restricciones de peso y volumen de la bodega

El uso de datos sintéticos permite ilustrar la lógica del modelo sin comprometer información sensible.

## Metodología
1. Generación de datos sintéticos representativos del proceso real.
2. Definición de restricciones de capacidad de la bodega.
3. Implementación de un modelo simplificado para maximizar el uso de la bodega.
4. Análisis de resultados y priorización de equipaje cuando se supera la capacidad.

## Resultados esperados
El prototipo entrega información como:
- Porcentaje de uso de la bodega por vuelo.
- Equipaje priorizado y equipaje potencialmente excluido.
- Métricas básicas para apoyar decisiones operativas previas al vuelo.

## Tecnologías
- Python
- Pandas, NumPy
- Jupyter Notebook

## Mejoras futuras
- Incorporar predicción de equipaje con datos históricos.
- Integrar variables operativas y comerciales.
- Automatizar la ejecución para garantizar resultados con al menos 4 horas de anticipación.
