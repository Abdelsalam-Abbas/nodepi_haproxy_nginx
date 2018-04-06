# nodepi_haproxy_nginx


this project aims to deploy 


1. NodeApi ( as much as instances as you want ) 
2. HaProxy 
3. Nginx ( proxy-server)
4. MySql



## Requirement:

vagrant >= 2.0.3
virtualbox >= 5.2.8

*note: it could work on earlier version but only tested on these version.


## Usage:


clone the repo 



edit as per your needs 

```abbas$ cat ansible_books/group_vars/all 
count_of_instances: 3
project_prefix: "abbas"
```

start the deployment 

`vagrant up`
