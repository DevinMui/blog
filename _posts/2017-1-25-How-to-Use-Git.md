## How to Use Git

![git](https://git-for-windows.github.io/img/git_logo.png)

Git is an incredibly useful tool for collaborating with other developers, backing up your code, and looking through changes in your code. Many high school students especially in my AP Computer Science class have no idea how to use Git (\*ahem\* Brian Anderson). Hopefully, after reading this document, you'll learn a thing or two about using Git.

### Windows

Delete your OS and install a Linux of your choice. 

Haha just kidding. Typically, a Windows OS will make your life much more difficult for development as you have to install a bunch of tools before you can start developing software unlike how on a Linux machine, you have all the tools required preinstalled. 

First off, you gotta install Git. Try Git Bash: https://git-scm.com/downloads

Next, familiarize yourself with the shell. In Git Bash, you can use normal Linux commands such as cd (change directory), ls (list), mv (move), and more! Of course, installing packages and such will be more complicated and will require extra dependencies to install. 

Now navigate to your directory which you want to put under version control (let's say under C:\User\Devin\Desktop\project):

`$ cd C:\User\Devin\Desktop\project`

Done!

### Mac

Open terminal

Install [Homebrew](http://brew.sh/): 

`$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Install Git:

`$ brew install git` (you may need to install XCode )

`$ cd Desktop/project`

Done!

### Linux

Open terminal

`$ sudo apt-get install git`

`$ cd Desktop/project`

Done!

### Next Steps

Setup Git:

`$ git config --global user.name "<your name>"`

`$ git config --global user.email "<your email>"`

If the project is not currently under version control:

`$ git init`

then

`$ git remote add origin <your github repo url here>`

If your project is already under version control or you finished the previous few steps:

`$ git add .` (add all your files to be checked out by Git)

`$ git commit -m "<your message here>"` (commit your files and add a message)

`$ git push --set-upstream origin master` (pushes your files onto Github)

`$ git push` (use this when you want to push again instead of the previous command)

`# git pull` (use this to pull changes from your project)

That's pretty much the basics for Git but of course, there is much more to learn. You can ignore files, make new branches, and much much more.
