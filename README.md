# ansible-vmware-vm-deploy

```

ansible-playbook -i hosts/vmware site.yml --extra-vars "cluster_name=Cluster vm_name=newvm.local template_name=/DC/vm/CentOS7.template datastore_name=Prod-DS resource_pool=Prod vm_cpu=4 vm_mem_mb=2048 swap_resize_gb=2 vm_vlan=VLAN_2108 vm_ip=10.94.8.140 vm_netmask=255.255.255.0 vm_gateway=10.94.8.1 vm_dns=10.0.0.3 folder=/TDCDC/vm/Arena vm_username=root vm_password=StrongPw osid=centos64Guest" --tags deploy

```
