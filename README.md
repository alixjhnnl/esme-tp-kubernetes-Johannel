# esme-tp-kubernetes-Johannel

## Description
Application Node.js simple affichant :
- `Hello ESME DevOps 2025!` sur le port 3000  
- Un endpoint `/health` pour vérifier l’état du service  

## Image Docker
L’image est disponible publiquement sur Docker Hub :  
👉 [https://hub.docker.com/r/alixjhnnl/esme-app](https://hub.docker.com/r/alixjhnnl/esme-app)

Tag utilisé pour cette version : **v1.0.0**

## Lancement local
```bash
docker run -p 3000:3000 alixjhnnl/esme-app:v1.0.0
