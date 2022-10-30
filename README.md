# loops-challenge

## using git
Go to your Terminal.

git clone "https://git..."
git remote-v, should show 2 entries (one for fetch, one for push)
git fetch origin main
git checkout [name of your branch], you should now be on your branch
git pull origin main, will pull from main branch
If you've already cloned and want to commmit,

Navigate to the directory where your folder is stored
git init
git checkout [branch name]
Follow steps 3-5 above, then steps 1-3 below
When you're ready to commit your changes,

git add .
git commit -m "message about your commit"
git push, this will push to your branch.
When you want to edit on your branch but first have to pull from main:

Create a pull request: [branch name] <-- main
Merge appropriately
In your Terminal, type the command "git pull origin main"
Your local repo should update after you close out of VSCode and refresh
Then, go to the browser and click on "new pull request", assign reviewers if needed
