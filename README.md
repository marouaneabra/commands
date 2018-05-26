# Useful Commands

### Downloading and Untarring a file

Get the tar file

```
wget <tar file>
```
Download the tar file on your local machine

```
tar xvzf <tar file>
```
Delete the tar file after a succesful download

```
rm <tar file>
```

### Forking your own repo

Clone the new repo where the fork is going to happen

Add the repo to be forked as an Upstream Remote inside the new repo using

```
git remote add upstream <repo github link>
```

Pull the changes to the new repo

```
git pull upstream master
```

then

```
git push origin master
```

Note: if fatal error stating that merge of unrelated histories occurs, use

```
--allow-unrelated-histories
```

### Branching using git

Create branch

```
git checkout -b BRANCH
```

Switch branch

```
git checkout BRANCH
```

Switch to master branch

```
git checkout origin master
```

Get changes

```
git pull origin master
```

Push changes

```
git push origin BRANCH
```

Then manually submit a pull request to repo on Github