## Add .env 

```
# AWS_REGION is used by Spark
AWS_REGION=us-east-1
# This must match if using minio
MINIO_REGION=us-east-1
# Used by pyIceberg
AWS_DEFAULT_REGION=us-east-1
# AWS Credentials (this can use minio credential, to be filled in later)
AWS_ACCESS_KEY_ID=
AWS_ACCESS_KEY_ID_TEMP=
AWS_SECRET_ACCESS_KEY=
AWS_SECRET_ACCESS_KEY_TEMP=
# If using Minio, this should be the API address of Minio Server
AWS_S3_ENDPOINT=http://minioserver:9000
# Location where files will be written when creating new tables
WAREHOUSE=s3a://warehouse/
# URI of Nessie Catalog
NESSIE_URI=http://nessie:19120/api/v1
```