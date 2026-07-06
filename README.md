# Git Course With Elzeroo

![Illustrative image](src/imgs/Diagram.png)
<br>

### To Clone Repo
```bash
$ git clone [Repo_URL]
```

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
----
### If you work with Team
### So , You want update your **Local Repo** from **Remote Repo** (For Changes Check)
```bash
$ git pull origin
```
---
### Git Configuration Part (Not Important)
#### Opens the Git configuration help page. 
```bash
$ git help config
```
#### Lists all Git configuration settings.
```bash
$ git config -l
```

#### Shows the global Git email address. (for getter value)
```bash
$ git config --global [user.email]
```

#### Sets the global Git email address. (for setter value)
```bash
$ git config --global [user.email] "hassanhashish33@gmail.com"
```

#### Opens the global Git configuration file for editing.
```bash
$ git config --global --edit
```
---
### Create Public Key and Use it 
#### 1. Generates a new RSA SSH key pair with a 4096-bit key.
```bash
$ ssh-keygen -t rsa -b 4096 -C "hassanhashish33@gmail.com"
```
##### 2. Enter file in which to save the key : **click Enter**
##### 3. Enter passphrase Like : 321
##### 4. in the Result like : Your public key has been saved in [**etc/etc.pub**]
#### 5. Displays the public SSH key.
```bash
$ cat [etc/etc.pub]
```
##### 6. Copy All Result and Save it in **Key Deploy (Github)**
#### 7. Tests the SSH authentication with GitHub.
 ```bash
$ cat [etc/etc.pub]
```
---
### Repo From Existing Project 
#### in this directory 
 ```bash
$ git init
```
#### Complete the Normal Steps
---



