Things I learned today, March 9, 2021:

Today we learned more about the command line, mostly how to use it to push changes to repositories on GitHub. 

The most important thing I learned was how to upload files to a new repository on GitHub. These are the commands that I enter in the command line to save to GitHub:

1. git init -
        This command creates a .git file in the folder we want to push to GitHub. 

2. git status -
        This command shows what branches you're on and what files are there and whether they are tracked or untracked. If it shows a file name in red, that file needs to be added and tracked so it can be committed.

3. git add . - 
        This command adds everything in red that was shown under the previous git status list.

4. git status - 
        This is the same command as before, however, when you run it after adding files, those files should show up green now.

5. git commit -m "comments" - 
        This command commits the files and they are ready to be uploaded! The comment added between the quotations is seen on GitHub as your comment relating to the upload.
    
6. git push - 
        This command actually pushes the changes. If you only put git push, the changes will be saved on your computer. If you have followed the steps on GitHub after creating your repo, you can upload straight to GitHub using git push origin master (or main, or whatever you called your main branch).

We also learned how to push easily from VS Code, without using the terminal! This is easier but I enjoy knowing how to do the push from the terminal as well. 

I uploaded the final changes using the easy method in VS Code! I had to troubleshoot a little but I figured it out.
