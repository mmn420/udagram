# Deployment Pipeline

The pipeline is set up and connected with this GitHub repository in CircleCI.

## Pipeline Order

1. Orbs install node, AWS CLI, and EB CLI.
2. Performs code check on the repository.
3. Install backend and frontend dependencies.
4. Build backend and frontend.
5. Deploy the frontend to AWS S3.
6. Deploy the backend to AWS Elastic Beanstalk.

![pipeline diagram](Screenshots/pipeline_diagram.drawio.png)
![CircleCi pipline](Screenshots/circleci_pipeline.png)
