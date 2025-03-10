# HacktoberFest-2021
Repository designed for beginners to contribute to open-source 


## ❓ What is Hacktoberfest 2021?

Hacktoberfest 2021 is a month long virtual festival event to celebrate open source contributions presented by Digital Ocean, Intel and DEV. It is the easiest way to get into open source!
https://hacktoberfest.digitalocean.com/

During the entire month of October 2021, all you have to do is contribute to any open source projects and open at least 4 pull requests. Yes, any project and any kind of contributions. You don’t need to be an expert in programming or coding. It can be a be a bug fix, improvement, or even a documentation change! And win an awesome T-shirt and awesome stickers.

## 😕 Why Should I Contribute?

The Hacktoberfest’s simple plain objective is:

    Support open source and earn a limited edition T-shirt!

But, it’s not just about the t-shirts or stickers. Its about supporting open source. Its about celebrating open source, and giving it back. If you’ve never contributed to open source before, this is the perfect time to get started because Hacktoberfest provides a large list of available contribution opportunities (and yes, there are always plenty for beginners too).

## 👌 What Can I Contribute?

Hacktoberfest® is open to everyone in our global community. Whether you’re a developer, student learning to code, event host, or company of any size, you can help drive growth of open source and make positive contributions to an ever-growing community. All backgrounds and skill levels are encouraged to complete the challenge.

It doesn’t need to be code. It can be even documentation. Or spelling fix.

You can contribute to any open source project hosted on Github.com and contribute anything between October 1 to October 31 midnight in 2021. You will find plenty of issues labeled with hacktoberfest or good-first-issue etc on Github. These will be the simple ones most probably and easy to fix.

## How to contribute
Submit your pull request here for HacktoberFest-2021 in any language you prefer.
You can submit any project of your choice.
Read the instructions below, follow them.

### Must do things: 

