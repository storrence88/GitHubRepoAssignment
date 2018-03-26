storr@Steven-XPS MINGW64 ~/desktop
$ cd GitHubRepoAssignment

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment
$ ls

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment
$ cd ..

storr@Steven-XPS MINGW64 ~/desktop
$ ls
'Coding 101'/   desktop.ini   GitHubRepoAssignment/   test/

storr@Steven-XPS MINGW64 ~/desktop
$ cd GitHubRepoAssignment

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment
$ git init
Initialized empty Git repository in C:/Users/storr/Desktop/GitHubRepoAssignment/.git/

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment (master)
$ touch readMe.md

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readMe.md

nothing added to commit but untracked files present (use "git add" to track)

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment (master)
$ git add .

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment (master)
$ git commit -m "added the readMe commit"
[master (root-commit) 3f19d30] added the readMe commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readMe.md

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment (master)
$ git remote add origin https://github.com/storrence88/GitHubRepoAssignment.git

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment (master)
$ git push -u origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 223 bytes | 111.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/storrence88/GitHubRepoAssignment.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

storr@Steven-XPS MINGW64 ~/desktop/GitHubRepoAssignment (master)
