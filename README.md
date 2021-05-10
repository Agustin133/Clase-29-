# Clase N° 29 - Modulo Cluster 

Este repositorio contiene el desafio N° 29 (Modulo cluster).
Basado en el desafío N° 28, le agregue a la ruta de comandos un parametro que puede ser opcional el cual va a ejecutar el servidor, si se ingresa CLUSTER se iniciara en modo Cluster, en caso contrario al ingresarse la palabra FORK o de no pasarlo se iniciara en modo Fork (*npm run dev + PARAMETRO OPCIONAL).

- Con *npm run prod, se ejecutara el servidor utilizando Forever.
- Con *npm run pmFork, se ejecutara el servidor con PM2 usando la funcionalidad fork.
- Con *npm run pmCluster, se ejecutara el servidor con PM2 usando la funcionalidad Cluster.

Tanto Forever como MP2 tienen habilitado el modo escucha.
