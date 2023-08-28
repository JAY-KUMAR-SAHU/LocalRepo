# local to remote
1. make a directory in local <br> <b>$ mkdir LocalRepo</b> <br>
2. go into that directory <br> <b>$ cd LocalRepo</b> <br>
3. see hidden files to find .git <br> <b> $ dir -force </b> (Windows) <br> <b> $ ls -a </b> <br>
4. initialize empty git repository in path/LocalRepo/.git/ <br> $ git init <br>
_____|<br>
_____|<br>
5. create files <br>
_____|<br>
_____|<br>
6. add all files <br> <b>$ git add .</b>
7. commit all files <br> <b>$ git commit -m "Initial Commit"</b>
8. add remote as 'origin' with repo link <br> <b> $ git remote add origin https://github.com/JAY-KUMAR-SAHU/LocalRepo.git</b> <br>
9. to verify remote <br> <b> $ git remote -v </b> <br>
10. to check branch <br> <b>$ git branch</b> <br>
11. to rename branch (if required) <br> <b> $ git branch -M main </b> <br>
12. to push in remote branch <br> <b> $ git push origin main </b> <br> //__________________________ OR _________________________\\ <br> to set upstream remote branch <br> <b> $ git push -u origin main </b><br><br>
13. Check status <br> <b>$ git status</b>