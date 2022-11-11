# loops-challenge

## using git
Go to your Terminal.

1. git clone "https://git..."
2. git remote-v, should show 2 entries (one for fetch, one for push)
3. git fetch origin main
4. git checkout [name of your branch], you should now be on your branch
5. git pull origin main, will pull from main branch

If you've already cloned and want to commmit,
1. Navigate to the directory where your folder is stored
2. git init
3. git checkout [branch name]
4. Follow steps 3-5 above, then steps 1-3 below

When you're ready to commit your changes,
1. git add .
2. git commit -m "message about your commit"
3. git push, this will push to your branch.

When you want to edit on your branch but first have to pull from main:
1. git fetch
2. git pull

Then, go to the browser and click on "new pull request", assign reviewers if needed


## using the profile storage site
Go to https://www.apispreadsheets.com/ and open up ProfileResponses.xlsx

To access the data:
Option 1: click File Data under the Actions menu on the left and view the data on the site.
Option 2: click File Data under the Actions menu on the left and then go to the URL above the table to view in another window.
Option 3: under ProfileResponses.xlsx click Download File.

To edit the columns:
1. Edit the code as needed so that the id's match what column names you want.
2. Download the excel file from the site.
3. Add/remove headers so that they match the id's in the code.
4. Save and reupload file onto the site.

To set up a new spreadsheet:
Follow this: https://lovespreadsheets.medium.com/save-web-form-data-to-spreadsheets-880f95431f00
