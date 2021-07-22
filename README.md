# prediccion-atraso-vuelos

Éste es el notebook a una postulación que hice, me gustó mucho la solución y como siento que refleja bastante bien mi lógica de desarrollo a la hora de hacer modelos, por lo que decidí publicarlo aquí.

La base de datos tratada es una base de datos pública del aeropuerto de Santiago, la cual contiene aterrizajes y despegues del aeropuerto de Santiago. El objetivo es predecir la probabilidad de atraso de los vuelos.

La estructura de este notebook es la siguiente:

1) Diccionario del dataset
2) Carga del dataset
3) Verificación/validación inicial de calidad de datos
4) El primer paso: definición del target y el contexto del negocio
5) Análisis univariado
6) Generación de variables adicionales
7) Análisis bivariado
8) Metodología de modelamiento
9) Definición de métrica de evaluación y tratamiento de variables cíclicas
10) Entrenamiento y evaluación de modelos
11) Síntesis, pasos a seguir e ideas finales
