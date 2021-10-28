# Spring PetClinic Docker Build Pod Template Example

[![CIS](https://app.soluble.cloud/api/v1/public/badges/a82bd89e-a976-4eaf-a8e8-38db1f48ec34.svg)](https://app.soluble.cloud/repos/details/github.com/jefferyfry/spring-petclinic-docker-build-podtemplate)  [![IaC](https://app.soluble.cloud/api/v1/public/badges/b74a19e7-0dc1-4205-b269-758403fd3537.svg)](https://app.soluble.cloud/repos/details/github.com/jefferyfry/spring-petclinic-docker-build-podtemplate)  

This is an example of running Docker builds on CloudBees Core on Kubernetes using agent pod templates (instead of configuring in the Jenkins UI). See the podTemplate folder and the Jenkinsfile. This example runs a maven build, docker build and pushes the image to docker hub. For how to do this by configuring the pod template in the Jenkins UI, see this [repo](https://github.com/jefferyfry/spring-petclinic-docker-build).

## Requirements
- CloudBees Core 1.212.2.1 with Kubernetes Plugin 1.10.2

