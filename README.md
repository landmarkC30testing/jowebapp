
**PREREQUISITE**
A server with Jenkins and Docker running on it (Jenkins user should be allowed to run Docker).
Github account.
Docker hub account.
Install the Docker Pipelines plugin on Jenkins
Install/Download kubernetets plugin (Only Required if passing K8s .kube/config)

K8S
Create Deployment and other related files for image 

Jenkins 
Docker Hub account details. Go to Credentials → Global → Add credentials  
Note that if you set the ID, you will need this specific ID to refer this credential from your scripts. Here we are just using dockerhub_id.
Create Pipelines for CI jobs 

ArgoCD
Using ArgosCD for deployment job 
Install ArgoCD cli
Install ArgoCD ON k8s cluster 
Create NodePort to access ArgoCD ** Ingress is preferential but not currently working on this build **
