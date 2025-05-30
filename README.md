# Task_04_Elevate_Lab
## Setup and Use a Firewall on Windows/Linux          
  1. UFW(Uncompiled firewall) on LINUX       
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
