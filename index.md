#Bio 812 Feb 7 Assignment - Russell Turner

###Questions

  * **1.** Git is great to manage projects and updates similar to a lab notebook in that all versions of your electronic copy are maintained in case you need to return to a previous version.
  
  * **2.** Codes, Scripts, and text documents that you think are important to your project incase you ever want to go back and edit something from an earlier version. Never save personal information like passwords or confidential information.
  
  * **3.** To undo a commit you can use either:
```{r}
git checkout HEAD~ 1 <file name>
  # or
git revert <commit_id>
```

  * **4.** To fix a detached head and return to the master branch you can use:
  
  ```{r}
  git checkout master
  ```
  
  * **5.** 
   * **Pros** Collaboration with muliple people is very easy. You can all work on the same document and then combine later to one streamline complete document. You can also easily track your files to see what has been changed and by who. 
   * **Cons** Largedatasets are difficult to handle using Git. Also learning to use git and the interface takes a while.
