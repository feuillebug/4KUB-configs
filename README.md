# 4KUB-configs

This repository sums-up different steps in learning to use Kubernetes. It supposes that you already have a Kubernetes environement running and an access to kubectl in your linux environement.

## Labs 01 : Pod introduction

The first lab features a nginx pod creation via yml file and it's exposition on the port 80 of the VM.

## Labs 02 : ConfigMap 

In this lab, we will create a config map file to expose a pod

## Labs 03 : Using deployment
In this lab, we are leaving the classic pod command to directly create deployment. Deployment allows in depth management of pods with update settings.

We will create a deployment file with nginx:latest, deploy it and then change the nginx version to 1.13.2.

After the redeploy the update will be propagated on the replicas.

Finally, a rollout undo will get us back to the last version of deployment.

In Bonus, we will create a namespace and deploy using it
