# Cron jobs and Bash Scripts task

## About The Task
Combine Cron Jobs & Bash Script to automate a certain process. 

## Built With
Git bash
Cron job

## Prerequisites
Install Cron
Install Git bash
Have basic bash scripting knowledge

## How It Works
This task prints out a task list every one hour, reminding the user on the tasklist he/she created.

## Test this project
Create a cron job that runs the script ```tasklist.sh```

* Creating a cron job
```
crontab -e
```
* A cron job that runs every hour
```
00 * * * * /home/faithkovi/crontask/tasklist.sh
```

## Issues encountered
None
