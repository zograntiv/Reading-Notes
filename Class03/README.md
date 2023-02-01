## Git Notes 

## Seeing your remote

# Remote Repositories

In order to collaborate on Git projects, you must interact with **remote repositories** , versions of a project residing online or on a network.

You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use **remote repositories** to push information to and pull data from.

For cloned repositories, git will automatically give the name **origin** to the server from which you cloned and name **master**

git remote command: allows you to view the short names of all specified remote handles , such as "origin"

**git remote** -v: you can view all remote URls next to their corresponding short names.

## Example:

$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)

## Adding Remotes

To create a new remote Git repository with a short name, use the following format: git remote add shortname url


