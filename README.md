This is an **unofficial** clone of the FreeRTOS project's [Subversion repository hosted on SourceForge](https://freertos.svn.sourceforge.net/svnroot/freertos).  You probably shouldn't depend on this repository being available for you to use.

`git-svn` config:

    [svn-remote "svn"]
        url = https://freertos.svn.sourceforge.net/svnroot/freertos
        fetch = trunk:refs/remotes/trunk
        branches = branches/*:refs/remotes/*
        tags = tags/*:refs/remotes/tags/*


## Updating from Subversion

1. `git checkout vendor`
2. `git svn fetch`
3. `git merge --ff-only trunk`
4. `git checkout master`
5. `git merge vendor`

