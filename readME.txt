GitHub Repository Assignment

Creating files to upload to a repository and share on GitHub.

Steps

C:\Users\abert>cd desktop

C:\Users\abert\Desktop>md GitHubRepoAssignment

C:\Users\abert\Desktop>cd GitHubRepoAssignment

C:\Users\abert\Desktop\GitHubRepoAssignment>git init
Initialized empty Git repository in C:/Users/abert/Desktop/GitHubRepoAssignment/.git/

C:\Users\abert\Desktop\GitHubRepoAssignment>copy NUL readME.txt
        1 file(s) copied.

C:\Users\abert\Desktop\GitHubRepoAssignment>readMe.txt

C:\Users\abert\Desktop\GitHubRepoAssignment>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readME.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\abert\Desktop\GitHubRepoAssignment>git add readME.txt

C:\Users\abert\Desktop\GitHubRepoAssignment>git commit -m "1st addition"
[master (root-commit) b017798] 1st addition
 1 file changed, 3 insertions(+)
 create mode 100644 readME.txt

C:\Users\abert\Desktop\GitHubRepoAssignment>git remote add origin https://github.com/Avocados39/GitHubRepoAssignment.git

C:\Users\abert\Desktop\GitHubRepoAssignment>git push -u origin master
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Avocados39/GitHubRepoAssignment.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\Users\abert\Desktop\GitHubRepoAssignment>copy NUL GitHubRepoAssignment.txt
        1 file(s) copied.

C:\Users\abert\Desktop\GitHubRepoAssignment>GitHubRepoAssignment.txt