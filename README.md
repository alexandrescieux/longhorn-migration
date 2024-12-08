# Longhorn-migration

## Start job

````bash
helm install longhorn-migration --namespace default --set volumes.old.name=old-pvc --set volumes.new.name=new-pvc .
````

## Delete job

````bash
helm delete longhorn-migration --namespace default 
````