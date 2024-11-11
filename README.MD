Setup Dockerfile and gitlab-pipeline
----------------------

###prerequisites
- **Docker**
- **gitlab**
- **heroku cli**

### Docker setup 

1. clone the project from github
2. Build the project with docker 
3. Run the project

###gitlab pipeline
The steps for the gitlab pipeline are the following:

- **Build** the Docker image.
- **Push** the image to Docker Hub.
- **Deploy** the image to Heroku.
