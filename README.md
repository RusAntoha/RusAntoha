Ill keep it short here, some screenshots and logs are in the related folder if you would like to see them

what i did:

Cloned the GitHub repository
Build docker on my PC
Run on my PC port 5000
Created dockerhub account
Pushed our file to dockerhub
created VM
added tcp 5000 (all) rule into firewall (deleted later)
installed docker on VM
Logged into dockerhub from VM
Pulled docker file
run it on VM port 5000
added curl
created hugging face "write" key
used ping, load_model and chat commands (made sure everything works, so had to troubleshoot a bit)
went to retool
created an app and a restAPI
created 2 queries for model_load and chat
created "Choose model", "Prompt", "Enter" and text output elements and linked them to queries (made sure it worked)
added retool IPs (TCP 5000) into firewall (cloud customers)
52.177.12.28/32
52.175.251.223/32
35.90.103.132/30
44.208.168.68/30
added assignment allow IP (TCP 5000)
147.87.0.0/16
