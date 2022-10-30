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

1. Create a pull request: [branch name] <-- main
2. Merge appropriately
3. In your Terminal, type the command "git pull origin main"
4. Your local repo should update after you close out of VSCode and refresh
5. Then, go to the browser and click on "new pull request", assign reviewers if needed
