# Git Commands
- These commands are used within Git Bash to make changes to your github repositiory
- Link to Git Guides: https://github.com/git-guides

# Important Commands:

## git clone
- Use: Clones a repository from Github to your local computer
- Syntax: `git clone [ENTER_REPO_NAME]`
- Example:
  1. Go to the Github Repository of Choice, for this example we will use this one!
  2. Click on the code section from the tabs
  ![Capture](https://user-images.githubusercontent.com/44104800/163730220-71e0ee17-2eed-400c-9184-d14ce66ce5db.PNG)
  3. Click on the code button and copy the link
  ![Capture](https://user-images.githubusercontent.com/44104800/163730290-70304f51-36b8-431f-b495-386de03a4f17.PNG)
  4. Go To your git bash command prompt. To download refer to:      https://github.com/dlandman27/Web_Programming/blob/main/git_basics.md 
  5. Go to the designated file directory you want to download the file and type the command
    `git clone [YOUR_COPIED_REPO_NAME]`
  6. You did it! Now you can open the repository from your IDE (For this we are using VSCode) and locate the folder from the directory chosen above

## git add
- Use: adds new or changed files in your working directory to the Git staging area.
- Documentation: https://github.com/git-guides/git-add

## git commit:
- Documentation: https://github.com/git-guides/git-commit

## git push:
- Pushes the commited changes to the online repository
- https://github.com/git-guides/git-push


# Example of using these commands together
```
1. git clone "REPONAME"
2. Open the repository and make some changes to your files from VSCode
3. open git bash and go to the file directory of the github repository
4. git add .
5. git commit -m "Add a message of what you did in quotes"
6. git push
Thats it! If you did this correctly you can see the changes from github online.
```
