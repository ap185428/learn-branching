# learn-branching in github
This line added in main branch
This line added in branch-1
This line added in branch-2
Hello patch - 1

## did what

### part - 1
created 2 branches from main ---> branch1 and branch2 <br>
made changes in same file i.e readme.md in branch1 and branch2 <br>
<br>
created pull request from branch1 <br>
merged pull request from branch1 ---> changes got merged easily <br>
<br>
created pull request from branch2 ---> got not able to merge automatically, you can still create a pull request <br>
created pull request ---> option to resolve conflicts ---> changes of main file and branch-2 shown ---> select whichever way you want ---> click on conflicts resolved ---> then branch can be merged <br>

### part - 2
created 2 branches from main ---> patch1 and patch2 <br>
<br>
created new file lets say file1 in branch1 <br>
created pull request from branch1 <br>
merged pull request from branch1 ---> changes got merged easily <br>
<br>
created new file lets say file2 in branch2 <br>
created pull request from branch2 ---> got no merge conflicts and pull request got merged

### part - 3
This branch i.e Feature branch will try to make a pull request to main branch and see if the event which has been specified in patch branch gets triggered or not.
The event which had on : branch : main did not get triggered.
The workflow file has to be present in that location for that event to get triggered.

Next made a commit in branch patch1 which had the event on : branch : main, this workflow got triggered. 

Created another branch patch-2 and made a pull request to path-1. The workflow on: branch: master did not get triggered.
