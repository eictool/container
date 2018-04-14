
This repo have Dockerfile and log files about building docker images under eictool orgnization at docker cloud https://store.docker.com/profiles/eictool

small base images including  basic devel tools are built by Dockerfile on docker cloud directly
Developers can build any software on top of base image by Dockerfile or mannually
Developers should upload Dockerfile or make a log file if building mannually

One container should contain one software tool only to keep things independent

As an example,the pythia event generator image, evgen_pythia6, is built mannually on top of a base image and pushed to docker cloud  
see its log file for details

For general container questions, refer to docker and singularity offcial sites and note at https://hallaweb.jlab.org/wiki/index.php/Note_about_container
