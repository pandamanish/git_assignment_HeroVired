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
Went to Git Bash and created a repository from the main branch
180  git checkout -b lfs

Installed a LFS on Gitbash a large files storage package
181  git lfs install

Tracking the *.bin file
182  git lfs track "C:\Users\17282\OneDrive\Documents\Python_Scripts\Assignments\git_assignment_HeroVired\bin_file\*.bin"

Adding 
183  git add .gitattributes

184  git commit -m "added 200mb bin file"

185  git push

186  git push -u origin lfs
