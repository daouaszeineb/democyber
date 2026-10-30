# democyber - TP DevSecOps

## Demarrage
1. Tester en local :
   docker build -t democyber:latest .
   docker run -d -p 8080:8080 democyber:latest
   curl http://localhost:8080/actuator/health   -> {"status":"UP"}
2. Creer le depot GitHub + secrets DOCKERHUB_USERNAME et DOCKERHUB_TOKEN
3. git init / add / commit / push (voir guide)
4. Suivre le TP : ajouter les etapes de tp-reference/ci-final.yml une par une.
