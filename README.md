# CloudFormation

#Steps to Follow
Create an S3 Bucket:
Create a new bucket with a unique name.
Update Lambda Function:
In the Lambda function code, locate the references to "vatsavcodefile".
Replace "vatsavcodefile" with the newly created S3 bucket

Deployment Steps:
1) KMS_KeyPair
2) VPC
3) LambdaFunction
4) S3Buckets
5) EMR autoscaling/EMR managed scaling


error message:
ElasticMapReduce Cluster with Id j-27XVMIKKN9QWM, is in state TERMINATED_WITH_ERRORS and failed to stabilize due to the following reason: {Code: INTERNAL_ERROR,Message: Failed to start the job: Failed to perform validation}