1. Update project list in [index.html](https://github.com/shradhaagarwal01/HacktoberFest-2021/blob/main/index.html) in this format

 ```html
 <li><h2>{Project Number}: {Project Name}</h2><iframe src={link to index file} width="100%" height="500" frameBorder='0'></iframe></li>
 ```
2. Update folder structure [here](# folder structure)
   Take help from this [article](https://medium.com/@shradhaagarwal01/how-to-represent-folder-directory-tree-with-links-in-github-readme-in-less-than-5-minutes-84230fdcb1)

## Folder Structure

### Projects

* [email-signature-template/](./Projects/email-signature-template)
  * [email-signature-template.html](./Projects/email-signature-template/email-signature-template.html)
* [survey-form/](./Projects/survey-form)
  * [index.html](./Projects/survey-form/index.html)
  * [style.css](./Projects/survey-form/style.css)
* [visiting_fbform/](./Projects/visiting_fbform)
  * [feedback.html](./Projects/visiting_fbform/feedback.html)


## Getting Started

## Instructions:

*Make sure you have a GitHub account. In case you don't have one, you can create your account by visiting https://github.com/ and clicking on ``Sign up`` option at the top right corner.*

### 1. Register yourself for Hacktoberfest
#### Link to register: https://hacktoberfest.digitalocean.com/
Click on "Start Hacking" and add your GitHub account.

### 2. Star and Fork this Repository
#### You can star and fork this repository on GitHub by navigating at the top of this repository.

GitHub repository URLs will reference both the username associated with the owner of the repository, as well as the repository name. For example, acmbvp is the owner of the Hacktoberfest repository, so the GitHub URL for this project is:

https://github.com/shradhaagarwal01/HacktoberFest-2021.git

When you’re on the main page of a repository, you’ll see a button to "Star" and “Fork” the repository on the upper right-hand side of the page, underneath your user icon.

### 3. Clone the Repository

To make your own local copy of the repository you would like to contribute to, let’s first open up a terminal window.

We’ll use the `git clone`  command along with the URL that points to your fork of the repository.

This URL will be similar to the URL above, except now it will end with `.git.` In the cloud_haiku example above, the URL will look like this:
https://github.com/your-username/HacktoberFest-2021.git

You can alternatively copy the URL by using the green “Clone or download” button from your repository page that you just forked from the original repository page. Once you click the button, you’ll be able to copy the URL by clicking the binder button next to the URL:

Once we have the URL, we’re ready to clone the repository. To do this, we’ll combine the git clone command with the repository URL from the command line in a terminal window:

`git clone https://github.com/your-username/Hacktoberfest.git`


### 4. Create a New Branch

To create your branch, from your terminal window, change your directory so that you are working in the directory of the repository. Be sure to use the actual name of the repository (i.e. Hacktoberfest) to switch into that directory.

#####    `cd HacktoberFest-2021`

Now, we’ll create our new branch with the git branch command. Make sure you name it descriptively so that others working on the project understand what you are working on.


##### `git branch new-branch`

Now that our new branch is created, we can switch to make sure that we are working on that branch by using the git checkout command:

##### ` git checkout new-branch `

Once you enter the git `checkout` command, you will receive the following output:

######  `Output:`
#####  `Switched to branch 'new-branch' `


At this point, you can now modify existing files or add new files to the project on your own branch.

#### Make Changes Locally

Once you have modified existing files or added new files to the project, you can add them to your local repository, which you can do with the git add command. Let’s add the -A flag to add all changes that we have made:

##### ` git add -A ` or ` git add . `

Next, we’ll want to record the changes that we made to the repository with the git commit command.

*The commit message is an important aspect of your code contribution; it helps the other contributors fully understand the change you have made, why you made it, and how significant it is. Additionally, commit messages provide a historical record of the changes for the project at large, helping future contributors along the way.*


If you have a very short message, you can record that with the -m flag and the message in quotes:

###### ` Example: `
##### ` git commit -m "Updated Readme.md" `

###### At this point you can use the git push command to push the changes to the current branch of your forked repository:
###### ` Example:`
##### ` git push --set-upstream origin new-branch `

### 5. Update Local Repository

*While working on a project alongside other contributors, it is important for you to keep your local repository up-to-date with the project as you don’t want to make a pull request for code that will cause conflicts. To keep your local copy of the code base updated, you’ll need to sync changes.*

We’ll first go over configuring a remote for the fork, then syncing the fork.

### 6. Configure a Remote for the Fork

Next up, you’ll have to specify a new remote upstream repository for us to sync with the fork. This will be the original repository that you forked from. you’ll have to do this with the git remote add command.

##### ` git remote add upstream https://github.com/shradhaagarwal01/HacktoberFest-2021.git`

In this example, // upstream // is the shortname we have supplied for the remote repository since in terms of Git, “upstream” refers to the repository that you cloned from. If you want to add a remote pointer to the repository of a collaborator, you may want to provide that collaborator’s username or a shortened nickname for the shortname.

### 7. Sync the Fork

Once you have configured a remote that references the upstream and original repository on GitHub, you are ready to sync your fork of the repository to keep it up-to-date.
To sync your fork, from the directory of your local repository in a terminal window, you’ll have to use the // git fetch // command to fetch the branches along with their respective commits from the upstream repository. Since you used the shortname “upstream” to refer to the upstream repository, you’ll have to pass that to the command:

##### ` git fetch upstream `

Switch to the local master branch of our repository:

##### ` git checkout master `

Now merge any changes that were made in the original repository’s master branch, that you will access through your local upstream/master branch, with your local master branch:

##### ` git merge upstream/master `

### 8. Create Pull Request

At this point, you are ready to make a pull request to the original repository.

Navigate to your forked repository, and press the “New pull request” button on your left-hand side of your Repo page.

# Hurray! You just got closer to completing your Hacktoberfest challenge.

# Contributers aka Hackers

<a href="https://github.com/shradhaagarwal01/HacktoberFest-2021/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=shradhaagarwal01/HacktoberFest-2021" />
</a>


Note : A star and a follow would be much appreciated. For any queries, feel free to reach out to me.
Happy Hacking!
