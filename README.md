gaia-custom-repo
=================

Experiment of using repo to manage gaia with customize distribution

Create a dir

    $ mkdir mozgaia
    $ cd mozgaia

init repo

    $ repo init -u https://github.com/gaia-local/gaia-local-repo.git


edit default.xml , modify a remote `https://github.com/<your_id>/` to your repository, ex: 

     <remote name="my-gaia" fetch="https://github.com/gasolin/"/>


sync repo

    $ repo sync


Refer to

## Reference

* Based on https://github.com/gasolin/gaia-custom-repo.git
* Git and repo cheatsheet http://source.android.com/source/developing.html#git-and-repo-cheatsheet
