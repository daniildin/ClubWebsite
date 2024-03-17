# BMCC Programming Club Website Project
Welcome to the Borough of Manhattan Community College Programming Club's website repository! This project is open source and anyone the club is welcome to contribute! Feel free to join this organization if you are a club member (or alumni!)

For a list of current goals, feel free to look at the issues, and consider joining our Github Organization (Club Members/Alumni only). Before contributing, please read and follow the steps outlined in the contribution section.Contributing
If you are interested in contributing, that is great!

Here you'll find out how you can contribute to this project, including the steps for making contributions and some resources to study if you're unfamiliar with this process or some of the terminology. You can go [here](# More-Resources) to find explanations for why we'd like you to follow each step when making contributions.

# How can I contribute?
1. Check to see if there are any open issues. If not, you can suggest something you'd like to work on. 
2. Fork this repo and make a branch titled after the feature you're working on, e.g. "recolor-navbar".
3. Update your fork and submit a pull request, tagging contributors.
   
Once reviewed, your request will be either accepted or denied.

# Contribution Notes
[1] Issues are a good place for us to discuss the feature being implemented, and how we think it should look/work. You can also look through them to figure out if people are already working on a particular feature. This will prevent two people from accidentally making the same thing, or you can reach out to someone already working on that feature and figure out how you could work together.

[2] Forking the project creates a copy of the repository under your Github ID, allowing you greater permissions when editing (making branches, pushing changes, etc). It is much easier for us to review smaller chunks of code, hence making a branch dedicated to one change.

[3] Using git fetch only updates your local repository with your remote repository. If there have been changes to the main repository since you made your fork, they would not reach your repository automatically, and of course some of those changes could present conflicts with your code or vice versa. There are three ways to update (read here):

The easiest way is to go to your forked repository, and click "Sync Fork".

If you have the Github CLI installed you can use the command $ gh repo sync owner/cli-fork -b BRANCH_NAME

You can fetch the "upstream" repository and then merge it into your own local repo via:

$ git fetch upstream

$ git checkout main

$ git merge upstream/main

[4] Something to note if you have not submitted pull requests before is that to 'edit' your pull request, all you need to do is:

Update your local branch.
Push to your remote branch.
Your changes should now be updated in the pull request.

# More Resources
Here are a few resources to learn the main ideas behind contributing. We will be covering this during club meetings, so don't feel detered from reaching out and asking questions!

Learning about git in general:
[W3schools](https://www.w3schools.com/git/default.asp) has a great walkthrough for beginners! 
Pro Git: This is a book that really covers just about everything. Don't feel the need to read through it, but it might be best to use it as a reference to look up things you don't know.
Consider downloading the Github Desktop App. If you're totally unfamiliar with the command line and the commands themselves, this is a useful tool to make the basics a little more beginner friendly. Make sure that you still study the concepts though so you understand what you're doing.
GitKraken is similar very powerful tool. I have no experience with it personally but the visualizer seems quite useful and it is free for students.
Also, see their gitlens plugin for VSCode.
Learn Git Branching is a pretty cool site that walks you through git in an interactive and visual way.
