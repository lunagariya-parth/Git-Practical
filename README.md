<a name="readme-top"></a>

<h1 align="center">Git- Practical Assignment</h1> 

## 1. Pull and Merge difference

1. Make example of pull request and two branch merge event.
2. Create a feature branch.

3. After commit Push this new branch.

4. Create Pull Request on GitHub.

5. After approving the pull request dev branch will be merged with the main branch. In this case we own the main branch so we can approve the pull      request.



## 2. Rebase
 
1. Try to rebase rebase-prac branch with main branch
    * rebase is used to maintain a clean project history.
   
  ```sh 
    git rebase main
  ```
  
 2. push main branch after the commit.

 3. create another branch named rebase-prac.

 4. push this rebase-prac branch after commit.

 5. Now to rebase rebase-prac branch with main branch we have to write "git rebase main " command.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 3. Change commit message
 1.Commit in feature branch and then change commit message
  ```sh 
     git commit --amend -m "changed commit message" 
  ```
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

 
## 4. cherry pick
 1.Pick some commits from feature branch to main branch
  ```sh 
     git cherry-pick (commit-id)  
  ```
  * Example:
  ```sh 
     git cherry-pick ebebc6b
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

  
 ## 5. Drop commit
  1.Remove some commit from main branch.
   ```sh 
      git reset --soft HEAD~3 
   ```
  * with this command the last three commits will be removed.
  
  * with this command the last three commits will be removed.
  * To remove the last commit from remote repo, we can simply run git reset --SOFT HEAD^

  * If we want to remove multiple commits from the top, we can run git reset --SOFT HEAD~3 to remove the latest three commits.

  * We can give the number of commits which we want to remove.

  2.After that push your changes to remote repo.
    
      git push -f origin main 

    
    
 <p align="right">(<a href="#readme-top">back to top</a>)</p>
  
<h3 align="center">Thank you</h3>
