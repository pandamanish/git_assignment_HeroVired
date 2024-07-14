# git_assignment_HeroVired

1. Created a repository git_assignment_HeroVired in github with Private mode and cloned it with my local repository using "git clone". 
2. created a dev branch using git bash in local and created calculator plus app.py file and did "git add">"commit">"push -u origin dev". 
3. post that went into main branch and merged the dev to main branch and created a release with v1.0 
4. Added Aditya vakharia as my collaborator. 
5. Implemented new feature featre/sqrt by creating a branch from the dev branch and added those sqrt function in the calculator plus app.py script.Pushed the changes to same branch in git hub using "git add">"commit">"push -u origin feature/sqrt". 
6. Switched back to dev branch and fixed the issue of the divide function , commmited the changes and pushed to the dev branch. 
7. To have the bug fixes in my feature branches i swithced to feature/sqrt branch and did a merge with the dev branch and pushed the changes. 
8. Opened Github UI>clicked on pull request>new pull request ( main <- dev)>created the request>clicked on Assigness on the right and added Aditya Vakharia>Aditya went to my repo, went to pull requests in his UI>clicked on my pull request which was reflecting there>clicked on files changed>reviewed my code and have the appropriate comments and then clicked on Approve.I came to my pull request then and did the merge closed my request.
9. went into dev branch using git bash and did a merge with the feature/sqrt .
10. Tested using VS code for the updated code. step 11 :Made a release of v2.0 with updated changes and bug fixes.

# Question 2 : Git LFS 

Created a new rep for this question due to the repository lare files push quota limit for exceeded.
https://github.com/pandamanish/git_assignment_HeroVired-LFS

# Question 3 : Git Stash
1. Branch creation of geometry-calculator using git clone
2. opened vs code and pasted code from vlearn using command code .
3. pushed the code and branch to git using git add and git commit comaands.
4. feature branch for circle area was created using git checkout -b feature/circle-area
5. code . #made changes in code introduced the circle functionality
6. git stash save "<message>" #to keep the track of stash made for circle code snipet
7. git status #to verify git stash worked or not
8. NOW WILL DO THE SAME WITH FEATURE/RECTANGLE-AREA PART OF THE CODE
9. git checkout geometry-calculator
10. git checkout -b feature/rectangle-area
11. code .
12. git stash save "<message>"
13. git status
14. #NOW WILL GO BACK TO FEATURE/CIRCLE-AREA AND PUSH THE CHANGES
15. git stash list ,to know the which number indicates to circle area stash
16. git stash apply stash@{<number>} #applying speicific stash
17. git add .
18. git commit -m "<message>"
19. git push -u origin feature/circel-area
20. Same was done for feature/rectangle-area. stashes were listed, its specific stash was applied and pushed to git.
21. 2 pull requests were generated from feature/circle-area to geometry-calculator and feature/rectangle-area to geometry-calculator
22. working code was pulled down to geometry-calculator repo.
23. one more pull request from geometry-calculator to main repo.
24. Pull requests were reviewd and approved by Aditya Vakharia at each stage.
