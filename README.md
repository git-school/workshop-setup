Git Workshop Setup
==================

Hello! To prepare for the workshop, we ask that you please do the following two things:

## 1. Get the Software

Please make sure you have an appropriate installation of Git installed! You should be able to access it from your computer's command line application. Follow the instructions in [the Installing Git repository](https://github.com/git-school/installing-git) for more detailed instructions.

## 2. Get the Materials

### Clone the Repository

Clone this repository using the `--recursive` flag so that the submodules are initialized:

```
git clone --recursive https://github.com/git-school/workshop-setup.git
```

Once cloned correctly, you should have additional subfolders inside the clone repsitories, and those subfolders should *not* be empty. If they are, run the command listed under "Update the Repository," below.

### Update the Repository

A day or two before the workshop, please take a moment to pull down the latest changes so everything is up to date. From inside the cloned repository, run:

```
git pull
```

and then

```
git submodule update --init --recursive
```
