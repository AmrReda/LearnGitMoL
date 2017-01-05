
###Exercise 1
####1 Create a new directory named bigger_file, and make a Git repository.
####2 copy the lorem-ipsum.txt file to this Git repository.
####3 Commit this file into the repository.
####4 Copy lorem-ipsum-change.txt from the zip file of the previous step, and add it to the directory. 
####5 Rename (or copy) this new file to lorem-ipsum.txt.

By following the preceding steps, you’ve created a change in the lorem-ipsum.txt file.
Git can detect these changes. Now, some questions and tasks:
###Exercise 2
####1 How many hunks does this change have? (Hint: Each hunk is delimited by a line that starts with @@. You can see these lines with git diff.)
####2 Using git add -p, stage and commit the change to just the second hunk.
####3 Now check out the latest code (removing the changes in the working directory). (Hint: use git status to see the syntax for how to do this.)
####4 Once again, copy the lorem-ipsum-change.txt file into the directory, and then rename (or copy) this new file on top of the lorem-ipsum.txt file.
####5 Now how many hunks does this change have?
####6 Commit the entire file.
###Exercise 3
In Git, adding files to the repository is achieved via the git add and git commit
commands. But what if you want to delete files from the repository? 

####1 Create a two new files (app.js and readme.md ) and Add them to Staging (git add .)
####2 Check if file has been add (git status)
####3 Commit both files to repository
####3 Now you decided to remove readme.md file (rm readme)
####4 check git status
####5 Commit your changes



