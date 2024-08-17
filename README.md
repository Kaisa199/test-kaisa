This tutorial shows how to deploy a simple house price prediction model.

## How-to Guide

### Start Jenkins service locally
```shell
docker compose -f docker-compose.yaml up -d
```
You can find the password for `admin` at the path `/var/jenkins_home/secrets/initialAdminPassword` in the container Jenkins.

### Push the whole code to Github for automatic deployment
```shell
git add --all
git commit -m "first attempt to deploy the model"
git push origin your_branch
```