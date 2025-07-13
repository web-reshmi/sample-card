## How to push project to GitHub
1. Intialize Git in the working directory
```
git init
```
2. Select all the files from your project working directory
```
git add .
```

3. Make a commit
```
git commit -m "First Commit"
```

4. Add git branch main
```
git branch -M main
```

5. Add the repository link for uploading the project files into it
```
git remote add origin https://github.com/your-username/repo-name.git
```

6. Now push the project files into the Repository
```
git push -u origin main
```

You can now check your GitHub repository for the project files


### For Pushing updated files from the project directory
1. Select all the files from your project working directory
```
git add .
```

2. Commit your project changes in the github
```
git commit -m "Second Commit"
```

3. Now push the updated files to the GitHub repository
```
git push -u origin main
```

Your updated files are now on your GitHub repository