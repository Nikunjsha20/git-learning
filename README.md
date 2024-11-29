1. git init :power our folder to be managed by git and initializes a new empty repository
Nikunj
.........
2.touch new.txt to create a folder..

3. rm -rf .git // rm -r .git
   git git 

[Working area || Staging Area || Repository Area]

working area : bunch of files..that are not currently handle by git..
it means those file arer not managed by git yet...

4. git status...
Staging Area : 
Staging Area : what all files are going to be a part of the next version..
that will be create this staging area in the place , where git knows. what change will be done from the last version to the next version

so add the file from working area to staging area --> git add <file>

5. git add <file> ...

6. git rm --cached <files> --> To move a file from staging area to working area...

commit ---> "commit" is the particular version of the project ....

7. git commit --> Registers Staging changes to a commit...

there we can write commit lines... and for exit this promt Enter escape then :wq colon wq and Enter


8. git log ---> list down all commit of the Repository If you want to exit out of git log promt press q...


9. git restore <file> -----> It remove all files changes from the staging area to be committed ...


10. `git commit -m "<message for commit...>"` -->

11. "git remote" -->

12. git remote add <name of remote> <link_of the remote>

13. git remote rename <oldName><newName>--> 
14. remote connection
15. git push <name of remote> <branch name_ By default master>.....


Note: The name of remote connection is always used to establish communication of b/w the Repos..

16. `git add <file1><file2><file3>` : This command will add Multiple file changes together in the staging area....

17. `git add .` : this command will add all files from woring repo to staging area..

18. `git pull <name of remote><name of branch>`: to fetch file the our local file. 

19. ## recommended Practice to do
    -make change
    -git add <filename>
    -git commit
    -git push
    -git pull

 -make change
    -git add <filename>
    -git commit
    -git push
    -git pull