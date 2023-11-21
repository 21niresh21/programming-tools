# Remote Repositories

## What is a remote repository ?

* Remote repositories are simply versions of your git project that are hosted elsewhere online (or local). There can be several remotes of your git project

## Working with remotes

### Your remotes

* To get the remotes you have configured - ```git remote```
* To get the remote shortnames and urls - ```git remote -v```
* To add a remote - ```git remote add <shortname> url```
* To fetch (fetches data to your local directory but does not merges) - ```git fetch <remote>```
* To fetch and merge - ```git pull```
* To push your work - ```git push <remote> <branchname>```
* To inspect a remote - ```git remote show <remote>```
* Rename remote - ```git remote rename <old> <new>```
* Remove remote - ```git remote remove <remote>```

## Tags

* Tags are used to mark specific points in repository's history as important like version releases
* Lightweight tags - a pointer to that particular commit
* Annotated tags(important tags to store all details of tag) - these tags are stored as full objects in the git database

## Tag commands

* To list tags - ```git tag```
* To create annotated tag - ```git tag -a <tag> -m <message>```
* To create lightweight tag - ```git tag <tag>```
* To create tag for older commits - ```git tag <tag> <part of checksum of commit>```
* To push tags (tags should be separtely pushed to remotes) - ```git push <remote> <tagname>```
* To push all tags - ```git push <remote> --tags```
* To push annotated tags only - ```git push <remote> --follow-tags <tag>```
* To delete tag from local repository - ```git tag -d <tag>```
* To delete tag from remote - ```git push <remote> --delete <tag>```
* To view version of files of particular tag (safe to create branch and get the files) - ```git checkout -b <branch> <tag>```


## Git aliases

* To give aliases - ```git config --global alias.<alias name> <command>```