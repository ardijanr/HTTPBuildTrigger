# Simple Contious Deployment Web Application 

Written in actix web

Checks if the branch has a new commit and triggers docker-compose in the /home/deploy directory.

Returns an error if build failed.

How To:
 - Create the user deployer
 - Add ssh keys to deployer, root and github
 - Run the scripts
 - Just clone repos into /home/deployer/repos folder
 - Add github actions
 - Done

Remember its the name of the folder that dermines the route.
