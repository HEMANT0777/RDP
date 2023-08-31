# windows–rdp

Easy setup just some steps

1. Fork it 

2. Signup here if you dont have ngrok account
https://dashboard.ngrok.com

3. Copy token from https://dashboard.ngrok.com

4. Paste that token in Settings (in top right of this page) > Secrets > Action > New Repository Secret and fill data as.     
 
 Secrete Name = 'NGROK_AUTH_TOKEN'
      
 Value = token that you copied in step 2.
 Add Secret key.
        
5. Enable github actions https://github.com/features/actions

6. Now open Actions tab on top of this page.

7. Accept whatever it says.

8. Now change "All Workflows" to "CI".

9. Below that you will see Run Workflow tap on it then again tap on Run Workflow.

10. Let it run for 2-3 mins.

11. Open https://dashboard.ngrok.com/status/tunnels 

11. Now copy host address

 ( like x.tcp.ngrok.io.xxxx )

default username : 'hemant'

default password : 'Password'

12. Enjoy 

Note:
1) You will get 7GB RAM RDP 
2) It will last till 2hr (per session) then you need to run it again
3) Don't open Unity Launcher and Epic Games.

All credits to https://github.com/HEMANT0777
