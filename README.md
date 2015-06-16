# Portal Config Files

These are the config files for the POC Data Portal. There are a few key types of information and organization schemas that enable the portal to run:

* `params-display.json`: this file contains display information and either values or a table reference for every filter and parameter on the portal.

* `table/1566/education`: this folder system currently maps to the UI and is expected by the front end of the Data Portal application. The sub-folders can only be removed if the corresponsing references in Slim and `visualization-chart.js` are also removed.

* `sp_mp_lit3_perc.json`: config files are named for the stored procedure they reference and contain information about what filters should be used and how the data should be transformed. The config files are formatted in a manner that ties very closely to how stored procedure results are returned.

## Workflow

Clone the repo and checkout the dev branch. Next, create a new branch locally named for whatever you are doing. So, for example, if you need to remove budget filters from all visualizations, you might name your branch "remove-budget-filters."

Do your work locally and test on your local Data Portal copy. When everything looks right and you think you are done, push your branch to GitHub and take out a pull request describing what you did and any questions you might have.

Within 48 hours (72 if there is a weekend in the middle), Gregor or Erika will review your pull request and merge changes into the dev branch if everything looks ok. Once that's done, you can delete your local branch and pull changes from GitHub.

If you are working locally for a longer period of time, *remember to pull changes* that others may have been working on to avoid conflicts down the road.

