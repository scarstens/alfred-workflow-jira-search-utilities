# Alfred App Workflow - JIRA Search Utilities

This workflow is for JIRA Server users. If you are using JIRA Cloud, this workflow has not been tested on JIRA Cloud and may or may not work. The purpose is to allow searching JIRA through the Alfred keyword interface.

## Installation
1. ###[Download the workflow](https://github.com/scarstens/alfred-workflow-jira-search-utilities/blob/main/JIRA-Server-Utilities-by-Seth.alfredworkflow?raw=true)
2. Find and open the file you downloaded (probably in your downloads folder or your desktop) and open the file.
<img width="707" alt="2021-04-08_17-00-07" src="https://user-images.githubusercontent.com/1483300/114110268-fc8e6a80-988b-11eb-89a3-d1530b70e4c8.png">

3. Click import to install the workflow
4. Activate alfred keyword search and use `jsconfig` to begin the workflow configuration wizard.
5. Enter your jira server domain first, likely something like `jira.mywebsite.com`.
6. Enter your JIRA Username (or possibly your Active Directory username)
7. Enter your JIRA Password (or possibly your Active Directory password OR you can paste a JIRA API Token)
8. If successful you will see a fullscreen popup indicating you are configured, you can hit escape to close the notification.
9. You can now search for JIRA tickets using 2 different workflows - either typing `js keyword` and hitting enter to enter the search only wizard, or you can bypass the wizard and search immediately using `jst keyword`. JST mean "Jira Search Tickets".
