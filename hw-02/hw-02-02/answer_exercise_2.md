# Replicaset NGINX 📦🌐


## Creacion replicaSet:
* Especificamos de forma declarativa (fichero YML) las 3 replicas:

![POD](./imatges/replicaSet.PNG)  


## Lo ejecutamos con el siguiente comando:

`` kubectl apply -f nginx-ReplicaSet.yml ``

![POD](./imatges/apply.PNG)  


## Escalar 10 replicas:

`` kubectl scale --replicas=10 rs nginx-server ``

![POD](./imatges/scale.PNG)  