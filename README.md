# PGN

+ Step 1:Start your docker application.
+ Step 2:Clone the repo
+ step 3: cd prometheus
+ Step 4:run the command: **docker compose up -d**
## Grafana login page would pop up:
   + **User** : admin
   + **password** : admin
+ prompts for a new password
+ open prometheus UI "localhost:9090"
+ Under status dropdown ,select targets and check if everything is running
+ go to grafana page "localhost:3000" and add a data source
+ Select prometheus for datasource and then type "http://localhost:9090" 
+ save and set ,go back to home page.
+ click on dashboard and click on import dashboard
+ type 1860 in ID bar and click on load
+ see the job is selected as siu
+ set auto refresh interval to 5 sec top right corner
+ change it to last 15 minutes
