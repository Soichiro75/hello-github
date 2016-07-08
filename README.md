# hello-github

This is my self-study repository by using [GitHubGuides](https://guides.github.com/).

## Install (ver. Mac)

### Install by Using Homebrew

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

### Setting Up Git

You should setting up Git as follows:

```
git config -l
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL ADDRESS"
git config -l
```

The *"YOUR EMAIL ADDRESS"* should be same your GitHub email address(\*1).

(\*1: You can see the GitHub email address on GitHub. *Your GitHut page > Your Profile Picture/Settings > Personal settings/Emails/Email*)

Because Contributions(\*2) are not counted if the email addresses are not same.

(\*2: The Contributions are on your Github profile page. It is graph that show your action record.)

For more details, see [Set Up Git](https://help.github.com/articles/set-up-git/), and [Why are my contributions not showing up on my profile?](https://help.github.com/articles/why-are-my-contributions-not-showing-up-on-my-profile/)


## How To Use

### Helpful Links

* [GitHub Guide](https://guides.github.com/): You can learn what is GitHub and how to use GitHub on the GitHubWebSite.
* [try.github](https://try.github.io/): You can try *gitcli* on the website in the form of hans-on.
* [git-scm](https://git-scm.com/doc): You can learn how to detail use by using *gitcli*



## Appendix

### How to Preview README.md on your PC

You can preview some .md-files while revising it on your PC before push GitHub.

- Install [Atom](https://atom.io/).

- Atom > Preferences > Packages > Search *"markdown-preview"* > Settings > Check Setting/*"Use GitHub.com style"*

- It can be activated from the editor using the **"Ctrl-Shift-m"** key-binding and is currently enabled for .markdown, .md, .mdown, .mkd, .mkdown, .ron, and .txt files.

<img src="https://github.com/Soichiro75/hello-github/blob/master/images/2016-07-08_Preview_md_onAtom.png" width="320px">

### Resize Image in README.md of GitHub

You can put image using Markdown, ` ![image](http://xxx/image.png)`

However, this is too big.

![DownloadDockerDmg](https://github.com/Soichiro75/hello-github/blob/master/images/2016-07-07_DownloadDockerDmg.png)

You can resize image by using direct HTML tag, `<img src="https://xxx/image.png" width="320px">`

<img src="https://github.com/Soichiro75/hello-github/blob/master/images/2016-07-07_DownloadDockerDmg.png" width="320px">
