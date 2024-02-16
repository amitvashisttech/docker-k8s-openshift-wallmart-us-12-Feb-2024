```
526  mkdir 08-Helm-Custom-Charts
  527  ls
  528  cd 08-Helm-Custom-Charts/
  529  ls
  530  helm create mywebapp
  531  tree mywebapp/
  532  cat mywebapp/templates/service.yaml
  533  cat mywebapp/templates/deployment.yaml
  534  ls
  535  cd mywebapp/
  536  ls
  537  vim values.yaml
  538  ls
  539  cd ..
  540  ls
  541  helm install my-web mywebapp --dry-run
  542  helm install my-web mywebapp
  543  helm list
  544  vim mywebapp/Chart.yaml
  545  kubectl get pods
  546  kubectl get deploy
  547  kubectl get svc
  548  kubectl edit svc my-web-mywebapp
  549  kubectl get svc
  550  ls
  551  vim mywebapp/Chart.yaml
  552  vim mywebapp/values.yaml
  553  helm list
  554  helm history my-web
  555  helm upgrade my-web mywebapp
  556  helm history my-web
  557  kubectl get pods
  558  kubectl get svc
  559  ls
  560  vim mywebapp/Chart.yaml
  561  vim mywebapp/values.yaml
  562  helm history my-web
  563  helm upgrade my-web mywebapp
  564  helm history my-web
  565  kubectl get pods
  566  helm history my-web
  567  helm rollback my-web
  568  helm history my-web
  569  helm rollback my-web --help
  570  helm history my-web
  571  helm rollback my-web 1
  572  helm history my-web
  573  kubectl get pods
  574  kubectl get svc
```
