# Slay the Spire - Final Fantasy Tactics Character Mod

This is the repository for the StSFFTCharMod. Links to resources and installations are provided down below.

## Development Tools
A complete list of installation tools can be found here.

https://github.com/daviscook477/BaseMod/wiki#for-modders

## Resources

#### Game Ideas Spreadsheet
The main spreadsheet that contains all the ideas that inspired this mod.
https://docs.google.com/spreadsheets/d/1nKYjXiD1efDs6C_2Z2TWwGSE5g2oiydLOPaicmURi6o/edit?usp=drivesdk


#### Artwork
The artwork and assets from the 2019 MYOCG HumbleBundle. Some good assets to be found here.
https://drive.google.com/drive/folders/1r8ADmpFq9AtU7evFow3hYvqC6AeS0tir?usp=sharing


## Getting Started
Begin by cloning this repo. Basic branch set up is as follows.

### Master & Develop

`master` and `develop` are protected branches. The current production version of the mod will live under master, while
the currently in development version of the mod. Work will never be committed directly to either branch as that will
undermine version control.

•`master` - The master branch. 
This branch will contain the shippable working copy of the mod, master is protected and should never be worked on directly.

•`develop` - The development branch. 
The branch that will contain the version we're happy with, this is the version that is 

### Work Branches

For development, we will be forking the repo and performing work by branching off of `develop`. Make sure your branch is named
after what you're implementing in as few words as possible (long commit messages get hard to read on GitHub due to bad word
wrapping).

For example, let's say I'm working on a module that focuses on adding character animations (totally out of left field here), 
I would then name my branch: `character-animations`.

When I am satisfied with this branch, I would open a pull request from `character-animations` to `develop` to have that work
merged in.

## Additional info
We're all a part of the #gamedev Discord channel in legit. Any ideas or communications we want to share can be found there,
so feel free to ask any questions that come to mind.


