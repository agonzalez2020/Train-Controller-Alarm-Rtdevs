# Train-Controller-Alarm-Rtdevs
Train-Controller-Alarm-Rtdevs es un projecto Uppaal que permite verificar propiedades temporales cuantitativas (QTP) sobre un modelo de un sistema de cruce ferroviario. El sistema es modelado previamente con el formalismo Real-Time DEVS (Discrete Event System Specification), luego se realizó una traducción de modelos RT-DEVS a Autómatas Temporizados (TA) que admite Uppaal. 
Las QTP son propiedades recurrentes en los sistemas de tiempo real (patrones) y son modeladas en Uppaal con autómatas temporizados (TA) que, junto a fórmulas TCTL, se puede verificar el cumplimiento de las mismas.

Por otro lado, el proyecto Uppaal contiene mutantes de las QTP. Estas permiten descubrir errores de temporización en el sistema ferroviario cuando el modelo del sistema no satisface los patrones. Si el modelo de sistema no verifica el patrón pero si verifica un mutante se habrá descubierto la fuente del error en el modelo del sistema.

# Requisitos
Uppaal 5.0 (https://uppaal.org/)

# Files
Uppaal-Train-Controller-Alarm.xml: projecto Uppaal
RT-DEVS-Train-Controller-Alarm.eps: especificación del sistema ferroviario con el formalismo RT-DEVS.

# Caso de Estudio: Sistema Ferroviario (cruce de trenes)
No se puede subir el articulo, tal como está?? y se podría decir que se encuentra en proceso de evaluación.

# Contenido del Proyecto Uppaal
## Templates:
Train: TA que modela el comportamiento de los trenes en la zona de cruce.
Controller: 
