Minion component for Adama
==========================

A minion container wrapped in a serfnode to use in Adama.

Quickstart
----------

Deploy with
[serfnode-deployer](http://github.com/waltermoreira/serfnode-deployer)
or run with:

```
$ docker run -v /:/host adama/minion
```

Build from source
-----------------

Build with
[doit_in_docker](http://github.com/waltermoreira/doit_in_docker):

```
$ eval $(docker run waltermoreira/doit_in_docker /alias)
$ cd adama-minion
$ doit_in_docker doit
```
