Objetivo: entrenar una red neuronal densa (MLP) que, a partir de la telemetria de un servidor (uso de CPU, uso de memoria, temperatura y trafico de red), prediga si el servidor va a fallar (1) o no (0).

Es un problema de clasificacion binaria sobre datos tabulares.

Pasos del notebook:

Imports y configuracion
Generacion / carga de los datos
Analisis exploratorio (EDA)
Preparacion de los datos (escalado + tensores + DataLoader)
Arquitectura de la red (clase nn.Module)
Funcion de perdida y optimizador
Bucle de entrenamiento
Evaluacion (precision, recall, matriz de confusion)
Guardar el modelo
Ejemplo de uso (inferencia)
