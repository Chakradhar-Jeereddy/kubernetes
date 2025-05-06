- Container orchestration automates the deployment, managment, scalling and networking of containers.
- Handles
  - Pod failures
  - Auto scalling

- Setting Base
  - Kubernetes (k8s) is an open-source container orchestration engine deveoped by google.
  - It was originally designed by google and is now maintained by the cloud native computing fundation (CNCF).

- Basic workflow
  - User communicates to control plane and provides necessary instructions to run containerized applications.
  - Instructions: Run 2 containers of Nginx, Run app in the largest server.
 
- Type of installations
   - Go to k8s website, download individual components and integrate them one by one.(Time consuming and requires great skills).
   - Use tools like Minikube, kubeadm to quickly setup K8s cluster for you.
   - Use managed kubernetes service (Order ready-made cluster from store).

- Managed kubernetes services being provided by AWS, IBM, GCP and others provides managed kubernetes clusters.
   - EKS by AWS
   - DigitalOcean
   - ASK by Azure

- Which cloud provider should we choose?
   - Easy to use
   - Cost effective
   - Free credits to get started.

- Conectivity options in kubernetes
  - API  (curl)
  - CLI (kubectl widely used)
  - GUI

- Kubectl
   - Allows to run commands against kubernetes clusters.
   - descrive nodes

- Authentication
   - Need two important details
      - DNS/IP address of the control plane.
      - Authentication credentials
   - These are defined in kube config file, it is located in home directory
     - kubectl config view
     - cat ~/.kube/config

  - Below kubectl command by default will look for the kubeconfig file in a file named config inside .kube folder in home directory.
     - kubectl get pods
     - kubectl get pods --kubeconfig "custom_config"
    


      - 
  

 
  
  
