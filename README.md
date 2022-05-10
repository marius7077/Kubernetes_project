# Kubernetes_project

https://github.com/Simras98/webservice1
https://github.com/marius7077/webservice2

### Create the first microservice
### Create Dockerfile
### mvn clean package
Dans intellij
```console
### docker build -t employee_service .
### docker run -p 9991:9991 -t employee_service --name employee_service
```
### Pour tester le container : http://127.0.0.1:9991/employee/findall
Optional pour démarrer container si besoin) {
```console
### docker ps -a
### docker start {id_container}
```
}
Dans pycharm
```console
### docker build -t pdf_service .
### docker run -p 5000:5000 -t pdf_service 
```
### Pour tester le container :  http://127.0.0.1:5000/1
