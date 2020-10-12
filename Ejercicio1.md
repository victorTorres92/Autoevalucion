#Ejercicio 1
##*Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?*

La aplicación que he elegido para la resolución de este ejercicio es el IDE Eclipse. 

Es una aplicación de escritorio basada en la arquitectura de microkernel. En este ejemplo vemos de forma clara la existencia de un nucleo o Kernel al que podemos agregar diferentes funcionalidades mediante plug-in bien sea para incorporar nuevos lenguajes, poder conectar con diferentes sistemas de base de datos, etc...

Si necesitamos que este conocido IDE evolucione a un patrón tipo microservicios, necesitamos independizar cada funcionalidad de forma que, por ejemplo, veríamos cada lenguaje de programación como un servicios distinto, escalable e independiente sin depender del kernel evitando así problemas de cuello de botella. 
