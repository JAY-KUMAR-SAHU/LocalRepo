# local to remote
1. make a directory in local <br> $ mkdir LocalRepo <br>
2. go into that directory <br> $ cd LocalRepo <br>
3. see hidden files to find .git <br> $ dir -force (Windows) <br> $ ls -a <br>
4. initialize empty git repository in path/LocalRepo/.git/ <br> $ git init <br>
|<br>
|<br>
5. create files <br>
|<br>
|<br>
6. add all files <br> $ git add .
7. commit all files <br> $ git commit -m "Initial Commit"
8. add remote as 'origin' with link <br> git remote add origin https://github.com/JAY-KUMAR-SAHU/LocalRepo.git <br>
9. to verify remote <br> $ git rempote -v <br>
10. to check branch <br> $ git branch <br>
11. to rename branch <br> $ git rempote -v <br>
12. to push in remote branch <br> git push origin main <br>
//__________________________ OR _________________________\\
 to set upstream remote branch <br> git push -u origin main <br>
<br>
13. Check status <br> $ git status