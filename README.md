# Alfred App Workflow - JIRA Search Utilities

This workflow is for JIRA Server users. If you are using JIRA Cloud, this workflow has not been tested on JIRA Cloud and may or may not work. The purpose is to allow searching JIRA through the Alfred keyword interface.
<img width="582" alt="2021-04-08_17-29-00" src="https://user-images.githubusercontent.com/1483300/114111923-1336c080-9890-11eb-8879-2b2fa0ae022c.png">

## Prerequisites
1. You must have jq installed. Please see https://stedolan.github.io/jq/

## Installation

1. Download the workflow](https://github.com/scarstens/alfred-workflow-jira-search-utilities/blob/main/JIRA-Server-Utilities-by-Seth.alfredworkflow?raw=true)
2. Find and open the file you downloaded (probably in your downloads folder or your desktop) and open the file.
<img width="707" alt="2021-04-08_17-00-07" src="https://user-images.githubusercontent.com/1483300/114110268-fc8e6a80-988b-11eb-89a3-d1530b70e4c8.png">

3. Click import to install the workflow
<img width="1680" alt="2021-04-08_17-05-03" src="https://user-images.githubusercontent.com/1483300/114111278-76275800-988e-11eb-9870-17f46e3d5094.png">

4. Activate alfred keyword search and use `jsconfig` to begin the workflow configuration wizard.
<img width="666" alt="2021-04-08_17-07-13" src="https://user-images.githubusercontent.com/1483300/114111276-758ec180-988e-11eb-8800-2e025ac20b7c.png">

5. Enter your jira server domain first, likely something like `jira.mywebsite.com`.
<img width="686" alt="2021-04-08_17-08-28" src="https://user-images.githubusercontent.com/1483300/114111275-758ec180-988e-11eb-8965-a64e5401c17a.png">

6. Enter your JIRA Username (or possibly your Active Directory username)
<img width="652" alt="2021-04-08_17-09-21" src="https://user-images.githubusercontent.com/1483300/114111274-74f62b00-988e-11eb-84a9-c0bf3d1fd12f.png">

7. Enter your JIRA Password (or possibly your Active Directory password OR you can paste a JIRA API Token)
<img width="656" alt="2021-04-08_17-11-17" src="https://user-images.githubusercontent.com/1483300/114111273-745d9480-988e-11eb-8a9e-326d81f48d45.png">

8. If successful you will see a fullscreen popup indicating you are configured, you can hit escape to close the notification.
9. You can now search for JIRA tickets using 2 different workflows - either typing `js keyword` and hitting enter to enter the search only wizard, or you can bypass the wizard and search immediately using `jst keyword`. JST mean "Jira Search Tickets".
<img width="582" alt="2021-04-08_17-29-00" src="https://user-images.githubusercontent.com/1483300/114111875-f0a4a780-988f-11eb-9e02-ef40e74d13b7.png">







