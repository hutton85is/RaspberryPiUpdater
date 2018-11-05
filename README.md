# RaspberryPiUpdater
A small program to update my raspberry pi every day at 4am<br>

The bash script "updateScript" is run by using "cron" every day at 3am.<br>
To do this simply run the command "crontab -e" in terminal and<br>
add this line "0 3 * * * /toyour/bash_script.sh" at the bottom 
