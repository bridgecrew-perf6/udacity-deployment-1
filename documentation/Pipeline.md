# The Pipeline Process

After every update to the source code on the GitHub, a pipeline deployment is triggered using CircleCi, these are the steps taken during the pipeline process:

- Front-End Install:
  Install all the npm packages needed for the frontend application.
- Back-End Install
  Install all the npm packages needed for the backend application.
- Front-End Build
  Builds/Compiles the frontend application using the source code.
- Back-End Build
  Builds/Compiles the frontend application using the source code.
- Deploy App
  Using the AWS Cli, environment variables are set, then the front-end s3 bucket is updated with the latest version of the front-end application, after that the api is updated to the Elastic Beanstalk.
