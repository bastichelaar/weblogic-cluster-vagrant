weblogic-cluster-vagrant
=======================

Based on https://github.com/biemond/biemond-wls  

uses CentOS 6.5 box with puppet 3.4.0

creates a patched 12.1.2 WebLogic cluster ( admin,node1 , node2 ) plus dynamic JMS, Cluster and Coherence cluster

used the following software
- jdk-7u51-linux-x64.gz

weblogic 12.1.2
- wls_121200.jar

Using the following facts

- environment => "development"
- vm_type     => "vagrant"


# admin server  
vagrant up admin

# node1  
vagrant up node1

# node2  
vagrant up node2