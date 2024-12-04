# Udagram Infrastructure
![Infrastructure.png](Infrastructure.png)


## Overview
The Udagram application is deployed using AWS services to ensure scalability, reliability, and accessibility. The infrastructure components include an S3 bucket for frontend hosting, Elastic Beanstalk for backend deployment, and RDS Postgres for database management.

### S3 Bucket
The frontend of the Udagram application is hosted on an AWS S3 bucket configured for public access. Users can access the application using the following URL:

**Frontend URL:** [http://hieu-udagram.s3.us-east-1.amazonaws.com/index.html](http://hieu-udagram.s3.us-east-1.amazonaws.com/index.html)

### Elastic Beanstalk
The backend server is deployed using AWS Elastic Beanstalk, providing a managed environment for application deployment. The backend can be accessed using the following URL:

**Backend URL:** [http://udagram-api.us-east-1.elasticbeanstalk.com/](http://udagram-api.us-east-1.elasticbeanstalk.com/)

### RDS Postgres
AWS RDS Postgres is used as the database to securely store and manage application data. This managed database service ensures high availability and durability for the application's data.

**DB connection:** [postgresql://postgres:postgres@postgres.ckqihxajzsno.us-east-1.rds.amazonaws.com:5432/postgres](postgresql://postgres:postgres@postgres.ckqihxajzsno.us-east-1.rds.amazonaws.com:5432/postgres)



