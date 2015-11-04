# red_docker
A set of interconnected Docker images implemeting a full Redmine suite.

Design goals are:
* Site should run on a Synology DS415+ under native Docker.
* Standard Redmine implementation.
* Site will have support for local GIT.
* GIT repositories must be accessible from Redmine.
* GIT repositories must be accessible via ssh.
* Site will have a backup on a second Synology (DS216+)
* Users can be added "on the fly", without restarting the server.
