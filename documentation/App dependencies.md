# App dependencies
## Back-End

```
- Node v14.15.1. 

- npm 6.14.8.

- AWS CLI and configured.

- A RDS database running Postgres.

- A ElasticBeanstalk .

- Some Env vars.
```

## Env Needed
```
`POSTGRES_HOST` : Your Postgres DB host  
`POSTGRES_USERNAME` : Your Postgres DB username  
`POSTGRES_DB` : Your Postgres DB username  
`POSTGRES_PASSWORD` : Your Postgres DB username  
`PORT` : application port
`AWS_DEFAULT_REGION` : Your MEDIA bucket AWS region EG.: "us-east-1"  
`AWS_BUCKET` : Your media bucket name EG.: "mediabucket123123"  
`JWT_SECRET` : Your JWT token secret, can be set to any value
```

## Front-End

```
- angular/cli.

- ionic.

- S3 Bucket (Just for Deloy).

- URL of The API In Environment file.
```