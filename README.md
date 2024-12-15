## README

This JHipster project is part of the tutorial at [Better Projects Faster](https://betterprojectsfaster.com/learn/tutorial-jhipster-docker-01).

forked from the repository:

https://github.com/dmoges/bpf-tutorial-jhipster-docker

## sonarqube - token

sqp_3a41a651b31fd0a754d515cda6b175f295c74a41

## sonarqube - commandline

mvn clean verify sonar:sonar \
 -Dsonar.projectKey=sonar-bpf-jhipster \
 -Dsonar.host.url=http://localhost:9000 \
 -Dsonar.login=sqp_3a41a651b31fd0a754d515cda6b175f295c74a41
