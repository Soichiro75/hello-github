# hello-github

This is my self-study repository by using [GitHubGuides](https://guides.github.com/).

## Install (ver. Mac)

### install by using homebrew

If your Mac is not installed Homebrew, you can install as follows:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
For more details, see [Homebrew Page](http://brew.sh/index.html)


You can install Git easily by using Homebrew as follows:

```
brew update
brew install git
git -version
```

### Set up Git

Then you should setting up Git as follows:

```
git config -l
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL ADDRESS"
git config -l
```

The "YOUR EMAIL ADDRESS" should be same your GitHub email address(*1).

(*1: You can see the GitHub email address on GitHub. Your GitHut page > Your Profile Picture/Settings > Personal settings/Emails/Email)

Because Contributions(*2) are not counted if the email addresses are not same. 

(*2: The Contributions are on your Github profile page. It is greph that show your action record.)

For more details, see [Set Up Git](https://help.github.com/articles/set-up-git/), and [Why are my contributions not showing up on my profile?](https://help.github.com/articles/why-are-my-contributions-not-showing-up-on-my-profile/)


