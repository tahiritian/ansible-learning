###what to find on this repo:  

We created this project during an internal hackathon.  
This project is about network automation with an ip fabric.  
The network topology is a 3 stages CLOS with 3 leaves and 2 spines.  
We used EBGP. 
All the devices used run Junos (we used vQFX10k).   
We used automation (based on ansible) to build (using jinja2 templates and variables defined with yaml) junos configuration files and to apply them on devices.  
we also enhanced with automation some of the ZTP requirements  
We also built automation content to run hitless maintenance operations on spines.  

###doc:  
visit wiki to get the doc regarding this project (https://github.com/ksator/ansible-junos-ZTP-ip-fabric/wiki) 

