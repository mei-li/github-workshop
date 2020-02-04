# github-workshop
Github flow workshop

## Install git

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Become a collaborator in this repository
Come over to me to add you as a collaborator of this repository.

## Part I  - Github flow
### Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the repository to your machine. Go to your GitHub account, open the repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

### Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd github-workshop
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```
The branch will be to edit the file `commit-messages.md` in this repository and add your tips. So name it something relevant, including your name so that it is not the same with the rest of the people.

For example:
```
git checkout -b add-george-tips
```

### Make necessary changes and commit those changes

Now open `commit-messages.md` file in a text editor, and add your tips for writing good commit messages. 

<img align="right" width="450" src="assets/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add commit-messages.md
```

Now commit those changes with a nice commit message using the `git commit` command:
```
git commit -m "Add HERE your commit message"
```
replacing the text in `""` with your commit message.

### Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

### Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button (in Gitlab it is called `Merge request`)
Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

### Get a review
Now exchange reviewes with a person sitting near you. In github you can assign them as a reviewer in your Pull Request or tell them your Pull request number.

### Submit a review
Github offers 2 ways of reviewing, either with `single comments` or with `start review` that let you add multiple comments that will be visible when selecting the `submit review`. This way they will show all together. Use the `signle comments`

Add a review and ask the author to make some change. A review should be respectful and explain the reason that the change is needed, giving context. 

### Address comments

Address the comments of the review or reply to them explaining your reasoning. If see that the suggested changes make sense, make the changes locally and push the updates. Use a meaningful commit message when addressing the comments eg. `Improve wording` instead of `addressing comments`

### Where to go from here?

Congrats!  You just completed the standard clone -> edit -> PR_ workflow that helps you collaborate and share knowledge with your team!


### [Additional material]
[Gitlab workflow](https://about.gitlab.com/blog/2017/03/17/demo-mastering-code-review-with-gitlab/)

