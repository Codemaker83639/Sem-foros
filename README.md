# Sem-foros

### Francisco Ogando (2021-0160)
<p>
Investigación: Problema de la concurrencia: semáforos
Siguiendo los videos anteriores realiza un resumen sobre el problema de la concurrencia en sistemas operativos, definiendo que son:
</p>

<p>
1-Concepto básico de semáforo en los sistemas operativos
</p>

<p>
2-Explica en qué consisten los semáforos binarios y enteros
</p>

<p>
3-Explica la relacion entre los semáforos y la sincronización
</p>

*El problema de la concurrencia en sistemas operativos según lo que pude apreciar refiere a la situación en la que múltiples procesos compiten por los mismos recursos del sistema, lo que puede llevar a situaciones de interbloqueo o de inconsistencia en los datos.* 

*Para gestionar esta concurrencia, se utilizan los semáforos, que son estructuras de datos que actúan como mecanismos de sincronización entre procesos. Los semáforos se utilizan para asegurar la exclusión mutua en el acceso a los recursos compartidos, es decir, garantizan que solo un proceso a la vez puede acceder a un recurso específico.* 

*Existen dos tipos principales de semáforos: los semáforos binarios y los semáforos enteros. Los semáforos binarios solo pueden tener dos valores posibles: 0 y 1. Se utilizan para controlar el acceso a un único recurso compartido y suelen utilizarse para implementar la exclusión mutua. Un semáforo binario se inicializa a 1 cuando el recurso está libre y se establece a 0 cuando el recurso está en uso por un proceso.* 

*Por otro lado, los semáforos enteros pueden tomar un rango de valores enteros. Se utilizan para representar múltiples recursos compartidos, como por ejemplo un conjunto de impresoras, y para controlar el número máximo de procesos que pueden acceder a ellos. Los semáforos enteros se utilizan para implementar la sincronización, ya que permiten que los procesos se esperen entre sí, esperando a que se libere un recurso antes de acceder a él.* 

*En resumen, los semáforos son una herramienta fundamental para gestionar la concurrencia en sistemas operativos, permitiendo la sincronización entre procesos y evitando situaciones de interbloqueo. Los semáforos binarios se utilizan para implementar la exclusión mutua, mientras que los semáforos enteros se utilizan para controlar el acceso a múltiples recursos compartidos y para implementar la sincronización.* 
