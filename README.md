# Kubernetes_Scenarios

   1  yum update -y
    2  yum install docker -y
    3  systemctl start docker
    4  systemctl enable docker
    5  yum install conntrack -y
    6  curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
    7  sudo install minikube-linux-amd64 /usr/local/bin/minikube
    8  /usr/local/bin/minikube start --force --driver=docker
    9  vim docker-compose.yml
   10  cd /opt/
   11  mkdir Docker 
   12  cd Docker/
   13  vim docker-compose.yml
   14  cd ..
   15  mkdir kubernetes
   16  cd kubernetes/
   17  vim namespace.yaml
   18  vim configmap.yaml
   19  vim namespace.yaml
   20  cd ..
   21  cd Docker/
   22  vim docker-compose.yml 
   23  cd ..
   24  cd kubernetes/
   25  vim secret.yaml
   26  cd /opt/
   27  clear
   28  cd kubernetes/
   29  ls -lrta
   30  vim secret.yaml 
   31  vim persistent-volume.yaml
   32  vim persistent-volume-claim.yaml
   33  vim web-deployment.yaml
   34  vim web-deployment.yaml
   35  clear
   36  cd ku
   37  cd /opt/kubernetes/
   38  ls -lrta
   39  vim web-deployment.yaml
   40  vim db-deployment.yaml
   41  vim web-service.yaml
   42  vim db-service.yaml
   43  ls -lrta
   44  clear
   45  curl -o kubectl https://amazon-eks.s3.us-west-2.amazonaws.com/1.20.4/2021 -04-12/bin/linux/amd64/kubectl
   46  curl -o kubectl https://amazon-eks.s3.us-west-2.amazonaws.com/1.20.4/2021-04-12/bin/linux/amd64/kubectl
   47  chmod +x ./kubectl
   48  mkdir -p $HOME/bin
   49  cp ./kubectl $HOME/bin/kubectl
   50  export PATH=$HOME/bin:$PATH
   51  echo 'export PATH=$HOME/bin:$PATH' >> ~/.bashrc
   52  source $HOME/.bashrc
   53  kubectl version --short –client
   54  kubectl get pods
   55  kubectl apply -f namespace.yaml
   56  kubectl get ns
   57  vim configmap.yaml 
   58  kubectl apply -f configmap.yaml
   59  vim secret.yaml 
   60  kubectl apply -f configmap.yaml
   61  vim configmap.yaml 
   62  kubectl apply -f secret.yaml
   63  vim persistent-volume.yaml 
   64  kubectl apply -f persistent-volume.yaml
   65  vim persistent-volume.yaml 
   66  vim persistent-volume.yaml 
   67  kubectl get api-resources
   68  kubectl get api-resource
   69  kubectl api-resource
   70  kubectl api-resources
   71  vim persistent-volume.yaml 
   72  kubectl apply -f persistent-volume.yaml
   73  vim persistent-volume.yaml 
   74  kubectl apply -f persistent-volume.yaml
   75  clear
   76  cd /opt/kubernetes/
   77  vim persistent-volume-claim.yaml 
   78  kubectl apply -f persistent-volume-claim.yaml
   79  kubectl apply -f web-deployment.yaml
   80  vim web-deployment.yaml 
   81  clear
   82  cd /opt/kubernetes/
   83  kubectl apply -f web-deployment.yaml
   84  vim web-deployment.yaml 
   85  vim web-deployment.yaml 
   86  cat web-deployment.yaml 
   87  kubectl api-resources
   88  vim web-deployment.yaml 
   89  cat web-deployment.yaml 
   90  vim web-deployment.yaml 
   91  kubectl apply -f web-deployment.yaml
   92  vim  db-deployment.yaml 
   93  web-deployment.yaml
   94  kubectl apply -f db-deployment.yaml
   95  kubectl apply -f web-service.yaml
   96  kubectl apply -f db-service.yaml
   97  kubectl get cm
   98  kubectl get pods
   99  kubectl get pods -n my-app
  100  kubectl get pods -n my-app
  101  kubectl get pods -n my-app
  102  kubectl get pods -n my-app
  103  kubectl get pods -n my-app
  104  kubectl get pods -n my-app
  105  kubectl get pods -n my-app
  106  kubectl logs web-deployment-dc469f978-wcqqf -n my-app
  107  kubectl get deployments -n my-app
  108  kubectl edit deployment web-deployment -n my-app
  109  kubectl get pods -n my-app
  110  docker pull my-web-app:latest
  111  cd /opt/
  112  ls -lrta
  113  git clone https://github.com/praveen1994dec/Kubernetes_Scenarios.git
  114  yum install git -y
  115  git clone https://github.com/praveen1994dec/Kubernetes_Scenarios.git
  116  ls -lrta
  117  cd Docker/
  118  cd ..
  119  ls -lrta
  120  mv Docker/ Kubernetes_Scenarios/
  121  mv kubernetes/ Kubernetes_Scenarios/
  122  cd Kubernetes_Scenarios/
  123  ls -lrta
  124  git add .
  125  git commit -m "added files for k8 and docker"
  126  git push
  127  git push
  128  history
