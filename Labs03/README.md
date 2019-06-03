# Labs 03 : Using deployment

In this lab, we are leaving the classic pod command to directly create deployment. Deployment allows in depth management of pods with update settings.

We will create a deployment file with nginx:latest, deploy it and then change the nginx version to 1.13.2.

After the redeploy the update will be propagated on the replicas.

Finally, a rollout undo will get us back to the last version of deployment.
