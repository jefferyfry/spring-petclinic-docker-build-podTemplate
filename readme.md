# Spring PetClinic Docker Build Example

This is an example of running Docker builds on CloudBees Core on Kubernetes using agent pod templates (instead of configuring in the Jenkins UI). See the podTemplate folder and the Jenkinsfile. This example runs a maven build, docker build and pushes the image to docker hub.

## Requirements
- CloudBees Core 1.212.2.1 with Kubernetes Plugin 1.10.2

