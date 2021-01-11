# NewLocalUser-Orbital

# Workflow Description: 
When triggered, this workflow will review machines and local users in Orbital and send a Webex alert on new user(s).


# Workflow Requirements: 
This workflow requires the Orbital_Credentials and Webex Teams Bot credentials. 
Please verify these settings prior to execution.

Please review these links:

  https://developer.webex.com/docs/bots#creating-a-webex-bot
  
  https://developer.webex.com/my-apps
  
  Based on these links You can create your own Webex Bot and Secure Webex Bot Account. 

  ![webex bot](webex.png)

Please create or review a Generic Schedule like this as a trigger:

![Schedule](sch.png)

After a successful run, you will see the new user reported by the workflow:

![Output](Webex-output.png)
