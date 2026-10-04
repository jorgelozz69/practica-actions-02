# practica-actions-02
 
Captura del pipeline con test y lint ejecutándose en paralelo, ambos en verde.

![Test,lint verdes](img/Captura1.png)
 
Captura del pipeline en rojo tras romper el test a propósito, con el log del error abierto.
 
![Test rojo](img/Captura3.png)

Captura del pipeline de nuevo en verde tras la corrección.

![Test y lint verdes tras correcion](img/Captura4.png)


Ejercicio de actions 3


Captura de las tres ejecuciones paralelas del job test por matrix.
 
![Ejecuciones paralelas](img/Captura7.png)

Captura mostrando que solo-en-main no se ejecuta en la Pull Request pero sí tras el merge.
 
![Ejecucion solo en main](img/Captura5.png)

Captura del log con los steps failure() y always() ejecutados tras un fallo forzado.


![Ejecucion fail y always](img/Captura6.png)
