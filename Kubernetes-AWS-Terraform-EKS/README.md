# Setting up IAM policies for the ALB Ingress Controller in EKS with Terraform

You can provision an EKS cluster with the right policies for the ALB Ingress Controller with:

```bash
terraform init
terraform plan
terraform apply
```

It might take a while for the cluster to be creates (up to 15-20 minutes).

As soon as cluster is ready, you should find a `kubeconfig_my-cluster` kubeconfig file in the current directory.


```