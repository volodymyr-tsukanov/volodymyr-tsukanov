<h1 align="center">Hello everyone! <img src="" width="28px" alt="👋"></h1>

<p align="center">
    <b>Welcome to my page!</b><br><br>
    <i>I'm Volodymyr<br></i><br>
</p>


### Links
[![LinkedIn](https://img.shields.io/badge/LinkedIn-393646?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/volodymyr-tsukanov-4b624a299)

### Languages
[![Java](https://img.shields.io/badge/java-393646?style=for-the-badge&logo=openjdk)](https://github.com/volodymyr-tsukanov)
[![C#](https://img.shields.io/badge/c%23-393646?style=for-the-badge&logo=csharp)](https://github.com/volodymyr-tsukanov)
[![DotNet](https://img.shields.io/badge/dotNet-393646?style=for-the-badge&logo=dotnet)](https://github.com/volodymyr-tsukanov)
[![C++](https://img.shields.io/badge/c++-393646?style=for-the-badge&logo=cplusplus)](https://github.com/volodymyr-tsukanov/virtual-ekosystem)
[![C](https://img.shields.io/badge/c-393646?style=for-the-badge&logo=c)](https://github.com/volodymyr-tsukanov)
[![Python](https://img.shields.io/badge/python-393646?style=for-the-badge&logo=python)](https://github.com/volodymyr-tsukanov)
[![Php](https://img.shields.io/badge/php-393646?style=for-the-badge&logo=php)](https://github.com/volodymyr-tsukanov)

[![HTML](https://img.shields.io/badge/html-393646?style=for-the-badge&logo=html5)](https://github.com/volodymyr-tsukanov)
[![CSS](https://img.shields.io/badge/css-393646?style=for-the-badge&logo=css3)](https://github.com/volodymyr-tsukanov)
[![SQL](https://img.shields.io/badge/SQL-393646?style=for-the-badge&logo=postgresql)](https://github.com/volodymyr-tsukanov/bazy-danych-project-apple)

[![Bash](https://img.shields.io/badge/bash-393646?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://github.com/volodymyr-tsukanov)
[![Batch](https://img.shields.io/badge/batch-393646?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://github.com/volodymyr-tsukanov)


### IDE & Software
[![VisualStudio](https://img.shields.io/badge/Visual%20Studio-393646?style=for-the-badge&logo=visualstudio&logoColor=blue)](https://github.com/volodymyr-tsukanov)
[![IntelliJIDEA](https://img.shields.io/badge/Intellij%20Idea-393646?style=for-the-badge&logo=intellijidea&logoColor=violet)](https://github.com/volodymyr-tsukanov)
[![AndroidStudio](https://img.shields.io/badge/Android%20Studio-393646?style=for-the-badge&logo=androidstudio)](https://github.com/volodymyr-tsukanov)
[![SQLDeveloper](https://img.shields.io/badge/Oracle%20SQL%20Developer-393646?style=for-the-badge&logo=oracle)](https://github.com/volodymyr-tsukanov/bazy-danych-project-apple)
[![NetBeans](https://img.shields.io/badge/NetBeans-393646?style=for-the-badge&logo=apachenetbeanside)](https://github.com/volodymyr-tsukanov)
[![Qt](https://img.shields.io/badge/Qt-393646?style=for-the-badge&logo=qt)](https://github.com/volodymyr-tsukanov/virtual-ekosystem)
[![Eclipse](https://img.shields.io/badge/Eclipse-393646?style=for-the-badge&logo=eclipseide)](https://github.com/volodymyr-tsukanov)

[![CodeBlocks](https://img.shields.io/badge/CodeBlocks-393646?style=for-the-badge&logo=codeblocks)](https://github.com/volodymyr-tsukanov/NList)
[![MonoDevelop](https://img.shields.io/badge/MonoDevelop-393646?style=for-the-badge&logo=monodevelop)](https://github.com/volodymyr-tsukanov)

[![Unity](https://img.shields.io/badge/Unity-393646?style=for-the-badge&logo=unity)](https://github.com/volodymyr-tsukanov)
[![Godot](https://img.shields.io/badge/Godot-393646?style=for-the-badge&logo=godotengine)](https://github.com/volodymyr-tsukanov)
[![Unreal](https://img.shields.io/badge/Unreal-393646?style=for-the-badge&logo=unrealengine)](https://github.com/volodymyr-tsukanov)
[![GameMaker](https://img.shields.io/badge/GameMaker-393646?style=for-the-badge&logo=gamemaker)](https://github.com/volodymyr-tsukanov)

[![Git](https://img.shields.io/badge/Git-393646?style=for-the-badge&logo=git)](https://github.com/volodymyr-tsukanov)


### OS
[![Android](https://img.shields.io/badge/Android-393646?style=for-the-badge&logo=android)](https://github.com/volodymyr-tsukanov)
[![Windows](https://img.shields.io/badge/Windows-393646?style=for-the-badge&logo=Windows)](https://github.com/volodymyr-tsukanov)
[![Linux](https://img.shields.io/badge/Linux-393646?style=for-the-badge&logo=kalilinux)](https://github.com/volodymyr-tsukanov)
[![Mac](https://img.shields.io/badge/Mac-393646?style=for-the-badge&logo=macos)](https://github.com/volodymyr-tsukanov)
</br></br>


<details>
<summary>Git shortcuts</summary>

## Setup
### Protect sensitive data from being stored
```
git config --global credential.helper ""
```

## Aliases
### add & commit
```
git config --global alias.ac '!git add -A && git commit -m'
```
### push to remote
```
git config --global alias.pmc 'push -u morig HEAD'
```
it is possible to use only `git push` after `git pmc`

## Get updates from remote
### Fetch & merge (leaves merge commit)
```
git fetch morig
git merge morig/<branch>
```
### Fetch & pull (on current branch, no merge commit)
```
git fetch morig
git pull
```
### Switch to remote branch (after `git fetch`, if no local branch)
```
git switch --track morig/<branch>
// or
git checkout --track morig/<branch>
```

## Push to remote
```
git add .
git commit -m 'msg'
git push morig <branch>
```

## Branches
### New branch from current branch
```
git branch <new-branch>
// or
git switch -c <new-branch>
// or
git checkout -b <new-branch>
```
### Switch branch
```
git switch <branch>
// or
git checkout <branch>
```
### Switch to previous branch (discard changes made with `git checkout <commit>` and not saved with `git switch -c`)
```
git switch -
```
### Rename (move) branch
```
git branch -m <old-branch> <new-branch>
```
### Delete branch
```
git branch -d <branch-to-delete>
```

## Traveling in time
### Checkout commit by hash from `git log`
```
git checkout <commit-hash>
```

## Stash
### Save
```
git stash save <save-name>
```
### Load
```
git stash list
git apply <index>
```

## Commit history (log)
### See commit history for current branch
```
git log --oneline --graph
```

## Revert
### Revert last n commits
```
git revert HEAD~<n>..HEAD
```
### Revert specified commit (by it`s hash)
```
git revert <commit-hash>
```

## Reset (for local use or force push)
### Delete last commit
```
git reset --hard HEAD^
```
### Delete last n commits
```
git reset --hard HEAD~<n>
```
### Delete specified commit (by it`s hash)
```
git reset --hard <commit-hash>
```
### Choose specific commit to delete from n last commits (opens text editor)
```
git rebase
// or
git rebase -i HEAD~<n>
```
### Force push to apply changes
```
git push morig <branch> --force
```

## Change branch tracking remote to morig
### Shows info about tracking remote (for current branch)
```
git branch -vv
```
### Alternative to `git switch --track` (when branch is alredy exists)
```
git branch --set-upstream-to=morig/<branch>
```

# .gitignore
```
<file>
<folder>/**	# with it content
*.<extention>
*<pattern>*	# all files that contains pattern
```

# README.md template:
# <repo-name>
<programming-language>, <IDE>;<description></br></br>


Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

[cc-by-nc]: http://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
</details>

<details>
<summary>Other</summary>
<h4 align="left">Default stuff<br></h4>
  
- 👋 Hi, I’m @volodymyr-tsukanov
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
</details>

<!---
volodymyr-tsukanov/volodymyr-tsukanov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.



Templates
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>


## About me

Hi, I'm Mona. You might recognize me as GitHub's mascot.

| Rank | Languages |
|-----:|-----------|
|     1| Javascript|
|     2| Python    |
|     3| SQL       |
--->
