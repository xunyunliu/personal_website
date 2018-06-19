## How to update your personal website with git commands

In your personal website folder, run the following commands:

```bash
git add .
git commit -m "Some Message"
git push -u origin master
```

The following command is used to rebuild the HTML files in the public folder:

```bash
hugo
```

Now commit changes in the public folder and now your website is updated:

```bash
git add .
git commit -m "Build website"
git push -u origin master

```



## How to update your personal website with gitkraken

1. make any changes to your website
2. perform hugo at the root level
3. commit and push changes from the public folder
4. commit and push changes from the root folder

### How to update the academic theme

Before updating for the first time, the remote origin repository should be renamed to upstream:

```bash
cd themes/academic
git remote rename origin upstream

```

To list available updates:

```bash
cd themes/academic
git fetch upstream
git log --pretty=oneline --abbrev-commit --decorate HEAD..upstream/master

```

Then, update by running:

`git pull upstream`