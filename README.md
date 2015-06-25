# Portal Config Files

These are the config files for the POC Data Portal. There are a few key types of information and organization schemas that enable the portal to run:

* `params-display.json`: this file contains display information and either values or a table reference for every filter and parameter on the portal.

* `table/1566/education`: this folder system currently maps to the UI and is expected by the front end of the Data Portal application. The sub-folders can only be removed if the corresponsing references in Slim and `visualization-chart.js` are also removed.

* `sp_mp_lit3_perc.json`: config files are named for the stored procedure they reference and contain information about what filters should be used and how the data should be transformed. The config files are formatted in a manner that ties very closely to how stored procedure results are returned.

## Workflow

These steps assume that you are using GitHub for Windows. The same can be accomplished from the command line.

1. Clone this repo locally

2. Check out the dev branch from the dropdown at the top that says "master"

3. Click "Manage" in the dropdown to go to the branch manager window. Click on the plus sign next to the branch you are currently on to create a new branch. Name it something meaningful related to what you are working on.

4. Make and commit your changes to your local branch, then click "Publish" in the upper right-hand corner. 

5. To the left of the Publish/Sync button is the pull request button; click that to send a pull request indicating that you are done with your changes and want to merge them in with the group's work. Describe what you want to do and *make sure you request to merge into the dev branch*

6. Gregor or Erika will review your changes and either comment/ask for additional work or merge your changes and close the pull request.

Remember, if you are working locally for a long time, you should check for new changes on the dev branch and merge them into your own work periodically. This will help you stay up to date and help the team avoid conflicting changes.
