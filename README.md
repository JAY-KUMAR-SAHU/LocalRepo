<!-- <style> -->
    p { color: green; }
<!-- </style> -->
# local to remote
1. make a directory in local <br> $ mkdir LocalRepo</p> <br>
2. go into that directory <br> <p>$ cd LocalRepo</p> <br>
3. see hidden files to find .git <br> <p> $ dir -force </p> (Windows) <br> <p> $ ls -a </p> <br>
4. initialize empty git repository in path/LocalRepo/.git/ <br> $ git init <br>
_____|<br>
_____|<br>
5. create files <br>
_____|<br>
_____|<br>
6. add all files <br> <p>$ git add .</p>
7. commit all files <br> <p>$ git commit -m "Initial Commit"</p>
8. add remote as 'origin' with repo link <br> <p> $ git remote add origin https://github.com/JAY-KUMAR-SAHU/LocalRepo.git</p> <br>
9. to verify remote <br> <p> $ git remote -v </p> <br>
10. to check branch <br> <p>$ git branch</p> <br>
11. to rename branch (if required) <br> <b> $ git branch -M main </b> <br>
12. to push in remote branch <br> <p> $ git push origin main </p> <br>
//__________________________ OR _________________________\\ <br>
 to set upstream remote branch <br> <p> $ git push -u origin main </p> <br>
<br>
13. Check status <br> <p>$ git status</p>