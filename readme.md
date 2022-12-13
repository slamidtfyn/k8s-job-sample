```sh
docker build -t job-sample .

docker tag job-sample:latest slamidtfyn/job-sample:latest

kubectl create -f job.yml

kubectl get pods

kubectl logs -l job-name=job-samle

kubectl delete job job-sample
```


