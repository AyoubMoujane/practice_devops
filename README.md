# practice_devops
This repository is a compilation of mini-project to practice devops concepts and technologies


**jenkins_docker_dind:** </br>
  **Goal**: </br>
  Pipeline to pull from a github repo, build an image and push it to dockerhub</br>
  **Architecture:** </br>
  Jenkins container with docker installed</br>
  Docker container running a docker daemon for the jenkins container (docker inside another docker container)</br>
