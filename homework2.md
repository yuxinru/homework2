# **<font color=#4B0082>Git WorkFlow</font>**
![image](https://wac-cdn.atlassian.com/dam/jcr:25d06843-2468-4e00-8ae7-11d4164f8995/hero.svg?cdnVersion=ht)

####       ----516030910128 余心如
---

##------------------------------
###<font color=#9400D3>*What is git workflow?*</font>
##------------------------------

----

####<font color=#9932CC>|> Concept <|</font>
#####A Git Workflow is a recipe or recommendation for how to use Git to accomplish work in a consistent and productive manner. 
####----------------------------------------------

---
####<font color=#9932CC>|> Some examples <|</font>
#####<font color=DA70D6>Centralized Workflow</font>
![image](https://dn-coding-net-production-pp.qbox.me/feebbee4-43de-487d-bedb-cc12a1e7c91e.png)

---
#####<font color=#DA70D6>Git-flow Workflow</font>
![image](https://dn-coding-net-production-pp.qbox.me/b84291d9-e16d-4af0-9149-2ae6faeea134.png)

---
#####<font color =#DA70D6>Fork Workflow</font>
![image](https://dn-coding-net-production-pp.qbox.me/0d3c05db-1ee9-430b-973e-f370ccd0b97e.png)

---
##------------------------------
###<font color=#9400D3>*Why git workflow?*</font>
##------------------------------

---
####<font color=9932CC>|> Advantages <|</font>
#####<font color=DA70D6>Feature Branch</font>
######*1*. Provide an isolated environment for every change to your codebase. 
######*2*. Let you represent development work at the same granularity as the your agile backlog. 

---
####<font color=9932CC>|> Advantages <|</font>
#####<font color=DA70D6>Distributed Development</font>
######Get our own local repository, complete with a full history of commits.
#####<font color=DA70D6>Community</font>
######Expected version control system for new projects

---
###-------------------------------------
###<font color=#9400D3>*How to use git workflow*</font>
###-------------------------------------
####First
#####--- Someone creates the central repository
![image](https://segmentfault.com/image?src=http://static.ixirong.com/pic/gitflow/git-workflow-svn-initialize.png&objectId=1190000002918123&token=87ea7a312eea3ac60744ef5997f686c7)

---
####Second
#####--- Other developer creates a local copy of the entire project.
![image](https://segmentfault.com/image?src=http://static.ixirong.com/pic/gitflow/git-workflow-svn-clone.png&objectId=1190000002918123&token=74230960454bff61cc38e28016dde2c4)  

---
####Third
#####--- Make changes and commit
![image](https://segmentfault.com/image?src=http://static.ixirong.com/pic/gitflow/git-workflow-svn-1.png&objectId=1190000002918123&token=318dfc4b7192333b4d04457a8dd58de3)
######(This happens in our local repository.)

---
####Forth
#####---Push new commits to central repository
![image](https://segmentfault.com/image?src=http://static.ixirong.com/pic/gitflow/git-workflow-svn-3.png&objectId=1190000002918123&token=093a21ecc0bdbebb13f61585151f72a7)
######(These changes will share with other developers on the central repository.)

---
####Finally
#####---Managing conflicts
######(To solve the problem , Git will pause the rebasing process and give you a chance to manually resolve the conflicts. T)
![image](https://segmentfault.com/image?src=http://static.ixirong.com/pic/gitflow/git-workflow-svn-8.png&objectId=1190000002918123&token=e9fff79b5189565698de39b45d42551d)

---
