# kubernetes_helm
deploying nginx chart to k8s cluster


helm install <release-name> <chart-path>


-x-x-x-x-x--x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x--xx

Steps for creating your own chart

(suppose you have ready with your maifest files ready)

1st step is to CREATE a directory structure.
$ helm create <chart-name>   #chartname is nginx-chart

2nd step to edit Chart.yaml

3rd step 
rm -r templates/*

4th step
move deployment.yaml & service.yaml file to templates directory

5th step
vi values.yaml

6th step
verify by LINT, template & dry Run

6th step
$ heml install <release-name> /.nginx-chart

o/p--deployed successfull



