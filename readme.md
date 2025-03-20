For this cicd pipeline you have to create an eks cluster and in that cluster you have to install ingress-nginx controller 
using the curl command and you can get it from ingress-nginx-page
you have to update the EKS_CLUSTER name and BACKEND_URL in github secrets
in values.yml file also you have to add the HOST that is dns of loadbalancer that was created 
