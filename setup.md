---
title: Setup
---
This setup tutorial will walk you through installing the software you will need for this workshop.
## Installing and configuring git <a name="git_configuration"></a>

### Installation
Install git. You can install using conda

~~~
$ conda install git
~~~
{: .language-bash}

### Configuring Git

The first time you use Git on a particular computer, you need to configure some things.

First, you should set your identity.
One of the most important things that version control like Git does is to keep track of who changes what.
This helps repository maintainers coordinate the efforts of all the people who contribute to the project.
Most importantly, it makes it easier to figure out who to blame when something goes wrong.
You can provide git your name and contact information with the following commands:

~~~
$ git config --global user.name "<Firstname> <Lastname>"
$ git config --global user.email "<email address>"
~~~
{: .bash}

Next, you might want to change the Git text editor.
As we will see later, certain Git commands will open text files.
When this happens, Git will use your environment's default text editor, which might not be the editor you are most comfortable using.
Using configuration commands, you can tell Git to use your favorite editor.

A popular chose is Vim. To use Vim, do

~~~
$ git config --global core.editor "vim"
~~~
{: .bash}

A more complete list of possible editors is available [here](http://swcarpentry.github.io/git-novice/02-setup/index.html).

To use VSCode as your core editor, do

~~~
$ git config --global core.editor "code --wait"
~~~
{: .language-bash}

You can check the configuration commands that you have set using:

~~~
$ git config --list
~~~
{: .bash}

## Create GitHub Account <a name="github_account"></a>
Create an account on [github.com] if you do not have one already. Remember the user name and password. If you are making a GitHub account, please remember that your username should be *recognizable* and *professional*.

### Download the resources:

<a href="file/molecool.zip" download>Download the `molecool` folder for the `git` practical</a>


### Conclusion
At the end of this set-up, you should have installed and created an account on GitHub, and configured git.


[anaconda]: https://www.anaconda.com
[https://www.anaconda.com/download]: https://www.anaconda.com/download
[github.com]: https://github.coms


{% include links.md %}
