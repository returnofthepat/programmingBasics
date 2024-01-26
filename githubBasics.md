# Github Basics

## prerequisetes

### a text editor

there is so many editors to choose from, so which should you choose?
take a look at this [repo][https://github.com/returnofthepat/editorTestRepo.git] for an informed decision and basics on keybindings. 

### brew command in terminal
this [website][https://brew.sh/]
Follow the guide on the website


### github account

To access a repository youll need to be able to access your github account



### github repository

to do anything youll need to install the gh command.
type "brew install gh" into the command line in your terminal

after that either access or create a repo on github.
once youre on the homepage of your repo click the "code" drop down menu
then select github cli


### Github cli

copy and paste the command given to you in the github cli into your terminal

the first time doing this it will ask you to login into your github account

follow the prompts in terminal and read carefully.

before redirecting you to a webbrowser to login, a one time passcode will be
printed into your terminal. you'll need to use that passcode to login.

after the first time logging in you can add new repos to your hearts content


## Git hub repository

when working with github your new best friends are the following

git add . / <file>
git commit - a
git push

this [website][https://git-scm.com/docs/git-commit] has more info on specifics

git add . will add all files in a directory
git add <file> will add a specific file

git commit -a will commit all files that have been added, then will take the user into vi. When in vi press "i" to enter insert mode, i usually type the date but you can type wtv(i can explain more if needed). when youre done typing your message press "esc" then ":" and type "wq".

git push will update the repository it's connected to.
