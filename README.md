# Deploying-app-with-K8-Gcloud

Simple example to deploy Python based app in Pod on Google cloud kubernetes engine using a Load balancer. The app as a whole includes a Voting app input interface, Voting app result interface, an in-memory DB- Redis, a worker application in .NET, a PostgreSQL DB.

Steps followed:

*As Root*
```

1. Create the simple YAML files and push it to Github.

2. Open the Google Kubernetes engine followed by firing up the shell. Create the cluster and connect the shell to the same. Finally, clone the repo.
$ git clone <Github URL>

3. Create the Pods and Services.
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml
$ kubectl create -f voting-app-pod.yml

4. Access the app interface by cicking on link or opening the URL and checkout the app functioning.

```
*As Root*
