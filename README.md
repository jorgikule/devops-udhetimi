# Udhetimi im ne DevOps

## Dita 1 - Linux
-Komandat baze: pwd, ls, cd, mkdir, touch, rm, cp, mv
-Permisionet: chmod
-Kerkimi: grep
- Instalimi i programeve: sudo apt

## Dita 2 - Git dhe GitHub
- git init, add, commit, log
- branch, checkout, merge
- GitHub - repo online

## Dita 3 - Docker
- Instalimi i Docker
- Images dhe Containers
- docker run, stop, start, rm
- Dockerfile - image i personalizuar
- Web server me nginx

## Dita 4 - Kubernetes
- Kubernetes menaxhon containers ne shkalle te madhe
- Minikube - cluster lokal per te mesuar
- Pod - njesia me e vogel ne Kubernetes
- Deployment - menaxhon Pod-et
- Service - ekspozon aplikacionin jashte

### Komandat kryesore:
kubectl get nodes
kubectl get pods
kubectl create deployment hello-k8s --image=nginx
kubectl expose deployment hello-k8s --type=NodePort --
port=80
minikube service hello-k8s --url

### Rezultati:
Aplikacioni nginx po punon ne Kubernetes!

## Dita 5 - Jenkins CI/CD
- Jenkins automatizon rrugetimin e kodit
- Pipeline - zinxhiri i hapave automatike
- Stage - cdo hap i pipeline-it
- Grovvy - gjuha e Jenkins

### Rezultati:
Pipeline me 3 stage ekzekutoi me sukses!
Finished: SUCCESS

