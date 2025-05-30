# Task_04_Elevate_Lab
## Setup and Use a Firewall on Windows/Linux          
**1. UFW(Uncompiled firewall) on LINUX**       
     Open bash,           
     Step 1: Installing UFW : ***sudo apt update***              
                              ***sudo apt install ufw y-***        
     Step 2: Enable UFW : ***sudo ufw enable***               
     Step 3: Check current firewall rules: ***sudo ufw status numberes***   
     Step 4: Block Telnet port : ***sudo ufw deny 23***    
     Step 5: Test blocked port : ***Telnet localhost 23***   
             Shows connection refusing or failed    
     Step 6: Allow SSH port : ***sudo ufw allow 22***    
     Step 7: Deleteing or removing the rule : ***sudo ufw delete deny 23***   
     Step 8: Displaying the status : ***sudo ufw status verbose***
**2. Windows Defender Firewall**     
    Step 1: Open Control Panel    
    Step 2: CLick System and Security -> Windows Defender firewall   
    Step 3: Go through Advanced settings   
    Step 4: Clicl Inbound rule -> New rule -> Port -> Specify port        
    -> Choose the type of connetio is to be block or allow         
    -> Apply to Domain, Private, Public   
    -> Name the rule -> Save
    Step 6: For removing or Deleting the rule, right click  and delete the new rule created  
