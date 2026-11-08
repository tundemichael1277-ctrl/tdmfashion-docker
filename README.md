This Docker is a software tool (platform) used to build, package and run applications.
Think of Docker as a way to put your application and everything it needs into a portable package called a container image.
For the TDM Fashion application, Docker is used to package the website and the necessary web server environment into a Docker image. This makes the application easier to run, test and deploy consistently across different environments.

The Docker image is stored in Amazon Elastic Container Registry (ECR), ready to be deployed to an AWS service such as EC2.