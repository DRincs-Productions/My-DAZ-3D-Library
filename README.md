[![Git Anti Virus Scan](https://github.com/DRincs-Productions/******/actions/workflows/antivirus.yml/badge.svg)](https://github.com/DRincs-Productions/*********/actions/workflows/antivirus.yml)

## How to work
Before you start creating a scene check the [wiki](https://github.com/DRincs-Productions/***********/wiki) to see if there is an element best suited for you.


## Request new material

If you need an Assert that is not included in this folder try checking in these bookmarks: [raindrop](https://raindrop.io/drincs)
in case you find what you needed or not, request to add a new Assert [here](https://github.com/DRincs-Productions/daz-assert-posing/issues/new/choose).

## Instructions (for those unfamiliar with Git)

First install [GitHub Desktop](https://desktop.github.com/) then clone this repo (watch [example](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop)).

(Important) After that you have to add the created folder as Daz library, like this.

![alt text](https://github.com/DonRP/BBS-3D/blob/master/images/2021-06-052.webp "Daz")


### Pull branch

To **insert** or **update** the Toolkit in your repo with Pull branch I recommend the following procedure:

(only if you want to insert the repo) Create a new empty branch, in the example I'll use **vscode-template**

```shell
git checkout -b daz-assert-templete
git checkout daz-assert-templete
git config pull.rebase false
git pull https://github.com/DRincs-Productions/daz-assert-templete.git main --allow-unrelated-histories

```
