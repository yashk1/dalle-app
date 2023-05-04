1. `git init` - To initiate a git repository locally
2. `git add .` - To add files to git
3. `git status` - To check the status of git
4. `git commit -m "message"` - To commit the files to the git 

We still haven't uploaded our file to git repo online, for that we need to remote into it

5. `git remote add origin git@github.com:yashk1/dalle-app.git` - this adds a origin where we can "push" our code
6. `git push -u -f origin master` - this pushes all the files to the github. -u means default, -f is to force it, master is the branch we are pushing our code
