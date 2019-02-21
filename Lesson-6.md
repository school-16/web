# Git :octocat:

## Github.com

1. [github.com](https://github.com) сайтында теркәлегез.
2. school-16 организациясенә керегез.
3. Почтага килгән хатлар аша теркәлүне һәм организациягә керүне раслагыз.
4. Беренче репозиториягезне ясагыз.

## Башлау

1. [git](https://git-scm.com/downloads) программасын уранштырышыз.
2. VS Code-ка кереп `Ctrl + Shift + P` төймәләренә басып, (`Select Default Shell`) теримнал итеп `bash`ны сайлагыз.
3. Терминалны ачыгыз (<pre>Ctrl + `</pre>)

## Gitны көйләү

```bash
git config --global user.name "Your Name"
git config --global user.email your_email@example.com
```

## Репозиторий белән эш

```bash
git init
git add index.html images styles.css
git commit -m 'Initialize repository with previous files'
```

## Читтәге репозиторийны стәргә
```bash
git remote add ----
git push -u origin master
```

## Тармаклану

```bash
git branch branch-name
git checkout bracnh-name
```

```bash
git add .
git commit -m 'Make some changes'
git push -u origin branch-name
```

```bash
git pull origin master
```