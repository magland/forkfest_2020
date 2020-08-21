# forkfest_2020

Welcome to Forkfest 2020! Here we will learn to use git and github to collaboratively fork some git repositories with friends.

### Step 1. Create a new github repo

### Step 2. Clone that repo onto your local machine

```bash
cd git (or whatever)
git clone https://github.com/<username>/<repo>
cd <repo>
```

### Step 3. Push some content into your repo -- use vscode

```bash
# you must have Visual Studio Code installed
cd <repo>
code .
```

You should install the awesome gitlens vscode extension (eamodio.gitlens)

You can add/commit/push from the vscode gui ... or you can use the command line:

```bash
git add <new-file>
git commit -m "new commit message"
git push # you will be prompted for you user name and password
```

### Step 4. Share you repo URL with the other folks in the fork fest!

Send the the URL of your repo

### Step 5. Check out the other repos that were shared with you!

View it on the github website

### Step 6. Fork one of the other repos!

Click the fork button the github website

### Step 7. Clone that forked repo.

```bash
git clone https://github.com/<you>/<forkedrepo>
```

Note: the forked repo is under your user name, not your friend's.

### Step 8. Modify that forked repo (or add some stuff) and then push to your forked repo.

Make some improvements! Then add the changes, commit the changes, and push to your forked repo.

### Step 9. Make a pull request.

Use the github website to make a pull request, to ask your friend to merge your changes into their repo.

### Step 10. Review the pull request(s) made on your repo. And possible accept the merge request (aka pull request)

Use the github website GUI to review the changes, make comments, and ultimately merge the changes suggested by your friends.

### Step 11. Pull the changes that your friends made into your local repo

```bash
cd <repo>
git pull
```

(or use the vscode GUI to pull)





