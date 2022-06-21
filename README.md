# code-server-heroku
The stuff you need to put a VS Code server in Heroku using Docker

Note: Last time I checked, you cannot use sudo in the code server due to Heroku limitations, so make sure everything you want is installed in the Dockerfile (since you can't install anything while using code-server in this way).
