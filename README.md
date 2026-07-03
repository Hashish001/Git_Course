# Git Course With Elzeroo

![Illustrative image](src/imgs/Diagram.png)
<br>
### To Review Status

```bash
$ git status
```

### Add file from **Working_Dirictory** to **Staging Area**

```bash
$ git add README.md
```
### Remove file from file from **Staging Area** to **Working_Dirictory** 

```bash
$ git rm --cashed README.md
```

### from **Staging Area** to **Local Repo**

```bash
$ git commit -m "Create the main project stucture"
```

### Show all **Local Branches** in **Local only**

```bash
$ git branch
```
---
### push from **Local Repo** to **Remote Repo**

```bash
$ git push [RemoteName] [BranchName]
```
#### LIKE
```bash
$ git push origin main
```
---

### Show all **Saved RemoteName**

```bash
$ git remote -v
```
### if it not exist

```bash
$ git remote add [origin] https://github.com/Hashish001/Git_Course.git
```

#### then
```bash
$ git push origin main
```



