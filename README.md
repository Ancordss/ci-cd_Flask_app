## projec 4 ci/cd python docker jenkins

### steps

#### continuos integration
-merge all code work into a master branch
-code reviews, copile,build, unit tests,integration tests

#### continuos delivery 
-deploy to test Server (in this case azure vm)
    -UAT,QA
-build are delivered throughout the life cycle

#### Continuis Deployment 
-deploy to prod sercer or release

#### work job
![image.png]()

in this case where deploy the image in the same machine where jenkins is running and if it is successful then it is going to publish it to the docker hub and then the next stage jenkins will actually deploy the image to the server

im trying to mimic o replicate the whole  flow of ci/cd here starting from checking out code and then deploying to one of these servers 

##### in a usual ci/cd enverinmoment basically this is how the things work. in this case im trying mimic in a local systems.

#### requeriments:
- python3x. text editor or IDE
- docker, dockerhub account
- git, git bash or github Desktop
- github account
- jenkins server on linux 
- linux server with docker installed (this will the deployment server).



