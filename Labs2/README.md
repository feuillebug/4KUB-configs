# Labs 02 : ConfigMap

In this lab, we will create a config map file to expose a nginx pod with a custom index.html.

To do so, we need to update our last nginx-pod.yml to mount a volume in the default nginx server folder (/usr/share/nginx/html).
Just as before, the conmmand.txt file sums up all the commands used in this lab.

To recap : 

1. Create index.html and fill it
2. Create a config map named nginx-conf
3. Update nginx-pod.yml (from Lab01)
4. Run the pod following as in Lab01
5. Expose the pod
6. Connect from a web browser to the nginx
7. Profit ??? :)
