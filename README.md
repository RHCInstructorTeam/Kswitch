### KSwitch
-----------

It is just a simple utility which lets you switch between the projects with ease being in the same cluster context. 

Important, you need to be logged into your kubernetes cluster first. 

### Usage
---------

> shub ocp4.2 ~ % git clone github.com/shkatara/Kswitch  
> shub ocp4.2 ~ % cd Kswitch  
> shub ocp4.2 ~ % chmod +x kswitch && mv kswitch /usr/bin  
> shub ocp4.2 ~ % kswitch kube-project

Note: Move it anywhere in the directories in your $PATH environment variable.

### Output
----------
> shub ocp4.2 ~ %  kswitch kube-systemasdas  
Error: The given project kube-systemasdas does not exist. Please check the name of your project.  
> shub ocp4.2 ~ %  kswitch kube-system  
Context "kubernetes-admin@kubernetes" modified.  
Project switched to kube-system.  

