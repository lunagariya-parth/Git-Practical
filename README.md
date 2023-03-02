<a name="readme-top"></a>

<h1 align="center">Git- Practical Assignment</h1> 

## 1. Pull and Merge difference

1. Make example of pull request and two branch merge event.
2. Create a feature branch.

3. After commit Push this new branch.

4. Create Pull Request on GitHub.

5. After approving the pull request dev branch will be merged with the master branch. In this case we own the master branch so we can approve the pull      request.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 2. Rebase
 
1. Try to rebase feature branch with master branch
    * rebase is used to maintain a clean project history.
   
  ```sh 
    git rebase master
  ```
  
 2. push master branch after the commit.

 3. create another branch named feature.

 4. push this feature branch after commit.

 5. Now to rebase feature branch with master branch we have to write "git rebase master " command.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 3. Change commit message
 1.Commit push on commit in feature branch and then change commit message
  ```sh 
     git commit --amend -m "changed commit message" 
  ```
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

 
## 4. cherry pick
 1.Pick some commits from feature branch to master branch
  ```sh 
     git cherry-pick (commit-id)  
  ```
  * Example:
  ```sh 
     git cherry-pick adff5634aa38365e2d32c2a9fdb30e8c5fa44528
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

  
 ## 5. Drop commit
  1.Remove some commit from feature branch.
   ```sh 
      git reset --soft HEAD~2 
   ```
  * with this command the last two commits will be removed.

  * To remove the last commit from git, we can simply run git reset --SOFT HEAD^

  * If we want to remove multiple commits from the top, we can run git reset --SOFT HEAD~2 to remove the last two commits.

  * We can give the number of commits which we want to remove.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

