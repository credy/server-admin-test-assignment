# Credy Serveradmin task
  * Create ansible inventory, that will deploy Openshift/Kubernetes cluster in 3 servers called `argentina`, `kasahstan` and `main`
  * Create ansible inventory, that will deploy Openshift/Kubernetes storage servers called `argentina_storage` and `kasahstan_storage`
  * Create 3 Openshift/Kubernetes templates named `argentina`, `kasahstan` and `spain` that will deploy MySql containers with persistance according to those rules:
    1. `argentina` Mysql server shoud only be deployed to server named `argentina` and persistance claims strictly in storage server `argentina_storage`
    2. `kasahstan` Mysql server shoud only be deployed to server named `kasahstan` and persistance claims strictly in storage server `kasahstan_storage`
    3. `spain` Mysql server deploys to whatever server with persistance claims on whatever storage server
