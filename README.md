# github-workshop
Github flow workshop

## Install git

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Become a collaborator in this repository
Come here to write your github handle so you can be added as a collaborator of this repository.


## Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/first-contributions.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd github-workshop
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Contributors list"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button (in Gitlab it is called `Merge request`)
Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

## Get a review
Ask a person next to you to look into your Pull request. Tell them your Pull request number or add them as a reviewer

## Submit a review
Github offers 2 ways of reviewing, either with `single comments` or with `start review` that let you add multiple comments that will be visible when selecting the `submit review`. This way they will show all together. 

Add a review and ask the author to make some change. A review should be respectful and explain the reason that the change is needed, giving context. Eg.
  

## Where to go from here?

Congrats!  You just completed the standard clone -> edit -> PR_ workflow that helps you collaborate and share knowledge with your team!

### [Additional material]
[Gitlab workflow](https://about.gitlab.com/blog/2017/03/17/demo-mastering-code-review-with-gitlab/)

