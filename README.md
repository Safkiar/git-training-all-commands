# git-training-all-commands



1. git clone https://github.com/Safkiar/git-training-all-commands
--- repo has been copied!

------------------

new branch has been added with command:

2. git checkout -b kiara-zadanie
2.1 git add README.md
2.2 git commit -m "Kiara dodaje system mruczenia"
2.3 git push -u origin main kiara-zadanie
<!-- u - upstream -->

------------------

--- Safir after Kiara

3. git checkout main
4. git checkout -b safir-zadanie

--- safir wdrążył zaawansowany system łapania myszy


------------- MERGE CONFLICT

5. git checkout main
6. git pull

------------- GIT STASH

git checkout -b kiara-trudne-zadanie

TEST CODE WITHOUT COMMIT 

git stash
git checkout main
---editing main
git add .
git commit -m "...commit"
git checkout kiara-trudne-zadanie
git stash pop


*hotfix* after git stash

----

git revert <id_commit> - new commit, revert changes from particular commit in past
git reset --hard <id_commit> - back in time and delete present

git log --oneline --graph   - commit tree

git checkout -b old-version <id_commit> - copy and create a new branch

git fetch - pull code without merging
git pull - merge with my current code
git diff - what changes have been done

to check other`s code: git log --oneline origin/main

git merge - merge two branches, create a new commit, with merged branches
git rebase - change branch origin , rebase create change ID

git cherry-pick x9y8z7 - take one commit

squash - destroys commits 

git rm --cached - leave file on disk but not on git

git clean -fd - delete folder which git do not follow

git bisect - dev tools for searching bugs in git commits!

