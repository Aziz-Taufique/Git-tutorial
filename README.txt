1. `git init` -> Powers your folder to be managed by git, and initialises a new empty repository. It also create a .git folder that has all the relevent logic to manage versions of you project.

2. `Working Area` -> There can be abunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not mangaged by git yet. A File which in in working area in cinsidered to be not in the staging area. When we do `git status` and we see a bunch of `untrackte files` then these are actulaay called to be in the working area.

3. `Staging area` -> What all files are going to be part of the next version that we will create.
This staging area in the place where git knows that chnages will be done tha last version to the next version   

4. `Repository Area` -> This area actually constains that details of all your previous registered version. And the files in this area, git already manages them and knows their version history.

5. `git add <file>` -> moves file rom working area to staging area
6. `git rm --cached <file>` -> moves file back from staging area to working area
7. `commmit` -> commit is a particular version of a project it captures a snapshot of the prject's staged changes and creates a version out of it.
8. `git commit` -> registers staging changes to a commit
9. `git log` -> list downs all the commits of the prepository. If you want to exif from git log press `q`.
10. `git restore <file>` => It removes all files changes form the staging area to be commited. This can be useful, if we did some dirty piece of code and now no more want it. Insted of deleting every change line by line, we can restore it or you can say restore last clean version of file.

