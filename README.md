# docker-apachegit
Apache Server - Clones codebase from GIT

This will only clone from a https repo.
With this container, you are able to deploy a Apache2/PHP7.4 docker service.
The init script will clone a GIT repo, and/or a particular branch. And serve the branch.

.git folder moved outside the webservers parent folder. 

Environment Variables

| VARIABLE | USAGE |
|----------|-------|
| GIT USER | GIT Repository Username / Deploy Username |
| GIT PASSWORD | GIT Repository Password / Deploy Key |
| GIT_URI | Trailing part of the URI, without HTTPS:// |
| GIT_BRANCH | Branch to checkout |
