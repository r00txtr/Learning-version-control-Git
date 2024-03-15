### Exercise 1: Creating and Managing a Simple Repository

#### Step 1: Set Up Git
If you haven't already, install Git on your computer. You can download it from the official website: [Git Downloads](https://git-scm.com/downloads).

#### Step 2: Configure Git
Open your terminal or command prompt and set your username and email address using the following commands:
```
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

#### Step 3: Create a New Repository
Create a new directory for your repository and navigate into it:
```
mkdir my_repository
cd my_repository
```
Initialize a new Git repository:
```
git init
```

#### Step 4: Add a New File
Create a new text file inside your repository directory, for example:
```
echo "Hello, Git!" > hello.txt
```
Add the file to the staging area:
```
git add hello.txt
```

#### Step 5: Make a Commit
Commit the changes with a descriptive message:
```
git commit -m "Added hello.txt file"
```

#### Step 6: Create a Branch
Create a new branch named "feature" and switch to it:
```
git branch feature
git checkout feature
```
Alternatively, you can combine the above commands into one:
```
git checkout -b feature
```

#### Step 7: Make Changes
Edit the `hello.txt` file, for example:
```
echo "Hello, Git! This is a new feature." > hello.txt
```
Add and commit the changes on the feature branch:
```
git add hello.txt
git commit -m "Updated hello.txt for feature"
```

#### Step 8: Merge Changes
Switch back to the main branch:
```
git checkout main
```
Merge the changes from the feature branch into the main branch:
```
git merge feature
```

#### Step 9: Push to Remote Repository (Optional)
If you have a remote repository (e.g., on GitHub), push your changes to it:
```
git remote add origin <remote_repository_url>
git push -u origin main
```

#### Step 10: Clean Up (Optional)
You can delete the feature branch if you no longer need it:
```
git branch -d feature
```

### Conclusion
Congratulations! You've successfully completed the exercise, which covered basic Git operations such as initializing a repository, creating branches, making changes, committing, and merging. Keep practicing these steps to reinforce your understanding and confidence in using Git for version control in your projects.
