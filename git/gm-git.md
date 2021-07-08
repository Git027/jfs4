:beginner: **git configuration**  
```sh
git config --list
git config --global list
git config --global user.name mlgit4
git config --global user.email mlgit4@gmail.com
```

:beginner: **configuring vs code as the editor**  
```sh

core.editor="C:\Users\Enzo\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
```

:beginner: **creating local repository**  
```sh
git init  
git status
# file in working directory
# Untracked files
echo "Smile with the Sun" >> mapo.txt
git status
# file in staging area
# Changes to be committed:
#   (use "git restore --staged <file>..." to unstage)
#         new file:   mapo.txt
git add mapo.txt
# file moved into repository
git commit -am "Write Poem, Giddygit status"
rm mapo.txt
git status
#   modified:   mapo.txt

```

:beginner: **logging**  
```sh
git log
git log --oneline
```

:beginner: **checkout**  
```sh
git checkout b9d04ad73ac44bb41d9ce4a65d4df313f7c083e6
```



