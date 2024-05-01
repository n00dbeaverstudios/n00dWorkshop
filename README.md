# n00dWorkshop

### Welcome to the n00dWorkshop!

This project contains every plugin that's available from n00dbeaverStudios from the Unreal Engine Marketplace and integrates them into one overarching working project that you can pull apart and modify for your own needs, and pragmatically see how everything is integrated!
 
# Installation

To get started follow the steps below.

## Prerequisties
On Windows, you will need to install [Git SCM](https://git-scm.com/) if you haven't already. For Linux users, git is already installed and ready to go. Its also recommended to use a desktop app such as GitHub Desktop for [Windows](https://desktop.github.com/) or [Linux](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1). But you are free to choose whichever app that suits you best. There are many.

> If you don't have access to the repositories but own the plugins, jump over to [Verification](https://verify.n00dbeaverstudios.com/) to get moving on that front. Once you have been verified, you'll gain access and will be able to download those as well!

## Initialising the submodules

### Clone all submodules
If you own all of the assets under [Plugins](https://github.com/n00dbeaverstudios/n00dWorkshop/tree/main/Plugins) and have been granted access to the private repositories, you can get started immediately!

Choose a working directory on your local machine to clone this project into, then use the following commands in Git Bash (right-click in the dir and choose Open Git Bash here):
```
git clone https://github.com/n00dbeaverstudios/n00dWorkshop.git
cd n00dWorkshop
git submodule update --init --recursive
```
Time to jump right in!

### Clone some submodules
If however, you don't own all the plugins or only have access to the public repos, don't sweat! We have you covered too!:
```
git clone https://github.com/n00dbeaverstudios/n00dWorkshop.git
cd n00dWorkshop
git submodule init
```
Say we owned n00dHolster and also want to clone two open source plugins n00dFootsteps and n00dEmotes.

Then do the following for each plugin that you have access to under the same Git Bash session:
```
git submodule update -- Plugins/n00dHolster Plugins/n00dFootsteps Plugins/n00dEmotes
```
You're good to go! See you in there!




