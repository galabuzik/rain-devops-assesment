# Rain Devops Assessment

This assessment is designed to evaluate the technical and organizational skills of a candidate.

## The exercise

- Fork the repo to your git account.
- Create a dockerfile that runs wordpress. (Please write your own dockerfile - not wordpress)
- Create a Docker Compose file contains (Jenkins + Sonar Scan)
- Prepare a pipeline that has the steps (Jenkinsfile in the repo)
  - Sonar Scan Results
  - Build Dockerfile
  - Upload to Dockerhub (you can use own dockerhub account it can be public)
  - Use Jenkins Secrets for Sonar scan and Dockerhub uploads
- Run your Docker Containers and make them accessible via browser. (You can use https://labs.play-with-docker.com/)
- Come with a solution with persist data (Wordpress database, Jenkins Configs and States)
- Share your repo.

### FAQ

Q: Should I use a specific technology?

A: Docker is peferable

Q: Can I use a my own Infra like AWS/GC/Azure?

A: Sure you can use also play-with-docker

## Why this test

This test is a basic layout to see how you confront with a simple problem and to talk with you about your construction decision.

### What is being tested

- Dockerfile Creation
- CI/CD Usage
- Container Configuration
- Use of Global Best Practice
- care of details

## Time requirements

This assessment is meant to test how a candidate works in a work-like situation, should not be longer than three hours.
