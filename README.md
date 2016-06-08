Git Workshop Setup
==================

Hello! To prepare for the workshop, we ask that you please do the following:

Clone the Repository
--------------------

Clone this repository using the `--recursive` flag so that the submodules are initialized:

```
git clone --recursive https://github.com/git-school/workshop-setup.git
```

Once cloned correctly, you should have additional subfolders inside the clone repsitories, and those subfolders should *not* be empty. If they are, run the command listed under "Update the Repository," below.

Update the Repository
---------------------

A day or two before the workshop, please take a moment to pull down the latest changes so everything is up to date. From inside the cloned repository, run:

```
git submodule update --init --recursive
```
