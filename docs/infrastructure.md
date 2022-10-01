# Udagram Infrastructure

![Architecture](architecture.png)

## AWS

### RDS Postgres

The application server uses AWS RDS Postgres as database for storing and retrieving information.

Database URI: `postgres://postgres:password123@udagram.ca17levzojpx.us-east-1.rds.amazonaws.com/udagram`

### Elastic Beanstalk

EB URL: `http://nfudacityudagram-env-1.eba-5wtme6b9.us-east-1.elasticbeanstalk.com/`

### S3 Bucket

Bucket URL: `http://nf-udagram-bucket.s3-website-us-east-1.amazonaws.com`

End users can access the application from the Bucket URL.
