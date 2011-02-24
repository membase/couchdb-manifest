# Building With Repo

## Get Repo

    $ curl http://android.git.kernel.org/repo > ~/bin/repo
    $ chmod a+x ~/bin/repo

## Clone the Manifest

    $ mkdir couchdb
    $ cd couchdb
    $ repo init -u git@github.com:membase/couchdb-manifest.git
    $ repo sync

## Build

    $ rake
