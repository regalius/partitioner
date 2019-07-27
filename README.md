# Partitioner
Simple bash script to create network partition in docker containers using iptables inside docker container

Usage
```
partitioner <mode> <target service> <blocked service> 

 mode:
   - partition <target service> <blocked service> - create a network blockade from  <target service> to <blocked service> 
   - join <target service> <blocked service> - remove blockades in <target service> to  <blocked service>
   - join-all <target service> - remove all network blockades in <target service>
```