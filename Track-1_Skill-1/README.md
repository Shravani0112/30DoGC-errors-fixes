Error-1:
I got the below error while performing the lab and when I clicked the <mark>check progress</mark> an alert box popped up with this error.
```Powershell 
      Please verify the web servers are serving on frontend of HTTP(s) Load Balancer 
```
- **Solution :**
   
Use "nucleus-jumphost-webserver1" as the cluster name while creating the cluster and also wait for 5-10min after completion of all the tasks. 
       `gcloud container clusters create nucleus-jumphost-webserver1`
