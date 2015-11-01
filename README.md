# MAC_PORT_COMMANDS
mac port commands 

1. selfupdate command

                        $ sudo port selfupdate
                        
2.  Show Ports Which Need Updating use the below command
      
                        $ port outdated 

3. upgrade all installed and outdated ports 
  
                        $ sudo port upgrade outdated


4. To get a list of inactive ports  
 
                        $ port installed inactive

5.Finding Leaves use the below command

                        $ port echo leaves

6.Finding Ports Depending on a Certain Port use the below command

                        $ port echo depends:<portname>
 
accurate dependents
      
                        $ port dependents <portname>

