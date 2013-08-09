gaia-custom-repo
=================

Experiment of using repo to manage gaia with customize distribution

Create a dir

    $ mkdir mozgaia
    $ cd mozgaia

init repo

    $ repo init -u https://github.com/gaia-local/gaia-local-repo.git -b tablet-master

sync repo

    $ repo sync

The result will be clone gaia (master) to this folder and clone `gaia-distribution` (tablet-master) to `distribution` sub folder.


Development settings

    // add default branch mapping to gaia/master
    $ git checkout --track -b master upstream/master

    // add personal remote gaia repository
    $ git remote add origin https://github.com/[your id]/gaia.git



## Reference

* Based on https://github.com/gasolin/gaia-custom-repo.git
* Git and repo cheatsheet http://source.android.com/source/developing.html#git-and-repo-cheatsheet
* gaia repo usage slide http://gasolin.github.io/gaia-repo/?full#14
