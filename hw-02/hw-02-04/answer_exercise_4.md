# Deployment - Recreate NGINX 📦🌐



### Despliege de un servicio mediante la técnica "Recreate":


![recreate](./imatges/recreate.PNG)  

`` kubectl create -f deployment.yml``



### Rollout deployment

`` kubectl rollout undo deployment.v1.apps/nginx-deployment``

![service2](./imatges/rollout.PNG)  


### Rollback a una version previa

Para volver a una version previamente creada le especificamos el numero de la version (Example revision 2):

`` kubectl rollout undo deployment/app --to-revision=2``



