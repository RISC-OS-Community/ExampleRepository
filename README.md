# Example Repository

This repository is just an example with instructions on how you can push your source code/projects and ideas in this community. This repository shows the typical structure of a repo as we use them, so you can have a clear idea of "where" is "what".

Normally your source code will always be hosted in the src directory.

## Before you start
Before you start please make sure you have read our code of conduct and you understand it and agree with it. By joining this community and using this github organisation you agree with the code of conduct.

You can find the code of conduct [here](./CODE_OF_CONDUCT.md)

## How to upload my code
There are two ways to create your repo and upload your code here:
1) You join this community and create the repo yourself and upload the code by yourself using git and github.com
2) You ask one of the admins to create the repo for you and you give them your source to be uploaded.

The preferred way is the first option, but if you do not intend to maintain your own code in the future (for example you're no longer interested in coding on RISC OS etc.) then the second option is probably the best for you.

### How to join this community

- [Create a github account](https://github.com/join)
- [Add an RSA key to your github account](https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
- [It's a good practice to protect your accoutn by adding 2 factors authentication](https://docs.github.com/en/github/authenticating-to-github/configuring-two-factor-authentication)
- [Join RISC OS Community, by filling up this form and give us your github account name and what type of contribution you would like to purse](https://paolozaino.wordpress.com/contact/)

#### What if I do not know how to use github?
We have got you covered :) Here there is a totally free Video Course splitted in small and very simple lessons you can watch from any device, [click here](https://app.egghead.io/playlists/how-to-contribute-to-an-open-source-project-on-github) for more info, scroll down and enjoy the course!

### How to ask to upload your code on here without joining this community

You can either contact me directly using this link [here](https://paolozaino.wordpress.com/contact/)
OR
You can request it by posting a request in the ROOL Forum in either the General Forum or the Aldershot.

When you ask for uploading your code we need your written permission and make sure you release your code with a ditribution license that is compatible with sharing the sources. You maintain the copyright (if you intend to do so), but we need a distribution license that allow us to share your sources. If youa re not sure which one is best for you we can help :)

### How to contribute to existsing projects

If you want to help us to maintain and improve software we host here please read the contributing guide you can find [here](./CONTRIBUTING.md)

### How to prepare my code to be uploaded here

Simple...

If you want to use git yourself: 
- we create a repository for you like this one
- you git clone it on your computer
- you cd into the directory created into your computer and create your ne branch called yourname-initial-commit (no sapces) using the command ```git branch jhon-initial-commit```
- you add your sources in the src directory
- you edit the README.md (with any text editor) and add info about your code (and how to build it if it needs compilation and which compilers it needs)
- When you're done you add your changes using ```git add .```
- Then you commit then using ```git commit -m "My initial commit"```
- Then you push them in the repo using ```git push -u origin jhon-initial-commit```
- When you are sure everything is in there you open a Pull Request using github.com (if you are not familiar with the git command) and we'll review your changes and add your code to the main repo

If you want us to upload your source intead:
- You zip your sources into an archive
- You add your distribution license and a README.md file with info about your code and how to build it if it needs to be compiled
- You send your zip to us

Thanks for supporting RISC OS!
