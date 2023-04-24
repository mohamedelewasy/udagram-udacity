# Pipeline Process

the pipeline will be triggered whenever master branch changed

1. push code to master branch
2. circleci triggered to start the build
3. install aws and elastic beanstalk
4. configure aws credentials
5. install frontend dependencies
6. install api dependencies
7. build frontend
8. build api
9. deploy frontend to s3 bucket
10. deploy api to elastic beanstalk
11. update eb environment
