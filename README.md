# MongoDB & Mongo-Express Kubernetes Deployment

 Deploy MongoDB and Mongo-Express using minikube.

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-FF0000?style=for-the-badge&logo=yaml&logoColor=white)

<img width="309" height="352" alt="image" src="https://github.com/user-attachments/assets/1ca6caac-b600-4b05-84ff-97079efef8db" />

### 1. mongodb-secret.yaml contains username and password in base64 encoding 

  username = root
  
  password = 4321

### 2. after start mongo-express
 ``` bash
kubectl logs pod_name
```
<img width="893" height="211" alt="image" src="https://github.com/user-attachments/assets/daea1817-473b-4701-a413-7e7c4d090dfe" />

### 3. get external ip
 ``` bash
minikube service mongo-express-service
```
<img width="1605" height="176" alt="image" src="https://github.com/user-attachments/assets/2f0bce0c-0cd0-4ce4-a2bf-c51369d21b56" />

### 4. web interface
<img width="2666" height="1394" alt="image" src="https://github.com/user-attachments/assets/7bf899a1-a52b-43b6-bb03-01b009fb1102" />
