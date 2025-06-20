🚀 Trend DevOps Project
🛠 Stack Used:
React App 

--------------------------------------------Output screenshots are in the Terraform folder------------------------------------------------------

Docker & Docker Hub

AWS EKS (Kubernetes)

Jenkins (CI/CD)

Helm + Prometheus + Grafana (Monitoring)

Bash Scripting

GitHub CLI

📦 Project Setup

1️⃣ Clone the App
git clone https://github.com/Vennilavan12/Trend.git

2️⃣ Setup EC2 with Docker & Jenkins

3️⃣ Dockerize the React App

4️⃣ Setup EKS using eksctl

5️⃣ Deploy App to Kubernetes

🔁 CI/CD Pipeline

📊 Monitoring Stack

1️⃣ Create Monitoring Namespace:

2️⃣ Install Prometheus + Grafana:

3️⃣ Access Grafana:





---------------------------------------------URLs ------------------------------------------------


Docker Hub Repos:
https://hub.docker.com/repository/docker/heisenbergzz/dev

EKS Cluster: trend-cluster in us-east-1

Jenkins on EC2:
http://3.239.172.34:8080
(Public IP of EC2 instance where Jenkins is hosted)

Docker Image App on EC2:
http://3.239.172.34:3000
(React app served directly via Docker from EC2 instance)

App Running on EKS via LoadBalancer:
http://a86ca331c710a4ffc9e0ab9781b12876-1228905747.us-east-1.elb.amazonaws.com:3000
(This is exposed from the Kubernetes LoadBalancer service)

-------------------------------------------------------------------------------------------------
